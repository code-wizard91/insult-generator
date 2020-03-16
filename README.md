## Index
[Brief](#brief)
   * [My Solution](#mysolution)
   
[Risk Assessment and Product Backlog](#riskbacklog)
   * [Risk Assessment](#spr1)
   * [Risk Assessment Table](#risktable)
   * [User Stories](#userstories)

[Sprints & Planning](#sprone)
   * [Trello Board Sprint 1.0](#sprone)
     
[My Deployment Method](#deploymentmethod)
   * [What I used](#techused)

[Visual Representation of my Solution](#visrep)

[Retrospective](#eval)

[Authors](#authorsinv)

[Acknowledgements](#acknowledgements)

<a name="brief"></a>
## The Product Brief

To create app using:
* Software Development with Python
* Continuous Integration
* Cloud Fundamentals
* Micro-service oriented architecture composed of at least 4 services that work together.

### Service #1

The core service – this will render the Jinja2 templates to interact with your application, it will also be responsible for communicating with the other 3 services, and finally for persisting some data in an SQL database.

### Service #2 and #3

These will both generate a random “Object”.

### Service #4

This service will also create an “Object” however this “Object” will be based upon the results of service #2 + #3.

### Service #5


<a name="mysolution"></a>
### Solution

My project is a Insult Generator where two services will be used to generated random parts of a insult which will be sent as lists in JSON to the front-end service which is #Service 1 and will be joined together to form a complete insult and store it in a Mysql DB. Service 5 will be used to add a random meme to the generated response


<a name="riskbacklog"></a>
## Risk Assessment and Product Backlog


<a name="spr1"></a>
## MosCow Prioritisation and Product Backlog (Trello Board) (Sprint 1)

The first list you see is the product backlog, I prioritised the list depending on the MVP of the project, this was done using coloured labels which represent the priority of each task (See labels below)

![Trello Image](/Images/sprint1.jpg)
![Trello Image](/Images/labels.jpg)

<a name="risktable"></a>
## Risk Assessment Table
![Risk Assessment Table](/Images/risktable1.jpg)


<a name="userstories"></a>
## User Stories (Users and Developers)

The User Stories was also done on Trello, I listed all the use-cases for the product in the perspective of a user and a developer.
(Click image for higher quality image) 

![UserStories](/Images/userstories.jpg)


<a name="sprone"></a>
## MosCow Prioritisation and Product Backlog (Trello Board) (Sprint 1)

Here is the First Sprint I did after defining the main requirements of the project. (Click image for higher quality image).

![Trello Image](/Images/sprint1.jpg)


<a name="deploymentmethod"></a>
## Deployment

![Deployment Pipeline](/Images/pipeline.jpg)

The Deployment pipeline for this Flask application was done using Git/Github for source control and automating that process using
webhooks with Jenkins FINISH THIS HERE

## How the process looks

Here is the actual test and building process taking place.

![Jenkins Coverage Report](/images/automation.jpg)

<a name="visrep"></a>
## Visual Representation of App


<a name="techused"></a>
### List of Technologies Used

* MySQL for Application Database
* Python - Coding in Flask
* Flask - Framework 
* Jenkins - CI Server
* Docker / Docker Swarm
* [Github Project](https://github.com/code-wizard91/Performance-Motors) - Version Control System
* [Trello Board](https://trello.com/b/5RcaZXRp) - Project Tracking Board
* Azure Services (MySQL Azure DB, Azure VM)

<a name="eval"></a>
## Retrospect

Eval will go here


<a name="authorsinv"></a>
## Authors

Mahboob Ali

<a name="acknowledgements"></a>
## Acknowledgements

* Jay Grindrod
