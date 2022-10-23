# Red or White?

![red_white](Images/red_white.png)

It's one of the most famous either/or questions, a restless debate and one that garners fierce loyalists on both teams. A simple question, yet has a multitude of varying responses as to why someone would prefer a glass of red versus white. There may be a never-ending set of answers as to why one prefers one type over the other. However, today we set aside our differences to focus on solving and understanding a greater complexity when it comes one the alcoholic beverage-its healthiness. While we rely on one of our five senses, taste, to largely determine our liking for wine, we look to explore on a more granular level the chemical makeup of wine and which one essentially is deemed the healthier option for people. 

Winemaking is a multi-billion dollar industry, an assembly process that leads to the creation an alchoholic beverage that is a global commodity product. With each wine brand and wine type, its process and ingredients are distinct. We will investigate a number of physicochemical variables to determine how largely red and white wine differ. Ultimately, through our data exploration and analysis, we seek to determine which wine is the healthier option for consumption. For our study, we will be utlizing data focusing on the Portuguese "Vinho Verde" wine, one of the most famous wine varities of Portugal, to determine if we are able to arrive at a conclusion. 

## Collaborators
| Name | Role | Description |
| :---         |     :---:      | :---         |
| Vannesa Martinez | Project Manager | Managing the project presentation and visualization|
| Aggie Jasinski | Data Gathering | Gathering the dataset csv's and preprocessing the datasets|
| Roman Dobczansky | Machine Learning | Creating the framework of the Machine Learning Model |
| Rasna | GitHub Repository and Databse | Organizing and maintaining the repository and the database creation|

## Data Sources
Datasets were obtain through Kaggle
- Red wine: [wineequality-red.csv](https://www.kaggle.com/code/vishalyo990/prediction-of-quality-of-wine/notebook)
- White wine: [winequality-white.csv](https://www.kaggle.com/datasets/piyushagni5/white-wine-quality?select=winequality-white.csv)

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
- Which qualities make up the healthiest wine?
- Which wine is a healthier option for consumers?

## Understanding the Variables
Before diving into our investigation and research questions, let’s take a step back to further understand a few of the explanatory variables are essential in the chemistry of wine and its balance crucial to make to the wine. 

### Sulfates
The presence of sulfates on labels can sometimes worry consumers, its pros in wine are crucial to the consumption and longevity of the wine stored in the bottle itself. Sulfates help to prevent wine from browning and minimize oxidation in wine and maintain its freshness. Wines with lower acidity need more sulfites than higher acidity wines. Other effects on the winemaking process include preventing the growth of unwanted microorganisms, promoting the growth of yeast for better fermentation, and improving the release of desirable compounds from grapes. 
From a health standpoint, that are a few risks associated that individuals can develop with consumption. Some side effects that can be presented include:
-	Headache
-	Rash
-	Hives
-	Swelling of the month and lips
-	Trouble breathing
-	Anaphylaxis

### Acidity and pH
Wine acidity greatly affects its flavor and aroma in several ways. Wines that present high acidity have a sharper taste while also affecting how the consumption affects how it will sit in an individual’s stomach. Fixed and volatile acidity tells us the concentration of acids present in wine. pH levels inform us of the intensity of acids present. 

### Residual sugar (RS)
Residual sugars is essential the natural grape sugar contents left behind and do not end up being converted to alcohol during the fermentation process. Residual sugar content after fermentation is inversely proportionate to the alcohol level. Meaning that higher alcohol wines contain less sugar, while low alcohol wines have more sugar. The RS amount is measured in grams per litre (g/L) and will affect a wine’s sweetness. 

### Alcohol content
This is the percentage of alcohol content of the wine. Veraison, the process that ripens the graphs that produces sugar, combined with fermentation, the yeast used in the winemaking transforms sugar into ethanol (alcohol), heat, and carbon dioxide. Essentially, the higher the sugar levels in the grape, the higher the alcohol levels in the wine.  


# Wine_Os
The plan for our machine learning model using tensor flow implements input variables as red and white wine data
The  output will determine which wines are highest in quality using the neural network nodes as metrics of fixed acidity, alchohol content, sulphates, and residual sugars 
This model will be conducted as a supervised ML model because we want to accept or reject the hypothesis that red wine is healthier and tastier because of higher levels said metrics than white wine based on our criteria.



