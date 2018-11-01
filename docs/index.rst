PROJECT LAB: SOFTWARE REQUIREMENTS SPECIFICATION
================================================

SRS
===


STUDENTS NAME AND ID:
===================== 

GUIMEYA JIOFACK JANNY CAROLE 201825800044

AHINKORA THOMAS  201825800061


PURPOSE
=======

The purpose of this document is to present a detailed description of a lap report
repository. It will explain the purpose and features of the Lab report, the interfaces of the lab report, what the lab report will do, the constraints under which it must operate and how the system will react to external stimuli. This document is intended for students, instructors, visitors, TAs and administrators of the system.


SCOPE OF PROJECT:
=================

This software system will be a lab report repository for student to be able to upload their assignments. This system will be designed to help instructors to read and mark uploaded assignments of student also other visitors can visit the system if they want to. The lab report will be to understand and use.

More specifically, this lab report is designed to allow an administrator to manage and communicate with a group of reviewers and student who post to a public web side. The software will facilitate communication between instructors, students, visitors and TAs via E-mail.  Preformatted reply forms are used in every stage of the report progress through the system to provide a uniform review process; the location of these forms is configurable via the application’s maintenance options.

DESCRIPTION:
============

This section will give an overview of the whole system. The system will be explained in its context to show how the system interacts with other systems and introduce the basic functionality of it. It will also describe what type of stakeholders that will use the system and what functionality is available for each type.


Product perspective:
====================


This system will consist of only one part: web portal. The web portal will be used for managing the information about the website and the?system as a whole. 


Since this is a data-centric product it will need somewhere to store the data. For that, a database will be used. The web portal will communicate with the database, however in slightly different ways. The web portal will also add and modify data. All of the database communication will go over the Internet.


Figure 1 - Block diagram
------------------------

Product functions:
==================

With the web application, student will be able to post their assignment and get information back from the instructors and TAs, the visitors will also be able to search for information. It will be possible for the administrator of the system to manage the options for those criteria that have that.


The result of the search will be viewed either in a list view.


The web portal will provide functionality to manage the system and the web information. It will also provide information about the system.


User characteristics:
=====================


There are five types of users that interact with the system: users of the web application, student, instructors, TAs, visitors and administrators. Each of these five types of users has different use of the system so each of them has their own requirements. 


The student users can post assignments and give feedback to the instructors. The instructors can also post assignment, mark assignment and give feedback to students.
The TAs also works like the instructors they have the same funtions. The visitors only search for information on the system.


The administrators also only interact with the web portal. They are managing the overall system so there is no incorrect information within it. The administrator can manage the information.


Constraints:
============


The Internet connection is also a constraint for the application. Since the application fetches data from the database over the Internet, it is crucial that there is an Internet connection for the application to function.


The web portal will be constrained by the capacity of the database.


Assumptions and dependencies:


One assumption about the product is that it can also be used on mobile phones 
Another assumption is that the visitors can be able to asses some information’s on the system.


Apportioning of requirements:
=============================


In the case that the project is delayed, there are some requirements that could be transferred to the next version of the application. Those requirements are to be developed in the third release.


Specific requirements:
======================


This section contains all of the functional and quality requirements of the system. It gives a detailed description of the system and all its features.


External interface Requirements:
================================


This section provides a detailed description of all inputs into and outputs from the system. It also gives a description of the hardware, software and communication interfaces and provides basic prototypes of the user interface. 


User interfaces:
================


A first-time user of the application should see the log-in page when he/she opens the application, see Figure 2. If the user has not sign up, he/she should be able to do that on the log-in page.


If the user is not a first-time user, he/she should be able to see the home page directly when the application is opened, see Figure 3. Here the user chooses the type of program he/she wants to conduct.


Every user should have a profile page where they can edit their e-mail address, ID number, select program, language and password, see Figure 4.


Figure 2 - Login page 
Figure 3 – Search page 
Figure 4 – Profile page


In Figure 5, Students, instructor, visitors, TAs and administrators interact with the system through a web-portal. A student should be able to register on the web-portal in order to log in and manage his/her account. An administrator should also be able to log in to the web-portal where he/she can administer the system by for instance editing restaurant or user information.

Hardware interfaces:
====================


Since the web portal have any designated hardware, it does not have any direct hardware interfaces. The hardware connection to the database server is managed by the underlying operating system on the computer and the web server.


Software interfaces:
====================

The system communicates with the web application in order to get information.


PRIORITIZATION AND RELEASE PLAN:
================================


PROGRAMMING LANGUAGE:
=====================


JAVA JDK 8 we use java language because in java everything is an object, it can be easily extended since it is based on the object model. It’s simple and easy to learn, it’s secure, it’s portable, it’s robust, it’s interpreted : java byte code is translated on the fly to native machine instructions and is not stored anywhere.java has a high performance and it’s multithreaded : it’s possible to write programs that can perform many tasks simultaneously.


