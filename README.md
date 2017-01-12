# montage
montage fix for pegasus-3.6 and binary staging

mDAG.c:
  - changed to pegasus-3.6 syntax (http://pegasus.isi.edu/schema/dax-3.6.xsd)
  - mDiffFit transformation added to use executables(mDiff, mFitplane) as items
  
svclib.c:
  - if the executable path does not exist as absolute path it will be interpreted as 
    relative path to the current working directory 
