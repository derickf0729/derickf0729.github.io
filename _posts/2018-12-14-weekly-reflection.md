---
layout:post
title:"Flag project-in progress"
date:2018-12-14
---
  
 Currenlty in my Greece flag program i've figured out how to create the stripes and the base of the flag. Below is the current state of my flag program. 
 ``` 
  (define gblue(make-color 13 94 175 ))
(define base  (rectangle 600 400 "solid" gblue))
(define stripe(rectangle 400 50 "solid" "white"))

(rectangle 400 50 "solid" "white")400 325
(put-image stripe 400 325 base)        
(put-image stripe 400 275 base)
(put-image stripe 400 225 base)

```
![download](/images/WeScheme Image.png)
