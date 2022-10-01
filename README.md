# workbook
Assignment provided by Planit 

To run follow the steps:

1. Choose the Test Stage/Profile to run from the pom.xml file
2. Choose the desired browser to be used

mvn clean test -P RegressionTest -Denv=PRODUCTION -Dbrowser=CHROME
mvn clean test -P SmokeTest -Denv=STAGING -Dbrowser=FIREFOX

   
