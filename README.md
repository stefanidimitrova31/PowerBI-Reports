# PowerBI-Reports
This repository contains PowerBI reports that I have created using different datasets.

1. Video Game Report - This report was created using dataset from https://www.kaggle.com/datasets/gregorut/videogamesales and displays some key metrics from the sales report such as All time Best Publisher and All Time Best Developer. Additionally, it has a drill-through feature which allows analysis of specific time period and/or genre.
  
2. Eyetracking - This report was created using a single experiment eye-tracking recording obtained by me during a trial with a patient. The participant was instructed to perform a TUG (Time Up and Go) test which comprises of:
   - Participant sat on a chair
   - Participant gets up
   - Participant walks around a traffic cone placed around 2-3m away from the chair
   - Participant sits back down on the same chair
  
   TUG tests are often used in post-stroke patients to assess balance, cognitive functions and obstacle negotiation. During the trials we obtained interesting data such as number of fixations and saccades as well as how often the participant looked at the obstacle (traffic cone). The report illustrates some of these key metrics.

3. PersonalGroceryReportBI

This report uses my personal data from the Lidl Plus app, showcasing my digital receipts. As someone passionate about healthy shopping and eating, it’s been exciting to analyse my own shopping habits through these visuals and DAX calculations. I hope you find the insights and visualizations as useful and interesting as I do! The data source for this project was pulled from an API, using python, as a flat file (Excel) which I then used to create a star schema data model in Power Query. This is the gold standard data model for reporting and ensures optimised queries when slicing the data.

4. Onyx Data

This dashboard is my entry to the #DataDNA July 2024 Challenge by Onyx Data - https://onyxdata.co.uk/data-dna-dataset-challenge/ . I found the dataset quite interesting. When I create dashboards I try to focus on and solve a specific problem - in this case, the dashboard itself focused on email analysis within a company and I chose to find out why the unopened emails remain unopened along with displaying some KPIs on the top and a general email overview at the bottom. I aim to answer questions such as: 

1. Does the sentiment of the email matter?
2. Does it matter if the email is sent outside of workdays/hours?
3. Does the seniority level of the sender matter?
