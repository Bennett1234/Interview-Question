# DS Interview-Question
### 1 what is the difference between hard soft margin SVM?
Hard-margin: This assumes that data is very well behaved, and you can find a perfect clssifier which will have 0 error on train data.

Soft-margin: Data is usually not well behaved, so SVM hard margin may not have solution at all. So we allow for a little bit of error on some points. So the training error will not be 0, but average error over all points is minimized.
