# Decision Tree Regressor

If the o/p is continuous then

1.Calculate the mean and std for all dataset.

2. Calculate mean and std for unique values in each feature.

3. Take STD and instances belongs that feature and calculate weighted std.

4. Subtract std for total dataset - calculate weighted std

5. Construct tree as same as the classification . Take root node which has highest std.

![Alt text](https://github.com/srirampamerla/Decision-Trees/blob/main/decr.png?raw=true)
![Alt text](https://github.com/srirampamerla/Decision-Trees/blob/main/decr2.png?raw=true)
![Alt text](https://github.com/srirampamerla/Decision-Trees/blob/main/decr3.png?raw=true)
![Alt text](https://github.com/srirampamerla/Decision-Trees/blob/main/decr4.png?raw=true)



If the features are continuous then

1. calculate the split point where target class changes from one state to another

2. For that split point calculate entropy and gain. for ex split point is 2.0(we need take <=2.0 and >2.0). In each condition check both + and -ve. Please refer the ss.

![Alt text](https://github.com/srirampamerla/Decision-Trees/blob/main/decr5.jpg?raw=true)
