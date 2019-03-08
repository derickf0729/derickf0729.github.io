- - -
layout:post
date:2019:03:08
name: Derick frias
- - -

link to game: https://www.wescheme.org/view?publicId=Vzdq8MET1C

Game title: Game

My game is about a robot that is in the forest looking for emeralds, but a dangerous red triangle is after the robot. 

Piece code: 
```
(EXAMPLE(onscreen? 80)(and(safe-left? 80)(safe-right? 80)))
(EXAMPLE(onscreen? -80)(and(safe-left? -80)(safe-right? -80)))

(define (onscreen? x)
  (and(safe-left? x)(safe-right? x)))
```
Explanation of the piece of code: 

The first line of the code is an example for the function onscreen?
The EXAMPLE is taking in the point 80 and then the function onscreen determines if it’s safe on the right and safe on the left.
On the second line it’s the same as the first line except i used a negative number. 
Then on the last two lines which is the definition of onscreen which starts off with (define then the function you want to define so (define(offscreen? Then you put a variable which leaves you with (define(offscreen? X). After the Third line on the fourth line is the rest of the definition which is where the function compares the number to safe-left? And safe-right?.

This is a screenshot of my game:
* * *
![download](/images/WeScheme Image.png)
* * *
