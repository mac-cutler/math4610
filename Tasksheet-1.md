---
layout: page
title: "Tasksheet 1"
permalink: /Tasksheet1/
---

# Math 4610 Fundamentals of Computational Mathematics: Tasksheet 1
## Problems/Questions
_ _ _ 
- Task 1: Set up an appointment to meet with your instructor via Zoom. There are a couple of ways to do this. During office hours you can join a Zoom meeting that will be running. The information, including a link and password will be sent to you via your email address. If you cannot make office hours, you can set up an appointment at another time to hold the meeting. To do this, (1) email your instructor with a time that will work, (2) copy the link 
\
[https://usu-edu.zoom.us/j/2708849140?pwd=OGFCTENRb08yQTJGQUg0cWU3b2Jrdz09](https://usu-edu.zoom.us/j/2708849140?pwd=OGFCTENRb08yQTJGQUg0cWU3b2Jrdz09)
\
in the return email into a browser, and (3) join the meeting on Zoom that has been set up.

_Soln._ Here is the text of the email I sent to you setting up our meeting on Friday afternoon. 
\
Hello Dr. Koebbe! 

My name is Mac Cutler. I am in your MATH 4610 course this semester. 

I was able to create a GitHub account and math4610 repository just fine, but am having trouble creating the link to my profile. How do you suggest doing that? After some googling I tried to create a page using the math4610 repository but apparently I have to upgrade my account if I want to use it. 

Also, I would be available this Wednesday or Friday between 12:00pm-1:00pm (both days) to meet. Would that work for you?  

Thanks so much! Looking forward to the course.
\
Mac

_ _ _
- Task 2: There are two parts to this task.
  - After creating a Github account at
  \
  [https://www.github.com/](https://www.github.com/)
  \
  email a link to your Github page. The links should be of the form
  \
  [https://username.github.io/](https://username.github.io/)
  \
  where the \lq\lq username\rq\rq\ is the name you chose when setting up your account. Your instructor should be able to see your repositories and any public files that are on the repository.
  - In class we discussed the creation of a repository for your work in this course. This must be done as soon as possible during or just after the first lecture. Once you have created a private repository named
  ```
  math4610
  ```
  with an initial README.md file, do the following. Make sure that the repository is private and that the only other collaborator is the instructor for the class. The instructor email is contained in the syllabus for the course and can be accessed as follows.
  \
  [https://jvkoebbe.github.io/math4610/syllabus/md/syllabus](https://jvkoebbe.github.io/math4610/syllabus/md/syllabus)
  \
  or
  \
  [https://jvkoebbe.github.io/math4610/syllabus/pdf/syllabus.pdf](https://jvkoebbe.github.io/math4610/syllabus/pdf/syllabus.pdf)
  \
  Note, that inviting your instructor to be a collaborator will cause an email to be automatically sent to your instructor.
  
_Soln._ Here is text of the email I sent to you regarding my github.io page. 
\
Hi Dr. Koebbe,

Thanks for meeting with me earlier today. I was able to get access to the student version of my github account. Just wanted to send over the link to my repository page and let you know I will be using Cygwin for the course.

Here is the link to my repository page:
\
[https://mac-cutler.github.io/math4610/](https://mac-cutler.github.io/math4610/)
\
See you next week!
\
Mac
\
The link works, so I'm assuming that's enough for the completion of that portion of the task. 

_ _ _
- Task 3: Email your instructor as to which command line environment you will use in the course. Possible choices are: (1) term on Cygwin, (2) term or xterm on Linux, (3) the command window on MacOS, or (5) PowerShell on Windows. If you plan on emulating your instructor's terminal emulator, you should probably install Cygwin. However, installation of Cygwin is not required for the course.
\
_Soln._ See text of email above. I will be using Cygwin for the course. 
---
- Task 4: In this problem, you will clone your math4610 repository. This will allow you the ability to work on the repository locally on a computer of your choice; say a laptop.
  - Open a command terminal of the type chosen in the previous task.
  - To make sure that "git" will work type the command
  ```
  % which git
  ```
  If the output from the command is something like no such command exists, git will need to be installed. The installation will be different for different operating systems. If you need help with the installation, contact your instructor.
  - git has a lot of commands. However, for this task choose a folder where you will place the repository as a subdirectory of the directory. So, change your directory location to your working directory. For example,
  ```
  % cd ~/my_working_dir
  ```
  Then do the clone via git.
  ```
  % git clone https://www.github.com/username/math4610
  ```
  You will see a couple of examples of cloning and working on repositories locally.

_Soln._ Here are the commands/output of me cloning my github repository. 
```
McK Cutler@DESKTOP-POKUN0C ~
$ cd ~/my_working_dir

McK Cutler@DESKTOP-POKUN0C ~/my_working_dir
$ git clone https://www.github.com/mac-cutler/math4610
Cloning into 'math4610'...
info: please complete authentication in your browser...
warning: redirecting to https://github.com/mac-cutler/math4610.git/
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (3/3), done.
```
_ _ _
- Task 5: Search the internet for sites that talk about Version Control Systems (VCS) like Github. Write a brief paragraph (3 or 4 sentences) that describe 
your findings. Include links to the sites you cite in your response. 

\
_Soln._ Essentially, version control software is used by developers (and anyone interested in coding) to fix problems in the same code collaboratively without 
altering the source code. Without somewhere to store the original, unchanged source code, any modifications one person 
makes to the code could severely limit the progress of other team members. Good version control software also contains a long-term history of all modification made 
to source code, so it can serve as a very good reference in case the project needs to go in a different direction, or progress needs to be reported.  
\
_Sources_
- [https://www.atlassian.com/git/tutorials/what-is-version-control](https://www.atlassian.com/git/tutorials/what-is-version-control)
