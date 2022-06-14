                          	
					







 Automation Test Strategy
Contract Management System



























Revision / Document History

Version	Date	Author	Description
0.5	6 Feb 2009	Makesh	Initial draft 
1.0	26 Feb 2009	Makesh	Updated as per the comments captured during team discussion w.r.t strategy
			
			



 
Table of Contents
1.	INTRODUCTION	4
2.	SCOPE	4
3.	APPROACH	4
3.1	PHASE I – APPLICATION UNDERSTANDING & AUTOMATION TEST ENVIRONMENT SETUP	4
3.2	PHASE II – FUNCTIONAL TEST CASE REVIEW	5
3.3	PHASE III	6
3.4	PHASE IV	7
4.	TEST ENVIRONMENT SETUP	7
4.1	HARDWARE CONFIGURATION	9
4.2	SOFTWARE CONFIGURATION	9
5.	TASK & BASELINE TASKS	10
6.	REVIEW PROCESS	11
6.1	TEST CASE REVIEW	11
6.2	AUTOMATABLE/NON- AUTOMATABLE REVIEW PROCESS	11
6.3	TEST SCRIPT REVIEW	11
6.4	BATCH MODE TEST EXECUTION REVIEW PROCESS	12
7.	APPROVAL PROCESS	12
7.1	TEST CASE APPROVAL	12
7.2	AUTOMATABLE/NON- AUTOMATABLE APPROVAL	12
7.3	BATCH MODE TEST EXECUTION APPROVAL PROCESS	13
8.	SCRIPT MAINTENANCE	13
9.	REPORTING AND STATUS UPDATES	13
10.	DELIVERABLES	13
11.	RISK & MITIGATION PLAN	13


 
1.	Introduction

This is the Automation Test strategy document which will dedicate the task & activities involved to complete the Functional Test Automation for Contract Management systems (hereafter referred as CMS).


2.	Scope 

The scope of the project is to perform the Functional Test Automation for CMS using QTP 9.5. In addition to the above, the existing test cases will be reviewed and should be tweaked to improve the quality of the test cases. Also wherever required new cases have to be created to ensure that maximum functional test coverage is obtained.

Up on completion of reviewing/enhancing/creating new test cases, the team will automate the feasible test cases and deliver the test scripts to ABC. 

Also Automation suite should help ABC QA team to perform the regression testing for upcoming releases.


3.	Approach

3.1	Phase I – Application Understanding & Automation Test Environment Setup

The first phase of the project is Application Understanding. The set of identified automation test engineers will take part in a series of session to understand the application functionality existing in CMS application. Also it has been planned in such a way that ABC will send Functional QA Lead and Develop Manager to conduct series of demo and interactive session to spread across the core functionality of the application to the automation team.

Moreover after each session, the automation team will share the understanding on the application what has been covered for that day via email. Any questions/clarification will also be asked in the same email so that ABC QA Lead can clarify them on the next day.

The above exercise will definitely help the team to clarify the doubts on the functional features and at the same time it will allow ABC whether the automation team has really understood the core functional features of the application.

This phase is planned for 3 weeks and at the end of first phase, the automation team should be having in-depth functional understanding of the application.

Parallely the Automation Project Manager will work with ABC Infrastructure team and XYZ Infrastructure team to get the necessary test environment ready before the start of phase3.

Deliverables for Phase1:

1.	Understanding email on the functional features from automation team ABC QA Lead
2.	Automation Test Plan



Required from ABC/XYZ:

1.	Application Demo and Session on Functional Features
2.	Establishing VPN connectivity for the accessing of server from both locations
3.	Getting the Automation Test Environment Setup 
4.	Getting the perforce setup for ongoing script maintenance
5.	Review of Automation Test Plan

3.2	Phase II – Functional Test Case Review

The phase will involve the Functional Test Case Review. In order to start with the review, ABC should provide access to the existing test cases that has been already written by internal QA team. Automation team will take stock of all the test cases and segregate them as per the functional understanding which has been achieved in phase1. 

The test cases will be allocated to the automation team and the information will be shared with ABC so that it is clear that who owns which feature and so on. This will really help to get in touch with the right resource for any clarifications/questions/suggestions.

Each member of the automation team will review the test cases and capture the review comments, if necessary information is missing like incomplete test procedure, not clearly defined expected results, invalid test cases, missing test cases for the functional features and so on.

