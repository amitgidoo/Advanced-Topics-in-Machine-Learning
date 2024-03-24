## Real Estate Rental Trends: Clustering for Insights

### Project Description
This project focuses on analyzing rental property listings using advanced machine learning techniques, specifically clustering, to uncover patterns and insights within the data. It explores the relationships between various property features, temporal dimensions, geographic locations, and rental prices, employing clustering algorithms to identify significant patterns. The project is part of the "Advanced Topics in Machine Learning" course, aiming to provide comprehensive insights into the rental market's dynamics.


### Motivation
In recent years, finding affordable housing in densely populated metropolitan areas has become an increasingly challenging task. This project is motivated by the need to gain a deeper understanding of the factors influencing high rental costs, especially affecting younger populations in cities like Tel Aviv-Yafo. Through the analysis of a large dataset of rental listings, we aim to uncover patterns and anomalies that could inform better housing policies and enable data-driven decision-making in the real estate market.


### Datasets
Our analysis is based on a dataset comprising approximately 275,000 rental property listings from the last decade in Tel Aviv-Yafo, one of Israel's most densely populated cities. This data was meticulously collected through web scraping techniques using Python's Requests and BeautifulSoup libraries. Extensive preprocessing was conducted to ensure data quality, including handling missing values, removing outliers, and engineering relevant features to enrich our analysis.


### Installation and Requirements
To run this project, follow these steps:

1. Clone the repository: `git clone https://github.com/your-repo-url.git`
2. Navigate to the project directory: `cd your-repo`
3. Install the required libraries: `pip install -r requirements.txt`

Refer to the `requirements.txt` file for the list of library dependencies.


### Usage

This project is structured into Jupyter notebooks, each focusing on different stages of the analysis:

1. **Data Scraping**: The `Data_Scrapper.ipynb` notebook is used for scraping rental data from online sources. 
2. **Merging Data**: Use the `Merge Data.ipynb` notebook to consolidate data collected from various sources into a single dataset.
3. **Data Preparation and Cleaning**: The `Prepare_and_cleaning_the_data.ipynb` notebook details the preprocessing steps such as handling missing values, outliers, and feature engineering.
4. **Machine Learning Methods and Visualization**: Finally, the `ML_methods_CLUSTRING_algorithm_and_Visualizations.ipynb` notebook applies various clustering algorithms to the processed data and visualizes the results.

  To run these notebooks, make sure you have Jupyter Notebook or JupyterLab installed, you can run the project also on Python.


### Methods and Techniques
The project employs several machine learning techniques, including:

- Clustering algorithms: K-Means, DBSCAN, and Hierarchical Clustering
- XGBoost for regression and feature importance analysis
- Linear and non-linear models
- Feature selection and dimensionality reduction techniques


### Results
The project successfully identified patterns and clusters within the rental data, revealing insights into the relationships between property features, temporal factors, and rental prices. Key findings include the identification of unexpected feature combinations influencing prices, the impact of time and location on rental costs, and the potential for better-informed housing policies based on data-driven analysis.

For detailed results, visualizations, and interpretations, please refer to the project report included in the repository.

### Contributions
This project was completed by Sahar and Amit as part of the "Advanced Topics in Machine Learning" course.

- Sahar: Project report writing, documentation, and result interpretation.
- Amit: Data preprocessing, feature engineering, model implementation, code development and too result interpretation.

### References

- Project report: Provided in the document titled "דו''ח פרויקט למידת מכונה.pdf".
- Python notebooks relevant to the project include:
  1. `Data_Scrapper.ipynb` for data scraping.
  2. `Merge Data.ipynb` for merging collected data.
  3. `Prepare_and_cleaning_the_data.ipynb` for data preparation and cleaning.
  4. `ML_methods_CLUSTRING_algorithm_and_Visualizations.ipynb` for applying machine learning clustering algorithms and visualizations.
- In addition to the Python notebooks, the project utilizes Excel files for data handling and preparation:
  1. `clean_final_data.xlsx` for the cleaned and prepared dataset, available in the repository.
  2. `final_merge_tel_aviv_data.xlsx` for the initial merged dataset, not available on GitHub due to size limitations. Please contact the project contributors for access to this file.
  3. The `real_estate_data` directory contains Excel files with the scraped rental listing data. Each file contains around 2,400 records, with each file comprising approximately 50 sheets and each sheet holding data for 48 listings. The files are named sequentially, e.g., `scraped_data_1-50.xlsx`, `scraped_data_51-100.xlsx`, and so on, up to `scraped_data_5701-5737.xlsx`.

### Contact

For any questions or inquiries, please contact us at:

- Amit: amit.gido2@gmail.com
- Sahar: saharsokolik2@gmail.com
