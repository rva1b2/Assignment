# Assignment
Assignment for Assurity Consulting
Following are the details under this folder Assignment
1. JMeter version used in 5.5
2. Assignment_TestPlan.jmx is the JMeter Script along with CategoryID the data file containing the CategoryID which is used and called in the Script
3. Category_Details is the csv file to which the CatID, Name and Path are written to
4. Copy or Download the three files as mentioned above in 2 and 3 to the local machine 
5. Following are the details to be done in the JMeter Side
   4a. JMeter5.5v the version used and to be invoked from command prompt with administrator privileges
   4b. Import the plugins from the Plugins Manager under the Options tab and import all the plugins
   4c. Open the File and browse the location where the Script is located
   4d. Update the Script (under CSVFileWriteScript BeanShell PostProcessor) for the filepath where the CSV has to be written(E:/AssurityConsulting/Scripts/Category_Details.csv to be changed to the location in your system providing the appropriate filepath)
   4e. Create a Category_Details.csv file in the same folder where the Script is present and provide this path in the Script of Step 4d
5. Script has ResponseAssertion check and Details written to CSV file only values of CategaoryID, Name and Path
6. Under the jp@gc_01Assignment_API of the Script the users, ramp-up, steady-state and ramp-down can be changed
7. Click Run to execute the test for the duration of 60 seconds as default or for the changed values as mentioned in 6
8. Refer the Assurity APITMSandbox - Performance Test Report.pdf for the test executed from  my end

   
