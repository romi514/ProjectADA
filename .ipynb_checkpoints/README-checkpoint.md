# Title

<b> Where should you go grocery shopping ? </b>

# Abstract

We buy from them ever week. Giants of the food industry have shapped our grocery habits with afforadable and accessible products through mass-distribution. There are often several hyper-stores near home and but we always end up grocery shopping at the same one by habit. But which ones deserves our money ? Which ones are the most eco-friendly, healthy, offering the biggest variety of products, and actively aware of consummer needs ?

With the extensive Open Food Facts Database, we propose to construct a ranking of stores of mass-distribution. We wish to explore criterions such as carbon-footprint, packaging, sold products (nutrition, variety,...), and the answer to customer needs (allergies, intolerances, food diets,...). A further analysis of ranking per country can be done based on their food industry.

# Research questions

- Which stores offer the widest variety of products ? How well do they tackle customer needs and restrictions such as allergies and diets ?
- Are standard nutrition rankings reliable, and if not how to create a trustworthy one ? And how well do stores choose their products regarding their nutrition ?
- To what extent do stores base their product choices on imported products, and thus take into account their environmental impact ? How extensively do they use packaging ?

# Dataset

We will use the [Open Food Facts](https://world.openfoodfacts.org/) database under the csv format. We will use the fields such as product name, quantity, packaging, categories, stores, nutrition facts, and ingredients.

Only a few products have a carbon footprint field. We plan on extending it with carbon footprint calculations based on where the product was sold, where it was imported from, and possibly the countries' size (since the store locations in the country remains unknown to us). Country information in this [external database](https://mledoze.github.io/countries/) by Mohammed Le Doze will be used to retrieve country geo-coordinates.

Only the top 20 stores or so will be compared since the others are extremely under represented. A normalization will have to be done for each store since some are under represented in order to compare product variety. 

Also, only 17% of the 1 million product entries have stores references so additional web scraping should be done tentatively to enrich our dataset.

# A list of internal milestones up until project milestone 2

- <b>3.11.2019</b> Explore the need and way to enrich the database for more stores, categories, nutrition, and carbon footprint fields.
- <b>10.11.2019</b> Add found information to database products, clean overall dataset, retain relevant information and products.
- <b>17.11.2019</b> Perform analysis for each criteria and create a store ranking for each
- <b>24.11.2019</b> Present the results with convincing and appropriate visualizations

# Questions for TA
- Only 17% of the products have a store assigned which reduces the dataset to 180167 products. We haven't found a way yet to find the stores of products with missing. Do you think the amount of data is sufficient for reasonable conclusions ?

- About 500 products already have carbon footprints. Do you think we should recalculate the carbon footprint for them since calculations won't take the same parameters into consideration ?




