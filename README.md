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
The EDA revealed several key insights and produced various visualizations to illustrate the data's characteristics. Some of the highlights include:
**Product Preference by Gender and Marital Status**:

![Screenshot 2025-06-20 160555](https://github.com/user-attachments/assets/e1198183-9242-4bf3-8243-15bbf6135265)







The KP781 treadmill is the most popular product overall. Males and partnered individuals tend to purchase the KP781 more frequently. KP281 is preferred by females and is a more affordable entry-level option.

**Fitness and Usage Influence Purchase**:




![Screenshot 2025-06-20 171256](https://github.com/user-attachments/assets/b3054bca-3a73-4685-b100-5333f1be647b)






Customers with higher fitness levels and usage frequency tend to purchase the advanced KP781. The KP481 is often chosen by customers with moderate fitness levels. Consider promoting the KP281 to less frequent users, positioning it as an initiation to a healthier lifestyle.

**Income's Impact on Product Choice**:

High-income earners favor the KP781, validating its premium positioning. Customers with lower incomes are more likely to purchase the KP281 or KP481. Offer targeted promotions or financing options for the more expensive models to customers with moderate incomes.

**Miles and Fitness Correlation**:

There's a strong correlation between miles run and fitness level. Customers aiming for longer distances prefer the KP781, highlighting its ability to support demanding workouts. Consider emphasizing this feature in marketing materials for the KP781.

**Age Demographics**:

The majority of customers are between 20 and 30 years old. Consider tailoring marketing campaigns to this age group, leveraging popular social media platforms. Explore ways to attract older demographics by highlighting the benefits of treadmills for maintaining health and fitness.

**Education Level**:

There's a positive correlation between education level and product purchase. Tailor marketing messaging to resonate with customers who value quality and innovation (KP781).

## 5. How to Run the Code
To run this analysis, you will need access to the dataset and a Google Colab environment.
1. **Open the Google Colab Notebook:** Open the Python notebook containing the code.
2. **Mount Google Drive:** Run the cell that mounts Google Drive (`from google.colab import drive` and `drive.mount("/content/drive")`) and follow the prompts to authenticate and allow access.
3. **Ensure Dataset Location:** Make sure the dataset file (`aerofit_treadmill_data (2).csv`) is located at the specified path (`/content/drive/MyDrive/Colab Notebooks/EDA/aerofit_treadmill_data (2).csv`) within your Google Drive. If not, update the path in the code.
4. **Run All Cells:** Execute the code cells sequentially or use the "Run all" option to run the entire notebook. The output, including visualizations, will be displayed within the notebook.
