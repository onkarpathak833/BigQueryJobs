#INSTRUCTIONS

1. Run the java file BigQueryJobs.java to View status of jobs, Cancel Jobs and Rerun/Re-create the BigQuery jobs.
2. Create a Google Cloud Platform Account by signing up on "console.cloud.google.com" with your email address.
3. Create a project using top Menu bar on Home Page of GCP. Link the Billing Account to your project. You will have to create a billing account
   by entering your debit/credit card and other billing details.
4. You will need Google Service Account credentials file in json format created from API & Services -> Credentials tab of Google Cloud Platform. Browse to the API & Services menu from the main Navigation Menu of GCP on top left corner.
5. Copy the content of your json file into "service-account.json" file inside "dataproc" folder of this source code (Java Project).
6. Make sure you have sufficient permissions assigned to service account email while creating Service Account Credentials. e.g. BigQuery Admin, BigQuery Editor.
7. Package the jar using Maven Build utility and run the Main class in the Jar to execute the methods.
8. Methods in this utility can be exposed directly as an API to re-use in your application.

#NOTES

1. Use JDK version 1.7 and above (This code is tested on JDK Version 1.8).
2. BigQuery API Version 1.41.0 client libraries are used in this utility.
