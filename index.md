---
title       : CheckMyBMI - A handy web based BMI calculator
subtitle    : See how you measure up
author      : 
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [mathjax, quiz, bootstrap]       # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
logo        : apple_with_tape.jpg
---

## What is BMI?

BMI or Body Mass Index is a simple metric that gives an indication of whether a person is underweight, overweight or a healthy weight.

$$latex
BMI = \frac{mass}{height^2}
$$

where mass is in kg and height is in metres.

It is independent of age (although it isn't appropriate for children) and works equally well for both genders. For example

```r
mass <- 60
height  <- 1.8

bmi <- mass/height^2
bmi
```

```
## [1] 18.52
```

--- .class #id 

## How does the app work?

CheckMyBMI is very simple to use. It is hosted on the web at 

<div style='text-align: center;'> https://kendra.shinyapps.io/newApp </div>

and will work with any modern browser or even on a smartphone.

The user simply enters their mass and height and presses "Go calculate!"

<div style='text-align: center;'>
<img height='50' src='assets/img/BMIpic.png'/>
</div>



--- &radio

## So just how fat are we getting?

What percentage of Australian adults are overweight or obese in 2014?

1. 22%
2. 37%
3. _60%_
4. 74%
*** .hint 
It's more than half the population!

*** .explanation 
It's 60% of the population or 3 out of every 5 adults.

--- .class #id

## Thanks for reading

I hope you will 
- give CheckMyBMI a go
- share it with your friends 

Many thanks and much kudos to Ramnath Vaidyanathan for the amazing Slidify package which was used to create this presentation. 
Check it out for yourself at http://slidify.github.io/



