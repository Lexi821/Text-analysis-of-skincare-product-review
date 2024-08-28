# Text analysis of skincare products review

## Table of Contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Methodology](#methodology)
- [Data Analysis](#data-analysis)
- [Visualization](#visualization)
- [Results](#results)
- [Recommendations](#recommendations)

### Project Overview
---

The primary objective of this project is to analyze the efficacy of various acne treatments by examining their semantic associations with positive skin health outcomes, such as reduced scarring, smoother skin, and overall skin health improvement. The goal is to identify which treatments are most closely related to desirable outcomes, providing insights that can inform product recommendations and treatment strategies.



### Data Sources

The analysis in this report is based on a dataset of skincare reviews from Ulta Beauty, available on Kaggle (https://www.kaggle.com/datasets/nenamalikah/nlp-ulta-skincare-reviews/data). The data includes detailed customer feedback, product names, and brands, verified purchase status, and user engagement metrics such as upvotes and downvotes. Data was originally sourced from Ulta's online platform on March 27, 2023 and is accompanied by visual content from Jocelyn Morales on Unsplash.

### Methodology

Similarity scores were calculated using a Word2Vec model trained on skincare product reviews, representing the semantic proximity between the word "acne" and words representing the skin health outcomes. The treatments were then combined with "acne" to create new vectors, and the similarity to the desired outcomes was measured. A baseline was established using the similarity scores directly associated with "acne."

### Data Analysis

<img src="/imgages/picture1.png">
<img src="https://github.com/Lexi821/final_project_2M_cis467/blob/main/final_project_2M_cis467/Dashboard%202.png">
<img src="https://github.com/Lexi821/final_project_2M_cis467/blob/main/final_project_2M_cis467/Dashboard%202.png">
<img src="https://github.com/Lexi821/final_project_2M_cis467/blob/main/final_project_2M_cis467/Dashboard%202.png">


### Visualization

<img src="https://github.com/Lexi821/final_project_2M_cis467/blob/main/final_project_2M_cis467/Dashboard%202.png">

### Results

The analysis results are summarized as follows:
1. The company's sales are relatively stable, with a noticeable peak during the holiday season(Dec, Jan).
2. "Dairy products" is the best-performing category in terms of sales, quantity and number of customers.
3. The United States has the highest sales among all regions.

### Recommendations

Based on the analysis, we recommend the following actions:
- Invest in marketing and promotions during peak sales seasons to maximize revenue.
- Focus on expanding and promoting products in Dairy products.
- focus on the U.S. market and increase promotion of high-selling products in this region, such as beverages and meat..




