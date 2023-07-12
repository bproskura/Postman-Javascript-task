# Postman-Javascript-task
This project contains API tests implemented using Postman and JavaScript. The tests are designed to validate the functionality of a publicly accessible RESTful API. The chosen API for testing is reqres.in, a simple API that provides mock data for various user-related operations.

# Test Scenarios
The following test scenarios have been implemented:  

- **[GET] All Users** - This test verifies the status code of the API response. It ensures that the request to retrieve all users returns a successful status code of 200.

- **[POST] New User** - This test validates the response received when creating a new user. It verifies the status code and checks if the response body contains the expected data.

- **[PUT] Update User** - This test ensures that the API allows updating user information correctly. It verifies the status code and checks if the updated user data matches the expected values.

- **[DELETE] Delete User** - This test validates the successful deletion of a user. It verifies the status code and checks if the response body is empty.

# Chosen API and Tests
The reqres.in API has been chosen for testing. It provides a simple set of endpoints to perform user-related operations. The tests implemented cover the core functionalities of the API, including fetching all users, creating a new user, updating user information, and deleting a user.

# Running the Tests
To run the API tests, you can follow these steps:

- Import the Postman collection provided in the postman folder of this repository.

- Once the collection is imported, you will see the four test cases listed: "All Users", "New User", "Update User", and "Delete User".

- To execute the tests, click on the "Send" button at the top right corner of the Postman application.

- After the test run is complete, you can view the test results, including the status codes and assertions, in the Postman collection runner.

# Test Results
Below are the screenshots of the test results for each scenario:

1. Get all users:

![Image alt](https://github.com/bproskura/Postman-Javascript-task/raw/main/Test1.png)

2. Create a new user:

![Image alt](https://github.com/bproskura/Postman-Javascript-task/raw/main/Test2.png)

3. Update an existing user:

![Image alt](https://github.com/bproskura/Postman-Javascript-task/raw/main/Test3.png)

4. Delete an existing user:

![Image alt](https://github.com/bproskura/Postman-Javascript-task/raw/main/Test4.png)

Please refer to the screenshots for a detailed view of the test results.
If there are any questions I am happy to give answers to them.
