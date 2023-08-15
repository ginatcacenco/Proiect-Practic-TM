# <h1 align="center">Proiect Practic Testare Manuala<h1>
# OrangeHRM Project
## Test Plan

## Revision history
### Test title
| Date | Version | Authors | Comments |
| :-----: | :---: | :---: |:---: |
| 11.03.2023 | v1.0| Ioana Marinescu| *Draft plan*|
| ***22.07.2023*** | v1.0| **Gina Tcacenco** | ***Test results for functional testing*** |
| 22.07.2023 | v1.0| Marian Dumitrache | Test results for GUl testing |

# 1. Introduction
    
This test plan describes the strategies, process, workflows and methodologies used to plan, organize, execute and manage testing process for OrangeHRM browser
application. 

## 1.1 Project objective
    
The scope of the final project for ITF Manual & Automation Testing Course is to use all gained knowledge through the course and apply them in practice using a live application. 
    
Application under test: <https://opensource-demo.orangehrmlive.com/> 
    
Application documentation: <https://www.orangehrm.com/assets/Files/Complete-Administrative-User-Guide.pdf?url=/Files/Complete-Administrative-User-Guide.pdf> 

Tools: Jira, Zephyr Squad.
    
## 1.2 Functionalities in scope
    
All features of Emergency Contacts module which were defined in software requirement specifications need to be: functional testing, GUI testing.  
   

## 1.3 Functionalities and tests out of scope

- All OrangeHRM features except Emergency Contacts module.
- Non-functional testing like stress, performance is beyond scope of this project
- No QA support for mobile application developed. Only web application will be tested.
- Automation testing is beyond scope.

# 2.Test process
    
## 2.1  Test planning
    
The Test Plan is designed to describe all details of testing for the Emergency Contacts module from the OrangeHRM application. 

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing and the risks associated with the plan.
    
### 2.1.1 Roles and responsibilities
    
* Software Developer: Daniel Atasiu
* Product Owner: Maria Ioana Gherman
* Project Manager: Catalin Rosu 
* QA Engineer: Tcacenco Gina - Ioana 
* Senior QA Engineer: Andrada Popescu  
    
### 2.1.2 Entry criteria 

* functional specifications are defined
* roles needed for the project are allocated
* initial project risks were detected and mitigated
    
### 2.1.3 Exit criteria 

* all test cases have been executed 
* the number of unresolved bugs is insignificant or have low priority 
* all resolved bugs have been re-tested and closed by QA team 
* deadline was reached 
* no detected major risks remained un-mitigated 
    
### 2.1.4 Risks
Project risks: 
* lack of experience of the QA team which can cause failure to meet the deadlines and inability to fix all bugs
* only one QA Engineer in the QA team 
* unavailability of the test environment 
* short trial period of Zephyr Squad and Jira tools which can cause short deadline and/or pressure on the team and inability to fix all bugs
    
Product risks: 
* the app doesn't work constantly
* the product does not meet the customer's expectations
* the product does not meet the requirements
    
## 2.2 Test analysis 

* Analyze business requirements to make sure that we have all the details for creating the test conditions 
* Write test conditions that will be tested in out test process
    
## 2.3 Test design
* Functional test cases will be created in Zephyr Squad 
* GUI test cases will be created in Zephyr Squad
* The test design techniques used for generating test cases are: equivalence partitioning, boundary value analysis. 
    
## 2.4 Test implementation
Verify that the following elements are ready before the test execution phase: 
* Test environment is up and running: <https://opensource-demo.orangehrmlive.com/web/index.php/auth/login> 
* Access to the test environment is given: username Admin, pass: admin123
* Cycle summary was created and the test cases were added to the cycle summary 

    
## 2.5 Test execution
* Test cases are executed on the created Cycle summary 
* Bugs were created based on the failed test cases. 
* Full regression pack was executed 
    
## 2.6 Test completion (test closure)
As the exit criteria were met and satisfied as mentioned in the 2.1 section, this feature is suggested to go live by the QA team. 
    
## 2.7 Test monitoring and control
Various periodic reports were generated to reflect the current status of the testing process, in case of major problems control measures could be taken.


# 3.Test deliverables
    
## 3.1  Test plan
    
## 3.2  Test conditions
The testing process will be executed based on the above requirements for the Emergency Contacts module. The following test conditions were found:
 * Enter data only for mandatory fields and check that the emergency contact is created/updated
 * Enter data for all available fields and check that the emergency contact is created/updated
 * Leave mandatory fields empty and check that the emergency contact cannot be created/updated
 * View all emergency contacts in a list
 * Check that it is possible to attach files  
 * Check all validation constraints for the fields 
    
## 3.3  Test cases
The test cases with steps can be viewed here: [Emergency contacts test cases.pdf](https://github.com/ginatcacenco/Proiect-Practic-TM/blob/main/test%20cases.pdf)
    
## 3.4  Daily test summary report 
    
## 3.5  Traceability matrix 
The traceability matrix was generated using Zephyr Squad and is detailed below or it can be downloaded from [here](https://github.com/ginatcacenco/Proiect-Practic-TM/blob/main/traceability%20matrix.xlsx):


![Traceability matrix](https://github.com/ginatcacenco/Proiect-Practic-TM/blob/main/traceability%20matrix.png)
    
## 3.6  Test case results
The test cases with steps can be viewed here: [Test case results](https://github.com/ginatcacenco/Proiect-Practic-TM/blob/main/test%20case%20results.pdf)
    
## 3.7  Bugs report
Bugs have been created based on the failed tests. The complete bug reports can be found here:  [Emergency contacts bugs.pdf](https://github.com/ginatcacenco/Proiect-Practic-TM/blob/main/bugs.pdf)
    
## 3.8  Test completion report
* As the Exit criteria were met and satisfied as mentioned in the appropriate section, this feature is suggested to ‘Go Live’ by the Testing team.
* Test execution chart was generated, the final report shows that a number 4 tests have failed of a total of 31.
* A number of 31 test cases were planned for execution and all of them were executed.
* A number of 4 total bugs were found, from which the priority is: 1 is highest, 1 is medium and 2 are low.

![Tests execution chart](https://github.com/ginatcacenco/Proiect-Practic-TM/blob/main/Execution%20report.png)

    
 









