---
layout: post
title: Methods of finding general solution of given differential equation
date: 2018-01-01 13:32:20 +0300
description: The post describes various methods of solving a given differential equations
#img: i-rest.jpg # Add image post (optional)
tags: [Mathematics,Science,Calculus]
---

Let us consider the given differential equation is
  > y'' + p(t)y' + q(t)y = g(t) ----------- (i)

If `g(t) = 0`, then it becomes homogenous differential equation. Here, we are going to discuss about the process of finding general solution of non homogenous equations i.e. `g(t) = 0` by the method of undetermined coefficients.

The differential equation is: `y''+p(t)y'+q(t)y=g(t)`, where g(t) can be in the following form:
- g(t) can be in algebric form or can be polynomial.
- g(t) can be in exponential form.
- g(t) can be in trigonometric form i.e. in form of sint or cost.

According to the nature of g(t), the particular solution of given differential equation can be determined.
For example:
- If `g(t) = 3cos2t` (It is in trigonometric form). It's particular solution can be `y = Acos2t + Bsin2t`
- If `g(t)` is in more than one form, two equations should be considered.

This can be more clear by the examples of given below:
- Find general solution of the given differential equations :
  > `y''+2y'+5y=3cos2t` ---- (i)

  First we consider homogenous equation:
  > `y''+2y'+5y=0`

  The characteristic equation is:
  > r^2+2r+5=0
  > `still left to write`

  The roots are complex so,
  > `yc = c1e^-tcos2t + c2e^-tsin2t` ---- (ii)
