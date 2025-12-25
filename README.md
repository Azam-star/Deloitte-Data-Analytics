# Deloitte-Data-Analytics
## Deloitte-Data-Analytics

## Business Problem 

Using a data unification algorithm, the tech team at our client, Daikibo, has converted all telemetry data collected from its 4 factories:

      1. Daikibo Factory Meiyo (Tokyo, Japan)
      2. Daikibo Factory Seiko (Osaka, Japan)
      3. Daikibo Berlin (Berlin, Germany)
      4. Daikibo Shenzhen (Shenzhen, China)
Each location has 9 types of machines, sending a message every 10 mins. Daikibo has been collecting this data for one month (May 2021) and they've shared this data in the form of a single JSON file.

The reason the client wanted to collect telemetry was to answer 2 questions:

In which location did machines break the most?
What are the machines that broke most often in that location?

## Task 
Your task is to analyse the telemetry data collected by Daikibo in a software called Tableau. Here are the steps that you need to take:
            
      1. Download the free trial of Tableau (link in the Resources).
      2. Install Tableau on your computer and register an account with the same email you used to download the software.
      3. Download the daikibo-telemetry-data.json.zip file -> unzip -> and import it in Tableau.
      4. Create a calculated measure field called "Unhealthy" with a value of 10 for every unhealthy status (representing 10 mins of potential down time since the previous message).
      5. Create a bar chart called “Down Time per Factory”.
      6. Create a new sheet with a new bar chart called “Down Time per Device Type”.
      7. Create a Dashboard with the 2 previous sheets and set the first chart to be used as a filter (selecting a factory in the first chart shows only the down time of the machines in this factory in the second chart).
      8. Select the factory with the most down time (click on its bar), make a screenshot of the dashboard and upload it as a submission for this task.
      







