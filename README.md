  Behaviour Driven Scenarios:
  
  Scenario: Success Verify that Content type of City bike API is application/json
  Scenario: Success Verify the response contains the data
  Scenario: Success Verify that the API return all the stations in city of Frankfurt in Germany
  Scenario: Invalid Submissions Verify the response when invalid endpoint URL
  Scenario: Verify the response when server is down	
  Scenario Outline: verify that the city Frankfurt is in Germany and return their corresponded latitude and longitude
  
  Project Structure 
---------------
-- Feature Folder 
   Feature Files which contain BDD style sytax to represent different scenario in Given, When Then format, Each Scenario is a test 
   Scenario Outline is used for Data driven tests.
   BikeSearch.feature file:Scenario Outline: verify that the city Frankfurt is in Germany and return their corresponded latitude and longitude
   test.feature file contains:  Scenario: Success Verify that Content type of City bike API is application/json
                  Scenario: Success Verify the response contains the data
                  Scenario: Success Verify that the API return all the stations in city of Frankfurt in Germany
                  Scenario: Invalid Submissions Verify the response when invalid endpoint URL
                  Scenario: Verify the response when server is down	

-- Step Definitions Folder 
   Logic is implemented in step definitions for Scenario Outline: verify that the city Frankfurt is in Germany and return their corresponded latitude and longitude.


  
  
