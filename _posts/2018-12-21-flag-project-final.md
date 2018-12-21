---
layout: post
title: "Flag Project - Final Submission"
date: 2018-12-21
---

## Flag of Greece by Derick Frias

## Describe your program

 I designed this flag for Greece
 I expect either a 3 or 2 because I was able to create the flag and make it as close to the real flag as possible, but i was not able to create a function do scale it.


## Current output

* * *
![Flag](/images/finalflag.png)
* * *

## Describe your process.

 First I made a refrence by researching the flag and creating a collage of the flag. Then I had to figure out how to connect each stripe to the same image, to figure this out I asked one of my peers how to use put-image and he explained to me what I was doing wrong and showed me how to properly use put-image which helped me to get to the point at which I am at now . 


## Explain your code.

   Choose a significant part of your program (15 lines max) and paste it below. Do not insert your entire program here. _then delete this instruction_
 The first argument is the color of my base and this a signicicant part of my program because I really wanted to get the exact colors of the flag. 
  This argument is what gives me base it's color and it's where all the stripes are put on. 

* * *

```
(define gblue(make-color 13 94 175 ))
(define base (rectangle 600 330 "solid" gblue))
(define stripe(rectangle 400 35 "solid" "white"))
(define longstripe(rectangle 800 35 "solid""white"))
(define verticalstripe(rectangle 45 325 "solid""white"))
(define horizontalstripe(rectangle 325 40 "solid""white"))
(define blueline(rectangle 800 35 "solid"gblue))
(define testbase(rectangle 600 400 "solid" "white"))
```

* * *

Each function above is what my flag is made out of
-   Then tell us how your code section fits into the whole.
 
<!--- Delete this comment and add your writing -->


## Program code

```
Insert entire program here _then delete this instruction_
```
