<body>
      <img src="images/socialvegan.jpg" alt="socialvegan" width="900" class="center">

</body>

Are you Vegan ? Is this dish gluten-free ? These are the types of questions that made us all come to realize that what you eat has become a standardized normality. The no-meat, no-dairy, no-gluten regimes have become household names for either the medical need or the trendy conviction. In 2016, 0.8% of the french population was assumed to be intolerant to gluten, yet 7% regularly buy gluten-free products.* . This is an example of how food diets do not only emerge from individual medical conditions but also, and mainly, from collective trends through advertisement, accessibility, and media coverage.

**(Source : AFDIAG / AFP / SIAL 2016)*

In France, food diets have also been subject to households' attention over the last decade. Google Trends shows us how interest of these food diets was raised in France over these years. A value of 100 corresponds to the peak popularity of the term worldwide.  

<p style = "padding-top: 20px">
<script type="text/javascript" src="https://ssl.gstatic.com/trends_nrtr/2051_RC11/embed_loader.js"></script> <script type="text/javascript"> trends.embed.renderExploreWidget("TIMESERIES", {"comparisonItem":[{"keyword":"sans lactose","geo":"FR","time":"2004-01-01 2019-12-01"},{"keyword":"sans gluten","geo":"FR","time":"2004-01-01 2019-12-01"},{"keyword":"vegan","geo":"FR","time":"2004-01-01 2019-12-01"}],"category":0,"property":""}, {"exploreQuery":"date=all&geo=FR&q=sans%20lactose,sans%20gluten,vegan","guestPath":"https://trends.google.com:443/trends/embed/"}); </script>
</p>


Along with a modern rise of social and cultural movements, the adoption of new eating habits and debates around different food diets are topics to stay. So how does production react to new consumption tendencies ?

In this post we will dive into a data-driven analysis of how supermarkets have accustomed themselves to food diets through product <a href="#diversity" style="color:#159957"> diversity</a> and <a href="#nutrition" style="color:#159957">nutritional benefits</a>.

<div style="  padding: 10px;
  border: 5px solid gray;
  margin: 0;
  background: #daeaf6;
  text-align: justify">
  
<a href = "https://ch-fr.openfoodfacts.org/"> 
	<img src="images/offlogo.png" alt="offlogo" width="100" align="right" hspace="15">
</a>
Our study is based on the public dataset <a href = "https://ch-fr.openfoodfacts.org/" style="color:#159957"> OpenFoodFacts</a>. <a href = "https://ch-fr.openfoodfacts.org/" style="color:#159957"> OpenFoodFacts</a> gathers more than a million products bought from supermarkets (mostly French) and scanned by over 15,000 users. The consumer can register product information such as its ingredients, nutitional intake, allergens, etc ...  We leverage this information to make a statistical examination of how diets are accounted for in the food-processing industry.</div>

# Diets

The different diets compared in this post are descibed in the following plot 

(Insert Plot Here)

They are all characterized by the restrictions on the consumption of certain food. For example, the Vegetalian (or vegan) diet excludes all animal products such as meat, eggs and dairy.

<a id="diversity"></a>
# Food Diversity

The French National Nutrition and Health Program (PNNS) was last revised in 2016 and was created by a multi-sectoral committee made up of representatives from different ministries, national health agencies, public research institutes and other relevant groups. It aimed at establishing guidelines for eating healthy with daily recommendations for nutrition. For instance, it advocated the consumption of fruits and vegetables regardless of their form, foods that are rich in calcium, or starchy food, while limiting the intake of saturated fat or salt. The program introduced 7 main food categories : *Fish Meat and Eggs, Fruits and Vegetables, Dairies, Fat Sauces, Starchy, Snacks,* and *Beverages*.

We use these categories to classify the food products of our dataset as they were established by experts to present groups with homogenous nutritive compositions.

The following interactive graph shows the percentage of products suitable for each diet over the whole set of 409,904 classified products.

(Interactive plot here)


We see that ...

<a id="nutrition"></a>
# Nutition Grade

Have you ever ask yourself the question if food products that you usually buy are healthy?

A table of nutritional values are mandatory on all prepackaged food and  display energy value, fat content, saturated fatty acids, carbohydrates, sugars, proteins and salt per 100g of product. But all these values are difficult to understand and to compare for the consumer. 

From 2016 Health law, the french government has recommended to set up a simple, readable and easily understandable graphic system, the <a href="https://www.santepubliquefrance.fr/determinants-de-sante/nutrition-et-activite-physique/articles/nutri-score" style="color:#159957">Nutri-score</a>.
The Nutri-score are A, B, C, D or E grades along with colour informations. This allows to inform the consumer of the nutritive value of the product and facilitate advice of health professionals on nutrition. Governments hope that this system will encourage producers to improve the nutritional quality of products.

To classify each product, international research teams create the score with two scoring mechanisms: a negative scoring, which accounts for what is considered unhealthy: calories, sugars, sodium and saturated fatty acids ... and positive scoring: fruits, vegetables, pulses, nuts, and rapeseed, walnut and olive oils, protein and fibre, in an adequate amount of which is considered healthy.

<a href="https://www.santepubliquefrance.fr/determinants-de-sante/nutrition-et-activite-physique/articles/nutri-score"> 
	<img src="images/nutriscore.jpeg" alt="nutriscore" width="200" align="left" hspace="15">
</a>


Since the creation of the Nutri-score, more than 180 food industries (Danone, Bonduelle, McCain, Fleury Michon, Findus, Nestlé, Panzani …) and distributors (Leclerc, Auchan, Intermarché, Casino…) have committed to put the logo on their products.

For consumers, the Nutri-score is used to compare the quality of food from different categories (usually sugary snacks have a worse score than fruits or vegetables) or from same food offered by different brands. For example, breakfast cereals can have a score between A and E. At a glance, you can choose which of your favorite cereals offer the best nutrition.

We compare the diets on the relative proportion of grade A, B, C, D, and E products for each food category.

(Insert plot here)

We see that ...

# Conclusion

Conclude on results



Plot example:

<iframe width="900" height="450" frameborder="0" scrolling="no" src="//plot.ly/~romi514/3.embed?showlink=false"></iframe>






