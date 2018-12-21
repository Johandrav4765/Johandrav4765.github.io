---
layout: post
title: "Flag Project - Final Submission"
date: 2018-12-21
---
# Flag of pakistan by Johandra Vargas 

## Describe your program

-  The program that I currently made represents the flag of Pakistan.
-   The grade I expect is a practitioner, because I worked really hard on it and asked peers for advice about it.

## Current output

* * *
![Flag](/images/oof.png)
* * *

## Describe your process.

-   At first I struggled with making such a flag. What i found complicated was making a cresent and putting the exact placement and measurements of simple shapes. I went around asking some of my peers for help, they recommended on working piece by piece. I questioned why we had to use the word height and width instead of using numbers? why we had to do all of this complicated code with fractions..Later on my peer told me that all of this will make the script easier when I revise and edit it. My teacher kept recommendening on using short cuts, these short cuts are just in case we change a specific type of abstraction in the functions.

## Explain your code.

- The simple parts contain simple shapes. They are the beginning process that leads to the combination. Each part represents a shape oof: rectangle, gr:rectangle,wc:circle,gc:circle, and ws: star. ah: represents the rotation of ws.
Combination represents the combination of the simple parts, each script within that section builds up until they lead to a final image. The image being the Pakistan flag.

-Simple parts: It provides basic height, width, size , type and color of a shape. It is the template for Combinations. Yet each shape contains it's very own specgic function, the functions well be used later on in the combinations to combine images together and make the flag.
Combinations: holds functions from simple parts, and create a new function to combine other functions. The function that I used was place-image, this allows me to prserve the shape and size of the shape while letting me put it on top of another shape, which is usual called the background.As I pile each shape in different functions, at some point the final result would be a flag.

* * *

#SimpleParts
oof = rectangle(75, height,  "solid", "white")

gr = rectangle(300, 200, "solid", "dark-green" )

wc = circle(60, "solid", "white")

gc = circle(55, "solid", "dark-green")

ws = star(25,"solid", "white")

ah = rotate(26, ws)
#Combination
oof-gr = place-image(oof, 35, 75, gr)

fc = place-image(wc, 185,100,oof-gr)

sd = place-image(gc,200,85,fc)

Pakistan = place-image(ah,210,75,sd) 

Simple parts: It provides basic height, width, size , type and color of a shape. It is the template for Combinations. Yet each shape contains it's very own specgic function, the functions well be used later on in the combinations to combine images together and make the flag.
Combinations: holds functions from simple parts, and create a new function to combine other functions. The function that I used was place-image, this allows me to prserve the shape and size of the shape while letting me put it on top of another shape, which is usual called the background.As I pile each shape in different functions, at some point the final result would lead 


* * *

-   Explain the code you posted by telling us about each argument.
-   Then tell us how your code section fits into the whole.
 
<!--- Delete this comment and add your writing -->


## Program code

#Pakistan Flag 

height =  280
circle-radius = height * 3/10

#Simple Parts 

oof = rectangle(75, height,  "solid", "white")

gr = rectangle(300, 200, "solid", "dark-green" )

wc = circle(60, "solid", "white")

gc = circle(55, "solid", "dark-green")

ws = star(25,"solid", "white")

ah = rotate(26, ws)

#Combination of Simple Parts 

oof-gr = place-image(oof, 35, 75, gr)

fc = place-image(wc, 185,100,oof-gr)

sd = place-image(gc,200,85,fc)

Pakistan = place-image(ah,210,75,sd) 
