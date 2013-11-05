Pimage standalone from SGAT. 

This aims to be
 - Pimage sample and time spent binning for SGAT
 - Pimage time-series grid samples from external DB
 - 
TODO


- implement model.bin as Pimage.default (don't know what class)


DONE
- implement chain.bin with new Pimage structure, it will take the
subsetted Pimage object, a matrix xy
 - overwrite [[ method to get the whole object with the ith pimg, and
   prevent replacement
 - build Pimage with two parts, main list of pimg and subsequent metadata
 - current pimg holds grid extent and grain, strictly it only needs
  its offset, its time and duration, and the image