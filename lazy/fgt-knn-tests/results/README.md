# [Stream Learning Research Project](https://github.com/dlcaio/research-project-stream-learning)

## Experiments' Results

### Parameteres used
* **k** = 3, 5
* **window_size** = 5000

### Artificial Datasets
### [SEA Concepts](https://github.com/vlosing/driftDatasets/tree/master/artificial/sea)

* 50000 instances
* Drift Properties:
	* Abrupt
	* Real
* 2 classes
* 3 features
### **k = 3**
![](sea-concepts-3.png)

### **k = 5**
![](sea-concepts-5.png)

### [Rotating Hyperplane](https://github.com/vlosing/driftDatasets/tree/master/artificial/hyperplane)

* 200000 instances
* Drift Properties:
	* Incremental
	* Real
* 2 classes
* 10 features

### **k = 3**
![](rotating-hyperplane-3.png)

### **k = 5**
![](rotating-hyperplane-5.png)

### [Interchanging RBF](https://github.com/vlosing/driftDatasets/tree/master/artificial/rbf) **[1]**

* 200000 instances
* Drift Properties:
	* Abrupt
	* Real
* 2 classes
* 10 features
### **k = 3**
![](interchanging-rbf-3.png)

### **k = 5**
![](interchanging-rbf-5.png)

### [Transient Chessboard](https://github.com/vlosing/driftDatasets/tree/master/artificial/chess) **[2]**

* 200000 instances
* Drift Properties:
	* Abrupt
	* Reoccurring
	* Virtual
* 8 classes
* 2 features
### **k = 3**
![](chessboard-3.png)

### **k = 5**
![](chessboard-5.png)

### [Mixed Drift](https://github.com/vlosing/driftDatasets/tree/master/artificial/mixedDrift) **[3]**

* 600000 instances
* Drift Properties:
	* Various
		* Real
		* Virtual
* 15 classes
* 2 features
### **k = 3**
![](mixed-drift-3.png)

### **k = 5**
![](mixed-drift-5.png)

---
### Real World Datasets

### [Weather](https://github.com/vlosing/driftDatasets/tree/master/realWorld/weather) ([original source](http://users.rowan.edu/~polikar/research/nse/))

* 18159 instances
* Drift Properties:
	* Virtual
* 2 classes
* 8 features
### **k = 3**
![](weather-3.png)

### **k = 5**
![](weather-5.png)

### [Poker Hand](https://github.com/vlosing/driftDatasets/tree/master/realWorld/poker) ([original source](https://archive.ics.uci.edu/ml/datasets/Poker+Hand))

* 829201 instances
* Drift Properties:
	* Virtual
* 10 classes
* 10 features
### **k = 3**
![](poker-3.png)

### **k = 5**
![](poker-5.png)



## References
**1, 2, 3.** V. Losing, B. Hammer and H. Wersing, "KNN Classifier with Self Adjusting Memory for Heterogeneous Concept Drift," 2016 IEEE 16th International Conference on Data Mining (ICDM), Barcelona, 2016, pp. 291-300, doi: 10.1109/ICDM.2016.0040.
