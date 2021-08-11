# DevOps Final Project

## Author
- Albert Richards
- Bradley Dobson
- Inaam Islam
- Umayr Ahmed
- Zahra Ahmed

### Links
- [Trello](https://trello.com/b/Puwzu6nB/final-project)

## Contents
- [Brief](#brief)
    - [Requirements](#reqs)
- [Project Planning](#building)
    - [Trello Board](#planning)
    - [Collaboration](#services)
- [Architecture](#arch)
    - [Infrastructure](#cla)
- [Risk Assessment](#risks)
    - [Initial Risk Assessment](#initial)
    - [Final Risk Assessment](#finalra)
- [Costs](#cost)
- [Technologies utilised](#tech)
    - [Reasons for using these Technologies](#reasons)
- [Things that went well](#suc)
- [Areas for improvement ](#improve)
- [Github links](#gitlink)

<a name="brief"></a>
## Brief

The brief for the DevOps Final Project is to deploy an application for a 'Spring Pet Clinic’ domain where we have a front end client using AngularJS and an API using Java.

<a name="reqs"></a>
### Requirements 

The requirements of the project, retrieved from the [QA-Community website](https://qa-community.co.uk/~/_/projects/final--devops) are as follows:

You will need to plan, design and implement a solution for automating the development workflows and deployments of this application. As part of your final deliverable you will need to discuss the project in a presentation and demonstrate these workflows

Using what you have learned consider the following:

-What tools will work for you best? For example: Terraform, Kubernetes, Ansible etc. There is no restrictions or requirements on which ones to use; you should decide which you feel are most appropriate and justify their use

-Multiple Environment support: How can a developer test their new features on an environment before merging their changes to the main branch?

-How can changes on the GitHub repository automatically build and deploy to testing and live environments?

-Running costs. What are your monthly estimates? How could they be improved?

<a name="building"></a>
### Project Planning
In order to fulfill the requirements of the project, we chose to deploy the application via the use of Terraform, Kubernetes, Jenkins and Docker as well as using Amazon Web Services as our cloud provider

<a name="planning"></a>
### Trello Board

The project planning was done through a Trello board. This consists of a Backlog, sprint, MOSCOW order of prioritisation as well as items to check on completion. Updates were made to this board constantly throughout development. 

<img width="960" alt="Trello" src="https://user-images.githubusercontent.com/84901993/128853141-0da1eb48-14b7-4497-91bf-ff4c2681003a.PNG">



<a name="services"></a>
### Collaboration

This was the first group project that we had attempted, so we tried to combine all of our knowledge and skills that we had gained so far in order to work together effectively. We used a [shared Github repository](https://github.com/BluDobson/project-3) that was created by Bradley Dobson, who then invited all of the other team members to become collaborators.

<a name="arch"></a>
## Architecture

<a name="cla"></a>
### Infrastructure
Shown below is a diagram of the Infrastructure we aimed to achieve:

![project](https://user-images.githubusercontent.com/84901993/128856042-b2d79c13-e9f6-4b02-bff1-86f103de27de.png)


<a name="ci"></a>


<a name=risks></a>
## Risk Assessment

For the risk assessments we produced an initial risk assessment that was created before we attempted to complete the project. Upon completion of the project we then went back to the initial assessment to review it and create our final risk assessment.
<a name=initial></a>
### Initial Risk Assessment
Below is a snapshot of part of our initial Risk Assessment:

<img width="880" alt="Initial RA" src="https://user-images.githubusercontent.com/84901993/128882342-e745abb0-72a4-4e62-8102-acbb933ad867.PNG">

The full Risk Assessment can be found on the [Github Repository](https://github.com/BluDobson/project-3) for this project.
<a name=finalra></a>
### Final Risk Assessment

Below is a snapshot of part of our final Risk Assessment:


The full Risk Assessment can be found on the [Github Repository](https://github.com/BluDobson/project-3) for this project.


<a name=cost></a>
## Costs


<a name="tech"></a>
## Technologies Utilised

* Project Tracking: Trello
* Version Control System: Git(Github)
* Cloud Service: Amazon Web Services
* Containerization: Docker
* Version Control for Docker Images: Dockerhub
* Continous Intergration Server: Jenkins
* Orchestration Service for Containers: Kubernetes
* Load Balancing: Nginx

<a name=reasons></a>
### Reasons for using these Technologies

#### Trello
When it came to deciding which service we should use for our Kanban Board, the group agreed that Trello would undoubtedly be the best choice. This is because of Trellos ease of use and that each team member has the most experience with Trello over any other type of Kanban board. Trello also makes collaboration with others very straightforward.

#### Git(Github)
We decided to use Git as our VCS due to Git being the most popular VCS and it is also the VCS that we had the most experience with as a group. We chose to use Github due to its ability to allow seamless collaboration without compromising the integrity of the original project.

#### Amazon Web Services
We used AWS as our cloud provider to help increase our knowledge of AWS and the tools it provides. Although the team had more experience with using Google Cloud Platform, we still had some knowledge of AWS. We felt as though we should use AWS to help advance our comprehension of AWS and take advantage of the services it has to offer. We had also not used AWS in project work prior to this and we felt as though we had the confidence to challenge ourselves. The AWS services also seemed to be tailored better to fit our project aim. All of these things contributed to our decision to use AWS.

#### Docker
Docker is the container service that we chose to use for this project. As a group, we decided that it would be best for us to use Docker as we all had experience with the service from our previous projects. That coupled with the fact that Docker is the industry leading service for containerization and its rapid deployment process is why we opted to use Docker.

#### Dockerhub

#### Jenkins
Jenkins is the Continous Intergration Server that we chose to use for this project.
We decided to use jenkins instead of these alternatives due to multiple reasons. Some of these reasons are that the software is free to use and its also easily modified and you are able to automatically build. The biggest reason we chose to use jenkins was because we have all used the software before and all felt confident with our ability to use it. 

#### Kubernetes
Kubernetes is the container-orchestration service that we chose to use for this project.
We decided on kubernetes due to its easy scalability and realiabilty. Also after dicussing using docker swarm instead we decided that kubernetes was able to be easierly intergrated into the project.

#### NGINX




<a name="suc"></a>
## Things that went well 

A number of things went well for us on this project:



<a name="improve"></a>
## Areas for improvement:


<a name="gitlink"></a>
## Github Links
- [Albert Richards](https://github.com/Albert-Richards)
- [Bradley Dobson](https://github.com/BluDobson)
- [Inaam Islam](https://github.com/InaamIslam)
- [Umayr Ahmed](https://github.com/Umayr12)
- [Zahra Ahmed](https://github.com/ZahraAhmed1)