The phase is planned for 4 weeks, on the first 2 weeks the automation team will work on reviewing the test cases and capture the review comments in the spreadsheet. The comments will be shared on weekly basis to ABC. After completing the above exercise, will definitely help to quantify the efforts involved in updating existing test cases and creation of new test cases.

On the third week, the team will start enhancing the existing test cases to improve the quality of the test cases and the same will be sent for review to ABC.

On the fourth week, creation of new test cases will happen and it will be shared with ABC for approval

While coming to classification of test cases, Automation team recommends in such a way that there will be 3 categories on how the test cases will be looked into.

a.	Sanity Level Test Cases: This will cover the basic functionality touching almost all the modules to ensure the application works fine and it can be drilled down for further testing. For example, it takes a tour of creating company, accounts, rules, approvals, authoring, creation of contracts and ends up finally checking the reports. Bulk import and Client tool will be checked separately during sanity. The coverage will be around 20% of test cases.

b.	Confidence Level Test Cases: Confidence level cases will cover all positive scenarios of the test cases with different test conditions. Also it may cover 40%-60%

c.	Regression Level Test Cases: The Regression cases will cover the negative scenarios as well as the out of box cases to check the application behaviour and this will be around 20%-30% of test cases.

After the completion of four week exercise, the below deliverables should be achieved and delivered to ABC
 
1.	Test Case Review Report
2.	Share the updated test cases
3.	Share the new test cases
4.	Share the Automation Feasibility Report
5.	Share the Automation Framework document

Required from ABC

1.	Access to Test Case Repository
2.	Clarifications on test cases posted by Automation Team
3.	Review of Test Case Review Report shared by Automation Team
4.	Review of Updated Test Cases
5.	Review of New Test Cases
6.	Review of Automation Feasibility Report
7.	Review of Automation Framework document.

3.3	Phase III
The phase 3 of the project is the creation of automated test scripts using QTP 9.5. The team will follow the instructions as per the framework. The framework will take care of the folder structure, shared modules and naming conventions of variables that are planned to be planned during the automation of test cases.
XYZ assume that 65%-75% of test cases can be automated that are available for CMS. Also it is evident that the automated scripts will be developed as per the classification developed so that it can be executed on need basis. 
The duration for completing 65%-75% of automation test cases has been estimated as 12 weeks from the completion of phase 2.
Team will make a weekly delivery of test scripts and share the execution of the batch test results to ABC team for approval. Any modification/suggestions will be made on the successive week and the same will be verified during the next batch execution.
Deliverables
1.	Weekly Script delivery along with Batch mode execution results
2.	Reporting of Functional Automation coverage achieved on weekly basis
Required from ABC:
1.	Acknowledgement of Test Script deliver on weekly basis
2.	Review of Batch mode execution results
3.	Provide suggestion on the test scripts delivered on weekly basis


3.4	Phase IV

Finally all the test scripts will be consolidated and executed in the batch mode for a final run and the results will be shared with ABC. Up on delivery of automated test scripts will require a project signoff from ABC.

The verification of test scripts will be performed on application hosted environment.

Deliverables
1.	Final Delivery of Test Scripts 
2.	Understanding Document
Required from ABC
1.	Acknowledgement on Final delivery of Test Script
2.	Comments on Understanding Document
3.	Project Sign-off
4.	Test Environment Setup

The test environment will consists of local CMS setup at XYZ to verify the test scripts developed by the team before making a weekly delivery to ABC. 

Also the infrastructure at XYZ has not been made according to Hardware configuration/ hosted application setup shared by ABC. Moreover the objective of having the local setup is to ensure the test scripts works fine and it can be further tested on ABC application hosted environment.

The perforce client will be installed in automation engineer desktop machines in order to perform the check-in/check-out of test scripts to perforce server.

In order to perform the above activities a VPN connectivity setup will be made so that so that any issues related to application can be solved immediately using RDC or VPN access.

Please find the Test Environment Diagram below.


 





4.1	Hardware Configuration

4.1.1	Workstations

Intel Pentium Core 2 Duo
2GB RAM 
150 GB HDD
10/100 Ethernet Care

4.1.2	Web Server

Intel Pentium Core 2 Duo
2GB RAM 
150 GB HDD
10/100 Ethernet Care

4.1.3	Application /Database Server  (Local Setup)

Intel Pentium Core 2 Duo
32 Bit Windows
4GB RAM 
150 GB HDD
10/100 Ethernet Care

