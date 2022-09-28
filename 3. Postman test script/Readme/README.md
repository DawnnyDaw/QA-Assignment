# Automated testing : API

## Setup

1. Download 2 files: `Test API.postman_collection.json` and `workspace.postman_globals.json`

![Import Collection](import-collection.jpg "Import Collection")

2. There are 2 scenario collections:
    - **Create Success** contains the following APIs:
      - `Post` Create a collection
      - `Get` Get a collection to check if it has created the new collection
    - **Delete Success** contains the following APIs:
      - `Delete` Delete a collection
      - `Get` Get a collection to check if it has removed the target collection

![Scenario Collection](scenario-collection.jpg "Scenario Collection")

3. You can run entire collection by clicking on three dots at the right of Test API bar and select run collection

![Run Collection](run-entire-collection.jpg "Run Collection")

4. Click Run Test API button

![Run Test Button](run-test-api-button.jpg "Run Test Button")

5. See the testing result

![Testing Result](Result-testing.jpg "Testing Result")

6. You can see the automated testing result with Monitor by clicking `Monitors` at menu bar and click Create a Monitor

![Monitors](Create-monitor.jpg "Create Monitors")

7. Set monitor name, select collection as Test API, select the  time and click Create Monitor button 

![Monitors](Create-monitor2.jpg "Create Monitors")
![Monitors](Create-monitor3.jpg "Create Monitors")

8. Click Run monitor for the first time

![Run Monitors](Run-monitor.jpg "Run Monitors")

9. Appreciate with the result

![Monitors Result](Monitors.jpg "Monitors Result")