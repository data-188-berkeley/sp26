---
layout: page
title: Welcome to Data 188!
nav_exclude: true
permalink: /
seo:
  type: Course
  name: Data 188 Spring 2026
---
# Main Page

{:.no_toc}

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

This is the course website for Data 188, "Introduction to Deep Learning", Spring 2026, UC Berkeley.

## Course Description

From the [UC Berkeley course catalog](https://classes.berkeley.edu/content/2026-spring-data-188-001-sem-001):

This course is an introduction to deep learning (also known as "deep neural networks"), and will cover the fundamental techniques that power deep learning algorithms, as well as exploring the intuitions and various "rules of thumb" behind successful deep learning methods. Topics include: neural network architectures, backpropagation, convolutional neural networks, sequence models (such as the transformer model), applications to computer vision and natural language processing, and more.

### Acknowledgements

This course is based off of a previous course, [Data C182 Fall 2024](https://datac182fa24.github.io/), designed by instructors Naveen Ashish and Eric Kim.

This course also adapts material from CMU's ["Deep Learning Systems"](https://dlsyscourse.org/) course (10-414/714, Fall 2025). Thanks to: Professor Zico Kolter, Professor Tianqi Chen, and Professor Tim Dettmers.

## Useful Course Links
**Important:** In this course, we will use Edstem to post announcements and important information.
It is the student's responsibility to actively monitor the Ed for any important announcements.

- bCourses: [link](https://bcourses.berkeley.edu/courses/1551684)
- Ed: [link](https://edstem.org/us/courses/91872/discussion)
- Gradescope: [link](https://www.gradescope.com/courses/1217889)
- Lecture Zoom link (TuTh 3:30pm - 5:00pm): [link](https://berkeley.zoom.us/j/98594186696)

**Note**: lecture starts during Week 01 (2026-01-20).
Discussion section and office hours will not start until Week 02 (2026-01-26).

## Textbooks
We will be using the following textbooks, all fortunately freely available online:
<ul>
<li>"Deep Learning: Foundations & Concepts" by Christopher Bishop & Hugh Bishop.
The free-to-use online version is at <a href="https://www.bishopbook.com/">Bishop Book</a>. Further, UC Berkeley students can access the PDF version via this link (CalNet login required): <a href="https://link-springer-com.libproxy.berkeley.edu/book/10.1007/978-3-031-45468-4">PDF</a>.
  </li>
  <li> "Deep Learning" by Ian Goodfellow and Yoshua Bengio and Aaron Courville. Free online link is <a href="https://www.deeplearningbook.org/">here</a>.
  </li>
  <li>
    (optional) Dive into Deep Learning <a href="https://d2l.ai/">D2LAI</a> is an excellent interactive online textbook and set of resources for Deep Learning ! (a PDF version of the entire book is also available online)
  </li>
</ul>

## Lectures
Lectures are Tuesdays and Thursdays, 3:30PM - 5PM, online via Zoom.
Lecture slides are provided via this website, and lecture videos are
provided via the bCourses ["Media Gallery"](https://bcourses.berkeley.edu/courses/1551684/external_tools/90481).

<!-- This Ed post ["Lecture Schedule"](https://TODO/add/link) contains more info about the lecture schedule, including: Zoom lecture links. -->

<!-- Here is an **optional weekly reading list** of supplemental material: [link](https://docs.google.com/document/d/1asBPDgxrI47hiQ2rjGBmdAXLWv02kopqDgcE4yyW718/edit).
While this is not required for the course, we believe that the material here can enhance understanding of the course and, more broadly, gain further exposure to the DNN field. -->

### Lecture Slides, Readings
Regarding reading:
The provided reading links are optional and are provided for students interested in additional resources.
The content in the reading will not always be "fair game" for exams: if something isn't covered in lecture/discussion/assignments, then it won't be in scope for exams.
The Bishop textbook doesn't always cleanly map to our lectures, but I've done my best to line things up.
Note that the Bishop textbook sometimes takes a different approach to concepts (eg Bishop is sometimes relatively probability-heavy) that we won't always follow in our course.

- Lecture 01 [Week 1, 2026-01-20] <a href="assets/lecture_slides/01_intro.pdf">Introduction</a>
  - Reading: (Bishop) Ch1.1
- Lecture 02 [Week 1, 2026-01-22] <a href="assets/lecture_slides/02_softmax_regression.pdf">ML Refresher, Softmax Regression</a>
  - Reading: (Bishop) Ch 1.2, Ch 5.4.4, Ch 7.2
- Lecture 03 [Week 2, 2026-01-27] <a href="assets/lecture_slides/03_manual_neural_nets.pdf">Manual Neural Networks</a>
  - Reading: (Bishop) Ch 1.2, Ch 1.3, Ch 4.1, Ch. 6.2, 6.3, 6.4
- Lecture 04 [Week 2, 2026-01-29] <a href="assets/lecture_slides/04_automatic_differentiation.pdf">Automatic Differentiation</a>
  - Reading: (Bishop) Ch 8.1, 8.2
- Lecture 05 [Week 3, 2026-02-03] <a href="assets/lecture_slides/05_automatic_differentiation_implementation.pdf">Needle Tour (Automatic Differentiation Implementation)</a>
  - Jupyter Notebook: <a href="https://colab.research.google.com/github/data-188-berkeley/lecture05_notebook/blob/main/05_automatic_differentiation_implementation.ipynb">"05_automatic_differentiation_implementation.ipynb"</a>
- Lecture 06 [Week 3, 2026-02-05] <a href="assets/lecture_slides/06_fc_init_opt.pdf">Fully-connected Networks, Optimization, Initialization</a>
- Lecture 07 [Week 4, 2026-02-10] Fully-connected Networks, Optimization, Initialization (continued)
- Lecture 08 [Week 4, 2026-02-12] <a href="assets/lecture_slides/07_nn_framework.pdf">Neural Network Library Abstractions</a>
- Lecture 09 [Week 5, 2026-02-17] <a href="assets/lecture_slides/08_norm_reg.pdf">Normalization, Regularization</a>
- Lecture 10 [Week 5, 2026-02-19] Neural Network Library Implementation
  - Jupyter Notebook: <a href="https://colab.research.google.com/github/data-188-berkeley/lecture10_nn_lib_impl_notebook/blob/main/10_nn_library_implementation.ipynb">"10_nn_library_implementation.ipynb"</a>
- Lecture 11 [Week 6, 2026-02-24] <a href="assets/lecture_slides/10_conv_nets.pdf">Convolutional Neural Networks</a>
- Lecture 12 [Week 6, 2026-02-26] <a href="assets/lecture_slides/11_computer_vision.pdf">Computer Vision</a>
- Lecture 13 [Week 7, 2026-03-03] <a href="assets/lecture_slides/12_computer_vision_part2.pdf">Computer Vision Part 2</a>
- Lecture 14 [Week 7, 2026-03-05] <a href="assets/lecture_slides/13_midterm_review.pdf">Midterm Review</a>
- Lecture N/A [Week 8, 2026-03-10] Midterm Exam (No lecture)
- Lecture N/A [Week 8, 2026-03-12] (No lecture)
- Lecture N/A [Week 9, 2026-03-17] (No lecture)
- Lecture 15 [Week 9, 2026-03-19] <a href="assets/lecture_slides/14_pytorch.pdf">Intro to PyTorch</a>
  - Jupyter Notebook: <a href="https://colab.research.google.com/github/data-188-berkeley/lecture15_pytorch_intro_notebook/blob/main/lec15_intro_to_pytorch.ipynb">"lec15_intro_to_pytorch.ipynb"</a>
  - Jupyter Notebook: <a href="https://colab.research.google.com/github/data-188-berkeley/lecture15_pytorch_intro_notebook/blob/main/lec15_intro_to_pytorch_gpu.ipynb">"lec15_intro_to_pytorch_gpu.ipynb"</a>
- Lecture N/A [Week 10, 2026-03-24] Spring Break (No lecture)
- Lecture N/A [Week 10, 2026-03-26] Spring Break (No lecture)
- Lecture 16 [Week 11, 2026-03-31] <a href="assets/lecture_slides/15_transformers.pdf">Transformers (MHA, Encoder)</a>
  - Bishop Chapter 12.1
- Lecture 17 [Week 11, 2026-04-02] <a href="assets/lecture_slides/16_transformers_part2.pdf">Transformers Part 2 (Cross attention, Decoder)</a>
  - Bishop Chapter 12.3
- Lecture 18 [Week 12, 2026-04-07] <a href="assets/lecture_slides/17_transformers_part3_vit.pdf">Transformers Part 3, Visual Transformer</a>
  - D2L: [Chapter 11.8](https://d2l.ai/chapter_attention-mechanisms-and-transformers/vision-transformer.html)
- Lecture 19 [Week 12, 2026-04-09] <a href="assets/lecture_slides/18_masked_autoencoder.pdf">Masked auto-encoder, large-scale pretraining</a>
- Lecture 20 [Week 13, 2026-04-14] <a href="assets/lecture_slides/19_scaling_up_training.pdf">Scaling up training (multi-GPU, distributed training)</a>
- Lecture 21 [Week 13, 2026-04-16] <a href="assets/lecture_slides/20_recommendation_systems.pdf">Intro to recommendation systems</a>
- Lecture 22 [Week 14, 2026-04-21] Large-scale NLP pretraining
  - D2L [Chapter 11.9](https://d2l.ai/chapter_attention-mechanisms-and-transformers/large-pretraining-transformers.html#encoder-only)
- Lecture 23 [Week 14, 2026-04-23]
- Lecture 24 [Week 15, 2026-04-28]
- Lecture 25 [Week 15, 2026-04-30] Final lecture: wrap-up,closing thoughts, advice


## Discussion Sections
You can attend any discussion section you like.
However, if there are less crowded sections that fit your schedule, those offer more opportunities for you to interact with your TA.
See this [calendar](calendar/) to view the available discussion section times and locations.

### Section Notes

- Discussion 01 (Week 2): Matrices, vectors, and gradients. [Section Notes]({%link assets/disc/dis01_question.pdf %}), [Solutions]({%link assets/disc/dis01_solution.pdf %})
- Discussion 02 (Week 3): Reverse-Mode Automatic Differentiation. [Section Notes]({%link assets/disc/dis02_question.pdf %}), [Solutions]({%link assets/disc/dis02_solution.pdf %})
- Discussion 03 (Week 4): Optimization and Initialization. [Section Notes]({%link assets/disc/dis03_question.pdf %}), [Solutions]({%link assets/disc/dis03_solution.pdf %})
- Discussion 04 (Week 5): Normalization and Regularization. [Section Notes]({%link assets/disc/dis04_question.pdf %}), [Solutions]({%link assets/disc/dis04_solution.pdf %})
- Discussion 05 (Week 6): Convolutional Neural Networks. [Section Notes]({%link assets/disc/dis05_question.pdf %}), [Solutions]({%link assets/disc/dis05_solution.pdf %})
- Discussion 06 (Week 7): Computer Vision, Midterm Review. [Section Notes]({%link assets/disc/dis06_question.pdf %}), [Solutions]({%link assets/disc/dis06_solution.pdf %})
- Discussion 07 (Week 8): Midterm Exam. [Section Notes]({%link assets/exam/midterm_blank.pdf %}), [Solutions]({%link assets/exam/midterm_solution.pdf %})
- Discussion 08 (Week 10): Transformer 1. [Section Notes]({%link assets/disc/dis08_question.pdf %}), [Solutions]({%link assets/disc/dis08_solution.pdf %})
- Discussion 09 (Week 11): Transformer 2. [Section Notes]({%link assets/disc/dis09_question.pdf %}), [Solutions]({%link assets/disc/dis09_solution.pdf %})
- Discussion 10 (Week 12): Transformer 3, Visual Transformers, and Large-Scale Pretraining. [Section Notes]({%link assets/disc/dis10_question.pdf %}), [Solutions]({%link assets/disc/dis10_solution.pdf %})
- Discussion 11 (Week 13): Masked Auto Encoders, Recommendation Systems. [Section Notes]({%link assets/disc/dis11_question.pdf %}), [Solutions]({%link assets/disc/dis11_solution.pdf %})


## Homeworks
All homeworks are graded for accuracy.
See the course syllabus for more info about homework policy.
For assignment due dates, see Gradescope.

**Tip**: For Colab notebooks, it's recommended to save your own copy of the notebook by doing "File -> Save a copy in Drive" before running any cells.

* (optional) [Python Colab Tutorial](https://colab.research.google.com/github/data-188-berkeley/hw0/blob/main/colab_tutorial.ipynb).

* [Homework 0](https://colab.research.google.com/github/data-188-berkeley/hw0/blob/main/hw0.ipynb): ML warmup, softmax classification. Due **Thu 2/5 at 11:59 PM PST** (2 hour grace period until Fri 2/6 at 1:59 AM PST).

* [Homework 1](https://colab.research.google.com/github/data-188-berkeley/hw1/blob/main/hw1.ipynb): Backpropagation.
  * Extended due date (again) **Sun 2/22 at 11:59 PM PST** (2 hour grace period until Mon 2/23 at 1:59 AM PST).
  * ~~Extended due date **Sat 2/21 at 11:59 PM PST** (2 hour grace period until Sun 2/22 at 1:59 AM PST).~~
  * ~~Due **Thu 2/19 at 11:59 PM PST** (2 hour grace period until Fri 2/20 at 1:59 AM PST).~~

* [Homework 2](https://colab.research.google.com/github/data-188-berkeley/hw2/blob/main/hw2.ipynb): Deep learning framework abstractions.
  * Extended due date (again) **Sun 3/15 at 11:59 PM PST** (2 hour grace period until Mon 3/16 at 1:59 AM PST).
  * ~~Extended due date **Thu 3/12 at 11:59 PM PST** (2 hour grace period until Fri 3/13 at 1:59 AM PST).~~
  * ~~Due **Sat 3/7 at 11:59 PM PST** (2 hour grace period until Sun 3/8 at 1:59 AM PST).~~

* [Homework 3](https://colab.research.google.com/github/data-188-berkeley/hw3/blob/main/hw3.ipynb): Intro to pytorch.
  * Extended due date **Sun 4/12 at 11:59 PM PST** (2 hour grace period until Mon 4/13 at 1:59 AM PST).
  * ~~Due **Thu 4/9 at 11:59 PM PST** (2 hour grace period until Fri 4/10 at 1:59 AM PST).~~

* [Homework 4](https://colab.research.google.com/github/data-188-berkeley/hw4/blob/main/hw4.ipynb): Transformers for NLP (machine translation)
  * Due **Fri 5/1 at 11:59 PM PST** (2 hour grace period until Sat 5/2 at 1:59 AM PST).

* Homework 5: Visual Transformer, Masked Autoencoder


<!-- - [Homework 1](https://github.com/datac182fa24/datac182_hw1_student), **due Tues Oct 8th 2024 11:59 PM PST**

- [Homework 2](/assets/homeworks/DataC182_FA24_HW2-2.pdf), **due Sun Oct 27th 2024 11:59 PM PST**

- [Homework 3](https://github.com/datac182fa24/datac182_hw3_student), **due Fri Nov 22nd 2024 11:59 PM PST**

- [Homework 4](https://github.com/datac182fa24/datac182_hw4_student), **due Sun Dec 15th 2024 11:59 PM PST**

- [Final Project](https://docs.google.com/document/d/1erKfrMXIY_JkPB_648wyaTXP89Llo4MyD68l_pZRwZo/edit?tab=t.0), **due Fri Dec 20th 2024 11:59 PM PST** -->
