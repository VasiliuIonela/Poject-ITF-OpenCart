# My Project in Manual Testing IT Factory
The scope of the final project for ITF Manual Tesing Course is to  use all gained knowledge throught the course and apply them in practice, using a live application.

Application under test: https://demo.opencart.com/admin/

Documentation: http://docs.opencart.com/en-gb/introduction/

API Documentation: https://docs.opencart.com/en-gb/system/users/api/

**The final project will be split into 2 sections:** [Testing section](https://github.com/VasiliuIonela/Poject-ITF-OpenCart/blob/main/README.md#1-testing-section) and [SQL section](https://github.com/VasiliuIonela/Poject-ITF-OpenCart/edit/main/README.md#2-sql-section)

Tools used: JIRA, Zephyr Squad.

# Functionals specifications
 The below Story was created in JIRA and describes the functional specifications of the Manufacturers module in the administration interface, for which the final project is performed upon: [manufacturer section](https://github.com/VasiliuIonela/Poject-ITF-OpenCart/blob/main/PDF%20(Jira).pdf).

The Manufacturer section is used to categorize products by manufacturer. This section can be accessed under Catalog > Manufacturers.

The manufacturer information should be created before products are added, so the manufacturer category can be selected when adding the product. Saving a product without including the manufacturer isn't advised, because customers can search for products in the store front through their manufacturer page. With the manufacturer missing from the product information, the product will not be available on those pages. The Manufacturer names can be deleted, and new manufacturer information can be added in its place.

To insert a new manufacturer, the following information is required:

Manufacturer name
Stores: Default will be selected if there is only one store. If you have more than one store using OpenCart, you can add a manufacturer to multiple stores by checking on them.
SEO Keyword: the keyword used for search engine optimization (optional).
Image: an image of the manufacturer (optional).
Sort Order: the position the manufacturer will be sorted among multiple manufacturers (optional).

# 1 Testing section
## 1.1 Test Planning
The Test Plan is designed to describe all details of testing for the Manufacturers module from OpenCart platform.

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for the testing, the resources and the schedule required to complete testing, and the risks associated with the plan.
### 1.1.1 Roles asigned to the project and persons allocated
* Project manager:
* Qa Lead:
* QA Engineer: Ionela Vasiliu
### 1.1.2 Entry criteria defined
* functional specifications are defined
* roles needed for the project are allocated
* initial project risks were detected and mitigated
### 1.1.3 Exit criteria defined
* number of unresolved bugs is insignificant or they have low priority
* all tests have been executed
* all resolved bugs have been re-tested and approved by the QA team
* deadline was reached
* no detected major risk remained un-mitigated
* exploratory regression testing must be performed on the My Info module, which includes the Dependents section
### 1.1.4 Test scope
* Tests in scope: The scope of this project is limited to the testing of the features in the succeeding sections of this document. Functional testing are in scope and needed to be tested.
* Tests not in scope:  Non-functional testing like performance, security testing is beyond scope of this project.  Automation testing is beyond scope.
### 1.1.5 Risks detected
* Project risks: the development team won’t have the necessary training for these tasks,	the database won’t support such a high volume of dates,	tight deadline,	sick personnel,	a few team members,	not having the necessary hardware equipment,	misunderstanding of the requirements.
* Product risks: Low performance of the OpenCart platform,	not having customer’s requests,	application will crash.

### 1.1.6 Evaluating entry criteria
The entry criterias defined in th Test Planning phase have been achieved and the test process can continue.
 ## 1.2 Test Monitoring and Control
 It will be done by generating periodic reports that reflect the current status of the test.
## 1.3 Test Analysis

The testing process will be executed based on the above  requirements for the 'Manufacturers' module. 

The following **test conditions** were found: 
* Check if an Admin is able to access the 'Manufacturers' section.
* Check if an Admin is able to sort manufacturers.
* Check if an Admin is able to edit a manufacturer by pressing 'Edit ' button in the right.
* Check if an Admin is able to delete a manufacturer name.
* Check if an Admin is able to access details of a manufacturer from the list.
* Check if an Admin is able to add a manufacturer name.
* Check if an Admin is able to select store when more store are existing using the platform.
* Check if an Admin is able to complete fileds in 'general feature" with valid information.
* Check if an Admin is able to complete fileds in 'general feature" with invalid information.
*  Check if an Admin is able to edit image in "general feature" "image" field.
*  Check if an Admin is able to delete image in "general feature" " image" field.
* Check if an Admin is able to add manufacutrer when fields are left in blank.
* Check if a user is able to access the 'SEO' feature.
* Check if a user is able to access the 'Design' feature.

## 1.4 Test Design
 Functional test cases were created in Zephyr Squad. Based on the analysis of the specifications, the  test design techniques used for generating test cases are:

**Test cases**: -> enter here test cases or at least the titles

The test cases with steps can be viewed here: [test_cases.pdf]().
## 1.5 Test implementation
 The following elements are needed to be ready before the test execution phase begins:
* Testing environment is up and running: https://demo.opencart.com/admin/
* QA testers have completely understood the requirements.
*	Create and prioritize test cases.
* Access to the testing environment is given: 	Username: demo | Password: demo
* Cycle summary was created.
* Test cases were added to the cycle summary.
* Preparing test data and ensuring it is properly loaded in the test environment.
## 1.6 Test Execution
* Test cases are executed on the created test Cycle summary: [cycle_summary_execution.pdf]()
* Bugs have been created based on the failed tests. The complete bug reports can be found here: [created_bugs.pdf]()
  * Full regression testing is needed after the bugs are fixed.
  ## 1.7 Test Completion
* Exit criteria was evaluated and passed.
* The traceability matrix was generated and can be found here: [Traceability_matrix.csv]()
* Test execution chart was generaetd, the final report shows...describe it
-enter here the final report
# 2 SQL section
