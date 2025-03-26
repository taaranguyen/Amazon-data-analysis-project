**📊 Amazon Data Analysis Project**

This Python project analyzes a dataset from Kaggle, focusing on Amazon sales data to uncover insights regarding discounts, ratings, customer feedback, and product performance across different categories. The project aims to explore various factors influencing customer satisfaction, sales growth, and the effectiveness of promotional strategies.



**📑 Table of Contents**

Project Overview

Data Overview

Goals of the Analysis

Technologies Used

Key Findings

Getting Started

Usage Instructions

License

Contributing



**📊 Project Overview**

This project uses the Amazon Sales Dataset from Kaggle to analyze relationships between product discounts, ratings, and sales performance. It also evaluates common feedback for products based on their rating levels and sales figures. The goal is to provide actionable insights and recommendations that can improve product performance, sales, and customer satisfaction.



**🗂️ Data Overview**

The dataset contains information about various Amazon products and customer reviews. The key features include:

- Product ID 🆔: A unique identifier for each product.

- Product Name 📛: The name of the product.

- Product Category 🏷️: The category or type of the product (e.g., electronics, clothing, etc.).

- Discounted Price 💲: The price of the product after applying any discount.

- Actual Price 💵: The original price of the product before any discounts.

- Discount Percentage 📉: The percentage discount applied to the original price.

- Product Rating ⭐: The average customer rating of the product (from 1 to 5).

- Rating Count / Sales Volume 🔢: The total number of ratings or sales volume for the product.

- User ID 🆔: A unique identifier for each customer who left a review.

- User Name 👤: The name of the customer who left a review.

- Review ID 🆔: A unique identifier for each product review.

- Review Title 📝: The title of the customer's review.

- Review Content 💬: The content or body of the customer's review.

- Image Link 🌐: A link to an image associated with the product (if available).

- Product Link 🔗: A link to the product page on Amazon.



**🎯 Goals of the Analysis**

The project focuses on the following key analyses:

- **Discounts vs Ratings Analysis:** Exploring the relationship between discount levels and product ratings. 💸📊

- **Discounted Prices vs Ratings:** Exploring the relationship between discounted prices on customer ratings. 🏷️➡️⭐

- **Feedback in High Discount, Low-Rated Products:** Identifying the most common feedback for products with high discounts but low ratings. 🔴💬

- **Feedback in High-Ticket, High-Rated, High Sales Products:** Analyzing the feedback for expensive products with high ratings and high sales. 💎⭐📈

- **Feedback in High-Ticket, Low-Rated, Low Sales Products:** Investigating the feedback for expensive products with low ratings and low sales. 💎🔴📉

- **Average Discount and Rating Across Categories:** Analyzing the average discount percentage and average rating level across different categories. 📊🏷️⭐

- **Average Discount and Total Sales Across Categories:** Investigating the relationship between average discount percentages and total sales across categories. 💲📈

- **Categories with High Sales and High Discount Percentages:** Identifying categories with the most sales and the highest discount percentages, and analyzing their best- and least-selling products. 🏆💸

- **Feedback in Low-Rated Products:** Identifying the most common feedback for products with low ratings. 🔴💬



**🛠️ Technologies Used**

This project was developed using the following Python libraries:

- **pandas**: For data manipulation and analysis. 📊

- **numpy**: For numerical operations. 🔢

- **matplotlib**: For data visualization and plotting graphs. 📈

- **seaborn**: For advanced statistical visualizations. 📉

- **collections**: For handling and organizing data efficiently. 🗂️

- **wordcloud**: For visualizing common feedback and word frequency. 🌫️

- **nltk.corpus**: For natural language processing tasks, including sentiment analysis and feedback analysis. 📝



**🔑 Key Findings**

Some key insights from the analysis include:

1. **Relationship between Discounts and Ratings:** There is a slight tendency for higher-rated products to be offered at higher discounts, although the relationship is not strong enough to establish a definitive pattern. 💸⭐

2. **Other Factors Impacting Ratings Besides Discounts:** Apart from discounts, factors such as unreliable product quality and malfunctioning items significantly impact customer ratings. These issues are often highlighted in lower-rated products. 🛑🔴

3. **Primary Drivers of Growth in Sales and Customer Satisfaction of High-Ticket Products:** The primary determinants for driving growth in high-ticket products include a combination of budget-friendly prices and high-quality products, which significantly contribute to both sales performance and customer satisfaction. 💎⭐

4. **Most Beneficial Categories from Discount Promotion:** Certain product categories benefit the most from discount promotions. Within these categories, the top 10 best-selling products outperform the least-selling products, both in terms of sales volume and customer ratings. 🏆💸

5. **Frequent Concerns in Low-Rated Products:** Common concerns expressed in low-rated products often include issues related to product quality, defects, and unmet customer expectations. These concerns are frequently mentioned in reviews. 🔴💬

**💡 Recommendations:**
- Improve Revenue and Rating in Underperforming Products: Focus on improving the performance of underperforming products by addressing the issues identified in low-rated reviews, particularly product quality and reliability. 🛠️💡

- Leverage Promotional Strategies for High-Rated Products: Utilize promotional strategies to further enhance the performance of high-rated products, capitalizing on their already positive customer feedback. 🚀⭐



**🚀 Getting Started**

**📜 Prerequisites**
To run this project, you'll need Python installed along with the following libraries:

- pandas 📊

- numpy 🔢

- matplotlib 📈

- seaborn 📉

- collections 🗂️

- wordcloud 🌫️

- nltk 📝

You can install these dependencies using pip:

_pip install pandas numpy matplotlib seaborn wordcloud nltk_

**📂 Dataset**

The dataset used in this project is available on Kaggle. Download the dataset and place it in the project directory to proceed with the analysis.


**📝 Usage Instructions**

1. Clone the repository to your local machine:

_git clone https://github.com/taaranguyen/Amazon-data-analysis-project.git_

2. Navigate to the project directory:

_cd Amazon-data-analysis-project_

3. Make sure to place the downloaded dataset in the appropriate folder (e.g., /data).

4. Run the analysis script:

_python analysis_script.py_

5. The results and visualizations will be generated, and you can review them in the output files or directly in the notebook.


**📄 License**

This project is licensed under the MIT License - see the LICENSE file for details.


**🤝 Contributing**

Contributions are welcome! If you'd like to contribute to this project, feel free to fork the repository, make changes, and submit pull requests with improvements or bug fixes.
