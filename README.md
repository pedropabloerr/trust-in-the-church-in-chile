![Header](https://github.com/pedropabloerr/trust-in-the-church-in-chile/blob/main/images/Church-Header.jpeg?raw=true)
## Trust in the Church in Chile
### A time series analysis of Latinobarometer survey 1995-2018
Analysis made by [Sathiya Raju](https://www.linkedin.com/in/sathiya-raju) and [Pedro Pablo Errázuriz](https://www.linkedin.com/in/pedropablo-errazuriz/)

### Summary

This research analysis the fall on the trust of the Church in Chile. We explore the data included in the survey [Latinobarometer](https://www.latinobarometro.org/latContents.jsp) and then we compare it with a database from the [NGO Red Sobrevivientes](https://www.redsobrevivientes.org/post/mapa-abusos) to look for an explanation of the sharp decline in the trust. 

### Pre-processing

We first encountered 15 different datasets that we had to convert to csv format. As the answers were encoded, we decoded them changing the label, and extracting the specific columns we needed for our analysis. Then we concatenated them in one database, and re-coded them in a manner that would serve our analysis, turning them into numerical variables and into categorical variables. 

As for the data from Red Sobrevivientes, we built their map of abuse cases into a spreadsheets data base, and cleaned it with python. 

### Analysis

We first compared the level of trust between Chile and other selected Latin American countries. We the dissagregated them by gender and by age cohort to look for attitudes towards the Church patterns. We finally compared both data bases using Tableau. We could conclude a correlation between the fall in the trust in the Church and the emergence of cases of sexual abuse involving its members, though it was not possible to quantify the effect of a case in particular. 

![decline in trust and emergence of cases](https://github.com/pedropabloerr/trust-in-the-church-in-chile/blob/main/images/Screenshot%202021-07-02%20at%2010.03.40.png?raw=true)

### Links

-[Our code](https://github.com/pedropabloerr/trust-in-the-church-in-chile/blob/main/code/mid_term_project_complete_file.ipynb)
-[Our cleaned Latinobarometer data base](https://github.com/pedropabloerr/trust-in-the-church-in-chile/blob/main/databases/data_all_v6.csv)
-[Our cases from Red Sobrevivientes data base](https://github.com/pedropabloerr/trust-in-the-church-in-chile/blob/main/databases/Cases_DataBase_V2.csv). 
-[Our presentation including visualizations](https://github.com/pedropabloerr/trust-in-the-church-in-chile/blob/main/presentation/Presentation.pdf).
-[Our Trello Board](https://trello.com/b/GzzGcTCn/mid-term-project "trello board trust in the church project").
