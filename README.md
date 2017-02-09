# Welcome this is the official repo for project 4
##UCLA ACM HACK

If you've missed the fourth session, check out the blog post first: 

##What do I turn in
For beginners you should solve all of the listed short exercises and receive points for completing those. These are unrelated to the project skeleton in this repo. For intermediate/advanced students you can work on the weekly project with your team, and receive points for completing that. You can only get credit for one or the other, but not for both so choose the one most appropriate for your skill level. Please only submit one .zip file per team. Include the contents of your entire android project, and also provide your team access code (Found on Hack School Dashboard) in a text file. Otherwise you will not receive credit! 

##Grading
Submissions will be due 1 week from the session, but we will accept late submissions taking some points for each day it is late. The lateness penalty for an assignment that is submitted between N and N+1 full days late (where N is nonnegative) is 2^N % of the assignment's value. That is, the penalty is 1% for being up to 1 day late, 2% for being from 1 to 2 days late, 4% for being from 2 to 3 days late, and so forth.

##Beginner Exercises

######Exercise 1:
For the first part your goal is build a very basic audio player
* Choose a random audio clip 
* Create a one page app with three buttons
* The first button should be for play/pause, meaning the image of the button should change when pressed from a play icon to a pause icon
* The second button should be a start button that begins playing the audio file
* The third button should be a stop button that stops playing the audio file.

Extra Credit: 
* For more points add a edittext, and have the audio player play a song based off the text provided. For example if you have audio1.mp3 and audio2.mp3, then typing in audio1 and hitting play should start the first audio file. 


######Exercise 2:
For the second part your goal is build a very basic video player
* Choose a random video clip 
* Create a one page app with three buttons
* The first button should be for play/pause, meaning the image of the button should change when pressed from a play icon to a pause icon
* The second button should be a start button that begins playing the video file
* The third button should be a stop button that stops playing the video file.

Extra Credit: 
* For more points add a edittext, and have the video player play a clip based off the text provided. For example if you have video1.mkv and video2.mkv, then typing in video1 and hitting play should start the first video file. 


######Exercise 3:
Add a button to the screen in exercise 1 that when pressed, causes the app to transition to the screen in exercise 2.

Note: Put all of your exercises into the same android project when submitting

##Intermediate/Advanced Project
The project is for intermediate/advanced students. If you are feeling confident you can attempt to 
complete the project without the skeleton, but it will be a lot easier to use it. We will be uploading the project solution later on, so if you haven't cracked it by then look at the solution to learn the correct implementation.

###Instructions
The goal is to build a basic camera application with as little guidance as possible, so try to come up with unique solutions when you run into problems. You're being given lots of flexibility so come up with your own implementation: grading will be very generous. For this project you've been only provided with the main menu ui, so the goal is to create the rest of the application your self. Here are instruction for each specific screen:

######Main Menu Screen
* Create two intents that will trigger when each of the respective buttons is pressed. 
* The "Take Picture" button should take you to a CameraActivity, and the "View Gallery" button should take you to the GalleryActivity. 

######Camera Screen
* This is the camera screen of your application, meaning the upper portion of this should act as the camera. So the above portion should update in realtime as you move your phone's camera around. 
* The big capture button should take a picture, and store it on your phones memory when pressed.

Extra Credit:
For additional points you can also implement the reverse direction button to switch between front and back cameras, and the flash button to toggle the flash on/off.

######Gallery Screen
* Should show the three most recent images that a user has capture using the camera screen

Extra Credit:
You can try implementing a dynamic screen which displays all of the images you have captured instead of the three most recent. This should be a scrollable view.

###End Product Goal
Main Menu
![](https://s3-us-west-1.amazonaws.com/acm-hack-ghost/2017/02/BruinCam-Menu_nexus5x-portrait.png)
Camera 
![](https://s3-us-west-1.amazonaws.com/acm-hack-ghost/2017/02/BruinCam-Camera_nexus5x-portrait.png)
Gallery
![](https://s3-us-west-1.amazonaws.com/acm-hack-ghost/2017/02/BruinCam-Gallery_nexus5x-portrait.png)
