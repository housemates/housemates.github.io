# Table of contents

* [About Housemates](#about-housemates)
* [Installation](#installation)
* [Development history](#development-history)
  * [Milestone 1: Mockup development](#milestone-1-mockup-development)

# About Housemates

Housemates is a Meteor application that provides the University of Hawaii community with a means to collaborate on finding off-campus housing. When you come to the site, you are greeted by the landing page.

Anyone with a UH account can login to Housemates by clicking on the login button. The UH CAS authentication screen then appears and requests your UH account and password. Once authenticated, you can create a profile that provides your location and preferences for roommates.
  
After creating a profile, you will be listed on the public directory page:

![](images/directory.png)

Housemates also provides a filter page, available to those who can login to the system with their UH account. The filter page allows you to display all portfolios with a given interest:

![](images/filter.png)

# Installation

First, [install Meteor](https://www.meteor.com/install).

Second, download a copy of Housemates, or clone it using git.
  
Third, cd into the app/ directory and install libraries with:

```
$ meteor npm install
```

Fourth, run the system with:

```
$ meteor npm run start
```

If all goes well, the application will appear at [http://localhost:3000](http://localhost:3000). If you have an account on the UH test CAS server, you can login.  

# Development History

The development process for Housemates conformed to [Issue Driven Project Management](http://courses.ics.hawaii.edu/ics314f16/modules/project-management/) practices. In a nutshell, development consists of a sequence of Milestones. Milestones consist of issues corresponding to 2-3 day tasks. GitHub projects are used to manage the processing of tasks during a milestone.  

The following sections document the development history of Housemates.

## Milestone 1: Mockup development

This milestone started on December 6, 2016 and ended on January 31, 2017.

The goal of Milestone 1 was to create a set of HTML pages providing a mockup of the pages in the system. To simplify things, the mockup was developed as a Meteor app. This meant that each page was a template and that FlowRouter was used to implement routing to the pages. 

Mockups for the following four pages were implemented during M1:

<img width="200px" src="images/landing.png"/>
<img width="200px" src="images/profile.png"/>
<img width="200px" src="images/directory.png"/>
<img width="200px" src="images/filter.png"/>

Milestone 1 was implemented as [Housemates GitHub Milestone M1](https://github.com/housemates/housemates/milestone/1)::

![](images/m1-milestone.png)


Milestone 1 consisted of five issues, and progress was managed via the [Housemates GitHub Project M1](https://github.com/housemates/housemates.github.io/projects/1):

![](images/m1-project.png)

Each issue was implemented in its own branch, and merged into master when completed:

![](images/m1-branch-graph.png)
