# Make a Digital Timer!
 
## Overview
For this assignment, you are going to 

A) [Solder your LCD panel](#part-a-solder-your-lcd-panel)

B) [Write text to an LCD Panel](#part-b-writing-to-the-lcd) 

c) [Using a time-based digital sensor!](#part-c-using-a-time-based-digital-sensor)

D) [Make your Arduino sing!](#part-d-make-your-arduino-sing)

E) [Make your own timer](#part-e-make-your-own-timer) 
 
## In The Report
Include your responses to the bold questions on your own fork of [this lab report template](https://github.com/FAR-Lab/IDD-Fa18-Lab2). Include snippets of code that explain what you did. Deliverables are due next Tuesday. Post your lab reports as README.md pages on your GitHub, and post a link to that on your main class hub page.

## Part A. Solder your LCD panel

**Take a picture of your soldered panel and add it here!**
![Code](https://github.com/jamiekimyu/IDD-Fa18-Lab2/blob/master/20180910_125008.jpg)

## Part B. Writing to the LCD
 
**a. What voltage level do you need to power your display?**
5V

**b. What voltage level do you need to power the display backlight?**
3.3V
   
**c. What was one mistake you made when wiring up the display? How did you fix it?**
I mixed up the pins on IO pins 12 and 11 and RS and E. To fix it I just switched the pins. In the future I want to try to use as many ground cables as possible so the connections are easier to read. 

**d. What line of code do you need to change to make it flash your name instead of "Hello World"?**
`lcd.print("hello, world!");` I would replace 'hello, world!' with my name

**e. Include a copy of your Lowly Multimeter code in your lab write-up.**
[Code](https://github.com/jamiekimyu/IDD-Fa18-Lab2/blob/master/code.ino)


## Part C. Using a time-based digital sensor

**Upload a video of your working rotary encoder here.**
[Working Rotary Encoder](https://www.youtube.com/watch?v=IWdhRCE1wdY)


## Part D. Make your Arduino sing!

**a. How would you change the code to make the song play twice as fast?**
The length of pause between each note is definied in the following code: `int pauseBetweenNotes = noteDuration * 1.30;`. To make the song play twice as fast I would multiple the variable `pauseBetweenNotes` by 0.5. 
 
**b. What song is playing?**
A Star Wars song

## Part E. Make your own timer

**a. Make a short video showing how your timer works, and what happens when time is up!**
[Timer](https://www.youtube.com/watch?v=Svlp_OsH0dg)

**b. Post a link to the completed lab report your class hub GitHub repo.**
