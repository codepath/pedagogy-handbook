# Learning Platform

## Overview

At CodePath, we have created the building blocks of a powerful learning and knowledge platform. This platform provides a significantly better way for developers to document their technical knowledge, collaborate on curriculum, and schedule and execute effective courses.

This isn't a single tool or software but instead a suite of software solutions specifically targeting technical documentation and training.

### Principles

This learning platform has a number of guiding principles:

* No online platform can ever replace the importance of social and in-person interactions
* Designing and building courses should be similar to building open-source software
* Courses must be measured and improved based on continuous feedback and analytics
* Leverage software and frameworks to ensure course quality from design to execution

We want to build the premier learning platform for highly effective, scalable, and outcome-oriented technical education. Our goal is for this platform to be capable of supporting by hundreds or even thousands of in-person high-touch courses at the same time.

### Platform

The learning platform consists of a variety of functions and features targeted around the following:

* **Curriculum Development**
  * Curriculum collaboration for technical content with easy branching and tracking
* **Course Scheduling**. 
  * Scheduling solution for courses offered where applicants can apply to a course
* **Admissions Management** 
  * Admissions system for accepting applicants and managing the end-to-end admission process
* **Hybrid Course Delivery System**
  * Online course platform for seamless hybrid courses combining live and online components.
* **Assignment Tracking and Scoring** 
  * Tracking assignment submissions from participants during the course with built-in scoring. 
* **Course Workflow Automation** 
  * Attendance management system for tracking absences
  * Automating operations during the course i.e grouping people into teams
* **Technical Q&A Support System**
  * Searchable question and answer system for technical issues during the course
* **Technical Guides**
  * Documentation of technical topics which is well-structured and searchable
* **Announcements and Reminders**
  * Online integrated communication and messaging platform during the course 
* **Analytics Platform** 
  * Collection and visualizations of classroom, instructor and participant analytics

Review the [Learning Platform Slides](https://docs.google.com/presentation/d/1i5NB29bR9rRNh7tKIVQJMX9kzMps1TmsghueZOryMgo/edit) for a high-level overview.

### Schema

At the core of this system are a few concepts:

| Concept | Description | Example |
| :--- | :--- | :--- |
| Course | Types of curriculum that can be used | Intro to Android |
| Cohort | Individual instances of a course that are run | February Android @ Facebook |
| Members | Students, moderators, and admins within cohorts | Jane Smith |
| Application | Students applying to be in a cohort | Jane's Application for Feb 2016 @ Facebook |

Each type of class and curriculum in our system is called a "course". Courses are developed, similar to how open-source software is developed, using git, github, and a certain directory structure. Think of the course system as a "framework for developing curriculum" just as [Ruby on Rails](http://rubyonrails.org/) is a "framework for developing web applications".

## Components

This learning platform consists of the following major software components:

![overview](http://i.imgur.com/I7bo6ko.png)

| Component | Description |
| :--- | :--- |
| Scheduler | Course scheduler for booking and viewing upcoming classes |
| Enrollment | Allow eligible applicants to apply to upcoming courses |
| Admissions | Manages the admission process for any course start to finish |
| Courses | Course content viewer available for access by participants |
| Discussions | Questions and answer companion for solving technical issues |
| Guides | Technical topic guides available to be searched and accessed |
| Mailer | Templatized emails to be sent to people before and during a course |
| Roster | Unified people tracking everyone involved with classes |
| Gradebook | Review and score assignments submitted during a course |
| Analytics | Collect and visualize classroom, student and instructor analytics |
| Billing | Organization tracking with automated billing based on per-seat |

### In Production

To achieve the functionality outlined above, the following software modules exist but need to be further developed:

* **Unified Member Database** - Unified database and API for all cohorts and members

  ![](http://i.imgur.com/B8fcOiQ.png)

* **Enrollment** - Custom course application system for applicants

  ![](http://i.imgur.com/FjXM3I4.png)

* **Admissions** - Admins can easily manage the entire end-to-end state tracking for applicants
* **Course Viewer** - Course content available for access by participants

  ![](http://i.imgur.com/tcfAyjM.png)

* **Guides** - Technical topic guides available to be searched and accessed

  ![](http://i.imgur.com/v0ijsL9.png)

* **Discussions** - Announcements and Questions and answer companion for solving technical issues

  ![](http://i.imgur.com/ygO4K8k.png)

* **Mailer** - Templatized emails to be sent to people before and during a course
* **Gradebook** - Review and score assignments submitted before and during a course
* **Roster** - Unified people tracking everyone involved with classes

## Future Modules

On top of our core learning platform, there are additional modules that we want to build in the future including:

* **Virtual Career Fairs**
  * End-to-end platform running large-scale virtual career fairs for our students
  * Matches students to companies for Zoom interviews, and manages the entire process before and after
* **Projects Showcase App**
  * List of apps created by project groups including short description and screenshots and team
  * Can be submitted and crowdsourced by our students 
* **Alumni Portal**
  * Opt-in to certain communication
  * Link to "staying involved" page
  * Links to all the ways to stay plugged in:
    * meetup, slack, facebook, opportunities
  * See upcoming classes and events
* **LinkedIn Tracker**
  * Track all students for job changes on their profiles
  * Connect with all students from our classes automatically
  * Web front-end for viewing all companies
* **Direct Talent Marketplace**
  * Provide access to opportunities from companies
  * Companies can signup to find alumni
  * Alumni can sign-up to find company opportunities
  * System helps match alumni to companies

## Resources

* [Learning Platform Slides](https://docs.google.com/presentation/d/1i5NB29bR9rRNh7tKIVQJMX9kzMps1TmsghueZOryMgo/edit)
* [Learning Platform Drawings](https://docs.google.com/presentation/d/1JXwY3e9sBs1438MzYHgRx5tjgCeZwl2SjF3arTggqOQ/edit#slide=id.g77656ad78_0_5)

