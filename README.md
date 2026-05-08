# Customer Personality Analysis
 
> Segment customers using machine learning and turn raw behavioral data into actionable marketing intelligence.
 
---
 
## Overview
 
This project analyzes a real-world marketing dataset to perform **customer personality analysis** — a technique used to understand the distinct behavioral and demographic profiles within a customer base. By applying unsupervised machine learning (clustering), the project identifies meaningful customer segments and surfaces actionable insights that can inform targeted marketing strategies.
 
---
 
## Objectives
 
- Clean and preprocess raw customer data for analysis
- Apply machine learning techniques to segment the customer base
- Profile each customer segment by key characteristics
- Provide actionable business insights derived from the segmentation
---
 
## Repository Structure
 
```
customer-personality/
│
├── Learner_Fullcode.ipynb       # Full analysis notebook (data prep → modeling → insights)
├── Project_1_Full_Code.html     # Rendered HTML export of the notebook
└── marketing_campaign.csv       # Source dataset containing customer attributes
```
 
---
 
## Dataset
 
The dataset (`marketing_campaign.csv`) contains customer records from a marketing campaign, including:
 
- **Demographics** — age, education, marital status, household size
- **Purchase behavior** — spending across product categories (wine, meat, fish, etc.)
- **Campaign response** — responses to previous marketing campaigns
- **Channel usage** — web, catalog, and in-store purchases
---
 
## Methodology
 
1. **Exploratory Data Analysis (EDA)** — Understand distributions, detect outliers, and identify missing values
2. **Feature Engineering** — Derive meaningful features (e.g., total spend, customer tenure, family size)
3. **Preprocessing** — Scale features and encode categorical variables
4. **Dimensionality Reduction** — Apply PCA to reduce feature space for visualization and clustering
5. **Clustering** — Use K-Means (or similar) to identify distinct customer groups
6. **Segment Profiling** — Characterize each cluster by demographic and behavioral traits
7. **Insights & Recommendations** — Translate findings into marketing action items
---
 
## Technologies Used
 
| Tool | Purpose |
|------|---------|
| Python | Core programming language |
| Pandas / NumPy | Data manipulation |
| Scikit-learn | Machine learning (PCA, K-Means) |
| Matplotlib / Seaborn | Data visualization |
| Jupyter Notebook | Interactive analysis environment |
 
---
 
## Getting Started
 
### Prerequisites
 
```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
```
 
### Running the Notebook
 
```bash
git clone https://github.com/epruitt/customer-personality.git
cd customer-personality
jupyter notebook Learner_Fullcode.ipynb
```
 
Alternatively, open `Project_1_Full_Code.html` in any browser to view the fully rendered analysis without running any code.
 
---
 
## Key Takeaways
 
Each customer segment discovered by the model represents a distinct personality type with unique spending habits, responsiveness to campaigns, and preferred purchase channels. These profiles enable marketing teams to:
 
- **Personalize** campaigns for high-value vs. budget-conscious customers
- **Optimize** channel spend based on where each segment shops
- **Improve** campaign conversion rates by targeting the right message to the right group
---
 
## Author
 
**epruitt** — [github.com/epruitt](https://github.com/epruitt)
