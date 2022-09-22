Expected Result : Create piechart | line graph that will show the presentation of data.
Steps to proceed: 
1. Create HTML dashboard page with cards representation for each visualisation chart.
2. Integrate plotly.js or chart.js library in the header of the html document.
3. Make network calls using javascript fetch api to the url : https://dev.socrata.com/foundry/health.data.ny.gov/gnzp-ekau
4. Change the data structure to be accepted by the chart library.
5. For the implementation of Chart libraries I have taken reference from: 
  https://www.chartjs.org/docs/latest/getting-started/ , https://www.chartjs.org/docs/latest/charts/doughnut.html , https://tobiasahlin.com/blog/chartjs-charts-to-  get-you-started/
6. As random method usage was required for pie charts, after research I have taken the reference from https://www.educative.io/answers/how-to-generate-a-random-color-in-javascript and modified it as per the rquirements. 
7. To fetch the data , Javascript has provided an inbuilt API "fetch", in the form of string a URL is passed from where we can retrive the data : https://health.data.ny.gov/Health/Hospital-Inpatient-Discharges-SPARCS-De-Identified/gnzp-ekau
8. Chart library receives the data in the expected format after data manipulations and then the output is represented using the data visualizations like pie charts and line graphs. 
