# Eniac E-commerce Analysis

Welcome to the second data analysis project for Eniac, an e-commerce tech company. This project aims to address an ongoing debate regarding the effectiveness of discount strategies. The analysis explores whether offering discounts benefits the company in the long run, focusing on customer acquisition, satisfaction, retention, and overall revenue trends.

## Project Overview
Eniac's Marketing Team Lead believes discounts drive long-term growth, while the Board is concerned that aggressive discounts hurt revenue and undermine the company's positioning in the quality segment. This project leverages internal company data (non-anonymized and slightly chaotic) to provide clarity on the impact of discounts and guide decision-making.

### Key Objectives:
1. Classify products into meaningful categories to simplify reporting and analysis.
2. Analyze the distribution of product prices across categories.
3. Determine how many products are discounted and assess the magnitude of discounts.
4. Investigate how seasonality and special dates (e.g., Christmas, Black Friday) influence sales.
5. Propose improvements to data collection processes.

### Deliverables:
- Insights and recommendations presented in a concise, engaging presentation for the company board.

## Repository Structure
```
├── data-cleaning
│   ├── data_cleaning.py       # Python code for cleaning and restructuring data
├── graphs
│   ├── sns_graphs.py          # Python code for creating Seaborn graphs
│   ├── images                 # Folder containing graph images
│       ├── distribution_prices.png
│       ├── discount_analysis.png
│       ├── seasonality_sales.png
│       ├── ...
├── README.md                  # Project documentation
```

## Instructions
### 1. Data Cleaning and Restructuring
The `data_cleaning.py` script contains the code for:
- Cleaning and preprocessing the raw internal data.
- Structuring the dataset to enable meaningful analysis, including handling missing values, categorizing products, and parsing dates for seasonal trends.

Data cleaning was performed using Google Colab, and the data frames are stored on Google Drive for seamless integration.

To run the script:
```bash
python data-cleaning/data_cleaning.py
```

### 2. Graphs and Visualizations
The `sns_graphs.py` script generates Seaborn visualizations for key analyses, such as:
- **Product Price Distribution:** Understanding price ranges across categories.
- **Discount Analysis:** Evaluating the percentage of products on discount and the magnitude of discounts.
- **Seasonality and Special Dates:** Analyzing the impact of events like Christmas and Black Friday on sales.

The generated images are saved in the `graphs/images` folder.

To run the script:
```bash
python graphs/sns_graphs.py
```

### Example Graphs:
- `distribution_prices.png`: Shows the distribution of product prices across categories.
- `discount_analysis.png`: Visualizes the percentage and size of discounts.
- `seasonality_sales.png`: Highlights seasonal trends and sales spikes during special dates.

## Insights and Recommendations
The analysis will provide:
- Clear categorization of products for better reporting.
- Data-driven insights into the effectiveness of discounts and seasonal promotions.
- Suggestions for improving data collection to enhance future analyses.

Data cleaning and analysis were conducted using Google Colab, with datasets seamlessly integrated from Google Drive.

## Requirements
- Python 3.8+
- Required Python Libraries:
  - pandas
  - numpy
  - seaborn
  - matplotlib

Install dependencies using:
```bash
pip install -r requirements.txt
```

## How to Use
1. Clone this repository:
   ```bash
   git clone <repository_url>
   ```
2. Navigate to the project folder:
   ```bash
   cd eniac-ecommerce-analysis
   ```
3. Run the scripts for data cleaning and graph generation as outlined above.

## Future Enhancements
- Automating seasonal trend detection.
- Integrating external datasets for broader context (e.g., competitor pricing).
- Creating an interactive dashboard for stakeholders to explore the data in real-time.

