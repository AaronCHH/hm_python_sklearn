# Python_sklearn
## Book Chapter
* Python資料科學自學聖經_碁峰 Ch8, Ch9

## Books


----
## Common
```python
from sklearn.linear_model import LinearRegression
lm = LinearRegression()
lm.fit(df_X, df_y)  
```
```python
from sklearn.neighbors import KNeighborsClassifier
k = 1
knn = KNeighborsClassifier(n_neighbors=k)
knn.fit(X_train, y_train)
```
```python
from sklearn.cluster import KMeans
k = 1
km = KMeans(n_clusters=k)
km.fit(df_X)
```
## Books
* [scikit-learn 新手的晉級](https://www.packtpub.com/product/mastering-machine-learning-with-scikit-learn-second-edition/9781788299879)

## Issue
* [ModuleNotFoundError: No module named ‘sklearn.externals.six‘](https://blog.csdn.net/hyluglare/article/details/107340470)
```bash==
pip install six
from six import StringIO
```
* inputer
```python=
# old
from sklearn import preprocessing
imputer = preprocessing.Imputer()
# new
from sklearn.impute import SimpleImputer
imputer = SimpleImputer()
```


###### tags: `sklearn` `scikit learn` `python`