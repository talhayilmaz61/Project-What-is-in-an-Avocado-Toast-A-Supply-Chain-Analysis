# Project-What's in an Avocado Toast. A Supply Chain Analysis
Explore the supply chain of three essential ingredients in avocado toast—avocado, sourdough bread, and olive oil—using the Open Food Facts database. This project reveals the origins and complexities of sourcing these staples, providing insights into the intricate supply chains that bring this popular breakfast dish to your table.

Tasks:
Apply your data manipulation and analysis skills to investigate the supply chain of ingredients for making avocado toast in the U.K. Your task is to determine the following information:

The name of the most common country of origin for each of the three key ingredients: avocados, olive oil, and sourdough.
Store the most common country of origin for each ingredient in the following variables: top_avocado_origin, top_olive_oil_origin, and top_sourdough_origin. Ensure that the country names contain only letters (A-Z) and spaces, with no hyphens or other characters.

To focus your analysis, subset each of the DataFrames to include only these relevant columns: 'code', 'lc', 'productnameen', 'quantity', 'servingsize', 'packagingtags', 'brands', 'brandstags', 'categoriestags', 'labelstags', 'countries', 'countriestags', 'origins', 'origins_tags'.

After completing this project, feel free to explore other questions using the food data!

Three pairs of files are provided in the data folder:
- A CSV file for each ingredient, such as `avocado.csv`, with data about each food item and countries of origin.
- A TXT file for each ingredient, such as `relevant_avocado_categories`, containing only the category tags of interest for that food.

Here are some other key points about these files:
- Some of the rows of data in each of the three CSV files do not contain relevant data for your investigation. In each dataset, you will need to filter out rows with irrelevant data, based on values in the `categories_tags` column. Examples of categories are fruits, vegetables, and fruit-based oils. Filter the DataFrame to include only rows where `categories_tags` contains one of the tags in the relevant categories for that ingredient.
- Each row of data usually has multiple category tags in the `categories_tags` column.
There is a column in each CSV file called `origins_tags`, which contains strings for the country of origin of each item.

After completing this project, you'll be armed with a list of ingredients and their countries of origin and be well-positioned to launch into other analyses that explore how long, on average, these ingredients spend at sea.
