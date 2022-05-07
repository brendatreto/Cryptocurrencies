# Cryptocurrencies

## Analysis Overview
The purpose was to use unsupervised machine learning to analyze cryptocurrencies and create reports based on their features

## Resources
- Data: crypto_data.csv
- Software: Python 3.7, Anaconda Navigator, Jupyter Notebook

## Results
After preprocessing the data we used the Elbow Curve to determine the number of clusters to use. 

![elbow_curve](https://user-images.githubusercontent.com/22451540/167230721-9d60aeee-0fe9-4c90-b71e-0c0fbcff1c2f.PNG)


We also used the Principal Component Analysis to reduce the number of dimensions, which can be visualized in the following plot.

![Pca](https://user-images.githubusercontent.com/22451540/167230825-5ea55c81-3b49-4087-9b16-0fb159c61acc.PNG)


Finally we used a scatter plot to reduce the information to two princiapl components

![scatter](https://user-images.githubusercontent.com/22451540/167230875-848a63e1-26eb-4570-a224-64386be4031c.PNG)


## Summary
After this process, we can say that there needs to be more analysis to determine the performance of each of this classes in order to make informed decisions. However, it will be much easier to do now that we now how to group them.
