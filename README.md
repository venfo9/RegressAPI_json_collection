# RegressAPI_json_collection
regress_api.postman_collection.json holds JS tests for Regress API (https://reqres.in/).  
regress_api.postman_environment.json includes environment variables for regress_api.postman_collection.json  
Use these files for automated testing with Newman or import them into Postman for semi-manual testing.

The collection includes five requests:
1. Create User
   Tests: "Checking the value of the 'name' field."
          "Checking the value of the 'job' field"
          "Checking that the value of the 'id' field is numeric."
          "Check the date and time format in the 'createdAt' field."
          "Checking the status code"
2. Update User
   Tests: "Checking the value of the 'name' field."
          "Checking the value of the 'job' field"
          "Check the date and time format in the 'createdAt' field."
          "Checking the status code"
3. Get userId after modification
   Tests: "The 'id' field should be a number."
          "The 'email' field should be a valid email address."
          "The 'first_name' field should be a non-empty string"
          "The 'last_name' field should be a non-empty string"
          "The URL format in the 'avatar' field should be valid."
          "The URL format in the 'support.url' field should be valid."
          "The 'support.text' field should be a non-empty string"
          "Checking the status code"
4. Delete User
   Tests: "Checking the status code"
5. Get userId after deletion
   Tests: "Checking the status code"
