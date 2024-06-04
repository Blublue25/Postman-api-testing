# Project Automation API

In this project I'm using Postman to test some functionality of the Reqres API. Then using Newman to run, test and export a html report of the Postman collections directly from the terminal


## Running Tests

To run tests. Navigate to the folder in command prompt, then run the following command

```bash
  newman run Reqres.postman_collection.json -e Reqres.postman_environment.json -d Data_test.csv
```

Run this command if you want to generate a html report

```bash
  newman run Reqres.postman_collection.json -e Reqres.postman_environment.json -d Data_test.csv -r htmlextra
```

![image](https://github.com/Blublue25/Postman-api-testing/assets/157490992/ecaeb025-43e8-4a1e-b00c-1db1edb4865c)
