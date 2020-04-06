# Instacart Classification Project

With my background in marketing and eCommerce, I was interested in tackling a consumer funnel project.
I chose the [Instacart Basket Analysis](https://www.kaggle.com/c/instacart-market-basket-analysis) dataset. This was a Kaggle competition a few years back. The dataset includes files for products, orders, and user order history. Using this information,
I did feature engineering and modeling to best predict whether a user will reorder a product. This is an important marketing question because it allows companies, like Instacart, to serve their customers with better product recommendations leading to increased Average Order Items, Order Value and customer loyalty.


Notebook Name | Purpose
------------ | -------------
instacart_pandas_cleaning | Initial Cleaning & Merging of Instacart CSVs
instacart_sql_feature_engineering | User & Product Features in SQL with AWS Database
Instacart_pandas_feature_engineering | User-Product Feature Engineering in Pandas
instacart_modelingwithfeatureselection | Running models with feature selection, not final results
instacart_modeling | All code for modeling & final results

The notebooks are listed in order of work in the table above. All data was intially stored in AWS with SQL tables for feature engineering. Next, the tables were converted to Pandas dataframes for further feature engineering. Modeling with Feature Selection contains tests with feature selection for improved scores, but the results were not optimal. Finally, the Modeling notebook contains all modeling and final results.








