---
layout: post
title: "Flag Project - Final Submission"
date: 2018-12-21
---

## Flag of _Pakistan_ by _Emir Kutun_

## Describe your program

<!--- I designed the flag of Pakistan. I would expect a 3 because I may have gotten a few minor details wrong, but generally, I got the characteristics right. -->

## Current output


* * *
![Flag](/images/final-flag.png)
* * *

## Describe your process.

<!--- I compared my flag to Pakistan's as accurately as possible.-->


## Explain your code.

-   (->(shape1 sSIZE m1 c1)
          xC yC
          (-> (shape2  eWIDTH eHEIGHT m1 c2)
                     xC2 yC2
                     (-> (shape3 cSIZE m1 c1)
                                xC3 yC3
                                (-> (shape4 rWIDTH rHEIGHT m1 c1)
                                           xC4 yC4
                                           (shape4 WIDTH HEIGHT m1 c2)))))
(define WIDTH 473)
(define HEIGHT 290)
(define eWIDTH 160)
(define eHEIGHT 150)
(define cSIZE 90)
(define sSIZE 37)
-   This shows my code and some of the definitions that make it what it is.
-   With these definitions, I can completely eliminate the use of code in the main code.

* * *

```
(define WIDTH 473)
(define HEIGHT 290)
(define eWIDTH 160)
(define eHEIGHT 150)
(define cSIZE 90)
(define sSIZE 37)
```

* * *

-   Explain the code you posted by telling us about each argument.
-   Then tell us how your code section fits into the whole.
 
<!--- This code makes it so whenever I type "WIDTH" into code, the program can recognize it as 473. This way, I can save time, because rather than typing "473", I can simply write "WIDTH". -->


## Program code

```
(->(shape1 sSIZE m1 c1)
          xC yC
          (-> (shape2  eWIDTH eHEIGHT m1 c2)
                     xC2 yC2
                     (-> (shape3 cSIZE m1 c1)
                                xC3 yC3
                                (-> (shape4 rWIDTH rHEIGHT m1 c1)
                                           xC4 yC4
                                           (shape4 WIDTH HEIGHT m1 c2)))))
(define WIDTH 473)
(define HEIGHT 290)
(define eWIDTH 160)
(define eHEIGHT 150)
(define cSIZE 90)
(define sSIZE 37)
(define rWIDTH 140)
(define rHEIGHT 310)
(define xC 345)
(define xC2 325)
(define xC3 295)
(define xC4 34)
(define yC 190)
(define yC2 170)
(define yC3 150)
(define yC4 146)
(define m1 "solid")
(define m2 "outline")
(define c1 "whitesmoke")
(define c2 "dark green")
(define shape1 star)
(define shape2 ellipse)
(define shape3 circle)
(define shape4 rectangle)
(define -> put-image)

```
