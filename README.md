# PostmanTests-for-NewWorld
Private repository for having all the postman tests for the new world API's.

**Running the tests in postman**
1. Download the test and environment files. 
2. Import both of them into postman.
3. Once imported, the test file will be considered as a collection (of tests). The environment file will automatically be considered as the environment to run the tests against.
4. Hit run beside the collection of tests (it will be available in expandable options). 

**Running the tests from CLI**
1. Download the test and environment files.
2. Install newman via npm. (Refer for instructions here https://www.npmjs.com/package/newman#using-newman-cli).
3. Once installed, in terminal, run the tests with command newman run {test_file_path} -e {environment_file_path}
