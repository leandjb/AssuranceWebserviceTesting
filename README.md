# README

## Description of the .zip file
This project contains the resources needed to perform automated web service testing using JMeter. Inside the file you will find:

- **JMeter Scripts (.jmx):** Test files that define the scenarios and endpoints to be tested.
- **Test Data:** CSV or similar files to feed the scripts with dynamic data.
- **Usage Instructions:** Quick guide to import and run the scripts in JMeter.

## Endpoints tested in JMeter

The JMeter scripts are configured to test the following web service endpoints:

1. **GET /api/personas**
   - Retrieves the list of registered people.
2. **POST /api/personas**
   - Creates a new person in the system.
3. **PUT /api/personas/{id}**
   - Updates the information of an existing person.
4. **DELETE /api/personas/{id}**
   - Deletes a person from the system.

Each endpoint is configured with response validations, execution times, and test data management to ensure service quality and performance.

## How to use the JMeter scripts

1. Unzip the `.zip` file.
2. Open JMeter and load the corresponding `.jmx` file.
3. Configure the test data if necessary.
4. Run the test and review the results in the JMeter panel.

---

For questions or support, check the internal documentation or contact the project owner.