# MCDonald_Market_Segmentation
     This project applies unsupervised machine learning techniques to perform market segmentation on McDonald's customer survey data. Using Principal Component Analysis (PCA) and K-Means clustering, we identify distinct customer groups based on their preferences, satisfaction, and behavior.

     # 🍔 McDonald's Customer Segmentation using Machine Learning

This project applies machine learning techniques to segment McDonald's customers based on their feedback and preferences. By identifying distinct customer groups, the goal is to provide actionable insights that can support personalized marketing strategies and improved customer service.

---

## 📌 Project Objectives

- Segment McDonald's customers based on survey responses.
- Identify key characteristics of each customer group.
- Enable targeted marketing and service improvements using data-driven insights.

---

## 🧠 Machine Learning Techniques Used

- **Principal Component Analysis (PCA)**: For dimensionality reduction while preserving variance in the data.
- **K-Means Clustering**: To group similar customers into distinct segments.

---

## 🛠 Tools & Technologies

- Python 🐍
- Jupyter Notebook 📓
- Pandas, NumPy
- Scikit-learn (PCA, KMeans)
- Matplotlib, Seaborn (for visualization)

---

## 📊 Project Workflow

1. **Data Preprocessing**
   - Cleaned and normalized customer feedback data.
   - standardized features.

2. **Dimensionality Reduction**
   - Applied PCA to reduce the feature space and improve clustering performance.

3. **Customer Clustering**
   - Used K-Means algorithm to group customers.
   - Determined optimal number of clusters using the Elbow Method.

4. **Cluster Profiling**
   - Analyzed each cluster's unique preferences and behaviors.
   - Labeled and visualized the segments for interpretation.

---

## 🧩 Customer Segments Identified (Example)

Cluster 0[“Convenience-Seeking Health-Conscious Women”]:
This segment primarily consists of females under the age of 44 who visit McDonald's frequently. They find the service convenient, and perceive the food as tasty,cheap and healthy.
   We can target this customers by advertizing more friendly services,Showcasing affordabily .This can help in preserving them.And we can make them as a primery Target.

Cluster 1[“Frugal but Health-Conscious Critics”]:
This segment includes the second least frequent visitors, generally over the age of 44. They find McDonald’s to be cheap, but also untasty and unhealthy.They are price-aware but highly critical of food quality and health impactConsider campaigns that emphasize healthier, cleaner options or menu transparencyPossibly difficult to convert unless significant brand and menu improvements are evident

Cluster 2[ “Busy Young Skeptics”]:
This group is mostly males under 44 who also visit often. However, they perceive the service as slow and the food as expensive.We can target them by Fast services and value deals.THey can be the secound target.

Cluster 3[“Disengaged Older Critics”]:
These are infrequent visitors, mostly males over 44. They find McDonald’s inconvenient, unhealthy, expensive, and even disgusting.
     Hard to convert; likely not a primary target. Focus on brand repair or skip this segment.


