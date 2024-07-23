# covid-19-

# Covid-19

## Problem Statement

This dashboard helps the World Health Organisation (WHO) understand the cases of Covid-19. It helps them know the number of cases confirmed in each country/region, they get to know their number of cases, number of death and those recovered from the Covid-19. it also let them know the number of cases by each country, with this dashboard they have identified the cases and further work on their process.


### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : In the report view, under the view tab, theme was selected.
- Step 5 : Since the data contains various ratings, thus in order to represent ratings, a new visual was added using the three ellipses in the visualizations pane in report view. 
- Step 6 : Four card visuals were added to the canvas, one representing Total deaths, total positive cases, total new cases & Total recovering case.
           Using visual level filter from the filters pane, basic filtering was used & null values were unselected for consideration into average calculation.
- Step 7 : A bar chart was also added to the report design area representing the Death by Country/Region. 
- Step 8 : Ratings Visual was used to represent different ratings mentioned below,

  (a) Active

  (b) Confirmed

  (c) Country/Region

  (d) Date

  (e) Deaths

  (f) New Cases

  (g) New Death

  (h) New Recovered

  (i) Recovered

  (j) WHO Region

  
In our dataset, Some parameters were assigned value 0, representing those parameters are not applicable for some cases.

All these values have been ignored while calculating rating for each of the parameters mentioned above.

- Step 9 : In the report view, under the insert tab, one text boxes were added to the canvas, the name of the report was mentioned.
- Step 10 : In the report view, under the insert tab, using image option from elements group a rectangle was inserted & similarly using image option company's logo was added to the report design area. 
- Step 11
- Step 11 : A card visual was used to represent sum of deaths.

![screenshot 1](https://github.com/user-attachments/assets/20c8e280-83f8-4567-b6bd-c722bfad7787)

        
 - Step 12 : A card visual was used to represent the New  Cases.

![Screenshot 2](https://github.com/user-attachments/assets/53c1c523-c616-4a69-9338-f20b3320aed4)



 - Step 13 : A card visual was used to represent the recovery cases

![Screenshot 3](https://github.com/user-attachments/assets/59550f47-3534-48d3-a1c8-18e630b43081)



 - Step 14 : The report was then published to Power BI Service.


![screenshot 7](https://github.com/user-attachments/assets/d7addd93-b0ac-424a-b61f-a666e547ae8f)
