# sendSMS
Feature to send SMS out to contacts

## Instructions on using dotenv
1. Create a file named `.env` at the root level of project.
2. Open the file and enter following information in this key=value format:
```
ACCOUNT_SID="ENTER_TWILIO_ACC_SID"
AUTH_TOKEN="ENTER_TWILIO_AUTH_TOKEN"
```
3. As long as `require('dotenv').config();` has been executed, you should be able to access the values using `process.env.key_name` e.g. `process.env.ACCOUNT_SID`.