WampServer in our project, we have used the server Wamp, which provides the basics for setting up your local Apache/PHP/MySQL environment on windows.


Apache is our web server software.


PHP is the general purpose scripting language that runs on Apache.


MySQL is the database server software that works hand-in-hand with PHP and Apache.
phpMyAdmin is a free software tool written in PHP, intended to handle the administration of MYSQL over the web. Concerning our project, we have used phpMyAdmin to develop our database.


SUBLIME is a test editor which helps us to write our srs in Read the doc.


DIA is an application which helps us to do our UML diagrams.


VISUAL STUDIO is a source code editor developed by Microsoft for windows, linux and macOS. It includes support for debugging, embedded Git control...in our lab project, we choose visual studio to implement our application and develop environment tools. 


ACTORS OF SYSTEM:
=================


Students

Instructors

TAs

Administrators

Visitors


DATABASE:
=========


A database is an organized collection of data, stored and accessed electronically. Database designers typically organize the data to model aspects of reality in a way that supports processes requiring information, such as (for example) modelling the online lab report of students assignment in lab and teacher give them feedback.


For this project, we have five (5) tables such as: students, instructors, TAs, administrators and visitors.


FUNCTIONAL REQUIREMENTS :
=========================


UML DIAGRAMS:
=============


UML means Unified Modeling Language. UML is a way of visualizing a software program using a collection of diagrams. UML 2.0 helped extend the original UML specification to cover a wider portion of software development efforts including agile practices.


Development process and UML diagram :


Behavioral UML diagrams:
------------------------


Use case diagram


A use case diagram is a set of use cases, actors and their relationships.it’s represents the use case view of a system. For our project lab, we have five (5) actors and then we have doing a use case of each actor of system. It represents a particular functionality of a system. Use case diagram is used to describe the relationships among the functionalities and their internal/external controllers. These controllers are known as actors. For example, for our lab project , our controllers is admin.


Sequence diagram


A sequence diagram is an interaction diagram. From the name it’s clear that the diagram deals with some sequences, which are the sequence of messages flowing from one object to another. It’s use to visualize the sequence of calls in a system to perform a specific functionality.


Activity diagram


Activity diagram describes the flow of contol in a system. It consists of activities and links. Activity diagram are used t visualize the floor of controls in a system.


Structural UML diagrams
-----------------------


Class diagram


A class diagram consists of classes, interfaces, associations and collaboration. In this lab project, this class diagram bellow represent basically the object-oriented view of our system.


Component diagram


A component diagram represent a set of components and their relationships. These components consist of classes, interfaces and collaborations. It represents the implementation view of a system.


Scenario/base scenario
======================


create account
--------------

Fill in your name


Enter your id


Enter your email


Enter your phone number


Enter your course


Enter your password


Press the button create


Press enter


login in the web portal
-----------------------

Fill in your name or email


Fill in your password


Press the button connection


check feedback
--------------

Click on feedback menu


Click on the link


Open the link


Read the link


Download the link


set the deadline
----------------


Click on the calendar


Select the date


Click on extend deadline


Click on update deadline


Press in save new deadline


delete account
--------------

Click on users account


Select the account


Click on delete


Click on suspend account


Press in the button enter


initialize a password
---------------------

Select user account


Choose the account


Click on the button initialize


Fill in the password


Save the new password


Press the button enter


send request
------------

Press request button 


Fill in your request


Press  send request

Save the request


give feedback
-------------

Click in student email


Choose the student email


Send feedback


REFERENCES:
===========


https://cn.bing.com/search?q=running+environment+phpmysql&src=IE-TopResult&FORM=IETR02&conversationid=&pc=EUPP_
https://www.tutorialspoint.com/uml/uml_standard_diagrams.htm
https://www.tutorialspoint.com/uml/uml_standard_diagrams.htm
https://courses.cs.washington.edu/courses/cse403/11sp/lectures/lecture08-uml1.pdf
http://www.nyu.edu/classes/jcf/g22.2440-001_sp09/handouts/UMLBasics.pdf
https://www.ibm.com/support/knowledgecenter/SS8PJ7_9.6.1/com.ibm.xtools.modeler.doc/topics/cinterfc.html
https://techwhirl.com/writing-software-requirements-specifications/
https://www.uml-diagrams.org/component-diagrams.html
https://www.ibm.com/developerworks/rational/library/dec04/bell/index.html
https://docs.staruml.io/working-with-diagrams/component-diagram
https://online.visual-paradigm.com/tutorials/component-diagram-tutorial/
https://www.tutorialspoint.com/uml/uml_component_diagram.htm
https://online.visual-paradigm.com/diagrams.jsp#diagramlist:proj=0&new=ComponentDiagram
https://www.smartdraw.com/component-diagram/
https://tallyfy.com/uml-diagram/










 





.. image:: img/activity_diagram.png