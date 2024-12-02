# Decision-Trees

Leaf node reaches(pure Spilt). If not Impure split

Classification

# Entropy and Gain

1.Calculate entropy for total dataset

2. Calculate entropy for each unique value in feature.

3. Calculate Gain

Calculate for all the features. Take the highest Gain as Root node and construct tree. if y values all belongs to one category we can declare the leafnode. if not calculate again entropy and gain and after filter of data.

![Alt text](https://github.com/srirampamerla/Decision-Trees/blob/main/dec1.png?raw=true)
![Alt text](https://github.com/srirampamerla/Decision-Trees/blob/main/dec2.pdf.png?raw=true)

# Gini

1.Calculate gini for total dataset

2. Calculate gini for each unique value in feature.

3. Calculate weighted avg for each feature

Calculate for all the features. Take the lowest gini index from weighted avg as Root node and construct tree. if y values all belongs to one category we can declare the leafnode. if not calculate again entropy and gain and after filter of data.

![Alt text](https://github.com/srirampamerla/Decision-Trees/blob/main/gini1.png?raw=true)

![Alt text](https://github.com/srirampamerla/Decision-Trees/blob/main/gini2.png?raw=true)

![Alt text](https://github.com/srirampamerla/Decision-Trees/blob/main/gini3.png?raw=true)


If the data set is less features we can use entropy& gain-- Takes more time

If the data set is more features we can use gini index
