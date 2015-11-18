# Smart Health Monitor
## The Goal
  The goal is to have wrist type widget (sensor) measuring health parameters (pulse for the initial version). 
  It will contain GPS module so we can have the location (speed) of the object (human), 
  3G module - we want to have internet connection outdoors, WiFi, gyroscope, panic button (button on the wrist widget).
  
## User Stories
	1. You have your parents/grand parents, far away from you. If they had a heart attack, or similar - the software will detect the pulse deltas and you'll receive a warning. You have a gps and 3g module to find out the location. Last but not least you have the panic button - if they fall down somewhere, or they're not feeling well, but don't have a chance to call you, or your relatives. 
	2. You are traveling to work by bus and you felt asleep into the bus. The widget detects you are sleeping by the pulse. Once you are close your bus station the widget tries to wake you up (alarm, vibration on the wrist, or slow voltage on the wrist)
	3. Car mode (manually activated) - while you are driving and you are tired just before you fall asleep your pulse fall down with a big delta (eyes are using big part of the blood pressure). In that moment we may use the same methods as we use in the bus case, but should be with high level of emergency.
	 
	
## What we have done so far
The current state is small web page displaying the pulse and tempreture using the sensors attached to a human. And data chart diagram showing BPMs. The demo html can be found into the demos folder.

##TODOs
We have to connect and use the other sensors. We need algorythms for detection of high rate, falling horizontally etc.

The code was built only for testing purposes during the 2015 IG Hack Week. You won't find something really useful here. It's our first playing with arduino and the SDKs, so the first goal was make it work (wire, detect, proceed and display the data) 
