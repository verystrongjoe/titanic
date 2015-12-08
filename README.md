# titanic
Sunday Study Material 




Titanic Survival Prediction
 
Prerequisite

[Degrees of freedom](https://en.wikipedia.org/wiki/Degrees_of_freedom_(statistics))
 : In statistics, the number of degrees of freedom is the number of values in the final calculation of a statistic that are free to vary.[1]
The number of independent ways by which a dynamic system can move, without violating any constraint imposed on it, is called number of degrees of freedom. In other words, the number of degrees of freedom can be defined as the minimum number of independent coordinates that can specify the position of the system completely.
 : 본자료 중 모집단에 대한 정보를 주는 독립적인 자료의 수 , http://www.statedu.com/term/7334

degree of freedom  : 주어진 조건에서 자유롭게 뽑을 수 있는 수
모집단이 아닌 표본에서 주로 쓴다.

표본분산에서 자유도 n-1로 나눠주는 경우?
http://dain.tistory.com/317
마지막 표본은 모집단의 수치에 맞추기 위해서 정해진 값을 뽑아야한다. 그래서 주어진 조건에서 자유롭게 뽑을 수 있는 수 마지막 표본은 자유롭게 못뽑는다.



 cross-classification  
   :  classification according to more than one attribute at the same time; "the cross-classification of cases was done by age and sex"
  
 (Mean, Median, Mode, and Range) [http://www.purplemath.com/modules/meanmode.htm]
    : The "mean" is the "average" you're used to, where you add up all the numbers and then divide by the number of numbers. The "median" is the "middle" value in the list of numbers The "mode" is the value that occurs most often. If no number is repeated, then there is no mode for the list.

 predictive modeling  -> [caret package](https://cran.r-project.org/web/packages/caret/index.html)

http://www.investopedia.com/terms/stratified_random_sampling.asp

provides a unified interface for modeling & prediction, and streamlines the model tuning process using resampling.

The package includes a createDataPartition function for splitting data into a training set and a test set (sometimes referred to as a validation set) via stratified random sampling. In this presentation, Kuhn delivered the best explanation I've seen of the decision on how to "spend" the available training data. His conclusion:

Statistically, the best course of action would be to use all the data for model building and use statistical methods to get good estimates of error. From a non-statistical perspective, many consumers of these models emphasize the need for an untouched set of samples to evaluate performance.


 
 
 r module to be installed
install.packages('Amelia');
install.packages("corrgram");
install.packages("Hmisc");
install.packages("caret")








Reference 
Story - http://trevorstephens.com/post/72916401642/titanic-getting-started-with-r
R Code - https://github.com/wehrley/wehrley.github.io/blob/master/SOUPTONUTS.md



bystats {Hmisc} R Documentation
Statistics by Categories

Description

For any number of cross-classification variables, bystats returns a matrix with the sample size, number missing y, and fun(non-missing y), with the cross-classifications designated by rows. Uses Harrell's modification of the interaction function to produce cross-classifications. The default fun is mean, and if y is binary, the mean is labeled as Fraction. There is a print method as well as a latex method for objects created by bystats. bystats2 handles the special case in which there are 2 classifcation variables, and places the first one in rows and the second in columns. The print method for bystats2 uses the print.char.matrix function to organize statistics for cells into boxes.

Usage