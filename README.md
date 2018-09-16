# ParaLife
https://prezi.com/view/no4CTOHRtG9Cp0lfYXRQ/

## Inspiration
We want to create a platform for those who are not able to interact with computers and the world as simply as others.
It should enable them to interact socially, access education and employment opportunities and get entertained without being much dependant on others.

## What it does
ParaLife uses gaze based technologies to control the mouse cursor movement through eye movement or nose movement to help the specially abled people to interact with computers.
Mouse clicks are simulated through eye blinks where:
1. Right blink -> right click
2. Left blink-> left click
3. Both blink-> double click

It also has a cross-platform app to enhance their experience and make their lives simpler by providing features like:
1. Easy social interactions through icon based communicator
2. Easy access to entertainment
3. Ease of accessibility through automation integration
4. Increased security through SOS features

## How we built it
We used openCV and Dlib library in python to mark face landmarks using HOG based features classifier.From the extracted features the position of nose/eyes is used to calculate the relative position to which the cursor should be moved. Also the Eye Aspect Ratio is calculated to detect eye blinks. 
Also we created a cross platform app using electron and javascript that provides the above mentioned features.

## Challenges we ran into
1. Coordinating the cursor movement with eye/nose movement
2. Trying to segregate natural blinks from intentional blinks
3. Creating an UX that can be easily controlled through gaze

## Accomplishments that we're proud of
1. Smooth and effective cursor movement just with use of inbuilt webcam.
2. Creating an effective icon to language communicator for easy social interactions

## What we learned
1. Facial Landmarking using openCV
2. Problems faced by paralytic people and their potential solutions

## What's next for ParaLife
1. Improve the accuracy of the cursor movement through better trained models 
2. Add more features to the platform like live ASL converter, voice control, medication tracker,etc to help a wider audience
3. Integrate the platform with iot solutions 
