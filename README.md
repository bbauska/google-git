---
title: "Google's Introduction to Git/GitHub"
author: "bbauska"
date last editted: "9/9/2023 4+pm"
output: 
  markdown:
    with_style
---

# google-git - Introduction to Git/GitHub by Google
## About this Course
In this course, you’ll learn how to keep track of the different versions of your code and configuration files using a popular version control system (VCS) called Git. We'll also go through how to setup an account with a service called GitHub so that you can create your very own remote repositories to store your code and configuration. 

Throughout this course, you'll learn about Git's core functionality so you can understand how and why it’s used in organizations. We’ll look into both basic and more advanced features, like branches and merging. We'll demonstrate how having a working knowledge of a VCS like Git can be a lifesaver in emergency situations or when debugging. And then we'll explore how to use a VCS to work with others through remote repositories, like the ones provided by GitHub.

By the end of this course, you'll be able to store your code's history in Git and collaborate with others in GitHub, where you’ll also start creating your own portfolio! 

In order to follow along and complete the assessments, you’ll need a computer where you can install Git or ask your administrator to install it for you.

<h2><a href="#table-of-contents">Table of Contents</a></h2>

### [**Week 1: Introduction to Version Control**](#ch1)
>#### 1.01 [**Introduction to Version Control**](#ch1-01)
>#### 1.02 [**Keeping Historical Copies**](#ch1-02)
>#### 1.03 [**Diffing Files**](#ch1-03)
>#### 1.04 [**Applying Changes**](#ch1-04)
>#### 1.05 [**Practical Application of Diff and Patch**](#ch1-05)
>#### 1.06 [**Version Control &amp; Automation**](#ch1-06)
>#### 1.07 [**What is Git?**](#ch1-07)
>#### 1.08 [**Installing Git**](#ch1-08)
>#### 1.09 [**First Steps with Git**](#ch1-09)
>#### 1.10 [**Tracking Files**](#ch1-10)
>#### 1.11 [**The Basic Git Workflow**](#ch1-11)
>#### 1.12 [**Anatomy of a Commit Message**](#ch1-12)
>#### 1.13 [**How to Login to Qwiklabs**](#ch1-13)
>#### 1.14 [**Week 1 Wrap-Up: Intro to Version Control**](#ch1-14)

### [**Week 2: Using Git Locally**](#ch2)
>#### 2.01 [**Intro to Using Git Locally**](#ch2-01)
>#### 2.02 [**Skipping the Staging Area**](#ch2-02)
>#### 2.03 [**Getting More Information About Our Changes**](#ch2-03)
>#### 2.04 [**Deleting &amp; Renaming Files**](#ch2-04)
>#### 2.05 [**Advanced Git Cheat Sheet**](#ch2-05)
>#### 2.06 [**Undoing Changes Before Committing**](#ch2-06)
>#### 2.07 [**Ammending Commits**](#ch2-07)
>#### 2.08 [**Rollbacks**](#ch2-08)
>#### 2.09 [**Identifying a Commit**](#ch2-09)
>#### 2.10 [**Git Revert Cheat Sheet**](#ch2-10)
>#### 2.11 [**What is a Branch?**](#ch2-11)
>#### 2.12 [**Creating &amp; Working With Branches**](#ch2-12)
>#### 2.13 [**Merging &amp; Merge Conflicts**](#ch2-13)
>#### 2.14 [**Week 2 Wrap-Up: Using Git Locally**](#ch2-14)

