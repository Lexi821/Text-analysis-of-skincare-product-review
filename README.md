# Text analysis of skincare products review

## Table of Contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Methodology](#methodology)
- [Data Analysis](#data-analysis)
- [Visualization](#visualization)
- [Results](#results)
- [Recommendations](#recommendations)
---

### Project Overview

The primary objective of this project is to analyze the efficacy of various acne treatments by examining their semantic associations with positive skin health outcomes, such as reduced scarring, smoother skin, and overall skin health improvement. The goal is to identify which treatments are most closely related to desirable outcomes, providing insights that can inform product recommendations and treatment strategies.



### Data Sources

The analysis in this report is based on a dataset of skincare reviews from Ulta Beauty, available on Kaggle (https://www.kaggle.com/datasets/nenamalikah/nlp-ulta-skincare-reviews/data). The data includes detailed customer feedback, product names, and brands, verified purchase status, and user engagement metrics such as upvotes and downvotes. Data was originally sourced from Ulta's online platform on March 27, 2023 and is accompanied by visual content from Jocelyn Morales on Unsplash.

### Methodology

Similarity scores were calculated using a Word2Vec model trained on skincare product reviews, representing the semantic proximity between the word "acne" and words representing the skin health outcomes. The treatments were then combined with "acne" to create new vectors, and the similarity to the desired outcomes was measured. A baseline was established using the similarity scores directly associated with "acne."

### Data Analysis

![Data Analysis](/images/Picture1.png)
<img src="/images/Picture2.png">
<img src="/images/Picture3.png">
<img src="/images/Picture4.png">
<img src="/images/Picture5.png">



### Visualization

Embedding projector:

<img src="/images/projector1.png">
<img src="/images/projector2.png">


### Results

The baseline scores are the similarity between vector(acne) and three outcome parameters. The baseline scores were as follows:
Healthy: 0.021453; Scar: 0.550615; Smooth: 0.182928
The following are the scores for each treatment compared to the baseline:
|Treatment|	Healthy	|Scar	|Smooth|
|---|---|---|---|
|Baseline(acne)|	0.021453235|	0.55061525	|0.18292814|
|Lactic	|0.05534291|	0.4666556|	0.21564613|
|Salicylic|	0.106446415	|0.53010076	|0.21828108|
|Vitamin|	0.06563923	|0.47145757	|0.2952657|
|Herbal| 	0.18950157|	0.37556463|	0.23659256|

### Recommendations

Herbal Remedies may offer the most comprehensive benefits across the measured skin health outcomes while all treatments offer some improvement over untreated acne. For smoother skin: Consider Vitamin Treatments as a potential primary recommendation. For a broad treatment strategy: Herbal Remedies could be recommended due to their strong association with positive outcomes across all categories.


