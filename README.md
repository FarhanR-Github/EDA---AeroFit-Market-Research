# EDA---AeroFit-Market-Research

## 1. Project Overview
This project performs an Exploratory Data Analysis (EDA) on the Aerofit treadmill dataset. The goal is to understand the dataset's structure, identify patterns and trends, visualize relationships between variables, and extract actionable insights for improving marketing and sales strategies for Aerofit products.

## 2. Dataset Source
The dataset used in this analysis is named `aerofit_treadmill_data (2).csv`. It was loaded directly from a Google Drive location within the Google Colab environment.

## 3. Tools/Libraries Used
The analysis was conducted using Python in a Google Colab notebook. The following libraries were utilized:
- **pandas**: For data manipulation and analysis.
- **numpy**: For numerical operations.
- **matplotlib.pyplot**: For creating static, interactive, and animated visualizations.
- **seaborn**: For creating informative statistical graphics.
- **IPython**: For display functionalities within the notebook.
- **google.colab**: For mounting Google Drive to access the dataset.

## 4. Key Findings and Visualizations
**Product Preference by Gender and Marital Status**:

![Screenshot 2025-06-20 160555](https://github.com/user-attachments/assets/e1198183-9242-4bf3-8243-15bbf6135265)













The EDA revealed several key insights and produced various visualizations to illustrate the data's characteristics. Some of the highlights include:
- **Data Structure and Summary:** Initial inspection of the data types, missing values, and summary statistics.
- **Value Counts:** Analysis of the distribution of categorical variables like 'Product', 'Gender', and 'MaritalStatus'.
- **Distribution Plots:** Visualizations of the distribution of numerical features like 'Age', 'Education', 'Usage', 'Fitness', 'Income', and 'Miles' using histograms with KDE.
- **Count Plots:** Graphical representation of the frequency of occurrences within binned numerical features ('Age', 'Education', 'Usage', 'Income', 'Miles') and categorical features ('Product', 'Gender', 'MaritalStatus').
- **Box Plots:** Visualization of the spread and potential outliers in numerical features.
- **Bivariate Analysis:** Exploration of the relationship between 'Product' and other features like 'Gender', 'MaritalStatus', and 'Age' through count plots.
- **Multivariate Analysis:** A pair plot to visualize relationships between multiple numerical variables.
- **Correlation Analysis:** A heatmap showing the correlation matrix of the numerical features, highlighting strong, moderate, and weak correlations.
- **Outlier Detection:** Identification of potential outliers in numerical features using the IQR method.
- **Conditional Probabilities:** Calculation of various conditional probabilities to understand the likelihood of certain events (e.g., percentage of female customers purchasing a specific product).

The report section in the notebook provides a detailed summary of the actionable insights and recommendations based on the findings.

## 5. How to Run the Code
To run this analysis, you will need access to the dataset and a Google Colab environment.
1. **Open the Google Colab Notebook:** Open the Python notebook containing the code.
2. **Mount Google Drive:** Run the cell that mounts Google Drive (`from google.colab import drive` and `drive.mount("/content/drive")`) and follow the prompts to authenticate and allow access.
3. **Ensure Dataset Location:** Make sure the dataset file (`aerofit_treadmill_data (2).csv`) is located at the specified path (`/content/drive/MyDrive/Colab Notebooks/EDA/aerofit_treadmill_data (2).csv`) within your Google Drive. If not, update the path in the code.
4. **Run All Cells:** Execute the code cells sequentially or use the "Run all" option to run the entire notebook. The output, including visualizations, will be displayed within the notebook.