### [**Week 3: Working with Remotes**](#ch3)
>#### 3.01 [**Intro to Working with Remotes**](#ch3-01)
>#### 3.02 [**What is GitHub?**](#ch3-02)
>#### 3.03 [**Basic Interaction with GitHub**](#ch3-03)
>#### 3.04 [**What is a Remote?**](#ch3-04)
>#### 3.05 [**Working with Remotes**](#ch3-05)
>#### 3.06 [**Fetching New Changes**](#ch3-06)
>#### 3.07 [**Updating the Local Repository**](#ch3-07)
>#### 3.08 [**The Pull-Merge-Push Workflow**](#ch3-08)
>#### 3.09 [**Pushing Remote Branches**](#ch3-09)
>#### 3.10 [**Rebasing Your Changes with Examples**](#ch3-10)
>#### 3.11 [**Best Practices for Collaboration**](#ch3-11)
>#### 3.12 [**Creating a Personal Access Token**](#ch3-12)
>#### 3.13 [**Week 3 Wrap-Up: Working with Remotes**](#ch3-13)

### [**Week 4: Collaboration**](#ch4)
>#### 4.01 [**Intro to Collaboration**](#ch4-01)
>#### 4.02 [**A Simple Pull Request on GitHub**](#ch4-02)
>#### 4.03 [**The Typical Pull Request Workflow on GitHub**](#ch4-03)
>#### 4.04 [**Updating an Existing Pull Request**](#ch4-04)
>#### 4.05 [**Squashing Changes**](#ch4-05)
>#### 4.06 [**Git Fork and Pull Request Cheat Sheet**](ch4-06)
>#### 4.07 [**What are Code Reviews?**](#ch4-07)
>#### 4.08 [**The Code Review Workflow**](#ch4-08)
>#### 4.09 [**Managing Collaboration**](#ch4-09)
>#### 4.10 [**Tracking Issues**](#ch4-10)
>#### 4.11 [**Continuous Integration**](#ch4-11)
>#### 4.12 [**Additional Tools**](#ch4-12)
>#### 4.13 [**Week 4 Wrap-Up: Collaboration**](#ch4-13)
>#### 4.14 [**Sneak Peek of the Next course**](#ch4-14)

