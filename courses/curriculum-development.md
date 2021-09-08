---
description: >-
  In this section, we will take a look at how our curriculum is built and the
  curriculum collaboration process.
---

# Curriculum Development

## Curriculum Workflows & Platform

All of our curriculum and related content are hosted and managed in a structure that is very similar to how software is collaborated on in the open-source world. In particular, the curriculum and almost all of our technical content:

* Source lives in Github repositories filled with folders and files that comprise the course
* Works like any code repo with issues, pull-requests, and commit history
* Content is developed using an enhanced [markdown formatting language](https://www.markdownguide.org/cheat-sheet/)
* Easily re-use snippets of content to avoid content duplication
* Code syntax highlighting, expandable text blocks, alert boxes, and many other features
* Full support for fully dynamic logic and conditionals and code snippets within the course content
* Full support for multiple course variations \(with the same content being packaged in different ways\)
* Special dynamic tag system enables dynamic insertion of data, dates, information seamlessly drawing from the cohort, location, user, and other details of the person viewing the course.
* Support for custom downloadable files which can be easily hosted and linked to
* Support for markdown-powered slide presentations using reveal.js

### **Approach Benefits**

Through our approach, we can use the same best-practice collaboration workflows pulled from software and easily:

* Manage multiple courses in parallel with different applications and start/end dates
* Manage version control and tracking changes \(branches on Github\)
* Collaborate on changes with pull requests, code reviews, and merges
* Full support for coding and dynamic data right within the course content pages
* Integrated assignment and project grading modules
* Real-time status reports for students available directly on the course system

### **Course Content Deployment**

* Curriculum developed using our platform can easily be linked into running classes powered by our linked technical course portal which is powered by these curriculum source packages.
* An automated release process ensures that content updates are pushed to the source repository, the content becomes reflected automatically on the course portal to students \(when pushed to the master branch\)
* Courses can be managed entirely from our organizer dashboard for your organization \(or through CodePath.org\)  
* Course participants can single-sign-on via Github and access any courses they are enrolled in

### Additional Curriculum Assets

In addition, often the markdown course content will link to content on the following third-party services:

* Speakerdeck/Google Slides - Slide decks
* Youtube - Video content playlists
* HackerRank - Coding assessments or quizzes

## Content Structure & Orientation

Courses are a combination of certain shared content \(introducing the course, explaining how to submit assignments\), and then a series of units of content in a carefully designed order. A “unit” is a particular section of the course that a user can focus on. A course is composed of a sequential series of “units”.

For example, a 6-week Android course could be split into six “units”. Each unit comprises the curriculum including technical guides, videos, et al for that one week in the course. In contrast, a 1-week full-time program might have five “units”. In this case, each “unit” might consist of a day.

### Diving Deeper into Curriculum Components

Each course curriculum is by design a sequence of units or modules. Within each well-constructed unit or module of content, we have the following pieces:

* **Unit Overview** - An overview for the unit and includes links to relevant pages, external resources, files, videos and other content to be reviewed that week.
* **Hands-on Lab** A hands-on lab for a given unit to be run usually during class time in a lab session. Typically this is a series of challenges/checkpoints to be completed by the student to develop a better understanding of key concepts.
* **Assignment/Submission** - Primary deliverable for a given unit. Typically this is a larger project that ties together the core use cases and concepts for this week. Usually includes a due date, a record video walkthrough, a set of required user stories, and additional optional user stories to extend the project.
* **Session or Group Activity** - group or “pod” activity to be completed during a class session i.e brainstorming app ideas that must be completed during that unit. Anything to complete in class.
* **Hints and Tips** - Hints, tips, troubleshooting, solutions, etc that a student should review before and during the completion of the assignment. Usually developed with a first pass and added to over time as students run into issues.

These units often include assets linked such as:

* **Slide decks** \(hosted in markdown, Speakerdeck, or Google Slides\)
* **Topic Videos** \(hosted on Youtube\) - Explaining specific concepts or topics to be used in this unit
* **Assignment or Lab Videos** - Intro videos pertaining to a specific assignment or lab

In addition, there is the **following shared content** that can be used across all units:

* **Files** - These are arbitrary files that can be linked throughout the course. Sample code, zip files, PDFs, etc belong in here.
* **Images** - These are arbitrary images to be displayed within the course templates.
* **Pages** - These are markdown content pages that are not associated to any one unit. These can be linked throughout the course. Usually for submission instructions, student outlines, etc.
* **Snippets** - These are arbitrary files associated with a course that should not be displayed within the course structure. This is typically for standalone content associated with a course such as pre-work for applicants, course outlines, or other content not associated with a particular unit.

## Curriculum Philosophies

Refer to our [guiding principles](../guiding-principles.md) and [measuring quality ](program-quality.md)pages for more insights into our program design philosophies.

#### Think of your course starting with an application and human-centric approach <a id="Think-of-your-course-starting-with-an-application-and-human-centric-approach"></a>

Don’t think of your course as teaching a topic, or teaching concepts. Start by asking yourself three questions:

* Who is my specific audience, and what do they know or care about already coming into this class?
* What do my target students specifically not know how to do yet that they’ll need to know to succeed?
* What do I specifically want to enable my audience to be able to build or bring into digital reality?

**Anchor everything to these three questions above, and return to them again and again.** Read this guide on [application-centered curriculum design](https://hackmd.io/@nesquena/application-centric-education) here.

## Diving Deeper into Developing Curriculum

For a deeper look at the actual process for developing a new curriculum in association with CodePath, check out our [New Curriculum Development Map](https://hackmd.io/@nesquena/course-development-map). In that document, we cover many more details about the key stakeholders, contractors, and the stages of rolling out a new course. This includes:

* [Recap of what's contained in a course content package](https://hackmd.io/I2gvkuQKSmyb6eeahrbCsw?view#What%E2%80%99s-in-a-course-content-packages)
* [The contractors involved in making a new course](https://hackmd.io/I2gvkuQKSmyb6eeahrbCsw?view#New-Curriculum-Map)
* [Stages of development with a new curriculum](https://hackmd.io/I2gvkuQKSmyb6eeahrbCsw?view#Development-Stages)
* [FAQ - Common questions related to our courses](https://hackmd.io/I2gvkuQKSmyb6eeahrbCsw?view#Other-Questions)

