# Red or White?

![red_white](Images/red_white.png)

It is one of the most famous either/or questions, a restless debate and one that garners fierce loyalists on both teams. A simple question, yet has a multitude of varying responses as to why someone would prefer a glass of red versus white. There may be a never-ending set of answers as to why one prefers one type over the other. However, today we set aside our differences to focus on solving and understanding a greater complexity when it comes one the alcoholic beverage-its healthiness. While we rely on one of our five senses, taste, to largely determine our liking for wine, we look to explore on a more granular level the chemical makeup of wine and which one essentially is deemed the healthier option for people. 

Winemaking is a multi-billion dollar industry, an assembly process that leads to the creation an alchoholic beverage that is a global commodity product. With each wine brand and wine type, its process and ingredients are distinct. We will investigate a number of physicochemical variables to determine how largely red and white wine differ. Ultimately, through our data exploration and analysis, we seek to determine which wine is the healthier option for consumption. For our study, we will be utlizing data focusing on the Portuguese "Vinho Verde" wine, one of the most famous wine varities of Portugal, to determine if we are able to arrive at a conclusion. 

## Insight on Portuguese Vinho Verde
What makes the quality of **“Vinho Verde”** so unique?

“Vino Verde” (its literal translation “green wine”) is not a grape type. **“Green” means young** rather than anything to do with its color. A single glass of wine contains thousands of different chemical compounds which determine its quality. We are to find out what characteristics make a Vinho Verde a Vinho Verde. Is it the region of Vinho Verde or the unique chemical compounds that make up this young wine's quality and taste.

## Collaborators
| Name | Role | Description |
| :---         |     :---:      | :---         |
| Vannesa Martinez | Project Manager | Managing the project presentation and visualization|
| Aggie Jasinski | Data Gathering | Gathering the dataset csv's and preprocessing the datasets |
| Roman Dobczansky | Machine Learning | Creating the framework of the Machine Learning Model |
| Rasna | GitHub Repository and Databse | Organizing and maintaining the repository and the database creation |

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- PostgresSQL
- sklearn

## Data Sources
Datasets were obtain via Kaggle
- Red wine: wineequality-red.csv
- White wine: winequality-white.csv

## Data Description
In our analysis we utilize two datasets that of the red and white Portuguese "Vinho Verde" wine brand to determine if the chemical components levels correlate with our hypothesis of the healthier wine. In both datasets, each focus on the same variables, which are part of our merged dataset. The variables that will be part of our examination are as followed:
- fixed acidity
- volatile acidity
- citric acid
- residual sugar
- chlorides
- free sulfur dioxide
- total sulfur dioxide
- density
- pH
- sulphates
- alcohol

## Investigation Questions
- Are there vast chemical compound differences between the red and white wine datasets being compared?
- Which type of wine presents less alcohol, acidity, and sulphate?
- Which wine is a healthier option for consumers?

## Machine Learning Module
By using Machine Learning models, we will try to predict Vinho Verde’s quality based on its chemical composition such as; acidity, sulfur, sulphates, and alcohol content. All while comparing Vinho Verde red and white. The plan for our machine learning model using tensor flow implements input variables as red and white wine data. The output will determine which wines are highest in quality using the neural network nodes as metrics of fixed acidity, alchohol content, sulphates, and residual sugars.

This model will be conducted as a supervised ML model because we want to accept or reject the hypothesis that red wine is healthier and tastier because of higher levels said metrics than white wine based on our criteria.

## Database
We will be creating a master database of red and white wine qualities by codifying red and white wines separately therefore making it easier to compare and contrast the qualities of red and white wines. We initiate our process by establishing an ERD that demonstrates the schema between the red and white wine datasets and utlize Postgres to create our relational database structure.

![QuickDBD-Wine_Os](https://user-images.githubusercontent.com/104734224/196826477-b6a80815-26ff-4401-b2f9-c23a12c77f00.png)
