---
title: 'Machine Learning to predict dropout in programming students (MSc Degree Thesis)'

permalink: /posts/2019/01/msc-thesis/
tags:
  - papers
  - master
  - degree
---

<h2>Machine Learning to predict dropout in programming students (MSc Degree Thesis)</h2>

This is a brief explanation about my Master Degree thesis. It includes topic and methodology.
Computer Science education is facing a problem: the demand of learning programming has increased in the last years. The lack of specialized teachers plus the weakness of short professional development courses are shown in this [publication](http://marcomoresi.com/publications/lesson_learned/) in addition to others. One of the most popular solutions to this situation are the online learning platforms. My work is based in one of them named [Mumuki](https://mumuki.io/). It's an open-source platform developed in Argentina. This is used by several universities and schools across the country and South America.
When students submit a solution to the platform, it  gives them back an assesment which can be Dark Red, Light Red or Green.
<ul>
    <li>Dark Red: Syntax Error, program does not compile</li>
    <li>Light Red: One of the test is not satisfied.</li>
    <li>Green: Everything is ok</li>
</ul>
Although the platform gives the students an assessment about their submissions, it does not depend on the kind of student. The main weakness of this kind of platforms is that it  does not usually provide personalized feedback to the different types of students.

In order to achieve the feature to generate formative feedback, the first important step is to detect when a student is in a dropout status. We define a dropout status as a moment when the student is near of droping out that exercise because he/she cannot solve it and decides to switch exercise or simply leave the platform for some time.

For this work, I have 4 million entries dataset of Haskell exercise's submissions done in Mumuki platform. Those were done in Mumuki.io so a priori we don’t have information about what kind of student made the submissions. Whether it is a computer science student or not, the age of students or some other information that allows us to understand what kind of student itis.
But we have all the information related to the submission, status, content, datetime and so on. 

The main objective of this work is to train a Machine Learning Model that can predict a dropout while the student is solving the exercise.
In order to achieve that objective I will carry out some experiments. First of all, I need to find out which of the features that I can build with submissions info has better performance in classifier. I will use Linear Regression as Baseline.

Before that, I will use a Deep Network, an LSTM, to predict dropout in programming students.
Hoping for good results.

Here you can access to my thesis.

<a href="http://marcomoresi.com/files/moresi_msc_thesis.pdf">Thesis (in Spanish)</a>


------