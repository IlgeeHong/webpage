---
authors:
- admin
categories:
- Randomized SQP
date: "2020-12-13T00:00:00Z"
draft: false
featured: false
image:
  caption: 'Image reference: [**Richtarik**](https://arxiv.org/abs/1506.03296)'
  focal_point: ""
  placement: 1
  preview_only: false
lastmod: "2020-12-13T00:00:00Z"
projects: []
subtitle: "Sequential Quadratic Programming (SQP) method is combined with Iterative random sketching (IRS) to provide exceptionally low computational complexities in solving large scale nonlinear optimization problem."
summary: ""
tags:
title: Randomized SQP
---

## Overview

- **Why Sequential Quadratic Programming (SQP)?**\
A big advantage of SQP is that it is not a feasible-point method (e.g. interior-point method) which only allows a feasible sequence of iterates. Finding a feasible point with respect to nonlinear constraints sometimes as hard as solving original problem. On the other hand, SQP method computes the search direction without considering the penalties of violating constraints, so that the penalty parameter only affects the size of step, but not the direction. This resolves the ill-conditioning issue and preserves the structure of the objective.<br>
<br>
- **Why Iterative Random Sketching (IRS)?**\
One of subroutine of SQP is solving linear system of equation. However, in large scale optimization setting, the floating point complexity to solve the linear system of equation is huge. Therefore, by using IRS, we can reduce the size of the linear system of equation, hence, solve the large scale nonlinear optimization problem with exceptionally low computational complexities.


