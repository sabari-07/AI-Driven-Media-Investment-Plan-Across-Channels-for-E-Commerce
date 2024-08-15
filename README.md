AI-Driven Media Investment Plan Across Channels for E-commerce
Introduction
This project was developed as part of a hackathon challenge aimed at creating an AI-driven media investment plan for e-commerce businesses. The primary goal is to optimize budget allocation across various paid media channels to maximize customer acquisition and conversion rates. By analyzing customer journey data and ad spend data, we used machine learning techniques to identify trends, patterns, and the influence of different channels at various stages of the customer journey. Based on these insights, the solution reallocates the budget across channels to achieve the highest conversions within a specified budget.

Problem Statement
In today's competitive digital marketing landscape, e-commerce businesses must continuously optimize their media investments. Understanding the performance of different ad channels at each stage of the customer journey is essential for effective budget allocation. This AI-driven solution provides deeper insights into customer behavior, enabling businesses to make data-driven decisions that enhance customer acquisition, increase conversion rates, and improve ROI on marketing spend.

Solution Approach
Our solution involves the following key steps:

Data Collection and Processing:

Collected customer interaction data across various channels, including customer IDs, channel sources (e.g., Google Paid, Meta, Email, Direct), ad campaign types, timestamps, and touchpoint types (e.g., purchase, landing).
Collected ad spend data, including the date, channel, campaign type, amount spent, impressions, clicks, conversions, and revenue.
Processed and cleaned the data for analysis.
Machine Learning Analysis:

Applied machine learning techniques to identify trends and patterns in channel performance at different stages of the customer journey.
Analyzed the influence of various channels on downstream customer behavior, determining which channels are most effective at initiating and closing conversions.
Budget Reallocation:

Developed a media investment plan that reallocates budgets across channels to maximize customer acquisition and conversion rates.
Ensured that all paid media channels receive at least 10% of the total allocated budget and that each campaign type under a paid media channel is allocated a portion of the budget.
Tech Stack
Python: The primary programming language used.
Libraries:
Pandas (v1.3.3)
Scikit-learn (v0.24.2)
Jupyter Notebook: Used for code development and documentation.
Installation
To run this project, follow these steps:

Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/ai-driven-media-investment-plan.git
cd ai-driven-media-investment-plan
Install the required libraries:

bash
Copy code
%pip install pandas==1.3.3
%pip install scikit-learn==0.24.2
Open the Jupyter Notebook:

bash
Copy code
jupyter notebook
Usage
Input Section: The notebook allows you to input a new budget amount and select a dataset for analysis.
Data Processing: The notebook details the data cleaning and preprocessing steps.
Algorithm: The notebook implements the machine learning model used for budget allocation and provides the logic behind the allocation process.
Results: The final section provides the results, including budget allocation across channels and estimated conversions.
Results
Example Output
Input Budget: $200,000
Output:
Google Ads: $60,000
Facebook: $50,000
Bing/Microsoft Ads: $30,000
Others: $60,000
Visualizations of the budget allocation are provided within the notebook.

Conclusion
The AI-driven media investment plan effectively reallocates budgets across various paid channels to maximize customer acquisition and conversion rates. Future work could involve refining the machine learning models and expanding the solution to incorporate more granular data.



