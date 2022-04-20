# Predict_Global_Crises

**Contributers and Contact Information: [ ]

	 Kone Mariam,leader (+225 0757126759, konemariam0856@gmail.com)

	 Ouattara Madeleine (+225 0546449133, ouattaramadeleine@gmail.com)


**Problem Statement addressed :

	The Problem

	Throughout history, we have seen how one country’s decisions and behaviors can affect others, if not the world. The most recent example is the crisis of 2007/08, when the US housing market collapsed and triggered the whole world to go into a crisis. Another - more recent - example is that of the insurgence of COVID-19 pandemic. Besides these, there are myriad other disruptive crises among world countries. Since history tends to repeat itself, one cannot help but wonder if one could minimize the effects of another country’s crisis on their own population.  

	The Challenge

	Given that all countries are connected to each other, construct a graph to see how much one country’s crisis will affect the other. Treat countries as nodes and their relationships as links. Leverage the different socio-economic and macroeconomic aspects that were captured for each country throughout time in order to predict a crisis, or, to predict what other countries will be affected by one country’s crisis. This would help countries minimize the effects of another country’s crisis on their own citizens.

**Solution:

	Implementation of a web application that will allow to predict a banking crisis of a country at a given year with its different partners.

**Objective of our solution:

	Realize an intelligent system that will prevent the arrival of a global crisis using Tiger Graph as the database 

**Description of the solution:

	Here we will treat countries as nodes and their relations as links. We will take advantage of the different socio-economic and macroeconomic aspects that have been captured for each country over time to predict a crisis or predict which other countries will be affected by a country's crisis. This would help countries minimize the effects of another country's crisis on their own citizens.

**Implementation of the solution:
  
	• use the WITS API to import our data,

	• preprocess the data on COLAB using the preprocessing libraries (pandas and scikit-learn),

	• visualize the data to extract information to predict a crisis using the visualization libraries (seaborn and matplotlib),

	• import the data sets obtained in TigerGraph and then apply the k-nearest neighbors classification model that TigerGraph makes available to us,

	• predict the countries in crisis according to the year and list for a country these partners affect and

	• set up a visualization interface with Plotly Dash.

#  Dependencies

	State any dependencies and their versions needed to be installed to test this project. This may include programming languages, frameworks, libraries, and etc.

# Installation

  	**step 1:
	
	Clone repository
	
	use the modelCrisis (1).ipynb template to clean up the global_crisis.csv dataset and get the output global_crisis_data_clean_final_2.csv 
	
	Donwload the zipped file export_333417696.tar.gz in the src folder
	
	
	Upload it on tgcloud.io

	load the csv file global_crisis_data_clean_final_2.csv located in the src folder

	Run queries such as predicting the crisis of a country with tg_knn_cosine_ss.
	
	**step 2:
	
	Using getPatenaries.ipynb to obtain the countries of import and export of the Ivory Coast, we obtain civ2010export_and_final_value.csv and civ2010import_and_final_value.csv. We can also get the partners of the partners of a country forming a graph.
	
	Donwload the zipped file crise_prediction.tar.gz in the src folder
	
	pload it on tgcloud.io 
	
	load the csv file global_crisis_data_clean_final_2.csv, civ2010export_et_valeur_finale.csv, civ2010import_et_valeur_finale.css and paysetcode.csv located in the src folder 
	
	Run queries to determine which countries will be impacted if the Ivory Coast is in crisis
	
	**step 3:
	
	Run all cells of the modelCrisis (1).ipynb model to display the dashboard visualization, the style.css file provides the dashboard formatting.
	
	

# References

	[Foreign_Trades_between_countries] https://wits.worldbank.org/Default.aspx?lang=en

	[tigerGraph] https://tgcloud.io/

	[gsql_graph_algorithms] https://github.com/tigergraph/gsql-graph-algorithms

	[Global_crises_data] https://www.hbs.edu/behavioral-finance-and-financial-stability/data/Pages/global.aspx
