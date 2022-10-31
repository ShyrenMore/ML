### **Machine Learning Practicals**

- [Simple Linear Regr](linear_reg.ipynb)
- [Multiple Linear Regr](multiple_reg.ipynb)
- [Logistic Regr (Built-in)](logistic_regr_builtin.ipynb)
- [Decision Tree](decision_tree.ipynb)
- [Support vector Machine](svm.ipynb)
- [Ensemble method - Bagging](ensemble.ipynb)
- [Principle Component Analysis](pca.ipynb)

### **Pre-proceesing**

**For words to numbers**

```
from sklearn.preprocessing import LabelEncoder, OrdinalEncoder

le = LabelEncoder()
oe = OrdinalEncoder()

dataset['Gender'] = le.fit_transform(dataset['Gender'])

oe = OrdinalEncoder(categories=[['First Owner','Second Owner', 'Fourth & Above Owner','Third Owner','Test Drive Car']])
```

**For scaling**

```
from sklearn.preprocessing import StandardScaler
scaler = StandardScaler()
X_scaled = scaler.fit_transform(X)

```