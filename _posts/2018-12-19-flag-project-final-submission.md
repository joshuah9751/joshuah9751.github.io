---
layout: post
title: "Flag Project - Final Submission"
date: 2018-12-21
---

## Flag of Sweden by Joshua Hernandez

## Describe your program

-   I designed for the country Sweden
-   I except a grade of atleast Apprentice or Practitioner.

## Current output

* * *
![Flag](/images/swedish-flag.png)
* * *

## Describe your process.

 -  Well, Instead of seperately typing down the code, I placed-image, I saw from a peer and I used that information to make my own flag, and one of my other peers had a type of blue that I was trying to look for so I asked and that is how I found the blue I was looking for.
 
## Explain your code.

-   Choose a significant part of your program (15 lines max) and paste it below. Do not insert your entire program here. _then delete this instruction_
-   Explain each argument in the code section. _then delete this instruction_
-   Tell us how it functions independently and within the whole program _then delete this instruction_

* * *

```
BR = rectangle(width, height, "solid", "royal-blue")

YR = rectangle(width / 8, height, "solid", "gold") 

YR2 = rectangle(width, height / 5, "solid", "gold")

BR-YR2 = place-image(YR2, width / 2, height / 2, BR)

BR-YR2-YR = place-image(YR, width / 3, height / 2, BR-YR2)
```

* * *

-   Explain the code you posted by telling us about each argument.
-   Then tell us how your code section fits into the whole.


## Program code

```
include image

size = 200
width = size * 1.6
height = size * 1



BR = rectangle(width, height, "solid", "royal-blue")

YR = rectangle(width / 8, height, "solid", "gold") 

YR2 = rectangle(width, height / 5, "solid", "gold")

BR-YR2 = place-image(YR2, width / 2, height / 2, BR)

BR-YR2-YR = place-image(YR, width / 3, height / 2, BR-YR2)
```
