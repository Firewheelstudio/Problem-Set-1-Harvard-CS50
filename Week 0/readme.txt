Welcome everybody to my first solo game! 

Still in early iteration, submitting for CS50 Problem Set 0. 

In order to use this, please visit https://scratch.mit.edu/

From there you will go to Create -> Load from your computer then use this file to run the game. 

Please click the green flag in the top right corner in order to use the game. 

The game idea is simply a Homerun Derby. Eventually I'd like to make it so you can
increase the speed of the ball being thrown towards 1x-2x and call the current speed 60-70mph range. 

Growing up we use to play baseball games on the N64 but I remember my favorite part of this whole game was just simply trying out the Homerun Derby and trying to get the maximum number of hits. 

Eventually 1.0 Goal (if I can keep iterating on this and submit it for the course online, we'll see what the next projects are) is to offer the ability to scale the difficulty to 1x-2x speed, then give a "Best of 20" and offer a way for people to keep a Total Yards Hit count, and an increase in points offered based on the speed of the ball. 

Currently in order to play you hit any button after hitting the Next Round button and it's limited to one speed setting. 

A known bug is that there is some issues with how to prevent the player from swinging multiple times and causing a bug in the words the Catcher is saying. It's also possible to swing multiple times and it should register a "Hit Ball" if you at least hit any button while the user already swung before and cause a mismatch in the intended graphics on screen.

Most significant bug fix before submitting was there was previous a co-routine issue where the words the Catcher said were from the Pitch that was Swung at before but it was fixed with adding some commands to the Forever If statement. 