 
 
TEST AUTOMATION TOOL EVALUATION
Success in any Test Automation (TA) effort lies in identifying the right tool forautomation. A detailed analysis of various tools must be performed before selecting atool. This requires a lot of effort and planning. The effort and learning obtained duringtool evaluation will in turn help during the execution of the TAThe entire process of tool evaluation can be broken down into three major phases:1.
 
Requirements Gathering2.
 
Tool Selection3.
 
POC using selected tool
1. Requirements Gathering
During the requirements gathering phase of tool evaluation one has to list out therequirements for the automation tool. Some of the important questions you will need toask would be:1.
 
What problems will the tool solve?2.
 
What technical capabilities will the tool need, to be compatible with yourenvironment?

 
Compatibility issues

 
Tool audience/users

 
Management goals

 
Testing requirements

 
Technology
Compatibility Issues
Your testing tool will need to be compatible with:

 
The operating systems your product supports

 
The development environments used to create your product

 
Third party software with which your product integrates

 
The test management tool used (in order to be able to integrate with it); this willeliminate data redundancy and will give the advantage of managing all test relateddata at a single location

 
The tool should also be version control friendly so that scripts created can be brought under source code control.
Tool Audience/users
The skills of people involved in test automation and that of the people who use theautomation scripts is another important criterion for the test tool evaluation process. The benefits obtained through automation boils down to how effectively the tool is being putto use.
Read free for 30 days.
Get 30 days of free Scribd membership when you invite your friends.

Invite FriendsInvite friends to join Scribd
 
Will your organization allow for staff training? Can your organization, within theimplementation time, allow for the learning curve required to become comfortable withthe tool?
Management goals
Typically, this will be based on the product roadmap and the goal for automation fromthe management perspective. Based on the product roadmap, the management mightconsider reviewing the time for which the tool has been in the market. They may alsoconsider whether the tool will be upgraded periodically to support newer technologies.Any management will have a budget and will fit efforts within a given budget. So it isalso important for the management to consider the licensing and maintenance cost of atool and the additional hardware required for running the scripts.
Testing Requirements
What type of testing problems do you want the testing tool to address?

 
Manual testing problems

 
Time constraints when implementing small changes in the system

 
Shorter regression testing timeframes

 
Test data setup

 
Defect tracking

 
Increased test coverage

 
Increased efficiency of the testing process
Technology
When considering technology requirements in the automation perspective, there are twoviews that must be taken:

 
Technologies that should be supported by the tool

 
Features required in the toolThe requirement could be for the tool to support all technologies that are used in the product and any new technology that is being planned to be implemented in the future. Alist of all the technologies used in the product and the platforms/browsers on which the product is supported must be created as the technical requirements for the tool. For a toolto be able to automate testing of the product, the important criterion is the tool’s ability toidentify access and work with all controls used in the application. Hence it is important tocreate a list of all controls (standard, custom and third party) used in the application andcheck if the tool is able to identify and handle all the listed controls.The technical stakeholders of the automation project will have a list of desirable featuresthat they need in the tool. This list of desirable features must be created in consultationwith the technical team. Apart from this, a list of all features supported by the tool mustalso be created so that all features of the tool are considered during evaluation. Anexample of few features that can be listed are the tool’s support for testing GraphicalUser Interface (GUI), Application Programming Interface (API) and Command LineInterface (CLI), support to extend tool using Open APIs like Win32 APIs, verification
 
 points supported in the tool, support of an efficient Recovery System and support for testreport creation.At the end of the requirements gathering phase, all necessary points to consider forselecting an automation tool are available. These points form the evaluation criteria forthe tool.
2. Tools Selection
The second step in test automation tool evaluation is the selection of tools. Whileselecting tools it is important to remember that no single tool will satisfy all therequirements. The tool that meets most of the evaluation criteria should be chosen afterdiscussion with stakeholders. Based on the tools limitations with respect to requirements,the automation activities must be planned.All tools that meet most of the evaluation criteria can considered for evaluation. Whenmany tools are found to satisfy the evaluation criteria, further analysis of tools should bedone. Do a feature categorization by listing each tool according to the following featuresit provides:

 
Mandatory features: These are the features that are essential to accomplish yourgoal in meeting your requirements within the constraints

 
Desirable features: these are features that will distinguish the best tools from theothers

 
Irrelevant features: Features that are not important and will not provide any real benefit to your situation.Rate these features and assess as many tools as possible to prepare a short list of a fewtools. Contact the relevant vendors and possibly ask for an evaluation version to run your proof of concept (POC).
3. POC Using Selected Tool
The last phase of tool evaluation is doing a proof of concept. Though conceptually thetool appears to satisfy the evaluation criteria, it is necessary to try the tool for a few testscenarios / cases in the product. Every tool vendor provides an evaluation version of theirtool for this purpose for a limited period of time. It is sufficient to use the evaluationversion for the POC.The scenarios chosen for POC are very important. They should be chosen in such a waythat the scenarios cover most of the controls and a few common features present acrossthe product. It should be a sample, which, when automated should give the confidencethat automation using the tool for the product will be successful. This will also help infinding available resources’ competence in using the tool. In case the POC fails, thereasons for failure must be analyzed and documented. The next tool for POC should beselected and this can be an iterative process till you identify the tool that most likely, suitsyour requirements.
