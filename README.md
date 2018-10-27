# Jira

The PowerPoint contains a kind of short guide to the most important functions of Jira.

## Table of contents

[1. About Jira](#1-about-jira)</br>
 [1.1 Log in](#11-log-in)</br>
[2. Basics](#2-basics)</br>
 [2.1 Create a project](#21-create-a-project)</br>
 [2.2 Create a board](#22-create-a-board)</br>
  [2.2.1 Kanban](#221-kanban)</br>
  [2.2.2 Scrum](#222-scrum)</br>
 [2.3 Create an issue](#23-create-an-issue)</br>
  [2.3.1 Create a subtask](#231-create-a-subtask)</br>
[3. Sprint](#3-sprint)</br>
 [3.1 Work with a sprint](#31-work-with-a-sprint)</br>
 [3.2 Settings](#32-settings)</br>
 [3.3 Complete an issue](#33-complete-an-issue)</br>
 [3.4 Burndown chart](#34-burndown-chart)</br>
[4. Log work](#4-log-work)</br>
[5. Users](#5-users)</br>
 [5.1 Project leader](#51-project-leader)</br>

## 1. About Jira

It is a tool for managing projects and ensures agile software development and monitoring. Also it supports Scrum and Kanban, which are a project-management methods. 
Jira isn’t a freeware, but even very large and well-known companies are trusting in this tool.

### 1.1 Log in

We recommend to choose the 7-day free trial version from de.atlassian.com/software/jira/try. Choose the free Jira Software (on the left) and fill in your data. To use it longer, you need a license. 

## 2. Basics

A project contains boards, which in turn displays the issues. 
An issue is mostly a user-story with some subtasks.
A Sprint is a period in which milestones have to be completed. 
The last term is workflow, which is a graphical representation of the process.

### 2.1 Create a project

First of all you have to create a project. After that open the project overview, to display all created projects. 
If you click on the three dots at the end of the line, you get to the respective project settings. 
Here you can enter the name, key, project type, category and a description.

### 2.2 Create a board

To do this, open the created project and use the drop-down menu to create a new board. Also there are some other possibilities, like searching boards or showing all existing boards.If you have created a board, you have the choice between Scrum and Kanban. 

#### 2.2.1 Kanban

Kanban is more a workflow visualization and useful when you're making changes to an existing project or when you have a fixed goal. 

#### 2.2.2 Scrum

Scrum in turn is more used for software engineering because of the possibility of creating sprints or for projects whose goals have not yet been defined.

### 2.3 Create an issue

To create a new issue, click on the plus sign on the left side. A window will open with some sections to fill in, for example the assignment to a project and the selection between four different task types: 
* Epic: It will be chosen for larger amount of work with more than a single Use-Case or stories.
* Story: It contains a number of tasks that fit together and the progress-type is often choosen as a use-case. The progress-type is often choosen as a use-case. Within a created Story, you could define an Epic.
* Task: It will be chosen for "normal" tasks which are needed to be done.
* Bug: It will be chosen for bug-fixing. 

Another important section is the assignment of a priority:
* Highest: This problem will block progress.
* High: Serious problem that could block progress
* Middle: Has the potential to affect progress.
* Low: Minor problem or easily worked around.
* Lowest: Trivial problem with little or no impact on progress.

Also you have the information about its status: 
The most of them are self-speaking, like “open” or “in work”. Building means that the source code has been committed and Jira is waiting for the code to be built before moving to the next status. And Build Broken means that the source code committed for this issue has possibly broken the build.

Also there are some more sections, like the description, etc. 

#### 2.3.1 Create a subtask

In Jira you also can create subtasks for every process type. Just open the issue and click on the symbol.

## 3. Sprint

A Sprint is a process within the projekt management method scrum (so you will need a scrum-board). It's a periode of time with selected tickets, which are to be done until the sprint ends. The duration can vary, but it is usually between 2 and 4 weeks. With this feature you have a easy coordination of the team.

### 3.1 Work with a sprint

Open the Backlog to see the overview of features and the sprint management. Here you can create an issue and have the possibility to set different fields e.g. “Issue Links” there can be set links between different issues. Jira will not however check if you do these issues in the right order.
 
### 3.2 Settings

With the "Create Sprint"-button you can create a sprint. Now you can drag and drop the different issues you want to work on in the particular sprints. Issues can be added even after the sprint is started so this is decision is not final, but should be close to final.

Press start sprint. After that should you can set the time and name for it. It will automatically show you how many workdays are in this periode of time, depending on how long your Sprint is going.

If you go to active sprints, there will be 3 Columns: To Do, In Progress, Done. Also you have the possibility to add Columns.
Choose the status from the left, drag it and drop it at the desired place.

### 3.3 Complete an issue

As mentioned before there is drag and drop system, for completing an issue just drag it and drop it into the "done"-section. 
If all tasks of a Story are being completed, JIRA will ask you automatically to resolve the parent issue as well.

### 3.4 Burndown chart

In your Scrum-board-menue you can find "reports". In this section you will see different charts for your project. The most important is the burndown chart, it displays the chart for the current Sprint. 
You can use it with story points or only the estimated time vers. The time needed.

## 4. Log work

While you create an issue you can estimate how long this issue will take.If you worked on that issue you can log the time you needed on it. This is a very useful tool to keep track of the time you needed andd it will help you to illustrate your workflow in charts, which will be mentioned a little later.

....................................

## 5. Users

Because you mostly wouldn’t do a project alone, it's important to add people. So that they can use the boards and the issues as well.
The only thing that is needed is the email address that the persons to be added used for registration.

### 5.1 Project leader

You can select a project leader and if he should be assigned automatically when creating issues.