4.1.4	QTP Server (Onsite Setup)

Intel Pentium Core 2 Duo
8GB RAM 
150 GB HDD
10/100 Ethernet Care

4.2	Software Configuration

4.2.1	Workstations

WinXP SP2
QTP 9.5
Perforce Client
Internet Explorer 7.0
Microsoft Office 2003


4.2.2	Web server

WinXP SP2
Tomcat 





4.2.3	Application/ Database Server  (Local Setup)

Windows 2003 Server
Tomcat
Oracle 10G 

4.2.4	QTP Server (Onsite Setup)

Windows 2003 Server
QTP 9.5
QTP License Management
Microsoft Office 2003 or 2007
Internet Explorer 7.0

5.	Task & Baseline Tasks

Project official Start Date: 27th Jan 2009

Sl.No	Tasks 	Start Date	End Date	Duration
Phase I	3 Weeks
1.	Application Understanding 	27th Jan 2009	13th Feb 2009	
Milestone 1: Delivery of Automation Test Plan
Phase II	4 Weeks
2. 	Test Case Review	16th Feb 2009	27th Feb 2009	
3.	Enhancing Existing Test Cases	2nd Mar 2009	6th Mar 2009	
4.	Creating New Test Case in addition to Existing Test Cases	9th March 2009	13th March 2009	
Milestone 2: Delivery of Test Case Review Report – 16th March 2009
Milestone 3: Delivery of Feasibility Report – 16h March 2009
Milestone 4: Delivery of Framework Document – 9th March 2009
Review of Frame work document  by ABC -  9th March to 13th March	1 Week
Review of Feasibility Report by ABC -16th March to  19th March	4 Days
Phase III	12 Weeks
5.	Developing Test Scripts using QTP 9.5	16th March 2009	5th Jun 2009	
Milestone 5: Weekly deliverables of Test Scripts with Batch Mode Results 
Phase IV	1 Week
6. 	Verifying Test Scripts in Batch Mode and fixing issues.	8th Jun 2009	12th Jun 2009	
Milestone 5: Final Deliverables of Automated Test Scripts – 12th Jun 2009
Milestone 6: Understanding Document/ KT on Automation framework – 8th Jun to 12th Jun

Note: The above timelines subjected to change if there is any change in scope. Also the timelines are defined based on the assumption that 30%-40% of test cases may require enhancements and the creation of new test cases ranging from 400 -500.

Moreover the timelines for test script development has been estimated based on the assumption that 65-75% of the test cases can be automated.



6.	Review Process

The below Review process will be carried out internally to ensure the quality has been met at each and every phase of the project.
6.1	Test Case Review 

Automation team will take stock of all test cases that are already prepared by ABC for CMS 3.2.5. The review will happen based on the application understanding the team has achieved in Phase1. The review will ensure that the following items.

a.	Valid Test Cases with Test Procedures written against the Application.
b.	Should validate the expected results dedicate correctly that needs to be checked.
c.	Should capture the incomplete procedures with proper comments on what is missing.
d.	Invalid Test Case with respect to the current application
e.	Gaps in test cases missing few features/out of box scenarios 
All the above will be captured and the same will be shared with ABC on a periodical basis during phase 2.

Also ABC & XYZ will have a conference call whenever required, if there are any clarifications to be asked from both sides. All the comments/suggestions will be captured and the same has to be implemented.

6.2	Automatable/Non- Automatable Review Process

The classification of automatable/non-automatable will be carried out based on the POC report will has been shared with ABC. Also the team will be educated on the POC report so that the classification is done properly.

Moreover the team will categorize the test cases that are automatable based on the core functionality of the application and see the benefit that can be achieved if those test cases are automated. As a first step the sanity test cases will be automated followed by Confidence and Regression test cases.

At the end of Phase2, XYZ will share the feasibility report to ABC for a review. ABC will review the feasibility report and provide their approval based on the report. If any clarifications are required then ABC & XYZ will have a conference call to complete the review of feasibility report.

Also XYZ will confirm the percentage of test cases that can be automated in the total test cases that can be automated.

Note: Test cases related to installation, upgrades and online help supported for different languages, comparing Bar & Pie Charts may not be automatable due to limitation with the tool. 
6.3	Test Script Review

The team will follow the instructions/steps that have been called out clearly in the Automation Framework document. Up on completion of test scripts for the automatable test cases, there will be a peer review of test scripts. Followed by Automation Lead/Manager will review test scripts and post comments accordingly. 

