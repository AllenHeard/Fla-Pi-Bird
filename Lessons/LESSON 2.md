##Lesson 2

###Introduction
This lesson aims to get students successfully moving graphics around the screen. The game requires the bird to move up briefly when the up arrow is pressed, and then it falls when there is no interaction. The pipes should enter the screen from the right and scroll from right to left.

###Learning Objectives
Students will understand about user interaction and how to model movement using Scratch code.

###Learning Outcomes

#####All students are able to
* Get the bird moving up and down.
* Get the pipes scrolling across the screen.

#####Most students are able to
* Get the bird pointing in different directions based on their direction of movement.

#####Some students are able to
* Modify the values to get the sprites moving slower/faster.

###Lesson Summary
Students will implement Scratch code to their previous game save to get the graphics moving as they should. At this stage it's important to point out to pupils at this stage that not every problem in the game is solved at once, so for instance, when this lesson is over, the bird will be able to crash into a pipe and nothing will happen yet.

###Starter
Talk about the various forms of user interaction in games (controllers, keyboard, gestures, etc). Then show this image on the screen and ask pupils to list any and all movement that could possibly be going on. They should also highlight what user interaction is required to play this game.
![Starter Image](https://github.com/AllenHeard/Fla-Pi-Bird/blob/master/Screenshots/Lesson%202%20starter%20image.jpg?raw=true)
###Main Development
We will start by adding some code to the Fla-Pi bird sprite (make sure it's selected) to get it appearing at the right place on the screen when the game starts.  
![Bird Start Position](https://github.com/AllenHeard/Fla-Pi-Bird/blob/master/Code%20Blocks%20by%20Lesson/2%20Moving%20Sprites/2.3%20Bird%20Code.jpg?raw=true)  
The next piece of code (still in the bird scripts section) will give the impression of movement by changing the costume of the bird to make it look like it's flapping its wings.  
![Bird Costume](https://github.com/AllenHeard/Fla-Pi-Bird/blob/master/Code%20Blocks%20by%20Lesson/2%20Moving%20Sprites/2.2%20Bird%20Code.jpg?raw=true)  
The last piece of code for the bird is to create movement when the user presses a key. The bird should also fall when there is no interaction from the user. The code starts with a when I receive start followed by a forever loop. So for a slong as the game is running do whatever is inside the loop. This consists of an if statement that checks if the up arrow is pressed, if it is, the bird rises up 5 and turns to point upwards, there is a brief delay of 0.05 seconds (this ensures the player doesnt rise too quickly). The bird then turns to face downwards. Finally, in hte else section, if nothing is pressed, the bird falls -5.  
  
At this stage students should save the file as Moving.sb and test it out, they could also experiment with different values in the degrees section and the y axis, or you may choose not to give more able students these values initially and let them discover what may work best.  
  
  
  
 



###Plenary

  