<h4>More Coursera Stuff to Know</h4>
•	[Crash Course on Python](https://www.coursera.org/learn/python-crash-course?specialization=google-it-automation)
•	[Using Python to Interact with the Operating System](https://www.coursera.org/learn/python-operating-system?specialization=google-it-automation&utm_source=gg&utm_medium=sem&utm_campaign=11-GoogleITwithPython-US&utm_content=B2C&campaignid=8986236679&adgroupid=119480419197&device=c&keyword=&matchtype=&network=g&devicemodel=&adpostion=&creativeid=506915205324&hide_mobile_promo&gclid=Cj0KCQiA4uCcBhDdARIsAH5jyUlfDESauOE0BGSN9fmf3ZlnfY4Tz7Ph6dZtva1nt-0xLfXlnINEnhsaAgWoEALw_wcB)
•	[Introduction to Git and GitHub](https://www.coursera.org/learn/introduction-git-github?specialization=google-it-automation)
•	[Troubleshooting and Debugging Techniques](https://www.coursera.org/learn/troubleshooting-debugging-techniques?specialization=google-it-automation)
•	[Configuration Management and the Cloud](https://www.coursera.org/learn/configuration-management-cloud?specialization=google-it-automation)
•	[Automating Real-World Tasks with Python](https://www.coursera.org/learn/automating-real-world-tasks-python?specialization=google-it-automation&utm_source=gg&utm_medium=sem&utm_campaign=11-GoogleITwithPython-US&utm_content=B2C&campaignid=8986236679&adgroupid=119480419197&device=c&keyword=&matchtype=&network=g&devicemodel=&adpostion=&creativeid=506915205324&hide_mobile_promo&gclid=Cj0KCQiA4uCcBhDdARIsAH5jyUkQMdQGCkaf46MgrSBj7Kt9DDMg88bxLDZFiTtEhnnwf61Lcw6ZHA4aAgLWEALw_wcB)


<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~ 01. (##) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image001.webp" 
  alt="" 
  style="border: 2px solid  red;" 
  width="500" />

<h2 id="ch1">1. Introduction to Version Control</h2>

<p>In week 1 you'll be introduced to the concept of version control, which will make managing and rolling back your code look super easy.</p>
<p>You’ll learn how to differentiate between files and the tools at your disposal to make this happen.</p>
<p>Next, you'll be introduced to Git and how you can leverage that platform to improve your coding abilities.</p>
<p>Once you’ve got a grasp on what Git is, you’ll install it and start using it to create and clone code repositories.</p>
<p>Last up, you’ll deep dive into Git in order to get more familiar with the different tools and commands it has to offer.</p>
<p>Learning Objectives:</p>
<ul>
  <li>Describe the concept of version control and why it is important to use,</li>
  <li>Utilize the diff and patch commands to automate differentiating and editing files,</li>
  <li>Explain what Git is and its benefits of use,</li>
  <li>Install Git on local machine,</li>
  <li>Utilize Git to create and clone repositories, add code, check the status of code, and commit code.</li>
</ul>

<h3 id="ch1-01">1.01 Introduction to Version Control</h3>
You've heard us talk a lot about programming and automation. This course focuses on a slightly different aspect. How to keep track of the different versions of your code and configuration files using version control systems or VCS. 
These are tools that everyone in IT can benefit from, even if it's not just for programming or automation itself. It will allow us to easily roll back when mistakes happen and also help us collaborate with others. 
You might have already heard of version control systems in the context of managing configuration files or maintaining the source code of programs and scripts. 
In this course, we'll introduce you to a popular VCS called Git, and show you some of the ways you can use it. We'll also go through how to set up an account with the service called GitHub, so that you can create your very own remote repositories to store your code and configuration. 
By the end of this course, you'll be able to store your codes history in Git, and collaborate with others in GitHub, where you'll also start creating your own portfolio. 
Nowadays, lots of employers were asked to see your GitHub portfolio when you're interviewing for IT roles. GitHub portfolios give companies an idea of what projects you've worked on and what kind of code you can write. This course will help you get your setup.
To ensure our project is a success, my team creates a narrative, figures out all the stake holders, and makes sure everyone is on the same page. After all of that comes the hardest part, executing the project to completion. To do that, it's essential we have a version control system, where each engineer can store and share the code they create. This lets us track different revisions, rollback problematic changes, and work together effectively. 
Throughout this course, you'll learn about Git's core functionality, so you can understand how and why it's used in organizations. We'll look at both basic and more advanced features, like branching and merging. We'll demonstrate how having a working knowledge of a VCS like Git can be a lifesaver in emergency situations or when debugging, and we'll explore how to use a VCS to work with others through remote repositories, like the ones provided by GitHub. To do all this, and so you can follow along with the exercises in these videos, you'll need to install Git on your computer. This will also let you interact with GitHub, and upload your code there. 
For the examples in this course, we'll show a bunch of different Python scripts. While you don't need to know any Python to use Git, we do recommend that you have a basic knowledge of the language, so that you can understand the examples and the functionality we'll be demonstrating. If you've done the courses on Python in this program, you're covered. If you haven't, that's okay. But you might need to freshen up your Python skills to follow some of our examples. Also, since all the scripts will use Python 3, you'll need to have Python 3 installed in your computer to run them. 
For our examples, we're going to use a Linux computer, interacting with the Linux command line through the most common command line tools. Again, if you joined us for the Python courses, you're already familiar with all these concepts. If you're jumping into this program with this course, you might benefit from reviewing some of the most basic Linux commands. 
Please remember, some of these topics and videos are a little complex, so they might not 100 percent sink in the first time around. That's totally natural. Take your time, and review any content that's not completely clear. You'll get the hang of it eventually. Also, don't forget that you can use the discussion forums to connect with your fellow learners and ask questions anytime you need. All right. Ready to get started learning about Git and version control. Let's get to it.


<div align="right">
  <b><a href="#table-of-contents">↥ Back To Top</a></b>
</div>
