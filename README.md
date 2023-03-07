# Lending Club Case Study
> Lending Club is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures.

> The company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default



## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
### Analysis Methodology
1. Data Sourcing
2. Cleaning Data
3. Univariate Analysis
4. Bivariate Analysis
5. Conclusion

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
Driving factor (Variables) in determining whether the borrower can be defaulter are as below:
- Term(term) 60 months  (Categorical Variable)
- Loan amount(funded_amnt_inv) > 12k (Continuous Variable)
- Interest rate(int_rate) > 12% (Continuous Variable)
- LC Grade(grade) D,E,G (Categorical Variable)
- Employment Length(emp_length) >= 10 years (Continuous Variable)
- Home Ownership (home_ownership) is OTHER (Categorical Variable)
- Annual Income (annual_inc) <50K (Continuous Variable)
- Verification status(verification_status) is Verified (Categorical Variable)
- Purpose of Loan(purpose) is for "renewable energy" of "home improvement“ (Categorical Variable)
- DTI(dti) > 12 (Continuous Variable)
- Loan disbursed/approved in December (Derived Variable)
- Borrower with verified income and high interest rate


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- numpy - 1.21.5
- pandas - 1.4.2
- matplotlib - 3.5.1
- seaborn - 0.11.2
- python - 3.7

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Thanks to
- https://www.geeksforgeeks.org/
- https://pandas.pydata.org/
- https://seaborn.pydata.org/
- https://stackoverflow.com/


## Contributor
Created by 
- Parth Gandhi : 
> [![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/Parth6288) 


Please feel free to contact us.

<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->