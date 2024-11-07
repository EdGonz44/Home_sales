# Home_sales
Module 22

## Project Overview
The purpose of this project was to utilize SparkSql to determine key metrics about home sales data. This was done through querying results on the average price of homes based on metrics such as: the amount of bed and baths a home has, the year it was built, view ratings, levels in building, and square footage of land. Afterwards, a query was tested for its runtime basedo on whether it was a regular Spark query, cached, or partitioned. 

### Analysis
The jupyter notebook used for this project was uploaded into a Google Colaboratory in order to save time on lenghty imports of Spark on local device. The finsihed jupyter notebook was then saved from Google Colaboratory onto github: [Home_Sales](). 
The querying results can be found within this Jupyter Notebook file, however it was found that there was a difference in runtimes based on the method of querying. A cached query had a noticeable cut-down of runtime compared to a regular Spark query once it had run its initial memory save. As for the partitioned query it seemed to have performed at a similar speed as the cached. This may be due to the simplicty of the dataset, which would make it ideal for quick cached queris, as well as being at an optimal size for partioning effectively.

## Project Structure
The project repository should have the following structure:

```plaintext
Home_sales/
│
├── Home_Sales_starter_code_collab.ipynb
└──README.md

```


