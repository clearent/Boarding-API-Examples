# Boarding-Api-Examples
Examples for merchants using the Clearent Boarding API. The repository includes Postman requests for boarding a merchant using the Clearent Boarding API and some diagrams of potential workflows. The tests are order dependent so you will need to modify certain values if you want to run tests individually.

## 1. First clone the repo:
```
git clone  https://github.com/clearent/Boarding-API-Examples
cd Boarding-API-Examples
git pull
```

## 2. Download and install postman:
https://www.postman.com/downloads/

## 3. Use postman to import the tests contained in the repository:
Go to File > Import and select a file with the .postman_collection.json extension.

## 4. Update the variables in the tests to match those provided for your integration.
Right click the imported test folder and select Edit and then click the Variables tab. Replace AccessKey, MerchantID, and ExchangeID values with those provided for your integration.

## 5. Run the tests.
Click the arrow next to the imported test folder and then click Run.

# Current Examples
 - BoardingApiExampleFlow.postman_collection.json include all the requests to onboard a merchant with Xplor in the US.  
 - Launch For Integrators Pricing Example.postman_collection.json includes all the requests to onboard a merchant using the Launch For Integrators flow in the US.  
 - The images folder contains diagrams.  
