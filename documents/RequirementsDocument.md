# Software Requirements and Use Cases

## Your Project Title
--------
Prepared by:

* `<McAlister Marshall>`,`<WPI>`
* `<Jake Claybrook>`,`<WPI>`
* `<Vanessa Villalba Simon>`,`<WPI>`
* `<Jace Howhenesian>`,`<WPI>`

---

**Course** : CS 3733 - Software Engineering

**Instructor**: Sakire Arslan Ay

---

## Table of Contents
- [1. Introduction](#1-introduction)
- [2. Requirements Specification](#2-requirements-specification)
  - [2.1 Customer, Users, and Stakeholders](#21-customer-users-and-stakeholders)
  - [2.2 User Stories](#22-user-stories)
  - [2.3 Use Cases](#23-use-cases)
- [3. User Interface](#3-user-interface)
- [4. Product Backlog](#4-product-backlog)
- [4. References](#4-references)
- [Appendix: Grading Rubric](#appendix-grading-rubric)

<a name="revision-history"> </a>

## Document Revision History

| Name | Date | Changes | Version |
| ------ | ------ | --------- | --------- |
|Revision 1 |2024-11-07 |Initial draft | 1.0        |
|      |      |         |         |
|      |      |         |         |

----
# 1. Introduction

Provide a short description of the software being specified. Describe its purpose, including relevant benefits, objectives, and goals.

This software is used to conect WPI faculty members to students who are looking for undergraduate research. The benefits for this software will increase student interaction between faculty and undergraduates and give students the oppertuity to do research while still in school. The goal of this software is to streamline the discorvery and application process for students to apply for research. This will reduce the time that professors spend looking for students, and make it much easier for students to apply.

----
# 2. Requirements Specification

This section specifies the software product's requirements. Specify all of the software requirements to a level of detail sufficient to enable designers to design a software system to satisfy those requirements, and to enable testers to test that the software system satisfies those requirements.


The software will allow students to create a profile and enter their contact information, completed
coursework, research interests, and other qualifications, as well as apply for research positions.

The software will allow faculty to select the candidates that they would like to interview for the position. faculty can also advertise research opportunities for undergraduate students,

The application should feature two main sections—a Student Page and a Faculty Page—each
offering customized options for creating profiles, posting opportunities, and managing
applications.

## 2.1 Customer, Users, and Stakeholders

A brief description of the customer, stakeholders, and users of your software.

The customers of our software are universities/colleges that are in need of a platform that advertises research positions and connect with qualified undergraduate students. The stakeholders of our software are the universities/colleges, programmers of the platform, and the faculty and students of the universities/colleges. The users of our software are the faculty and students of the universities/colleges.

----
## 2.2 User Stories
This section will include the user stories you identified for your project. Make sure to write your user stories in the form : 
"As a **[Role]**, I want **[Feature]** so that **[Reason/Benefit]** "
Students:
1. As a faculty, I want to post my research oppertunities to the software so that users have easy access to the research
2. As a student, I want to create an account and enter my personal information so that the faculty can evaluate my qualifications
3. As a student, I want to edit my profile after creating it so that I can make any relevant changes and keep my academic information up to date
4. As a student, I want to log in using my WPI email/password or Auth0 SSO so that I can access my account securely.
5. As a student, I want to view all research positions posted by faculty so that I can browse opportunities.
6. As a student, I want to click a position and view full details so that I understand requirements and expectations.
7. As a student, I want the system to recommend positions that match my profile so that I don’t have to manually search through everything.
8. As a student, I want to submit a short statement with my application so that the faculty understands my motivation.
9. As a student, I want to track the status of all of my applications so that I know if they are pending, approved, or rejected.
10. As a student, I want to withdraw my pending application so that I can stop pursuing positions I am no longer interested in.

Faculty:
1. As a faculty member, I want to activate my account from the preloaded list so that I can start using the system.
2. As a faculty member, I want to confirm my identity via email verification so that the system knows I am a real WPI faculty member.
3. As a faculty member, I want to log in with WPI email/password or SSO so that I can securely access my faculty dashboard.
4. As a faculty member, I want to view my own profile so that I can confirm my information.
5. As a faculty member, I want to approve or reject recommendation requests from students so that I can support or decline their application.
6. As a faculty member, I want to create one or more research positions so that I can find undergraduate students for my projects.
7. As a faculty member, I want to specify required major(s), GPA, topics, languages, and courses so that the right students apply.
8. As a faculty member, I want to add, edit, or remove items from predefined lists (topics, languages, majors, etc.) so that the system remains accurate.
9. As a faculty member, I want to view all students who applied to my positions so that I can review candidates.
10. As a faculty member, I want to view the academic profile of an applicant so that I can evaluate their fit.
11. As a faculty member, I want to approve student applications so that I can recruit students for the position.
12. As a faculty member, I want to reject student applications so that I can filter out unqualified or mismatched candidates.





----
## 2.3 Use Cases -Mcalister

This section will include the specification for your project in the form of use cases. 

Group the related user stories and provide a use case for each user story group. You don't need to draw the use-case diagram for the use cases; you will only provide the textual descriptions.  **Also, you don't need to include the use cases for "registration" and "login" use cases for both student and faculty users.**

  * First, provide a short description of the actors involved (e.g., regular user, administrator, etc.) and then follow with a list of the use cases.
  * Then, for each use case, include the following:

    * Name,
    * Participating actors,
    * Entry condition(s) (in what system state is this use case applicable),
    * Exit condition(s) (what is the system state after the use case is done),
    * Flow of events (how will the user interact with the system; list the user actions and the system responses to those),
    * Alternative flow of events (what are the exceptional cases in the flow of events and they will be handles)
    * Iteration # (which sprint do you plan to work on this use case) 

Each use case should also have a field called "Iteration" where you specify in which iteration you plan to implement this feature.

You may use the following table template for your use cases. Copy-paste this table for each use case you will include in your document.

| Use case # 1      |   |
| ------------------ |--|
| Name              | "enter your reponse here"  |
| Participating actor  | "enter your reponse here"  |
| Entry condition(s)     | "enter your reponse here"  |
| Exit condition(s)           | "enter your reponse here"  |
| Flow of events | "enter your reponse here"  |
| Alternative flow of events    | "enter your reponse here"  |
| Iteration #         | "enter your reponse here"  |

| Use case # 1      |   |
| ------------------ |--|
| Name              | "create student account and profile"  |
| Participating actor  | "student"  |
| Entry condition(s)     | "student has a valid wpi email"  |
| Exit condition(s)           | "profile is created"  |
| Flow of events | "1. Student prompts software to create account
                    2. Software brings up registration form
                    3. student fills out all fields"
                    4. software validates fields 
                    5. student submits forms |
| Alternative flow of events    | "field filled out incorrectly, software flags error message
                                   email is already in use, notifies the user with an error message"  |
| Iteration #         | "1"  |

| Use case # 2      |   |
| ------------------ |--|
| Name              | "edit student profile"  |
| Participating actor  | "student"  |
| Entry condition(s)     | "student has a valid wpi email and is logged into their account"  |
| Exit condition(s)           | "edits are completed"  |
| Flow of events | "1. Student prompts software to enter edit profile
                    2. Software brings up profile edit form
                    3. student fills out neccessary fields"
                    4. software validates fields 
                    5. student submits forms |
| Alternative flow of events    | "field filled out incorrectly, software flags error message"  |
| Iteration #         | "1"  |

| Use case # 3      |   |
| ------------------ |--|
| Name              | "student login"  |
| Participating actor  | "student"  |
| Entry condition(s)     | "student has a valid wpi email and has an account"  |
| Exit condition(s)           | "login is verified"  |
| Flow of events | "1. Student prompts software to login
                    2. Student enters login credientials
                    3. student submits login credentials
                    4. software authenticates 
                    5. student is logged in |
| Alternative flow of events    | "credentials not valid, software flags error message"  |
| Iteration #         | "1"  |

| Use case # 4      |   |
| ------------------ |--|
| Name              | "view research positions"  |
| Participating actor  | "student"  |
| Entry condition(s)     | "student is logged into their account"  |
| Exit condition(s)           | "all items are loaded"  |
| Flow of events | "1. Student prompts software to enter research information 
                    2. Software brings up items
                    3. displays all information about the research positions0opl |
| Alternative flow of events    | "no positions are avaliable and displays so"  |
| Iteration #         | "1"  |

| Use case # 5      |   |
| ------------------ |--|
| Name              | "view reseach positon details"  |
| Participating actor  | "student"  |
| Entry condition(s)     | "student is logged into their account"  |
| Exit condition(s)           | "page is loaded and displays"  |
| Flow of events | "1. Student prompts software to view a specific research position
                    2. Software retrieves details
                    3. software displays details"
                    4. student views page |
| Alternative flow of events    | "position removed, displays as so"  |
| Iteration #         | "1"  |

| Use case # 6      |   |
| ------------------ |--|
| Name              | "view reccomended position"  |
| Participating actor  | "student"  |
| Entry condition(s)     | "student is logged into their account"  |
| Exit condition(s)           | "the personalized list is displayed"  |
| Flow of events | "1. Student prompts software to view a reccomended positons
                    2. Software retrieves details
                    3. software displays details"
                    4. student views page |
| Alternative flow of events    | "no matches, displays as so"  |
| Iteration #         | "2"  |

| Use case # 7     |   |
| ------------------ |--|
| Name              | "apply for research position"  |
| Participating actor  | "student"  |
| Entry condition(s)     | "student is logged into their account"  |
| Exit condition(s)           | "application is submitted"  |
| Flow of events | "1. Student prompts software to apply
                    2. Software displays form fields
                    3. student fills out all fields"
                    4. software validates fields 
                    5. student submits forms |
| Alternative flow of events    | "field filled out incorrectly, software flags error message
                                   email is already in use, notifies the user with an error message"  |
| Iteration #         | "2"  |

| Use case # 8     |   |
| ------------------ |--|
| Name              | "view appolication status"  |
| Participating actor  | "student"  |
| Entry condition(s)     | "student is logged into their account and has submitted at least 1 application"  |
| Exit condition(s)           | "page is viewed/exited"  |
| Flow of events | "1. Student prompts software to see application statuses
                    2. Software displays all applications and statuses 
                    3. displays any updates |
| Alternative flow of events    | "unable to find applications on account"  |
| Iteration #         | "2"  |

| Use case # 9     |   |
| ------------------ |--|
| Name              | "withdrawing application"  |
| Participating actor  | "student"  |
| Entry condition(s)     | "student is logged into their account and have a pending application"  |
| Exit condition(s)           | "application is withdrawn"  |
| Flow of events | "1. Student prompts software to open appilcations
                    2. Student prompts software to withdraw specific application
                    4. software withdraws application |
| Alternative flow of events    | "application has been approved while button is still active, displays cannot withdraw"  |
| Iteration #         | "2"  |


| Use case # 10      |   |
| ------------------ |--|
| Name              | "submit faculty refrence"  |
| Participating actor  | "student"  |
| Entry condition(s)     | "student is logged into their account, is applying for a positon needing a refrence"  |
| Exit condition(s)           | "application is submitted"  |
| Flow of events | "1. Student prompts software to add refrence
                    2. Software displays form fields
                    3. student fills out all fields
                    4. software validates fields 
                    5. student submits forms |
| Alternative flow of events    | "field filled out incorrectly, software flags error message
                                   faculty not found, notifies the user with an error message"  |
| Iteration #         | "2"  |


FACULTY:
|-------------------------------------------|

| Use case # 11      |   |
| ------------------ |--|
| Name              | "create faculty account and profile"  |
| Participating actor  | "faculty"  |
| Entry condition(s)     | "faculty has a valid wpi email"  |
| Exit condition(s)           | "profile is created"  |
| Flow of events | "1. Faculty prompts software to create account
                    2. Software brings up registration form
                    3. Faculty fills out all fields
                    4. software validates fields 
                    5. Faculty submits forms |
| Alternative flow of events    | "field filled out incorrectly, software flags error message
                                   email is already in use, notifies the user with an error message"  |
| Iteration #         | "1"  |

| Use case # 12      |   |
| ------------------ |--|
| Name              | "verify faculty email"  |
| Participating actor  | "faculty"  |
| Entry condition(s)     | "profile creation is started"  |
| Exit condition(s)           | "email is validated"  |
| Flow of events | "1. Faculty validates email
                    3. Software checks validation token 
                    4. software displays validation sucessful |
| Alternative flow of events    | "expired token, software flags error message"  |
| Iteration #         | "1"  |

| Use case # 13      |   |
| ------------------ |--|
| Name              | "faculty login"  |
| Participating actor  | "faculty"  |
| Entry condition(s)     | "faculty has a valid wpi email and has an account"  |
| Exit condition(s)           | "login is verified"  |
| Flow of events | "1. faculty prompts software to login
                    2. faculty enters login credientials
                    3. faculty submits login credentials
                    4. software authenticates 
                    5. faculty is logged in |
| Alternative flow of events    | "credentials not valid, software flags error message"  |
| Iteration #         | "1"  |

| Use case # 14      |   |
| ------------------ |--|
| Name              | "View faculty profile"  |
| Participating actor  | "faculty"  |
| Entry condition(s)     | "faculty is logged in"  |
| Exit condition(s)           | "profile is displayed"  |
| Flow of events | "1. faculty prompts software to view profile
                    2. software retrieves and displays profile data |
| Alternative flow of events    | "profile cannot be found, software flags error message"  |
| Iteration #         | "1"  |

| Use case # 15      |   |
| ------------------ |--|
| Name              | "create research position"  |
| Participating actor  | "faculty"  |
| Entry condition(s)     | "faculty is logged in"  |
| Exit condition(s)           | "research positon is created and published"  |
| Flow of events | "1. faculty prompts software to create a research positon 
                    2. Software brings up profile edit form
                    3. faculty fills out neccessary fields"
                    4. software validates fields 
                    5. faculty submits forms |
| Alternative flow of events    | "field information not valid, software flags error message"  |
| Iteration #         | "1"  |

| Use case # 16      |   |
| ------------------ |--|
| Name              | "define research position requirements"  |
| Participating actor  | "faculty"  |
| Entry condition(s)     | "faculty is logged in"  |
| Exit condition(s)           | "research positon requiremnts is added to previous posted positon and published"  |
| Flow of events | "1. faculty prompts software to define research positon requiments
                    2. Software brings up profile edit form
                    3. faculty fills out neccessary fields"
                    4. software validates fields 
                    5. faculty submits forms |
| Alternative flow of events    | "field information not valid, software flags error message"  |
| Iteration #         | "1"  |

| Use case # 17      |   |
| ------------------ |--|
| Name              | "manage predefined list"  |
| Participating actor  | "faculty"  |
| Entry condition(s)     | "faculty is logged in"  |
| Exit condition(s)           | "predefined lists and info updated"  |
| Flow of events | "1. faculty prompts software to edit predefined lists
                    2. Software brings up edit list
                    3. faculty fills out neccessary fields"
                    4. software validates fields 
                    5. faculty submits forms |
| Alternative flow of events    | "field information not valid, software flags error message"  |
| Iteration #         | "2"  |

| Use case # 18      |   |
| ------------------ |--|
| Name              | "view research positon applicants"  |
| Participating actor  | "faculty"  |
| Entry condition(s)     | "faculty is logged in"  |
| Exit condition(s)           | "research positon applicants are displayed"  |
| Flow of events | "1. faculty prompts software to show research positon application for different projects
                    2. Software brings up list information of applicants |
| Alternative flow of events    | "no applicants, software flags error message"  |
| Iteration #         | "2"  |

| Use case # 19      |   |
| ------------------ |--|
| Name              | "view applicant profile"  |
| Participating actor  | "faculty"  |
| Entry condition(s)     | "faculty is logged in"  |
| Exit condition(s)           | "applicant profile is displayed"  |
| Flow of events | "1. faculty prompts software to show research positon applicant
                    2. Software brings up applicant profile with neccesary information"|
| Alternative flow of events    | "applicant not found, software flags error message"  |
| Iteration #         | "2"  |

| Use case # 20      |   |
| ------------------ |--|
| Name              | "approve reseach positon applicant"  |
| Participating actor  | "faculty"  |
| Entry condition(s)     | "faculty is logged in and has applicants for positons"  |
| Exit condition(s)           | "application updated to being approved"  |
| Flow of events | "1. faculty prompts software to show research positon applicant
                    2. Software brings up applicant profile with neccesary information"
                    3. Faculty verifies applicant as appoved
                    4. software submits that information and updates profile|
| Alternative flow of events    | "applicant not found, software flags error message"  |
| Iteration #         | "2"  |

| Use case # 21      |   |
| ------------------ |--|
| Name              | "reject reseach positon applicant"  |
| Participating actor  | "faculty"  |
| Entry condition(s)     | "faculty is logged in and has applicants for positons"  |
| Exit condition(s)           | "application updated to being rejected"  |
| Flow of events | "1. faculty prompts software to show research positon applicant
                    2. Software brings up applicant profile with neccesary information"
                    3. Faculty verifies applicant as rejected
                    4. software submits that information and updates profile|
| Alternative flow of events    | "applicant not found, software flags error message"  |
| Iteration #         | "2"  |

| Use case # 20      |   |
| ------------------ |--|
| Name              | "manage reccomendation requests"  |
| Participating actor  | "faculty"  |
| Entry condition(s)     | "faculty is logged in"  |
| Exit condition(s)           | "updates reccomendation status"  |
| Flow of events | "1. faculty prompts software to show research positon reccomendations
                    2. Software brings up applicant profiles with neccesary information"
                    3. Faculty approves or rejects reccomendation
                    4. software submits that information and updates profile|
| Alternative flow of events    | "no reccomended applicants, displays so"  |
| Iteration #         | "2"  |


----
# 3. User Interface -

Here you should include the sketches or mockups for the main parts of the interface.
You may use Figma to design your interface:

  Example image. The image file is in the `./images` directory.
  <kbd>
      <img src="images/figma.jpg"  border="2">
      <img src="images/User Interface/Home.png">
      <img src="images/User Interface/Research Opportunties.png">
      <img src="images/User Interface/Register.png">
      <img src="images/User Interface/Student Login.png">
      <img src="images/User Interface/Student Page.png">
      <img src="images/User Interface/Student Profile.png">
      <img src="images/User Interface/Student Edit Profile.png">
      <img src="images/User Interface/Faculty Login.png">
      <img src="images/User Interface/Faculty Page.png">
      <img src="images/User Interface/Faculty Profile.png">
      <img src="images/User Interface/Faculty Edit Profile.png">
  </kbd>
  
----
# 4. Product Backlog - Jake

Here you should include a link to your GitHub repo issues page, i.e., your product backlog. Make sure to create an issue for each user story.

Issue Page Link:
https://github.com/jclaybrook04/CS3733-Term-Project-Team-RouteRunners/issues


----
# 5. References

Cite your references here.

For the papers you cite give the authors, the title of the article, the journal name, journal volume number, date of publication and inclusive page numbers. Giving only the URL for the journal is not appropriate.

For the websites, give the title, author (if applicable) and the website URL.

----
----
# Appendix: Grading Rubric
(Please remove this part in your final submission)

These is the grading rubric that we will use to evaluate your document. 

| Max Points  | **Content** |
| ----------- | ------- |
| 4          | Do the requirements clearly state the customers’ needs? |
| 2          | Do the requirements avoid specifying a design (note: customer-specified design elements are allowed)? |
| | |  
|    | **Completeness** |
| 14 | Are user stories complete? Are all major user stories included in the document?  |
| 5 | Are user stories written in correct form? | 
| 14 |  Are all major use cases (except registeration and login) included in the document? |
| 15 | Are use cases written in sufficient detail to allow for design and planning? Are the "flow of events" in use case descriptions written in the form of "user actions and system responses to those"? Are alternate flow of events provided (when applicable)? | 
| 6 |  Are the User Interface Requirements given with some detail? Are there some sketches, mockups?  |
| | |  
|   | **Clarity** |
| 5 | Is the document carefully written, without typos and grammatical errors? <br> Is each part of the document in agreement with all other parts? <br> Are all items clear and not ambiguous? |
| | |
|**65**|**TOTAL**|


