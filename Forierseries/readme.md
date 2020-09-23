___
#  Why Fourier
## Forier help in mathematical interpretation of signals.This helps in analysing stability of a motor, stability of voltage in grid, could predict the unstability points of system.
___
# What is Forier Series
## for understanding fourier series we must know the following basic undersrandings
 1. A peodic signal in the x-t plane represents a vector alternating  along x-axis. Here x-axis represents a single dimension. Dimension here mean horizontal, vertical, or dimension represented by any of ax+by=c ; where a, b!=0;
 2. The above said vibrating vector can be reresented as a series of head to tail connected, periodically alternating vectors.
 3. We can also recover the signal back from series of vectors resulted after fourier series.

 4. signal --> periodic vector ---> forier series --> series of vectrors.
___
 # What is Forier Transform
## for understanding fourier transform we must know the following basic undersrandings
 1. A nonpeodic signal in the x-t plane represents a vector vibrating  along x-axis. Here x-axis represents a single dimension. Dimension here mean horizontal, vertical, or dimension represented by any of ax+by=c ; where a, b!=0;
 2. The above said vibrating vector can be reresented as a infinite series of head to tail connected, periodically alternating vectors.

  3. We can also recover the signal back from series of vectors resulted after fourier transform .
   4. signal --> nonperiodic vector ---> forier transform --> infinite series of vectors.

 ## Understanding above points, Fourier transform helps in achiving 2nd point.
 ___
 # How Fourier.
 ## The below formulas are for fourier transform. where -- 
 ## N= no of samples of signal.
 ## n= nth sample.

![image](data:image/png;base64,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)

## The below formulas are for fourier series. where --
## T = period of signal,
## m,n= frequency of resulting vectors.
![image](https://lh3.googleusercontent.com/proxy/cRDuQAowt761BLxt0yno72GkhXTE0-QjQjlDRmKs60HUP6vretaiE1TfdmBnwp9NVz3ZfL22jkZyAZQXLltA8Kg4iyIEdU4Qt9GCWvvcAh5LSpMHDS6LWjk) 
# About project
 
## The above project is about realising fourier visually. Here we ssample x,y points of a path in a plane and represent x values and y values in terms of series of vectors using the Forier transform. We recover the signal back using there alternating signal.We here conform the forier by recovering signal from resulted vectors.
# References 



1. [Coding Challenge #125](https://www.youtube.com/watch?v=Mm2eYfj0SgA&t=1077s )
2. [What is Fourier Series](https://www.youtube.com/watch?v=r6sGWTCMz2k&t=519s)

_ref 1 is from coding train community where great learning happens._

# Series or Transform 
  ## Lot of time we get confused between Forier series or Forier transform. FS is used for the signals which are perodic signal and FT is used for NonPeriodic signals. By perodicity it also meant that the signal is infinlite and practically exist for long time. Nonperiodocity represents the signals under stability and are about to decay. 


# Path.js  

## This file represents the path used whose visualisation is achived from forier series.