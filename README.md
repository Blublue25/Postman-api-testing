# Project Automation API

In this project, I'm using Postman to test some functionality of the Reqres API. Then using Newman to run, test, and export an HTML report of the Postman collections directly from the terminal

## Prerequires

You have to have Node.js and Newman installed on your machine.
## Running Tests

To run tests. Navigate to the folder in the command prompt, then run the following command:

```bash
  newman run Reqres.postman_collection.json -e Reqres.postman_environment.json -d Data_test.csv
```

## Generate HTML Report
Run this command if you want to generate an HTML report.

```bash
  newman run Reqres.postman_collection.json -e Reqres.postman_environment.json -d Data_test.csv -r htmlextra
```

After running, Newman will create a folder. Enter the folder, and you will see a link to the report.

![image](https://github.com/Blublue25/Postman-api-testing/assets/157490992/ecaeb025-43e8-4a1e-b00c-1db1edb4865c)
