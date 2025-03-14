# Cluster Labels with Descriptions and Underlying Premises

Below are the cluster labels based on the combined insights from your mean/median statistics and SHAP analysis, along with the premises that support each label.

---

## Cluster 0 – Moderate Engagement / Mixed Success
**Premise:**  
- **Score:** Average performance (mean ≈ 71.6, median = 73)  
- **Engagement:** Moderate assessment completion (mean ≈ 0.83, median = 0.90) and moderate VLE clicks (mean ≈ 1796, median = 1312)  
- **SHAP Insight:** The moderate values in key features like assessment_completion_ratio indicate that these students do not strongly lean toward either passing or failing, resulting in mixed outcomes.

---

## Cluster 1 – High Engagement / High Success
**Premise:**  
- **Score:** Good performance (mean ≈ 78.3, median ≈ 79.5)  
- **Engagement:** High assessment completion (mean ≈ 0.93, median ≈ 0.92) and high VLE clicks (mean ≈ 2212, median ≈ 1912)  
- **SHAP Insight:** High values in these features push the prediction away from failure, leading to a very high pass rate among students.

---

## Cluster 2 – Good Performance with Lower VLE Engagement
**Premise:**  
- **Score:** Comparable performance (mean ≈ 78.4, median ≈ 80.3)  
- **Engagement:** Lower VLE clicks (mean ≈ 1217, median ≈ 696.5) and a slightly lower assessment completion_ratio (mean ≈ 0.79)  
- **SHAP Insight:** Despite the strong performance, the reduced online activity results in mixed predictive strength, indicating that while scores are high, engagement is lower.

---

## Cluster 3 – Very Low Engagement / High Failure
**Premise:**  
- **Score:** Extremely low performance (mean ≈ 2.38, median = 0)  
- **Engagement:** Nearly zero assessment completion (mean ≈ 0.025, median = 0) and very low VLE clicks (mean ≈ 97.5, median ≈ 29)  
- **SHAP Insight:** The near-zero engagement features drive the model to predict failure almost universally in this cluster.

---

## Cluster 4 – High Engagement / High Performance
**Premise:**  
- **Score:** High performance (mean ≈ 79.2, median ≈ 80.5)  
- **Engagement:** High assessment completion (mean ≈ 0.93, median ≈ 0.92) and high VLE clicks (mean ≈ 2522, median ≈ 2259)  
- **SHAP Insight:** Consistently high engagement features reliably push predictions away from failure, resulting in excellent outcomes.

---

## Cluster 5 – Exceptional Engagement / Top Performers
**Premise:**  
- **Score:** The highest performance (mean ≈ 83.8, median ≈ 85.9)  
- **Engagement:** Extremely high assessment completion (mean ≈ 1.18, median ≈ 0.92) and very high VLE clicks (mean ≈ 9061, median ≈ 8105)  
- **SHAP Insight:** The extreme levels of engagement and high scores strongly drive the model toward success, marking this cluster as top performers.

---

## Cluster 6 – Low Engagement / Consistent Failure
**Premise:**  
- **Score:** Lower performance (mean ≈ 65.4, median ≈ 66)  
- **Engagement:** Low assessment completion (mean ≈ 0.53, median ≈ 0.43) and low VLE clicks (mean ≈ 966, median ≈ 637)  
- **SHAP Insight:** The consistently low engagement features lead the model to predict failure, indicating a high risk in this cluster.

---

## Cluster 7 – Over-Achievers with High Completion
**Premise:**  
- **Score:** Moderate performance (mean ≈ 75.6, median ≈ 77.1)  
- **Engagement:** Exceptionally high assessment completion (mean ≈ 2.13, median ≈ 2.10) and high VLE clicks (mean ≈ 3401, median ≈ 3106)  
- **SHAP Insight:** Despite moderate scores, the outstanding completion ratios push the model toward predicting a pass, suggesting a group of over-achievers.

---

## Cluster 8 – Low Engagement / Underperforming (Distinct Module)
**Premise:**  
- **Code Module:** Distinct pattern (median ≈ 1)  
- **Score:** Relatively low performance (mean ≈ 66.2, median ≈ 67.7)  
- **Engagement:** Moderate-to-low assessment completion (mean ≈ 0.56,
 median ≈ 0.50) and low VLE clicks (mean ≈ 657.8, median ≈ 390.5)  
- **SHAP Insight:** The lower engagement features, combined with the distinct 
module context, contribute to a higher risk of failure in this cluster.

---

## Cluster 9 – High Success / Consistent Pass (Distinct Module)
**Premise:**  
- **Code Module:** Associated with a distinct module pattern (median ≈ 1)  
- **Score:** Good performance (mean ≈ 76.2, median ≈ 78.2)  
- **Engagement:** High assessment completion (mean ≈ 0.89, median ≈ 0.90) and moderate VLE clicks (mean ≈ 1286.7, median ≈ 973.5)  
- **SHAP Insight:** Despite the module context, the high engagement and robust scores push predictions toward consistent passing.

---
