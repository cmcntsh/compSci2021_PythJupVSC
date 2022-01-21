# Python in Jupyter Notebooks and VSCode, Deployment Environments

This is part of a set of pages on introduction to computer science. https://github.com/cmcntsh/IntroCompSci2021_topics

This week we're going to practice the basics of Python programming. I would recommend starting with the tutorial assignments before watching the videos. The videos are a great set of videos produced by Microsoft. There's probably more material there than you will be able to watch this week.

I'm also going to introduce you to the concept of having multiple environments when deploying software and applications.

One of the things that was a bit new to me when I started working in informatics was the systems I was working with did not just have one version or instance of the system. There were often three. (Sometimes more.) The instances are often named something similar to Development, Testing, and Production. You may wonder why more than one instance of a system may be needed. 

I'll illustrate with a story told to me by one of the senior members of the team I currently work on and a video which describes some of the functions of this type of arrangement. In the early days of the system I currently work on, the healthcare system only had the production system. Enterprise level servers can be quite expensive so you don't want to use more resources than you have to. This team member thought he was working on a different part of a system. He was going to drop a database table and reload it. Only after he gave the SQL command to truncate a table (truncate drops a table completely) did he realize he was in an important part of the database and that he had just made a serious mistake. He brought the EMR for the entire healthcare system down. The table had to be restored from a backup. I realized I needed to be VERY careful when working in the production environment for our system. One of the main purposes of having multiple instances of systems is so development and testing work can be done outside of the production environment so the production environment doesn't get slowed down or disabled when trying something new.

## Exercises

* Educative - Learn Python 3 from Scratch - Loops https://github.com/cmcntsh/exerPythEdBasLoops
* Educative - Learn Python 3 from Scratch - Data Structures https://github.com/cmcntsh/exerPythEdBasDataStructures
* Educative - Learn Python 3 from Scratch - Libraries https://github.com/cmcntsh/exerPythEdBasLibraries
* Educative - Learn Python 3 from Scratch - Executing Python Code https://github.com/cmcntsh/exerPythEdBasExecuteCode
* (old, probably won't use again) Python basics tutorial https://github.com/cmcntsh/exerPythBasicsTutorial
* (old, probably won't use again) Python data science tutorial https://github.com/cmcntsh/exerPythDataScienceTut
* (old, probably won't use again) Create .py files assignment https://github.com/cmcntsh/exerPythCreateBasic

## Assigned Instructional Material

* Importance of DTAP (Development, Testing, Acceptance, & Production) environments (17 min): https://www.youtube.com/watch?v=pdNmlvJL7qw
* New Approaches to Software Development Lifecycle and Application Lifecycle Management (pdf included in this repository)

## Optional Material

* Microsoft Python for beginners playlist (44 videos approx 5 hours 20 min): https://www.youtube.com/playlist?list=PLlrxD0HtieHhS8VzuMCfQD4uJ9yne1mE6
* Microsoft More python for beginners playlist (20 videos approx 2 hours 25 min): https://www.youtube.com/playlist?list=PLlrxD0HtieHiXd-nEby-TMCoUNwhbLUnj
* Microsoft Even more python for beginners data tools playlist (31 videos approx 2 hours 35 min): https://www.youtube.com/playlist?list=PLlrxD0HtieHhHnCUVtR8UHS7eLl33zfJ-
* Python Advanced Tutorial: https://github.com/cmcntsh/exerPythAdvancedTut
* How to Learn Python for Free (6 free courses introduced) How to Learn Python for Free: https://www.makeuseof.com/how-to-learn-python-for-free/
  * The first course (Google's Python Tutorials) looks to be quite old and uses Python 2.7. We're using Python 3.x. One of the biggest differences is how the print statement is crafted. Python 2.7 doesn't use parentheses with the print statement. There are some other minor differences. But the basic concepts are the same.
  * Google's Python Tutorial (pretty old, a bit confusing) https://developers.google.com/edu/python/
  * Microsoft EdEx https://learning.edx.org/course/course-v1:Microsoft+DEV236x+3T2018/home
  * FreeCodeCamp https://www.youtube.com/watch?v=rfscVS0vtbw
  * Introduction to Python Programming on Udemy https://www.udemy.com/course/pythonforbeginnersintro/?ranMID=39197&ranEAID=TnL5HPStwNw&ranSiteID=TnL5HPStwNw-_8s.x3nvoYc3AK9KX4QlDw&LSNPUBID=TnL5HPStwNw&utm_source=aff-campaign&utm_medium=udemyads
  * Educative Learn Python 3 https://www.educative.io/courses/learn-python-3-from-scratch
  * MakeCode Python https://makecode.com/blog/minecraft/python-release
* Free Python course on Scrimba https://scrimba.com/learn/python
* Free Python and Pandas courses on Kaggle https://www.kaggle.com/learn
