# Airbnb in Santa Clara County

## Introduction

**Airbnb in Santa Clara County** is a data analysis and visualization project that examines Airbnb listings and guest reviews in the Santa Clara County region. Using Python for data analysis and **Tableau** for interactive visualizations, this project explores trends, pricing patterns, guest sentiments, and other key metrics related to Airbnb properties in the area. The project provides insights into the local short-term rental market, helping hosts, guests, and real estate analysts make informed decisions.

## Features

- **Data Analysis:** In-depth analysis of Airbnb listings, including price trends, location-based insights, property types, and guest sentiments.
- **Sentiment Analysis:** Analyzes guest reviews to extract positive, neutral, and negative sentiments, giving insights into guest experiences.
- **Interactive Dashboard:** Explore the Airbnb data through an interactive Tableau dashboard for better decision-making and visualization of trends.
- **Visualization of Key Metrics:** Highlights average price per night, occupancy rates, types of properties, geographical distributions, and sentiment analysis results.
- **Cross-platform Accessibility:** The dashboard is accessible on any web browser.

## Technologies Used

- **Python:** For data cleaning, preprocessing, sentiment analysis, and general data analysis.
- **NLTK:** For performing sentiment analysis on Airbnb guest reviews.
- **Pandas:** For data manipulation and analysis.
- **Tableau:** For creating the interactive dashboard and visualizations.
- **Jupyter Notebooks:** For exploratory data analysis and insights generation.

## Prerequisites

Before running the project, ensure you have the following installed:

- **Python 3.x**
- **pip** (Python package manager)

## Installation

To run the project locally, follow these steps:

1. **Clone the repository:**

    ```bash
    git clone https://github.com/pp11-web/Airbnb-in-Santa-Clara-County.git
    ```

2. **Navigate to the project directory:**

    ```bash
    cd Airbnb-in-Santa-Clara-County
    ```

3. **Install the required dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

4. **Run the Jupyter Notebook:**

    Launch Jupyter Notebook in your terminal:

    ```bash
    jupyter notebook
    ```

5. **Open and explore the notebooks** to see the analysis:

    - `Airbnb_Analysis.ipynb` (Main analysis notebook)
    - `Sentiment_Analysis.ipynb` (Guest review sentiment analysis)

## Tableau Dashboard

Explore the Airbnb data for Santa Clara County using the **interactive Tableau dashboard**. Click on the link below to view it:

[Interactive Airbnb Dashboard](https://public.tableau.com/views/DataVisualizationProject_17012396837990/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

The Tableau dashboard provides insights into:

- **Average nightly prices** for Airbnb properties across different neighborhoods.
- **Distribution of property types** (entire home, private room, etc.).
- **Geographical mapping** of Airbnb listings in Santa Clara County.
- **Occupancy rates** and trends based on available data.
- **Sentiment analysis results** of guest reviews (positive, neutral, negative).

## Data Source

The data used in this project is sourced from Airbnb’s public dataset for Santa Clara County. This dataset includes information on property listings, nightly rates, host details, and guest reviews. The data was cleaned, processed, and analyzed using Python, with visualization in Tableau.

## Usage

### Exploring the Analysis

- **Data Cleaning & Processing:** The data was cleaned to remove missing values and standardized for analysis.
- **Sentiment Analysis:** Guest reviews were analyzed using NLTK’s sentiment analysis tools, classifying reviews into positive, neutral, or negative sentiments.
- **Visualization:** The cleaned data and sentiment results are visualized in the Tableau dashboard, providing insights on Airbnb trends.
- **Custom Filters:** Users can filter by property type, neighborhood, pricing, and sentiment to focus on specific metrics.

## Sentiment Analysis

This project performs **sentiment analysis** on Airbnb guest reviews to understand the overall guest experience. Using **Natural Language Processing (NLP)** techniques from the **NLTK** library, reviews are classified into the following categories:

- **Positive:** Reviews that reflect a good guest experience.
- **Neutral:** Reviews that are neither positive nor negative.
- **Negative:** Reviews that indicate a poor guest experience.

The sentiment analysis helps hosts understand their guest feedback and improve their services.

## Customization

To customize the project:

- Modify the layout in the **`app.py`** file to add or remove components.
- Adjust the visualizations in the **`graphs.py`** file to change how the data is presented.
- Update the dataset or add new data sources to analyze additional trade metrics or countries.

## Contributing

We welcome contributions to this project. If you’d like to contribute:

1. **Fork the repository.**
2. **Create a new branch:**

    ```bash
    git checkout -b feature/your-feature
    ```

3. **Commit your changes:**

    ```bash
    git commit -m "Add new feature"
    ```

4. **Push your changes:**

    ```bash
    git push origin feature/your-feature
    ```

5. Open a **Pull Request** to merge your changes.

## Future Enhancements

- **Improved Sentiment Analysis:** Use more advanced models like **VADER** or **TextBlob** to perform more accurate sentiment classification.
- **Forecasting trends:** Use machine learning models to predict future Airbnb trends in the area.
- **Host performance:** Add analysis of host response times, ratings, and other factors impacting guest experience.

## License

This project is licensed under the **MIT License**. For more details, see the [LICENSE](LICENSE) file.

## Acknowledgements

Special thanks to **Tableau Public** and the **Airbnb open data** community for providing the resources and tools to make this project possible.

