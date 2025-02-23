# Movie Revenue Prediction and Network Analysis

This project explores the key factors influencing movie revenue using machine learning and network analysis techniques.  By combining predictive modeling with social network analysis of cast and crew relationships, the project aims to provide actionable insights for movie producers and directors to optimize financial outcomes.  The workflow includes data preprocessing, exploratory data analysis, network construction, and predictive model development.

## Data

The primary dataset, `modelled_data.csv`, contains information on 4053 movies and 41 features.  This dataset is enhanced by network features derived from actor and movie relationships.

## Project Structure

The project is organized into several Jupyter Notebooks:

*   `gross_revenue_prediction.ipynb`:  Loads and preprocesses the data, performs basic EDA, and sets the stage for predictive modeling.
*   `relations.ipynb`: Constructs movie-actor networks and calculates centrality measures for actors and movies.  Demonstrates the use of network analysis to derive features.
*   `rating-quarter-EDA.ipynb`: Explores patterns and trends in movie ratings across different quarters of the year. (Note: Unable to extract detail due to file read error)


## Impact
This project has the potential to significantly impact the film industry by providing data-driven insights that can lead to:

*   **Optimized Casting Decisions:** Identify actors and collaborators with the highest potential for box office success based on network centrality and past performance.
*   **Data-Informed Budget Allocation:**  Allocate resources more effectively by understanding which factors have the greatest influence on revenue.
*   **Targeted Marketing Strategies:** Tailor marketing campaigns to specific audiences based on genre preferences and movie characteristics.
*   **Reduced Financial Risk:**  Make more informed investment decisions by leveraging predictive models to assess the potential profitability of a movie before its release.

## Data insight and Visualizations
![quarter-rating-relation](https://github.com/user-attachments/assets/7f8382b9-7a45-4ab1-a3da-17f1e8c373b0)  ![quarter-metascore-relation](https://github.com/user-attachments/assets/017ff1b5-568c-4d59-873d-6e6d0516e210)

**The bar plots reveal a clear trend: both Aggregate Rating and Metascore are notably lower for movies released in the fourth quarter (October-December).**


## Setup

1.  **Clone the repository:**
    ```
    git clone https://github.com/memarathe/Movie-revenue-prediction.git
    cd [repository directory]
    ```
2.  **Install dependencies:**
    ```
    pip install pandas networkx scikit-learn matplotlib seaborn
    ```
3.  **Place the dataset:** Ensure that the `modelled_data.csv` file is located in the `datasets/` directory.



