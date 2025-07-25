# API Test Collection

This repository contains Postman API test collections for [Reqres.in](https://reqres.in) demo API.

git clone https://github.com/hninwaimon-source/api-automation-testing.git
or
Download the Zip file and Import to the Postman

## How to Run the Tests

Check if Node.js is installed ->
node -v

Install Newman globally ->
npm install -g newman

Verify Newman is installed ->
newman -v

You can run this collection using [Newman](https://www.npmjs.com/package/newman):

```bash
newman run filepath/login-tests.postman_collection.json
