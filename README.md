**Pet Circle - Task 2 - Automating API testing for the Pets collection of https://petstore.swagger.io/ **

**Requirements**
1. Setup: Access the Swagger Petstore API documentation https://petstore.swagger.io/
2. Scenario Creation: Using the documentation, devise test scenarios for each CRUD
operation (Create, Read, Update, Delete) for the "Pets" resource
3. .Create: Design scenarios to test the creation of pets in the Petstore. Consider
various inputs and edge cases.
1. Read: Create scenarios to test retrieving pet details from the Petstore. Include
scenarios for existing and non-existing pets.
2. Update: Design scenarios to test updating existing pet details in the Petstore. Include
scenarios for updating different attributes.
3. Delete: Develop scenarios to test deleting pets from the Petstore. Consider
scenarios for deleting existing and non-existing pets.

**Tech stack used**
Postman

**Summary of my tests**
I have written scripts for each request in such a way that they can be chosen to run independently or as a collection. 

**Download my test folder firstly**
1. Navigate to my Git repo https://github.com/kk-github2/kk-petcircle-Task-2.git
2. Click on Code dropdown and download my entire test collection > save on your local folder

**Set Up Postman (on your local)**
1. Install Postman and double click to open
2. In the top left click the hamburger menu and go to File > Import
3. Choose to open an entire folder
4. Locate the downloaded folder from my Git repo on your local (It should be a file with the postman_collection extension)
5. Choose the folder by a single click and choose 'upload'
6. Once you confirm to import all files, your postman left nav should now have the entire collection including all separate request files

**Running the tests:**
1. To run specific requests as a test </br>
Click on each request and then hit "SEND" next to the request URL at the top.

2. To run all tests together as an entire collection </br>
Choose the 3 dots next to the collection name and select 'Run collection'.</br>
(a) You can choose to run the entire collection or choose specific/multiple tests to run</br>
(b) You can choose to run your collection manually or schedule it

![image](https://github.com/kk-github2/kk-petcircle-Task-2/assets/162652411/67df556e-f84a-4097-9f61-7ff095b972ce)


