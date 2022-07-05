# Lending Club Case Study
> The data set consist of loan applicant details & their loan status, with data fetched from Lending club portal.
The analysis looks if there is any corelation between those applicant inormation and loan repayment ability.
These co relation will be highlighted.


## Table of Contents
#Attempt is to find correlation between borrower's available background check & loan repayment possibility, by performing Exploratory data analysis on the data
#Python Jyupitar notebook used for the analayis
#Performed univariate and bivariate analysis on this data set, 
and found that applicant income, employee length, employee title, locality, debt to income ratio has corelation to some extent. 
And can be used in future while issueing loan




## General Information
- Lending club is portal where borrower's and lenders connect each other for monetory loan prospects.
- The portal gathers the information of applicants who requests for the loan. These details such as demographic details, income, 
personal details can help in understanding their ability of repayment the loan.
- Early detection of loan payment inability shall be predicted through this analysis



## Conclusions
Income and installments are corelated. Additionaly dti can be linked to it.
Applicant likely to repay loan in case annual income above 82000/- and installment as 410/-. If income is less, in that case installment has to be lesser than 410/-​

Applicants with debt to income ratio less than 16 perform better in term repaying loan than with dti higher than 16.​

The loan terms I.e. interest rate also influenced the repayment ability. Interest rates higher than 15% have less probability of repayment. Maybe higher interest rates linked to higher installments and causing 3rd point.​

Some localities are seen to have less repayment ratio. E.g. (880-890) & (830-840 ) zip code have more defaulters than fully paid applicants.​

Some firms applicants, like "wal-mart", "postal service" have higher loss making customers than usual. 




## Technologies Used
- pandas library 
- numpy library  
- matplotlib 
- seaborn
- difflib(SequenceMatcher)

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by...Upgrad



## Contact
Created by [@ksoham9552] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->