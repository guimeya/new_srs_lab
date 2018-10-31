PROJECT LAB:
============

SRS
---

NAME: GUIMEYA JIOFACK JANNY CAROLE 201825800044

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


The Internet connection is also a constraint for the application. Since the application fetches data from the database over the Internet, it is crucial that there is an Internet connection for the application to function.



 





.. image:: img/activity_diagram.png