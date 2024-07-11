# travelminit_test_project
Project created for the final exam for QA tester course with IT Factory.
https://itfclasses.atlassian.net/projects/IGB/versions/10433/tab/release-report-all-issues

<h1>Testing Project for **travelminit.ro**</h1>

The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application

Application under test: **travelminit.ro**

Tools used: Jira, Zephyr Squad.

<h2>Functional specifications:</h2>

The below stories were created in Jira and describes the functional and GUI specifications of the **travelminit** website,  for which the final project is performed upon.

![gui - test - story2](https://github.com/Biacna/travelminit_test_project/assets/118627174/e8f7ca65-59ca-4eea-85dc-2c210767b7dd)

![searchbar-test-story](https://github.com/Biacna/travelminit_test_project/assets/118627174/c5d80d21-3dcd-40cf-9964-a22348fd9652)

Here you can find the release that was created for this project:
![test-release](https://github.com/user-attachments/assets/96997da7-8f19-4622-9e62-13d0690adda5)

<h2>Testing process</h2>

The test process was performed based on the standard test process as described below.

<h3>1.1 Test planning</h3>

The objective of this project is to ensure that the client`s standards and requirements regarding the product are met. Functional accuracy and seamless user experience for travelminit website before releasing the final product for our customer is the main focus for our team.

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the roles of the personnel, the resources and schedule required to complete testing, and the risks associated with the plan. The test plan that was created for this project can be found here **(inserati link catre documentul cu planul de testare)**

<h4>1.1.1. Roles asigned to the project and persons allocated</h4>

<ul>
  <li>Project manager - Roger Mangianello</li> 
  <li>Product owner - Humberto Cincodemayo</li>
  <li>Software developer - Devon Boots</li>
  <li>QA Engineer - Ignat Bianca</li>
</ul>

<h4> 1.1.2 Entry criteria defined </h4>

**-	business requirements are final and approved
- ensuring the availability of human resources
- the roles are defined and uderstood
- the testing objectives are defined
- the risks are identified and mitigated
- entry and exit criteria are defined
-	design and mock-ups are available and approved
**

<h4> 1.1.3 Exit criteria defined </h4>

**-	all test cases executed
-	test coverage achieved
-	management of defects by fixing the bugs
-	test completion documentation is prepared
**

<h4> 1.1.4 Test scope</h4>

<h5> Tests in scope: </h5>

**This release verifies travelminit website`s functionalities:
- user should easily filter the search results to match the needs
- user should easily search accommodations through the website using filters
**

<h5>Tests not in scope: </h5>

**Non-functional testing like stress, performance, security, localization and accessibility is beyond scope of this project.
No QA support for mobile applications developed. Only web applications will be tested.
Automation testing is beyond scope.
**

<h4>1.1.5 Risks detected</h4>

<h5>Project risks:</h5>

**-	system integration risks with third party associates
-	legal changes that can appear during development process
-	technical errors from hosting services
- misscomprehension or possible errors in documentation and requirements 
**

<h5> Product risks: </h5>

**-	web app is exposed to fraud which could affect clients trust
-	location services errors
-	usability and performance problems
- negative feedback from users
**

<h4>1.1.6 Evaluating entry criteria</h4>

The entry criteria defined in the Test Planning phase have been achieved and the test process can continue.

<h4>1.2 Test Monitoring and Control<h4>

**-	daily defect reports
-	reporting defects daily as a result of testing, in order to fix them
-	ensuring communication with the team through the project manager when needed
-	collect data
-	risk management and mitigation
-	progres tracking**
-	
![test-metrics](https://github.com/user-attachments/assets/ff7ccfc9-b3fb-452c-a4e0-cc3ab20b757e)

<h3> 1.3 Test Analysis </h3>
The testing process will be executed based on the application requirements. <b></b>. <br><br>

The following test conditions were found: <br>

![test-conditions1](https://github.com/user-attachments/assets/30ee2adc-413f-4323-8fae-b0b53bba39b5)

![test-conditions2](https://github.com/user-attachments/assets/a3d3a17e-29c3-478c-93df-ddee61f99ce6)

<h3>1.4 Test Design</h3>

Functional test cases were created in Zephyr Squad based on the analysis of the specifications. The test cases can be accessed here **(inserati linkul catre fisierul cu testele, in format pdf, word sau csv)**

<h3>1.5 Test Implementation</h3>

The following elements are needed to be ready before the test execution phase begins:

**- test cases are reviewed
- testing environment is assured
- ensure the roles and responsabilities of team members
- availability of test data
- business requirements**

<h3>1.6. Test Execution </h3>

Test cases are executed on the created test Cycle summary: **CycleSumm1**

Bugs have been created based on the failed tests. The complete bug reports and summaries can be found here:

[Bug report 1](https://github.com/Biacna/travelminit_test_project/blob/main/IGB-48-bug-report-submit-button.pdf)

[Bug report 2](https://github.com/Biacna/travelminit_test_project/blob/main/IGB-50-bug-report-search-func.pdf)

![bug-ticket1](https://github.com/user-attachments/assets/8db99757-f259-4d14-9246-c9aab0166359)

![bug-ticket2](https://github.com/user-attachments/assets/ddaabdd7-b969-442d-8605-ecfeae1028eb)

Full regression testing is needed on the impacted areas after the bugs are fixed and retesting will be done for every functionality that was previously failed.

<h3>1.7 Test Completion</h3>
As the Exit criteria were met and satisfied as mentioned in the appropriate section, this feature is suggested to ‘Go Live’ by the Testing team

The traceability matrix was generated and can be found here:

![traceabilitymatrix1ultimul](https://github.com/user-attachments/assets/c60f21b9-1d99-47b9-9391-2568b9200fcd)

Test execution chart was generated and can be found below:

![test-metrics](https://github.com/user-attachments/assets/b2cc445f-7ef2-479e-a5a2-a5e73d4b83a6)

**For this project were created 2 tests that were executed multiple times. The tests in scope verified the search functionality and form functionality. The search functionality was verified using basic parameters and specific filters, while the functionality of the submit button on the booking form was verified using valid parameters. Other functionalities were out of this project`s scope. The detected bugs can impact the good functionality of the web application if not fixed promptly. Working on this project I learned about the importance of having comprehensive and understandable requirements, to be more specific and accurate and organized through the test case design and implementation.**


