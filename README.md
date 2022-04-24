Thanks again for attending my session at RIMS!

Here are some follow-up resources you may find interesting:

# Files

files/
- BryceChamberlain-DIYRiskManagementDataExploration.pdf: PDF of presentation slides.
- fraud_insurance_claims.csv: Data used. From https://www.kaggle.com/datasets/mykeysid10/insurance-claims-fraud-detection. 
- fraudulent-hobbies.pbix: Power BI document that I used.
- fraudulent-hobbies.pdf: Final PDF built with Adobe Illustrator

*The R Shiny application is not included since it contains some proprietary code.*

# Links

| Link      | Description |
| ----------- | ----------- |
| https://github.com/oliver-wyman-actuarial/easyr | R package open-sourced by my team. Contains `dict()` function used in the presentation. |
| https://www.kaggle.com/brycechamberlain/easyr-tutorial | easyR tutorial. |
| https://github.com/superchordate/storyteller | My custom AutoML script for finding stories in data. Clone the project and modify scripts to run on new data. |
| https://www.ft.com/vocabulary | Visual vocabulary from Financial Times. Good inspiration for chart types. |
| https://youtu.be/iyO1wSbvtu0 | Youtube video showing how to start working with a PDF export in Adobe Illustrator. |
| https://superchordate.shinyapps.io/for-rims/ | My R Shiny application. |
| https://www.linkedin.com/in/brycechamberlain/ | My LinkedIn page. |

# Software

Here is some software you might be interested in:

**AutoML**

* https://github.com/superchordate/storyteller
* https://rapidminer.com/
* https://www.datarobot.com/
* https://aws.amazon.com/sagemaker/
* https://developer.apple.com/machine-learning/create-ml/
* https://docs.h2o.ai/h2o/latest-stable/h2o-docs/automl.html 
* https://github.com/ydataai/pandas-profiling (neat Python tool for Exploratory Data Analysis, not complete AutoML)

**Business Intelligence**

* https://powerbi.microsoft.com/en-us/ 
* https://www.tableau.com/ 

**Design**

* https://www.adobe.com/products/illustrator/free-trial-download.html
* https://inkscape.org/ 

# Recommended R Packages

I recommend exploring and visualizing data in Power BI, but if you need to modify/preprocess data then R is a good solution. Keep in mind PowerBI has PowerQuery built in though which is also very good for preprocessing. 

Here are some packages that I use a lot:

* **dplyr**: The reason R is better for data manipulation is this packages. It makes working with data very intuitive and easy. 
* **magrittr**: Exclusively for the double-pipe `%<>%` which lets you write cleaner code. 
* **easyr**: This package makes things that were historically difficult in R easier. In particular, `read.any` helps reading files (it reads most data formats automatically), `todate/tonum` flexibly convert characters to dates or numbers and cover more edge cases than other similar functions, and `jrepl` which joins and replaces data from related datasets and turns a 2-step operation into one while checking to confirm data isn't duplicated in the join. See docs on GitHub for many more useful functions. 
* **purrr**: Has some other functions that are useful. Namely `pluck`.
* **tidyr**: Has some useful functions like replace_na but is a large dependency so I avoid using it when I can. That said, it still comes in handy sometimes. 

# Keeping in Touch

Please feel free to reach out to me if you'd like to collaborate or ask a question:

* LinkedIn: https://www.linkedin.com/in/brycechamberlain/
* Email: bryce.chamberlain@oliverwyman.com.
* Personal email: superchordate@gmail.com.

