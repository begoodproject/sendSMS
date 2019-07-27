# sendSMS
Feature to send SMS out to contacts

## Instructions on using dotenv
1. Create a file named `.env` at the root level of project.
2. Open the file and enter following information in this key=value format:
```
ACCOUNT_SID="ENTER_TWILIO_ACC_SID"
AUTH_TOKEN="ENTER_TWILIO_AUTH_TOKEN"
MYNUMBER="ENTER_YOUR_MOBILE_NUMBER"
CONTACT1="ENTER_USERS_MOBILE_NUMBER"
```
3. As long as `require('dotenv').config();` has been executed, you should be able to access the values using `process.env.key_name` e.g. `process.env.ACCOUNT_SID`.
