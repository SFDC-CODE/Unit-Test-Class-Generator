# Unit-Test-Class-Generator
Generate Unit Test class for Salesforce Apex Class and Trigger

## Please follow the steps given below sequencially to run the application:
Step-1: Install [Force.com CLI](https://developer.salesforce.com/tools/forcecli) if it is not installed already

Step-2: Login to your Salesforce Org and create a Remote site settings for your own org (e.g. https://na4.salesforce.com or 
https://samplename-dev-ed.my.salesforce.com if custom domain is enabled in your Org)

Step-3: Create **ApexClassSymbolTable.cls, GenerateApexClass.cls, ApexTestClassGenUtil.cls and UnitTestDataFactory.cls** classes in order

Step-4: Create sample **TemperatureConverter.cls and AccountDeletion.trigger**

Step-5: Create the Visualforce Component **UnitTestClassComponent.component**

Step-6: Create 2 Visualforce Email Templates **GenerateTestClassTemplate.email and GenerateTriggerTestClassTemplate.email**

Step-7: Copy 2 Sample JSON files somewhere in your local machine

Step-8: Go to the command prompt from the directory where you have saved the Sample JSON files

Step-9: Log into the Salesforce Org, where you have copied/created the files mentioned above using **force login** command

Step-10: Once your login is successful run **force apex apexjson.txt** to generate Unit Test Class for **TemperatureConverter.cls**

Step-11: Run **force apex triggerjson.txt** to generate Unit Test Class for **AccountDeletion.trigger**

### You can modify the Sample JSON files to modify test data or create your own test cases 

### In case you want to support more complex Apex Classes and Triggers, modify UnitTestClassComponent and UnitTestDataFactory accordingly
