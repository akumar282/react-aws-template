# react-aws-template

## getting started
1. Use this template in a new repositiory or codespace
2. npm install

Depending on what aws services you use, add config accordingly
If using AWS Amplify: 

3. amplify pull --appId <APP_ID> --envName <ENV_NAME>

If issues with webpack occur regarding top level await, use craco.js and replace scripts.

    "start": "craco start",
    "build": "craco build",
    "test": "jest",
    "eject": "craco eject"

Package and config is included.
