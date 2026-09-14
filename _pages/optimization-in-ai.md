---
layout: page
permalink: /optimization-in-ai/
title: Optimization in AI
description: Department of Industrial Engineering, Tsinghua University
nav: true
nav_order: 4
---

<!-- Course information follows the current Class 01 slides in optimization_in_AI.
     Later topics are tentative; do not publish the legacy class_02–class_14 decks.
     Topic groups are not individual class numbers. -->

How does the structure of a learning problem shape the optimizer—and how does that choice affect training?
This course connects optimization theory, algorithm design, and the practical behavior of AI training.
We will study gradient and stochastic methods, momentum, adaptive optimizers, and weight decay, with attention to
convergence, conditioning, gradient noise, and the compute and memory constraints of modern models.

[Course information](#course-information) · [Schedule](#schedule) · [References](#references)

## Course information

- **Instructor:** [Jianhao Ma]({{ '/' | relative_url }}) · [jianhao@tsinghua.edu.cn](mailto:jianhao@tsinghua.edu.cn)
- **Teaching assistant:** Yuzhen Chen (陈禹臻), Department of Industrial Engineering
- **Class time:** Wednesdays, 9:50–11:25.
- **Location:** 六教 6B113.
- **Office hours:** Wednesdays, 1–2 pm.

## Schedule

<div class="table-responsive" markdown="1">

| Topic                       | Coverage                                                                                       | Materials |
| :-------------------------- | :--------------------------------------------------------------------------------------------- | :-------- |
| Introduction                | Course overview; problem structure and optimizer design                                        |           |
| Mathematical foundations    | Matrix calculus, backpropagation, autodiff, convexity, optimality, and smoothness              |           |
| Gradient descent            | Convergence, stepsizes, conditioning, and smooth and nonsmooth problems                        |           |
| Stochastic gradient descent | Gradient noise, minibatches, learning-rate schedules, and convergence                          |           |
| Momentum                    | Heavy-ball dynamics, acceleration, and stochastic averaging                                    |           |
| Adaptive optimizers         | AdaGrad, RMSProp, Adam, and Muon                                                               |           |
| Weight decay                | L2 regularization, decoupled weight decay, and AdamW                                           |           |
| Selected advanced topics    | Topics chosen based on course progress and recent developments, including second-order methods |           |

</div>

**Guest lecture:** Yushun Zhang (DeepSeek). Date and topic to be announced.

## References

- Stephen Boyd and Lieven Vandenberghe, [_Convex Optimization_](https://web.stanford.edu/~boyd/cvxbook/).
- Sébastien Bubeck, [_Convex Optimization: Algorithms and Complexity_](https://arxiv.org/abs/1405.4980).
- Elad Hazan, [_Optimization for Machine Learning_](https://arxiv.org/abs/1909.03550).
- Jorge Nocedal and Stephen J. Wright, _Numerical Optimization_.

### Related courses

- Yuxin Chen, [Large-Scale Optimization for Data Science](https://yuxinchen2020.github.io/large_scale_optimization/syllabus.html), University of Pennsylvania.
- Damek Davis, [Numerical Optimization for Data Science and Machine Learning](https://damek.github.io/STAT-4830/), University of Pennsylvania.
- Dmitriy Drusvyatskiy, [Advanced Optimization](https://ddrusvyat.github.io/DSC-243/), UC San Diego.
