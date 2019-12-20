# Title

<b> How do diets compare ? </b>

While our first approach was mainly focused on a store comparision, we refocused our work on more complete features of products from the Open Food Fact database. After further analysis of the database following Milestone 1, we decided to exploit food categories, packaging, and nutrition to make a comparision between modern eating habits.

# Abstract

Wether it be for medical purposes or ethical beliefs, most humans are confronted to diet restrictions at some points in their lives. From an ethical standpoint, animal abuse and ecological principles can lead to the choice of Veganism, and provide a narrower product choice in grocery shopping. Obesity can be fought by avoiding sugar rich products, and thus by choosen to follow a ketogenic diet. Guten-free or lactose-free diets are sometimes necessary after discovering an intolerance. However, making the sacrifice isn't so easy. But, how do diet choices affect ourselves and our surroundings? More accurately, what are the environmental and nutritional impacts of diets ?

With our work, we want to provide a better understanding of the effects in choosing certain diet types, based on how nutritious and eco-friendly they are.

# Research questions

- Which diet provides the best products in terms of nutrition ?
To answer this question, we manage first to compute our own nutriscore ranking methods and compared the obtained result with true nutriscores already available in the row data. Secondly, we needed to estimate the diet in which each product belong and thus to implement a diet classification method. Finally, a graphical visualization has been implemented to interpret our results.
 
- Do certain diets favorize certain packaging methods ? How does each diet participate in recycling?
To investigate this question, we classified the available packaging according to the materials present in it, and compared the results for each of the diets obtained with our diets classification method. However, the outcome of the result visualization showed us that the packaging repartition among the diets is almost the same for each of them, which could not lead to any interpretation except the fact that product packaging doesn't seems to be impacted by the type of diet in which the product belong. 

The data story resulting from our analysis as well as results visualization are available on our post [The Inside Of How You Eat](https://romi514.github.io/ProjectADA/)

# Work before Report/Milestone 3

- Create Website for story visualization
- Implement machine learning algorithm to classify samples into food categories (e.g. Random Forest classifier)
- Explain approach to our nutrition ranking and compare it to the one available in the database
- Preprocess the raw data in order to be able to find informations needed for diets classification, find relevant strategy for diets classification and create informative visualizations
- Expand story of predicted nutriscores as well as the predicted food categories among the classified diets 

# A list of internal milestones up until project milestone 3

- <b>3.11.2019</b> Explore the need and way to enrich the database for more products, categories, nutrition, packaging, diets.
- <b>10.11.2019</b> Add found information to database products, clean overall dataset, retain relevant information and products.
- <b>17.11.2019</b> Investigate possible interesting analysis regarding the used of diets, food categories, nutrition rank
- <b>24.11.2019</b> Implement consistent ranking method for nutriscores
- <b>8.12.2019</b> Implement relevant classification algorithms for food categories and diets classifications
- <b>15.12.2019</b> Implement appropriate data visualization to merges results and investigate interpretations relevant to our datastory
- <b>20.12.2019</b> Create website and integrate to it relevant results and visualizations for our analysis

Romain : Food category classification, Website designer and Task helper

Mat : Data cleaning, Ideas provider and Nutriscore explorer

Titi : Data cleaning, Diet study and classification

Val : Packaging explorer, Data visualizer

Our exploration where all plots are displayed is available at : https://nbviewer.jupyter.org/github/romi514/ProjectADA/blob/master/project_tagADA.ipynb



