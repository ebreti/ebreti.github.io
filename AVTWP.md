Water consumption by households in Associação Vila Tijuca  
========================================================
author: fmarianoc  
date: November 12th, 2014

Situation
========================================================

- One vila with 21 houses and one common area. 
- 22 water meters for internal control.  
- One external water meter used by the concessionaire for billing.  
- One limit of 10500 liters per day to pay the minimal fee.  
- The limit was extrapolated during the World Cup.  
- Unbalanced consumption among the households.  
- Need to charge wasters.  


First Attempt
========================================================

- Data collected in one Google Drive spreadsheet and downloaded to DropBox folder.
- Knitr app to generate graph of consumption by water meter and ranking of households.  
- 15 consecutive daily records to map consumption by household.  
- Emails sent to households to show the consumption map.  
- Weekly records to control the vila's consumption.  


Shiny App
========================================================

- Combo box to select water meter.  
- Submit button to show graph of consumption of water meter selected.  
- Minimal documentation at front end.  
- Link to complete documentation in GitHub.  
- Data stored in Amazon's AWS S3.  


Data
========================================================



- 449 measures of 5 variables.
- variable names: idmedidor, unidade, dataleitura, leitura, coletivo.
- measures of external water meter: 31.
- measures of each internal water meter: 19.
- 19 * 22 + 31 = 449 OK!  
