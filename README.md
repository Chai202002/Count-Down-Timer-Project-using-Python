Generally, we use a countdown timer to complete a task before a fixed time interval. We set a target time and then the countdown starts. For instance, the time for an online exam is scheduled in advance. The remaining time after the start of the test is gradually reduced and shows a notification when the time has elapsed. I have given a graphical interface to this timer using the python Tkinter library so that it would be easy to use by the users.
Our program handles the following tasks:
*	Set the Countdown time
*	Start Countdown
*	Pause the Countdown time (without sleep function)
*   Play music in the background (when the remaining time reaches zero)
Since it's a GUI project, users need to set the time through a Combo box and press the 'Set' button. When the set button is pressed, two more buttons (the 'Start' button and 'Pause' button) will appear on the right side. Users can start and pause the timer as their need. The pause feature makes the Timer more reliable. When the users press the start button, the remaining time will show on the screen and every second will decrease by 1. When the remaining time reaches zero, a notification will be popped up with music, playing in the background. When the 'Set' Button is pressed, this 'Get_Time' function takes the time set by the user. If the users try to set the default value (0:0:0, see the yellow line), the program will show a warning message on the screen to set the correct time. After pressing the 'Set' Button, the 'Start' and 'Pause' buttons appear on the right side that allows the users to Start and Pause the time as their need.
