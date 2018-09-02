# IDD-Fa18-Lab1: Blink!

**A lab report by Chris Kruger**

## Part A. Set Up a Breadboard

[insert a photo of your breadboard setup here]


## Part B. Manually Blink a LED

**a. What color stripes are on a 100 Ohm resistor?**<BR>
A 100 Ohm resistor has brown (band + multiplier), black (band), and yellow (tolerance) stripes.<BR>
The 220 Ohm resistor supplied for this lab has red (bands), brown (multiplier), and yellow (tolerance) stripes.
 
**b. What do you have to do to light your LED?**<BR>
Have to hold down the switch to turn the LED on. 

## Part C. Blink a LED using Arduino

### 1. Blink the on-board LED

**a. What line(s) of code do you need to change to make the LED blink (like, at all)?**<BR>
The "digitalWrite()" function is used to change the voltage level of the LED, setting it to "HIGH" turns it on.

**b. What line(s) of code do you need to change to change the rate of blinking?**<BR>
A combination of "digitalWrite()" and "delay()" are used to control the rate of blinking. First, setting digitalWrite() to "LOW" turned the LED off, and delay() can be populated with time in ms to control how long the LED is in the digitalWrite() state for. Finally you can use digitalWrite() to set it back to HIGH to get the LED back on.

**c. What circuit element would you want to add to protect the board and external LED?**<BR>
You need to add a resistor to protext the LED and board.
 
**d. At what delay can you no longer *perceive* the LED blinking? How can you prove to yourself that it is, in fact, still blinking?**<BR>


### 2. Blink your LED

**Make a video of your LED blinking, and add it to your lab submission.**

[link to your video here; feel free to upload to youtube and just paste in a link here]


## Part D. Manually fade an LED

**a. Are you able to get the LED to glow the whole turning range of the potentiometer? Why or why not?**


## Part E. Fade an LED using Arduino

**a. What do you have to modify to make the code control the circuit you've built on your breadboard?**

**b. What is analogWrite()? How is that different than digitalWrite()?**


## Part F. FRANKENLIGHT!!!

### 1. Take apart your electronic device, and draw a schematic of what is inside. 

**a. Is there computation in your device? Where is it? What do you think is happening inside the "computer?"**

**b. Are there sensors on your device? How do they work? How is the sensed information conveyed to other portions of the device?**

**c. How is the device powered? Is there any transformation or regulation of the power? How is that done? What voltages are used throughout the system?**

**d. Is information stored in your device? Where? How?**

### 2. Using your schematic, figure out where a good point would be to hijack your device and implant an LED.

**Describe what you did here.**

### 3. Build your light!

**Make a video showing off your Frankenlight.**

**Include any schematics or photos in your lab write-up.**
