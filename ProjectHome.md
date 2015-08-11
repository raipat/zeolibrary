## ZeoLibrary ##

You can use this library for either reading and analysing the .csv (via Zeo website) the .DAT files (from the SD card), or to stream data live from your Zeo Bedside Display.

### ZeoStream ###

Stream live data from the serial port of your [Zeo Bedside Display](http://www.myzeo.com/sleep/). For the correct hardware setup follow the instructions at [Zeo Raw Data Library - Getting Started](http://www.sleepstreamonline.com/rdl/starting.html). About every second a ZeoSlice object is read and communicates current raw brainwave data and processed frequency bin data. About every 30 seconds the Sleep Manager communicates the average current sleep stage.

![https://lh3.googleusercontent.com/-zezfMyKqBW4/UFZws5ctjXI/AAAAAAAACKI/y5pU6RSWDys/s800/eeg-20120914-034208.png](https://lh3.googleusercontent.com/-zezfMyKqBW4/UFZws5ctjXI/AAAAAAAACKI/y5pU6RSWDys/s800/eeg-20120914-034208.png)


### ZeoReader ###

Import your sleep-data files (csv / DAT) into [Processing](http://www.processing.org).

"zeodata.csv" could previously be exported from the Zeo website. "ZEOSLEEP.DAT" files can be taken directly off the Zeo Bedside Display's memory card, if the device has been updated to firmware v2.6.3O.

The ZeoReader class imports and parses "zeodata.csv" and "ZEOSLEEP.DAT" files, cleans out unusable nights, and creates ZeoNight objects for every night. Each ZeoNight object holds sleep data information that originated from the Zeo Sleep Manager sensor readings, and sleep diary information that has been entered through the Zeo website. The library gives you easy access to that data and offers simple functions to compute averages for various sleep data values (total sleep, REM, light sleep, deep sleep, sleep onset time, awakenings, ...)



![https://lh3.googleusercontent.com/-kyMnmCK9m3Q/UDWAC9USvpI/AAAAAAAABz0/goQQExJxEmU/s640/sleep-totalz-20120822-205510.png](https://lh3.googleusercontent.com/-kyMnmCK9m3Q/UDWAC9USvpI/AAAAAAAABz0/goQQExJxEmU/s640/sleep-totalz-20120822-205510.png)

### Install ###
  1. Download zeolibrary zip file
  1. Download Processing from http://processing.org/download/?processing
  1. Install zeolibrary by following the guide at http://wiki.processing.org/w/How_to_Install_a_Contributed_Library
  1. Open Processing and open some of the zeolibrary examples via File>Examples>Contributed Libaries>Zeolibary

### Examples ###
[ZeoLibrary Examples](http://www.evsc.net/home/zeolibrary) on my website

![http://www.evsc.net/v8/wp/wp-content/uploads/2012/08/graphComparison-20120825-151613-630x225.png](http://www.evsc.net/v8/wp/wp-content/uploads/2012/08/graphComparison-20120825-151613-630x225.png)


### Links ###
[Zeo Sleep Manager](http://www.myzeo.com/sleep/) The hardware you'll need!

[Adventures in Sleeping](http://www.evsc.net/research/adventures-in-sleeping) Blogpost  about my Zeo experience