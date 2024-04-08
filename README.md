## Watch Screen Design A/B Testing Project

### Overview
The watch company is conducting a study to enhance its sales by investigating a new watch screen design. This project aims to evaluate the effectiveness of the new design (Design B) compared to the existing design (Design A) through A/B testing.

### Dataset Features
- **Campaign Name:** Identifies each advertising campaign.
- **Date:** Records the date of each entry, providing a temporal dimension.
- **Spend:** Reflects the investment in each campaign (in dollars).
- **Impressions and Reach:** Measure visibility and unique impressions achieved by the ads.
- **Website Clicks, Searches, View Content, Add to Cart, Purchase:** Capture user interactions during the campaigns, providing insights into engagement and conversion.

### Hypothesis
- **Null Hypothesis (H0):** The new watch screen design (Design B) does not significantly improve marketing campaign performance, measured by user engagement and sales metrics, compared to the existing design (Design A).
- **Alternative Hypothesis (H1):** The new watch screen design (Design B) surpasses the existing design (Design A), leading to a noticeable enhancement in user engagement and sales metrics in marketing campaigns.

### Methodology
To determine the more effective watch screen design for enhancing sales and engagement, an A/B test was conducted. The detailed analysis can be found in the accompanying ipynb file. The resulting analysis aimed to guide the company in determining how to showcase its watches, thus shaping future marketing strategies.

### Analysis Results
Upon analyzing the data, it was found that:
- There were no significant differences between the two designs when using "purchase number" as the metric.
- In terms of cost, the control group (Design A) outperformed the test group (Design B).
- The test group did not show statistical significance in improving marketing campaign performance concerning conversion rate and cost per click.
- Notably, the analysis indicated a negative t-statistic with a p-value smaller than 0.05 for click-through rate, suggesting a significant difference between the groups, with the test group exhibiting lower values.
- Overall, the test group did not demonstrate benefits across all measured metrics; in fact, it increased costs and decreased click-through rate.

### Conclusion
Based on the analysis results, it can be concluded that the new watch screen design (Design B) did not outperform the existing design (Design A) in terms of enhancing sales and engagement. Further optimizations may be required to improve the effectiveness of the new design in future marketing campaigns.
