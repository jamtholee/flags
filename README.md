# Flags

Bringing a little bit of science to the art that is setting the Oxford flags.  

This project is currently maintained by Jameson Lee and Joe Hitchen.

## Usage

https://flags.jamesonlee.com/isis/  
https://flags.jamesonlee.com/godstow/

## FAQs

#### How do I interperate the charts? 
* The "differential", (very) simplified, can be read as the difference between the water levels at the top of the river, and the bottom.  Under perfect still stream conditions, you would expect the difference between the height of the water at the top and bottom to be ~0 (it won't be for various reason).  If the differential is large, then you would expect water to be flowing significantly from the top to the bottom.

#### Where do the predictions come from?
* There's two "predictions" on the chart.  The first is the coloured bands, which come from us having a best guess at how the river levels correlate to the flow conditions.  The second is the predictions in the top right, which come from an artificial neural network that we've trained (and are still training).

#### Why do the boundaries keep changing? 
* The boundaries are our best guess at how much differential corresponds to which flag - we're trying to fine tune this (as well as the algorithms) to make it as accurate as possible, based on current and historic data.  We're also experimenting with using machine learning to predict the flag, which should hopefully be much more accurate (but harder to visualise on a chart).

#### Why do the data points keep fluctuating/group in 4s/do something else weird? 
* More than anything, this is most likely due to sensor noise.  Sometimes, a lock only changes a reading once every hour, but gives us a reading every 15 minutes.  Sometimes the river is so high the sensor saturates.  Basically, the sensor's behaviour is sometimes unpredictable.

#### Is OURCs involved in this project? 
* Nope. Both of us have been OURCs Captain of Coxes, and one is now a senior umpire, but this has always been a personal project and there are no plans to change that.

#### I have other questions not answered here
* Feel free to submit your questions as an [issue](https://github.com/jamtholee/flags/issues/new), and we'll do our best to respond.  You'll need a free Github account to create an issue.  Do bear in mind that both of us are no longer students, so it may take us a while to get back to you!


## Project Roadmap & News
We are both happy with the current state of the project, and there is no major work planned.  If there is sufficient demand we can start collecting and displaying the data for other rivers.  We remain open to other suggestions too - particularly from those able to help implement them.  Again, open an [issue](https://github.com/jamtholee/flags/issues/new) to start the discussion.

We will continue to tweak visual boundaries and update predictions algorithms as we see fit.
  
**2021-11-01** - Support for light blue flag added
**2020-02-13** - Radley, Abingdon, and Wallingford added  
**2020-02-02** - Machine Learning predictions added   
**2019-10-16** - After the server went down; Joe took over hosting and day-to-day maintenance of the project  
**2018-09-18** - Entire project rewritten (Updated from the joy that is PHP)  
**2016-02-04** - Project kicked off  

## Disclaimer & Credits
These charts and predictions should not be used as a substitute for the OURCs flag, or a sensible risk assessments based on current conditions.  We take no liability for the accuracy or reliability of the information or data presented here.

Many thanks to the EA for their data API: *This uses Environment Agency flood and river level data from the real-time data API (Beta)*.