The owner of the test script will modify them according to the review comments. All the comments will be captured in the review document for future reference.

The exercise will cover the following

a.	Naming conventions of scripts.
b.	Adding proper comments for future reference.
c.	Coding Standards defined as per the framework document.
d.	Validating the re-usable functions/VB scripts for handling few challenges during automation.
e.	Tweaking the scripts for better execution.
6.4	Batch Mode Test Execution Review Process

The batch mode execution will be performed at each and every week during the course of phase3. At each and every week after the completion of batch test the results will be reviewed.

The review will ensure that all the test cases have been executed successfully and there were no scripts issues. Subsequently the failures test scripts will be analyzed for the root cause. If there is an application issue, the team will send across the information to ABC and defect Id will be associated with test cases so that it need not be looked in when same test scripts fails during successive batch test execution.

By performing this activity will help the team for a long run, since the scripts are verified each and every week to ensure the final delivery is met in time.

7.	Approval Process 

The approval process will be carried out for the below sections to ensure that XYZ & ABC where in the same page during different phases of the project.

7.1	Test Case Approval

Based on the test case review report, the team will update/modify the existing test cases. Up on completion of test case enhancement for each and every day will be shared with ABC for Review. 

ABC should review with their counter parts and ensure the test case captures as per application functionality. They should provide the acknowledgement on the enhancement made to the existing test cases and also on the new test cases developed by the team. The approval should also say that if there is any changes/modification required to the test cases that has been shared for review to ABC.
7.2	Automatable/Non- Automatable Approval

XYZ will share the Feasibility report based on the expert review of the test cases that are available for CMS. ABC should provide the acknowledgement on the feasibility report which will be considered as an input to start the development on test scripts.

The feasibility report will confirm the percentage of test cases that can be automated, percentage that cannot be automatable due to tool limitation, application environment and so on.

7.3	Batch Mode Test Execution Approval Process

Up on completion of batch mode execution on every week, XYZ will share the batch mode results to ABC with the review report on the number of test cases passed /Failed due to Application issues. 

ABC should provide the acknowledgment on the batch mode execution. This will be captured on weekly basis to ensure that weekly milestones are achieved with better quality.

Note: The script failed due to script issue will be fixed and the same will be updated during the weekly project status meeting.

8.	Script Maintenance

The test scripts will be checked-in in the perforce server. Also the scripts will be modified in such a way that all comments will be noted before enhancing the scripts for scripts issues or with respect to any change in application UI/functionality.

All team members will have their own perforce account to check-in the scripts after completion.

9.	Reporting and Status Updates

There will be a weekly status meeting with ABC to update on the progress made on weekly basis, plan for the next week and deliverables expected the following week. 

Also any issues causing Roadblock will be discussed during the weekly status call. If there is any impact to the schedule will be intimated to the team. 

10.	Deliverables


Sl.No.	Deliverables	Deliverable Mode 
1	Automation Test Plan	Word Document
2	Test Case Review Report	Spreadsheet Document
3	Automation feasibility Report	Spreadsheet Document
4	Automation Framework Document	Word Document
5	Automation Test Scripts 	QTP Scripts bundled
6	Understanding Document	Word Document


11.	Risk & Mitigation Plan

Sl.No	Risk	Mitigation Plan
1	Any change in scope of project / change in application functionality	XYZ will review the scope/change in functionality update ABC whether it can be accommodated with the existing schedule or it will impact the current timelines. Also it can set the priorities correctly so that it is clear whether it has to be addressed immediately or can be considered at the end during completion of project
2	More than 40% of effort involved in test cases enhancement	XYZ will review the effort required to accommodate more effort that is required to modify the test cases.

Also intimate ABC about the increase in scope of work with the updated timelines
3	Any script issue during the execution of test scripts in batch mode	XYZ will get the script issue resolved on or before the next batch test execution
4	More than automating 75% of test cases will have an impact to the timelines	XYZ will check with ABC on the test cases and set the priority accordingly and update ABC on impact of project completion date.
5	Any application issues during the automation of test cases	ABC should help XYZ in fixing the issue, since there is time zone there will be a delay in fixing the issue. In that case XYZ will try to cover it up within the current schedule. In worst case there will be an impact to the current project timelines.

----------------------------------------------------End of Document---------------------------------------------------------------------
