# Flags

Bringing a little bit of science to the art that is setting the Oxford flags  

This project is currently maintained by Jameson Lee and Joe Hitchen.

## Usage

https://flags.jamesonlee.com/[isis/godstow]/

## FAQs

#### How do I interperate the charts? 
* The "differential", (very) simplified, can be read as the difference between the water levels at the top of the river, and the bottom.  Under perfect flat conditions, you would expect the difference between the height of the water at the top and bottom to be ~0 (it won't be for various reason).  If the differential is large, then you would expect water to be flowing significantly from the top to the bottom.

#### Where do the predictions come from?
* There's two "predictions" on the chart.  The first is the coloured bands, which come from us having a best guess at how the river levels correlate to the flow conditions.  The second is the predictions in the top right, which come from an artificial neural network that we've trained (and are still training).

#### Why do the boundaries keep changing? 
* The boundaries are our best guess at how much differential corresponds to which flag - we're trying to fine tune this (as well as the algorithms) to make it as accurate as possible, based on current and historic data.  We're also experimenting with using machine learning to predict the flag, which should hopefully be much more accurate (but harder to visualise on a chart).

#### Why do the data points keep fluctuating/group in 4s/do something else weird? 
* More than anything, this is most likely due to sensor noise.  Sometimes, a lock only changes a reading once every hour, but gives us a reading every 15 minutes.  Sometimes the river is so high the sensor saturates.  Basically, the sensor's behaviour is sometimes unpredictable.

#### Is OURCs involved in this project? 
* Nope.

#### I have other questions not answered here
* Feel free to submit your questions as an [issue](https://github.com/jamtholee/flags/issues/new), and we'll do our best to respond.  You'll need a free Github account to create an issue.  Do bear in mind that both of us are no longer students, so it may take us a while to get back to you!

## Project History & News
**Project Future** - todo
  
**2020-02-xx** - Machine Learning predictions added   
**2020-02-xx** - Data collection routine rewritten  
**2019-10-xx** - After the server went down; Joe took over hosting and primary maintenance of the project  
**2018-09-xx** - Entire project rewritten (Updated from the joy that is PHP)  
**2016-02-xx** - Project kicked off  
