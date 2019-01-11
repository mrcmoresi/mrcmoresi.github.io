---
title: 'Machine Learning to predict dropout in programming students (MSc Degree Thesis)'

permalink: /posts/2019/01/msc-thesis/
tags:
  - papers
  - master
  - degree
---

<h2>Machine Learning to predict dropout in programming students (MSc Degree Thesis)</h2>

This is a briefly explanation about my Master Degree thesis, it includes topic and methology.
Computer Science education is facing a problem, the demanding of learn programming has been increased in last years. The lack of specialized teachers plus the weakness of short professional development courses, shown in this [publication](http://marcomoresi.com/publications/lesson_learned/) in addition with others. One of the most popular solutions to this situation are the online learning platforms. My work is based in one of them name [Mumuki](https://mumuki.io/), it's a open-source platform developed in Argentina. This is used for several universities and schools along the country and South America.
When students submit a solution the platform give back to them an assesment which could be Dark Red, Light Red or Green.
<ul>
	<li>Dark Red: Syntax Error, program dont compile</li>
	<li>Light Red: One of the test is not satisfied.</li>
	<li>Green: Everything is ok</li>
</ul>
However the platform give to the student an assesment about his submissions, it dont depend on the kind of student. The main weakness of this kind of platforms is that usually it does not provide personalized feedback to different types of students.

In order to achieve the feature to generate formative feedback, the first important step is detect when an student is in a dropout status. We define a dropout status as a moment when the student is near of drop out that exercise because he/she can not solve it and decide to switch exercise or simply leave the platform for a time.

For this work, i have a 1 million entries dataset of Haskell exercise's submissions done in Mumuki platform. Those was done in Mumuki.io so a priori we dont have information about what kind of student was done the submissions. Wheter is a computer science student or not, age of students or some other information that allows us to understand what kind of student is.
But we have all the information related to the submission, status, content, datetime and so on. 

The main objective of this work is train a Machine Learning Model that can predict a dropout while the student is solving the exercise.
In order to achieve that objetive i will pose some experiments. First of all i need to find out which of the features that i can build with submissions info has better perfomance in classifier. I will use Linear Regression as Baseline.

Before that i will use a Deep Network, an LSTM, to predict dropout in programming students.
Hoping have good results.

PDF Coming soon ...
------