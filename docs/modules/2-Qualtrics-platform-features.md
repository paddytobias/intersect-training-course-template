---
layout: page
title: "Introducing the Qualtrics platform and features"
short-title: "Mod. 2" # This will appear in the Nav bar in the header
show-in-nav-bar: true
# teaching: 15
# exercises: 5
# questions:
# - "Why would I be interested in High Performance Computing (HPC)?"
# - "What can I expect to learn from this course?"
# objectives:
# - "Be able to describe what an HPC system is"
# - "Explain when and why HPC can be helpful for computionally intensive research"
# - "Explain how using HPC differs from using a laptop or desktop computer"  
# keypoints:
# - "High Performance Computing (HPC) typically involves connecting to very large computing systems elsewhere in the world."
# - "These other systems can be used to do work that would either be impossible or much slower or smaller systems."
# - "The standard method of interacting with such systems is via a command line interface called Bash."
---

Here is a list of our members who have an instance of Qualtrics for you to use:


|University               |License type             |Data Centre location              |
|-------------------------------|------------------------|----------------------------|
|University of New England|[University-wide](unesurveys.qualtrics.com)|Sydney|
|Charles Sturt University|[Business, Justice and Behaviour](https://csufobjbs.au1.qualtrics.com)|Sydney|
|Southern Cross University|[University-wide](https://scuau.qualtrics.com)|USA|
|University of New South Wales|[University-wide](unsw.qualtrics.com)|Sydney|
|Australian Catholic University|[University-wide](https://acu.qualtrics.com)|USA|
|La Trobe University |[University-wide](latrobe.co1.qualtrics.com)|USA|
|Deakin University|[University-wide](https://deakinsurveys.au1.qualtrics.com)|Sydney|
|University of Canberra|[Education](canberra.qualtrics.com) & [Health](canberrahealth.qualtrics.com)|USA|
|Western Sydney University|[University-wide](surveyswesternsydney.qualtrics.com)|Sydney|
|University of Newcastle|[Business and Law](newcastlebusandlaw.qualtrics.com) & [Psychology](uonpsychology.qualtrics.com)|USA & Sydney, respectively|
|University of Sydney|[University-wide](sydney.qualtrics.com)|Sydney|
|University of Technology Sydney|[Health](utshealth.qualtrics.com) & [Business](utsbusiness.qualtrics.com)|Sydney & USA, respectively|

> Information current @ 22 March 2018.

## Logging into Qualtrics
Some universities will have LDAP ("Lightweight Directory Access Protocol") integration, meaning that you will be able to log in with your university credentials. If you're university hasn't configured this, then you will have to create an account before logging in.

![Qualtrics login](/images/qualtrics_login.png)

## Basic features of Qualtrics
### The Qualtrics survey library
Once you have logged in, you will be displayed with your library of surveys. (Obviously if you are new to Qualtrics, this library will be empty - it won't be long before we fix that!) It is here that all of the surveys that you build will be automatically saved for you to return to.

If you have multiple surveys active at once, this view is a helpful dashboard to monitor how they are going. Each item in this library will tell you how long the survey is (i.e., _how many questions it has_ and the _estimated response time_) and, if it has a **status** of active then, it will also show how many responses there have been so far.

In the top left corner of this window you will also notice **All Folders**. Clicking on this will open a menu on the lefthand side of your screen, which is where you can organise your surveys by filing away surveys in particular folders.

Today we're going to focus on building surveys, however if you want to know more, here is a page on [organising your projects in Qualtrics](https://www.qualtrics.com/support/survey-platform/my-projects/organizing-your-projects/).

### Creating a project, building a survey
On this page you will see a green button in the top right corner called **+ Create Project** - surprise, surprise, this is where we'll start our surveys today. Clicking on this button will take you to a collection of templates.

Aside from the templates, the three most common options you will use here are **Blank Survey Project** to create your survey from scratch and **Create From Existing** where you can copy an existing survey and modify it under a new project.  

For our purposes, in order to further explore the Qualtrics platform, let's create a project using **Blank Survey Project** and call it "Course Example".
![Create Survey Example](/images/create-example-project.png)

Then we'll come to a window with many more features for use to build our survey. For the time you are on Qualtrics, you will probably spend 80-90% of your time on this screen, so let's explore its many options. This is called the Survey Editor for obvious reasons.

### Introducing the Survey Editor
#### Toolbar
![Toolbar](/images/toolbar.png)

The first thing to pay attention to is the toolbar at the top, which includes:
- **Look & Feel** - here you can design your survey appearance including adding any headers and footers, adding logos, applying colors, etc. We'll explore this a bit later on.
- **Survey Flow** - where you configure the sequence of your survey using, what Qualtrics calls, "blocks". We dive into this feature in our Intermediate course, but if you want to find out more information, [here's a page on it](https://www.qualtrics.com/support/survey-platform/survey-module/survey-flow/survey-flow-overview/)
- **Survey Options** - where there is a number of options to tailor how the survey performs, which you can easily turn on or off.
- **Tools** - a very helpful menu to further enhance your survey performance and analysis. Such things like creating a email list of your participants or importing a pre-made survey can be done here.
- **Collaborate** - last but not least, our option to share the survey with anyone who has access to Qualtrics for them to help you in its design.

Then on the righthand side we have an option to **Preview Survey** and to search (which searches all of the text in your questions)

The line of options above the toolbar (with **Survey**, **Actions**, etc) is also interest but let's return to this later. Basically, these are the options that we'll want to use as we progress through the survey workflow. For now, we are in the **Survey** tab because we are building a survey.

#### Developing questions
The next significant part on this page is where we can create and edit our survey questions.

One important thing to learn about Qualtrics surveys is that they are created using "**blocks**". Blocks are like sections or components of the survey. The advantage of building your survey with blocks is that it is that you can engineer the experience of the respondent, depending on a few factor, with some ease (again, **Survey Flow** is where we would do this, which we cover in the Intermediate Course). If this is not something of importance to you, then you can have all of your questions in just one block. To add another block, click on **Add Block** at the bottom.
