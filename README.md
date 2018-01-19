# Software Documentation
## This is [Team 5827's](http://www.lwrobotics.org) documentation on getting everything set up and running for a new season!
#### Initializing the environment
> **Note:** These steps are absolutely necessary in getting a development environment set up
1. **Get a robot** _This can be an old robot or your current one_
2. **Connect all the devices** Make sure all the devices on the robot are connected and show up on the NI Web Dashboard which can be found at `roborio-5827-frc.local`. The NI Web Dashboard is only accessible through [Internet Explorer 8 or higher](https://support.microsoft.com/en-us/help/17621/internet-explorer-downloads). None of the other browsers work.
3. **Get the latest firmware for motor controllers** and update the firmware through the Web Dash _**You need to update the motor controllers first**. Otherwise, you will be unable to detect the motor controllers. It is important that you update the motor controllers, as otherwise you will be unable to control the motor controllers_
4. **Flash the RoboRIO** This software to update is usually provided in the FRC Update Suite. _If the RoboRIO is not updated, it will not be compatible in the competitions_
5. **Update the radio** The software to update the radio is also provided with the FRC Update Suite _If the radio is not updated, you will be unable to connect to the robot at competitions_
6. **Download third-party support** Some companies, like Cross the Road Electronics, require you to download some extra software into the robot and the NI Web Dash in order for their electronics to work. _This information is often hidden, so make sure that you have installed everything needed_ 
7. At this point, if all of the above steps were completed without any issues, then your robot should be successfully initialized and ready to put into play at competitions
#### Creating a Testing Environment
> **Note:** Start fiddling with your robot with the example project so that you can know the quirks of the newly updated WPILib, what motor controller is connected to which port, and much more. **_This step is not necessary, but recommended_** Also, make sure to **_test your code periodically_**, so that if there is an issue, it will be easier to find
1. **Familiarize yourself with the FRC libraries** Go to [WPILib](https://wpilib.screenstepslive.com/s/currentCS) and find the documentation that shows the differences made to the library for this year. Or if you are new, go to the docs ([Java](first.wpi.edu/FRC/roborio/release/docs/java/)/[C++](http://first.wpi.edu/FRC/roborio/release/docs/cpp/)) and read through the different classes and methods to familiarize yourself
