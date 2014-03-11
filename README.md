##To Use this Tasker Script on your Phone

Download the single project file from my GitHub to your phone.

Open Tasker

![Home Icon](https://raw.github.com/redleader36/ingress-tasker-scripts/screenshots/screenshots/tasker1.jpg)
Long press on the Home icon and select Import.

![Import File](https://github.com/redleader36/ingress-tasker-scripts/raw/screenshots/screenshots/tasker2.jpg =250x)
Navigate to your download folder (usually /sdcard/Download/)
Select the Ingress project file you previously downloaded

![Ingress Project](https://github.com/redleader36/ingress-tasker-scripts/raw/screenshots/screenshots/tasker3.jpg =250x)
Click on the Ingress Project tab at the bottom of the screen, next to the home button.
Make sure both Ingress and Ingress Menu profiles are turned on.

Next, click on the VARS tab at the top.  This is the easiest way to insert the variables for your specific phone.

![Ingress Vars](https://github.com/redleader36/ingress-tasker-scripts/raw/screenshots/screenshots/tasker4.jpg =250x)
This is where you can input the X and Y coordinates of all the Ingress App buttons and the loop delay of each function.  You will only have to do this once.  I find it much easier to use in Landscape mode.  The variables are pretty self explanatory, but they tell the script exactly where to emulate screen presses.  The %INGRESS_ACQUIRE_X is the X coordinate of the Acquire button on your Ingress Scanner, the %INGRESS_ACQUIRE_Y is the Y coordinate of the Acquire button and so on.

To find your XY coords, just check out Drop's website: http://ingressdrop.com/device-tap-points/#SGS4.  (It looks like their Acquire1 is equal to my %INGRESS_GROUND and Acquire2 is %INGRESS_ACQUIRE)
Alternatively, you can find the tap points yourself by following this tutorial: http://ingressdrop.com/getting-your-tap-points/ 

The DELAY variables tell the script how many seconds to pause during their respective scripts.  Leave these at default values unless you notice the loops are running too fast or slow.  The Recycle delay will be a second or two to allow for the Recycle animations.

%INGRESS_GROUND_X and %INGRESS_GROUND_Y are coordinates on the screen to use for picking up items -- I usually make this a half inch above the arrow.
