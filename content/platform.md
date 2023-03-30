+++
title = "Platform"
date = "2023-03-17"
sidemenu = "true"
description = "Welcome to Golab Platform"
+++

## OUTLINE
---------------

Golab uses LIMS (Laboratory Information Management System), a software application designed by Slingr specifically to manage and track laboratory data and workflows. 

LIMS can help laboratories increase efficiency, reduce errors, costs, and comply with regulatory requirements. It can also provide a central repository for laboratory data, enabling better collaboration and data sharing among different departments, organizations and users.


## Introduction
---------------


A step by step guide to use your platform

* [Users](#users)
* [Login](#login)
* [Administration Panel](#administration-panel)
* [Settings Panel](#settings-panel)
* [Dashboard](#dashboard)
* [Samples](#samples)
* [Methods](#methods)
* [Templates](#templates)
* [Tests](#tests)

## Users
---------------

The platform allows three types of users: Admins, Technicians and Patients

#### Admins:
Admins are typically responsible for the overall management of the LIMS application. They have full access to all features and functionality of the application and are responsible for configuring and maintaining the system. 

#### Technicians:
Technicians are responsible for performing laboratory tests and managing samples. 

#### Patients:
Patients are typically the end users of the LIMS application. They may interact with the system through a patient portal or mobile app.


## Login
---------------

Users and passwords are given by administrators of the platform. Once you get yours, login into your account using the following link: [Golab Slingr Platform](https://golablims.slingrs.io/dev/runtime/login.html)

#### Login Panel



## Administration Panel
---------------


## Settings Panel
---------------


## Dashboard
---------------

In the dashboard of the app Golab you can take a quick look at the status of the samples status and patients status.
We have some indicators that give us a quick look at how many New Samples, Samples in Process, Samples in Review and Samples Rejected there are.
There is a bar chart that shows us the number of Samples created per week, a line graph for the status of those samples (ready, discarded, with issues), there are also pie charts of Patients per month, Samples per test type, etc.


## Samples
---------------

Each sample created will have the status "New" and then it can be changed to "Processing" where the test will be performed, after that it will go to the status "In review", here the sample will be checked and it will be seen if everything is in order or something goes wrong.
If all turned out well, it goes to the "Ready" state, but if not, it will move to the "With issues" state where it will check again and here you can go back to "Ready" or move forward to "Rejected", here what can happen is to take the samples again and repeat the whole process or it just goes to "Discarded" where the sample is like the state name said, it will be discarded and the whole process workflow will end.

## Methods
---------------

This are the particulars procedures to carry out the tests that patients need to get. For example, a physical analysis has many methods like spectrophotometry, x-ray fluorescence, titrations, etc.


## Templates
---------------

The templates already have the most important patient information and test results sorted with their own methods that patient need.


## Tests
---------------

Here you can see the test types, the days it will take and its status.

## Notifications
---------------

We used Mailchimp to keep our patients and technicians informed about the status of their samples. We send automated email notifications to patients when:

* **Samples have been created**: Includes the sample code so patients can follow their sample on our app.
* **Samples results are ready**: Includes link to our Android and IOS app.
* **Samples have been rejected for any reason**: Includes the reason why their sample has been rejected.

We also send notifications to our lab technicians when:

* **Samples are about to expire**: Includes the sample's link to our platform.
* **Samples have expired**: Includes the sample's link to our platform.

This helps reducing the risk of inaccurate or unreliable test results. Also helps to keep our patients informed of any issues or delays that may arise during the testing process and reduces the amount of time they spend waiting for their results.

{{< figure src="/img/notification-sample.gif" class="platform-notification" width="100%" >}}

[(Back to top)](#introduction)