# Titanic Survival Prediction 

##Prerequisite
아래는 알아야될 키워드에 대한 간단한 정리

|Keyword|Description|
|----------|:-------------:|
| [Degrees of freedom](https://en.wikipedia.org/wiki/Degrees_of_freedom_(statistics)) | In statistics, the number of degrees of freedom is the number of values in the final calculation of a statistic that are free to vary.[1] The number of independent ways by which a dynamic system can move, without violating any constraint imposed on it, is called number of degrees of freedom. In other words, the number of degrees of freedom can be defined as the minimum number of independent coordinates that can specify the position of the system completely. 본자료 중 모집단에 대한 정보를 주는 독립적인 자료의 수 , http://www.statedu.com/term/7334 |
| degree of freedom  | 주어진 조건에서 자유롭게 뽑을 수 있는 수, 모집단이 아닌 표본에서 주로 쓴다. 표본분산에서 자유도 n-1로 나눠주는 경우에 대한 내용은 [여기](http://dain.tistory.com/317)를 참조 |
| cross-classification |  classification according to more than one attribute at the same time; "the cross-classification of cases was done by age and sex" |
|  (Mean, Median, Mode, and Range) [http://www.purplemath.com/modules/meanmode.htm] | The "mean" is the "average" you're used to, where you add up all the numbers and then divide by the number of numbers. The "median" is the "middle" value in the list of numbers The "mode" is the value that occurs most often. If no number is repeated, then there is no mode for the list. |

## R Library
R의 기본적인 라이브러리 구성외에 추가로 설치해야되는 라이브러리
```
install.packages('Amelia');
install.packages("corrgram");
install.packages("Hmisc");
install.packages("caret")
```


## Reference 

아래의 Story를 보고 타이타닉 생존 예측 이전에 사전 지식을 습득하고
R Code를 보고 데이터 수집 그리고 전처리, 모델 생성 및 정교화까지 다 해볼 수 있는 좋은 예제 따라해보자

Story - http://trevorstephens.com/post/72916401642/titanic-getting-started-with-r

R Code - https://github.com/wehrley/wehrley.github.io/blob/master/SOUPTONUTS.md
