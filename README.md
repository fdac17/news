
# [Course Evaluation](https://utk.campuslabs.com/courseeval/)

# Dec 8, Noon, location TBD
 - Gymnasics Outcomes (attendance optional)
 
# Dec 4
 - Final report due: no final exams
    The [format and content](https://github.com/fdac17/FinalProjects/blob/master/README.md) for the report

# Final Project Presentation on Dec 4
  - (15m presentation + 2m for questions)
  - REMember
  - The Bitcoin
  - Discord API

# Final Project Presentation on Dec 1
  - (15m presentation + 2m for questions)
  - Redit
  - Topological Analysis
  - NFL

#  Final Project Presentation on Nov 29
 - (15m presentation + 2m for questions)
 - Pitchfork Review 
 - Open Source Contributions
 - Startup analysis
 
#  Final Project Presentation on Nov 27 
  - Social Media Image Analysis
  - Open Secrets 

#  Final Lecture on Nov 20


# Class on Nov 10, 13, 17
 - Work on FP

# Class on Nov 8
 - Mini-Project3 Step-2 due

# Class on Nov 1, 3, 6
 - Work on FP

# Class on Oct 27, 30
 - FP - progress reports
 - Mini-Project3 Step-1 due Oct 30

# Class on Oct 25
 - Work on FP; Mini-Project3 Step-1
 - Please ask questions: 
      - the mp3.ipynb has been updated on Mini-Projec3
      - it contains the minimum set of steps
             Investigating univariate
	     Transformations
	     Investigating multivariate
	     Model selection
	     Model diagnostics
	     Prediction using liner models
	     Advanced prediction
	     
# Class on Oct 18, 20, 23 
 - Work on FP; Mini-Project3 Step-1

# Class on Oct 16
- Questions on MP2: last day

# Class on Oct 11, 13
- Data analysis using R
- Remaining FP proposals

# Class on Oct 9
 - Data Discovery Step-3 due
 
# Class on Oct 4
- Discovery: Mini Project2 - Step1-2
    - Someone has dropped the entire NPM_packages database with all your collections, so please rerun the gathering again
    - and please avoid dropping the entire database, if you need clean slate just drop your collection only
    ```
    db.all_netid.delete_many({}) #good as long as netid is yours
    db.all_netid.drop() #good as long as netid is yours
    client.drop_database('NPM_packages') # BAD, please never do it as you remove everyone elses collections
    ```
    - Some created another database npms to store package info, please use the same NPM_packages database, just a different named collection: 
        instaed of all_netid - npms_netid
- Final project proposals are due
   The  group needs to submit a project proposal (1.5-2 pages in
   IEEE format (see https://www.overleaf.com/latex/templates/preparation-of-papers-for-ieee-sponsored-conferences-and-symposia/zfnqfzzzxghk).
   The proposal 
   should provide a brief motivation of the project, detailed
   discussion of the data that will be obtained or used in the project,
   along with a time-line of milestones, and expected outcome.

# Class on Oct 2
- Discovery: Mini Project2 - Challenge introduced
- Mini-Project1: additional presentations

# Class on Sep 27-29
- Work on the proposal for the final project

# Class on Sep 25
- Discovery: Mini Project2 - Step2 - Introduction
- Mini-Project1: additional presentations (JTL, Jacob M, James C, Jonathan And. and Ad.)

# Class on Sep 22
- Discovery: Mini Project2 - Step1 - Introduction

# Class on Sep 20
- Please update this [spreadsheet](https://drive.google.com/open?id=1uV-XEBPLNG9GBExjDFo5KafsUwKVINfN1Zs6k2wohdM) with your final selections
- More info on text analysis + comments on Mini-project1
- Discovery: Mini Project2 - Step1 - Introduction
- Questions on GCloud

# Class on Sep 18
- Final project selection finalized: start working on FP proposals   
- GCloud practice due

# Class on Sep 13
- Team 5: Joshua Hickman
- Team 7: Sean Whalen
- Team 8: Ty Vaughan
- Teasers for the final project
- Questions on GCloud

# Class on Sep 13

- Mini-project1 due
- Team 1: Chris Shurtleff
- Team 2: Denizhan Pak
- Team 3: William Lifferth
- Team 6: Devanshu Agrawal

# Class on Sep 11

- Dedicated to pair discussions of the Mini-project1

- Work on organizing into final project teams

# Class on Sep 8

- Ideas for the final project (be ready to present your pitch if you want to do it) 

     - Please add your teaser to fdac17/FinalProjects/
     - Please raise an issue against fdac17/FinalProjects indicating which project you'd like to work on

- Will go over the gcloud practice

# Class on Sep 6

- Ideas for the final project (be ready to present your pitch if you want to do it) See fdac17/FinalProjects/README.md for a list of presented teasers.

# Class on Sep 1

- Analysis of self-description in .md files: fork fdac17/students
  then git clone (or pull) in your docker terminal and play with students/TeamingAnalysis.ipynb and students/DataStructures.ipynb. Available NOW

- [Mini-Project 1](https://github.com/fdac17/Mini-Project1) will be introduced
        
   1. Q: Do I need to keep stuff in Mini-Project1.ipynb? A: Absolutely not, you should create a new notebook YourUTID_Mini-Project1.ipnb  (please do not 'git rm Mini-Project1.ipnb', though)      
   1. Q: How do I raise issue if my peer has not created a fork yet? A: The forks are due Sep 6: thats why we have multiple steps in this assignment. If the fork is not there yet: raise issue regarding absence of the fork on fdac17/news
   1. Q: How come I need to have X number of commits by certain date? A: To avoid situation when all work is done at the end, or the intermediate results are not saved. The purpose of this is to practice frequent commits: do something, then commit before it disappears.
   1. Q: How do I know someone's GH id? A: Please see students/MapIDs.md 

- Google cloud infrastructure will be introduced fdac17/gcloud

# Class on Aug 30

- We will go over data discovery fdac17/lectures/dd.pdf  and fdac17/lectures/db.pdf 


# Class on Aug 28

- Please make sure you can login via ssh/putty: your key has been
  inserted in the authorized_keys, so you should not need to retype
  your password

- Common question: "when I try to ssh into my container saying that the host key may have been changed. By default it's using strict host key checking which I could turn off. What's the best action for this?" Answer: remove offending key from .ssh/known_hosts (or remove .ssh/known_hosts)
 
- We will go over why we use the tools fdac17/lectures/tools.pdf

- We will go over some magic behid these tools fdac17/lectures/magic.pdf

- Also, please see https://github.com/fdac17/students/blob/master/FAQ.md
  Feel free to edit/submit a pull request.

- Feel free to add something about yourself to the .md file: many
are quite bare and may not contain sufficient info for clustering.

- Please do homework in fdac17/Practice0 (to familiarize with basic python tools) (Due Aug 30)

# Class on Aug 25

- Will finalize the file submission
  - please rename your .md and .pub file to your *utkid* in all
  lowercase, some files use GitHub id.

```  
git mv YourGithubID.md yourutkid.md
git mv YourGithubID.pub yourutkid.pub
git commit -m 'renamed files'
git push
```
   - Then create a new pull request.

- If you have not accepted GitHub invitation, please do

- I'll go over syllabus and provide some background information



# Class on Aug 23

- Will be led by the TA
     - Make sure you accept your github invitations
	 - Go through the fork students create your utid.md file
	   providing your name and interests: see audris.md for
	   inspiration, and also provide your  utid.key with your public
	   ssh key.
     - Follow through ssh/putty setup
     - Make sure you do it during the class so we can start ready Aug
       25
	 - [Full details](https://github.com/fdac17/news/blob/master/Preliminary.md)
	
# Syllabus for "Fundamentals of Digital Archeology"
* **Course:** [COSCS-445/COSCS-545]
* ** MK524  2:30-3:20 MWF**
* **Instructor:** Audris Mockus, [audris@utk.edu](mailto:audris@utk.edu) office hours MK613 - on request
* **TA:** Andrew Valesky, [avalesky@vols.utk.edu](mailto:avalesky@vols.utk.edu) office hours MK619 Wed 11:00 - 1:00 
* **Need help?**

Simple rules: 

1. There are no stupid questions. However, it may be worth going over the following steps:
1. Think of what the right answer may be.
1. Search online: stack overflow, etc.
     - code snippets: On GH [gist.github.com](https://gist.github.com/) or, if anyone contributes, [for this class](https://github.com/snippets/fdac17/)
     - answers to questions: [Stack Overflow](http://stackoverflow.com/)
1. Look through [issues](https://github.com/fdac17/news/issues)
1. Post the question as an issue.
1. Ask instructor: [email](mailto:audris@utk.edu) for 1-on-1 help, or
   to set up a time to meet 


## Objectives
The course will combine theoretical underpinning of big data with
intense practice. In particular, approaches to ethical concerns,
reproducibility of the results, absence of context, missing data,
and incorrect data will be both discussed and practiced by writing
programs to discover the data in the cloud, to retrieve it by
scraping the deep web, and by structuring, storing, and sampling it
in a way suitable for subsequent decision making.  At the end of the
course students will be able to discover, collect, and
clean digital traces, to use such traces to construct meaningful
measures, and to create tools that help with decision making.

## Expected Outcomes
Upon completion, students will be able to discover, gather, and analyze
digital traces, will learn how to avoid mistakes common in
the analysis of low-quality data, and will have produced a working
analytics application.

In particular, in addition to practicing critical thinking,
students will acquire the following skills:

*  Use Python and other tools to discover, retrieve, and process data.
  
*  Use data management techniques to store data locally and in the cloud.
  
*  Use data analysis methods to explore data and to make predictions.

## Course Description

A great volume of complex data is generated as a result of human
activities, including both work and play. To exploit that data for
decision making it is necessary to create software that discovers,
collects, and integrates the data.

Digital archeology relies on traces that are left over in the course
of ordinary activities, for example the logs generated by sensors in
mobile phones, the commits in version control systems, or the email
sent and the documents edited by a knowledge worker. Understanding
such traces is complicated in contrast to data collected using
traditional measurement approaches.

Traditional approaches rely on a highly controlled and well-designed
measurement system. In meteorology, for example, the temperature is
taken in specially designed and carefully selected locations to
avoid direct sunlight and to be at a fixed distance from the ground.
Such measurement can then be trusted to represent these controlled
conditions and the analysis of such data is, consequently, fairly
straightforward.

The measurements from geolocation or other sensors in mobile phones
are affected by numerous (yet not recorded) factors: was the phone
kept in the pocket, was it indoors or outside?  The devices are not
calibrated or may not work properly, so the corresponding
measurements would be inaccurate.  Locations (without mobile phones)
may not have any measurement, yet may be of the greatest interest.
This lack of context and inaccurate or missing data necessitates
fundamentally new approaches that rely on patterns of behavior to
correct the data, to fill in missing observations, and to elucidate
unrecorded context factors. These steps are needed to obtain
meaningful results from a subsequent analysis.

The course will cover basic principles and effective practices to
increase the integrity of the results obtained from voluminous but
highly unreliable sources.

*   Ethics: legal aspects, privacy, confidentiality, governance
   
*   Reproducibility: version control, ipython notebook
   
*   Fundamentals of big data analysis:
    extreme distributions, transformations, quantiles,
    sampling strategies, and
    logistic regression

*   The nature of digital traces:
    lack of context,
    missing values, and
    incorrect data

## Prerequisites

Students are expected to have basic programming skills, in
particular, be able to use regular expressions, programming concepts
such as variables, functions, loops, and data structures like lists
and dictionaries (for example, COSC 365)

Being familiar with version control systems (e.g., COSC 340), Python
(e.g., COSC 370), and introductory level probability (e.g., ECE 313)
and statistics, such as, random variables, distributions and
regression would be beneficial but is not expected. Everyone is
expected, however, to be willing and highly motivated to catch up in
the areas where they have gaps in the relevant skills.

All the assignments and projects for this class will use github and
Python. Knowledge of Python is not a prerequisite for this course,
provided you are comfortable learning on your own as needed. While
we have strived to make the programming component of this course
straightforward, we will not devote much time to teaching
programming, Python syntax, or any of the libraries and APIs.  You
should feel comfortable with:

1. How to look up Python syntax on Google and StackOverflow.
1. Basic programming concepts like functions, loops, arrays, dictionaries, strings, and if statements.
1. How to learn new libraries by reading documentation and reusing examples
1. Asking questions on StackOverflow or as a GitHub issue.


### Requirements

These apply to real life, as well.

* Must apply "good programming style" learned in class
    * Optimize for readability
* Bonus points for:
    * Creativity (as long as requirements are fulfilled)

## Teaming Tips

* Agree on an editor and environment that you're comfortable with
* The person who's less experienced/comfortable should have more keyboard time
* Switch who's "driving" regularly
* Make sure to save the code and send it to others on the team

## Evaluation

* Class Participation – 15%: students are expected to read all
   material covered in a week and come to class prepared to take
   part in the classroom discussions. Responding to other student
   questions (issues) counts as classroom participation.

* Assignments - 40%: Each assignment will involve writing (or modifying a template of)
   a small Python program.

* Project - 45%: one original project done alone or in a group of 2 or 3
   students. The project will explore one or more of the themes covered
   in the course that students find particularly compelling.  The
   group needs to submit a project proposal (2 pages IEEE format)
   approximately 1.5 months before the end of term.  The proposal
   should provide a brief motivation of the project, detailed
   discussion of the data that will be obtained or used in the project,
   along with a time-line of milestones, and expected outcome.

## Other considerations

As a programmer you will never write anything from scratch, but will
reuse code, frameworks, or ideas.  You are encouraged to
learn from the work of your peers. However, if you don't try to do
it yourself, you will not learn. [Deliberate practice][deliberate-practice]
(activities designed for the sole purpose of effectively improving
specific aspects of an individual's performance) is the only way to
reach perfection.

Please respect the terms of use and/or license of any code you find,
and if you re-implement or duplicate an algorithm or code from
elsewhere, credit the original source with an inline comment.

## Resources
### Materials

This class assumes you are confident with this material, but in case you need a brush-up...

* [Python for beginners](https://www.python.org/about/gettingstarted/)
  and [Python Dictionaries](http://pythonprogramminglanguage.com/dictionary/)

#### Other

* [Mining the Social Web, 2nd Edition](http://shop.oreilly.com/product/0636920030195.do)

##### Databases

* [A MongoDB Schema Analyzer](https://github.com/variety/variety). One JavaScript file that you run with the mongo shell command on a database collection and it attempts to come up with a generalized schema of the datastore. It was also written about on the official MongoDB blog.

##### R and data analysis
* Modern Applied Statistics with S (4th Edition) by William
  N. Venables, Brian D. Ripley. ISBN0387954570
* [R](https://www.coursera.org/learn/r-programming) 
* [Code School](http://www.codeschool.com/courses/try-r)
* [Quick-R](http://www.statmethods.net)

##### Tutorials written as ipython-notebooks
* [python-data-cleaning](http://nbviewer.ipython.org/github/ResearchComputing/Meetup-Fall-2013/blob/master/python/lecture_21_pandas_processing.ipynb)
* [python tutorial for engineers](http://nbviewer.ipython.org/gist/rpmuller/5920182)

#### GitHub

* Git and GitHub
    * [Official GitHub Help](https://help.github.com/)
	* [GitHub Issues](https://guides.github.com/features/issues/)
    * [Recommended resources](https://help.github.com/articles/what-are-other-good-resources-for-learning-git-and-github)
* GitHub Pages
    * [Official site](http://pages.github.com/)
    * [Thinkful guide](http://www.thinkful.com/learn/a-guide-to-using-github-pages/)


<!-- Links -->
[docker]:http://www.eecs.utk.edu/resources/it/kb/docker
[class-site]:http://web.eecs.utk.edu/~audris/fdac
[deliberate-practice]:http://www.psy.fsu.edu/faculty/ericsson/ericsson.exp.perf.html
[pull-request]:https://help.github.com/articles/creating-a-pull-request
[create-repo]: https://help.github.com/articles/create-a-repo
[forking]: https://guides.github.com/activities/forking/
[ref-clone]: http://gitref.org/creating/#clone
[ref-commit]: http://gitref.org/basic/#commit
[ref-push]: http://gitref.org/remotes/#push
[pull-request]: https://help.github.com/articles/creating-a-pull-request
[raw]: https://raw.githubusercontent.com/education/guide/master/docs/forks.md
