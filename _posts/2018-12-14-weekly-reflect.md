---
layout: post
title: "Flag Project in Process"
date: 2018-12-14
---

I finished the first draft of the Pakistani flag, fixing my previous mistakes from last time, such as the thickness of the moon.
Here it is: ```(put-image(star sSIZE m1 c1)
          xC yC
          (put-image (ellipse  eWIDTH eHEIGHT m1 c2)
                     xC2 yC2
                     (put-image (circle cSIZE m1 c1)
                                xC3 yC3
                                (put-image (rectangle rWIDTH rHEIGHT m1 c1)
                                           xC4 yC4
                                           (rectangle WIDTH HEIGHT m1 c2)))))
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
(define c1 "whitesmoke")
(define c2 "darkgreen")```
