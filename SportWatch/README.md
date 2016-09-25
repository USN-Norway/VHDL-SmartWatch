# VHDL-SmartWatch
##Task:
Using only the resources available in the NEXYS 3, namely switches, leds, press buttons, 7-segment displays, etc. to design an alarm clock. Add other features like:

* 12h or 24h option; 
* A simple calendar with day/month or perpetual calendar with day/month/year; 
* Days of the week; 
* A chronometer with stopwatch and lap timer; 
* Incremental speed when setting clock, alarm clock or calendar; 
* Any other creative features!

##Design
--
(**TEAM MEMBERS: Qinghui. Liu, Zhili. Shao, Joseph. Fotso**)

We use three buttons (Btn1, Btn2, and Btn3), that are used to change the mode, set the time, set the alarm, set date, start/stop the stopwatch, set/start timer and so on, to implement all required functions of the digital clock. 4-digit 7-segment LCD will be use to display kinds of information, like date, clock, timer etc. upon the mode selected. 

Pushing Btn1 changes the mode from Clock to Alarm, Calendar, Stopwatch, Timer, and then back to Clock. 5 LEDs will be used to indicate which mode is selected by lit on. The functions of Btn2 and Btn3 vary upon the mode selected by users, as below… 