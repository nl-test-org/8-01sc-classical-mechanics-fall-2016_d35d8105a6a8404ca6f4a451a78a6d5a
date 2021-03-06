---
course_id: 8-01sc-classical-mechanics-fall-2016
layout: course_section
menu:
  leftnav:
    identifier: fc4bb7fe8852f18ed0a7cc1c4ea5e402
    name: "Lesson 10: Circular Motion \u2013 Acceleration [10.1-10.4]"
    parent: 3c7d357cbb95e729679b539d23714ede
    weight: 660
parent_title: 'Week 3: Circular Motion'
title: "10.1 Circular Motion \u2013 Acceleration"
type: course
uid: fc4bb7fe8852f18ed0a7cc1c4ea5e402

---

« [Previous]({{< baseurl >}}/sections/week-3-circular-motion/9.3-period-and-frequency) | [Next]({{< baseurl >}}/sections/week-3-circular-motion/10.2-angular-acceleration) »

Acceleration in Circular Motion: \\(\\vec{a} = r\\frac{d^2\\theta}{dt^2}\\hat{\\theta} + r(\\frac{d\\theta}{dt})^2(-\\hat{r})\\)

{{< youtube _0PrwAbgoMA >}}

**For circular motion, show that \\( \\frac{d \\hat{\\theta}}{dt} = -\\frac{d \\theta}{dt}\\hat{r}\\)**

We know that \\( \\hat{\\theta } \\) changes direction as we go around a circle, and so if a particle is undergoing circular motion, we expect \\(\\frac{d\\hat{\\theta }}{dt}\\) to be non-zero. To figure out exactly what it is, let us write \\(\\hat{\\theta }\\) in terms of \\(\\hat{i}\\) and \\(\\hat{j}\\) for an arbitrary \\(\\theta\\).

![A diagram illustrating circular acceleration.](/coursemedia/8-01sc-classical-mechanics-fall-2016/41c189b5309d6b11cfa74969017977e6_polarCoords1.svg)

\\( \\begin{align} \\hat{\\theta} = -\\sin(\\theta) \\hat{i} + \\cos(\\theta) \\hat{j} \\end{align} \\)

Since \\(\\hat{i}\\) and \\(\\hat{j}\\) are constant anywhere in space, they are not time-dependent, so now the derivative becomes much more clear. Using the chain rule, we have:

\\( \\begin{align} \\frac{d\\hat{\\theta}}{dt} = -\\cos(\\theta) \\frac{d\\theta}{dt} \\hat{i} - \\sin(\\theta) \\frac{d\\theta}{dt} \\hat{j} = - \\frac{d\\theta}{dt} \\left(\\cos(\\theta) \\hat{i} + \\sin(\\theta)\\hat{j} \\right) \\end{align} \\)

We know that \\( \\left(\\cos(\\theta) \\hat{i} + \\sin(\\theta)\\hat{j} \\right) = \\hat{r} \\), so we can now simply write this derivative as:

\\\[ \\begin{align} \\frac{d\\hat{\\theta}}{dt} = - \\frac{d\\theta}{dt} \\hat{r} \\end{align} \\\]

« [Previous]({{< baseurl >}}/sections/week-3-circular-motion/9.3-period-and-frequency) | [Next]({{< baseurl >}}/sections/week-3-circular-motion/10.2-angular-acceleration) »