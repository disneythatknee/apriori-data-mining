# apriori-data-mining

---


## 📝 Tasks, Skills & Insights

### **1. Apriori Algorithm for Frequent Itemsets**
- **Skills**: Python, efficient_apriori, mlxtend, pandas, matplotlib  
- Implemented the Apriori algorithm from scratch and compared results to mlxtend.  
- Visualized the top 50 frequent itemsets and association rules.  
- **Insights**:  
  - Grocery items like shrimp, avocado, and almonds appeared most frequently.  
  - Strong association rules showed cross-selling opportunities (e.g., customers buying burgers often purchased meatballs and eggs).  

---


### **2. Frequent Itemsets on Large Dataset**
- **Skills**: Disk-based Apriori implementation, big data handling (5GB+), performance analysis  
- Applied Apriori to a large dataset (5GB+), too big for memory.  
- Tested different minimum support thresholds to evaluate performance and itemset richness.  
- **Insights**:  
  - Lower thresholds → exponentially more itemsets, but higher runtime.  
  - Larger frequent itemsets appeared with lower thresholds, uncovering deeper associations but at greater computational cost.  

---


### **3. Frequent Itemsets on Additional Datasets**
- **Skills**: Apriori mining, comparative dataset analysis  
- Extended Apriori analysis to two additional datasets.  
- Compared frequent itemset sizes and runtime behavior across datasets.  
- **Insights**:  
  - Dense datasets yielded larger itemsets.  
  - Sparse datasets produced fewer associations, highlighting dataset structure sensitivity.  

---


### **4. Clustering with Frequent Itemsets**
- **Skills**: Clustering (KMeans, Agglomerative), unsupervised learning, cluster validation, visualization  
- Performed clustering on frequent itemset-transformed datasets.  
- **Datasets**:  
  - Banknote Authentication  
  - Vehicle Silhouettes  
- **Insights**:  
  - Banknote dataset → strong cluster separation (authentic vs forged notes).  
  - Vehicle silhouettes dataset → overlapping features reduced cluster purity, showing limitations of unsupervised methods.  

---


### **5. Advanced Analysis with UCI Datasets**
- **Skills**: Apriori on real-world datasets, association rule analysis, data visualization  
- Deepened analysis on Banknote Authentication dataset.  
- **Insights**:  
  - High-confidence rules linked variance and skewness to authenticity labels.  
  - Demonstrated Apriori’s applicability beyond synthetic retail datasets.  

---
