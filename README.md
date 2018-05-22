# ncku-datamining-homeworks
NCKU-DataMining-Homeworks

======================================================================================

## Homework assignment #1
### 1. Show that if discrete attributes A and B are fully dependent, then U(A, B) = 1
### 2. Design a program to perform the following tasks without considering the 11th attribute that has many missing values.
> Download files 'mushroom.txt'.<br>
> Feature selection will be stopped when the goodness of an attribute subset cannot be improved. 
* (a) Perform forward selection to find an attribute subset for classification.
* (b) Perform backward selection to find an attribute subset for classification.
* (c) Discuss the results obtained in (a) and (b) 

======================================================================================

## Homework assignment #2
### 1. 
> Download data set 'ecoli.txt' for discretization.<br>
> Feature selection will be stopped when the goodness of an attribute subset cannot be improved.<br>
> [Multi-interval discretization of continuous-valued attributes for classification learning](http://web.donga.ac.kr/kjunwoo/files/Multi%20interval%20discretization%20of%20continuous%20valued%20attributes%20for%20classification%20learning.pdf)
* (a) Perform equal-width with ten bins, equal-frequency with ten bins, and the entropy-based discretization on the continuous attributes. Clearly specify the intervals of a discretized attribute.
* (b) For each discretization method, perform forward and backward selection to find an attribute subset for classification. Clearly specify the chosen attribute and the goodness of the attribute subset in each iteration.
* (c) Discuss the results obtained in (b).
*  [Comparative Analysis of Supervised and Unsupervised
Discretization Techniques](https://www.researchgate.net/profile/Rajashree_Dash/publication/266058863_Comparative_Analysis_of_Supervised_and_Unsupervised_Discretization_Techniques/links/55727c6b08aeacff1ffacde8/Comparative-Analysis-of-Supervised-and-Unsupervised-Discretization-Techniques.pdf)

### 2. Prove equation of estimating statistical bounds
> The upper bound of generalization at node t: eupper(N, e, α)<br>
*  N: the number of training instances classified by node t.<br>
* n: the number of misclassifications at node t.<br>
* e: error rate at node t (e = n / N)<br>
* [Confidence interval](http://people.stern.nyu.edu/gsimon/Pamphlets/ConfidenceIntervalCollection16APR08.pdf)

### 3. Use the data shown in table to grow a decision tree by the gain ratio. (unpruned)

| Customer ID | Gender| Car Type | Shirt Size  | Class |
| :---:       | :---: | :---:    | :---:       | :---: |
| 1           | M     | Family   | Small       | C0    |
| 2           | M     | Sports   | Medium      | C0    |
| 3           | M     | Sports   | Medium      | C0    |
| 4           | M     | Sports   | Large       | C0    |
| 5           | M     | Sports   | Extra Large | C0    |
| 6           | M     | Sports   | Extra Large | C0    |
| 7           | F     | Sports   | Small       | C0    |
| 8           | F     | Sports   | Small       | C0    |
| 9           | F     | Sports   | Medium      | C0    |
| 10          | F     | Luxury   | Large       | C0    |
| 11          | M     | Family   | Large       | C1    |
| 12          | M     | Family   | Extra Large | C1    |
| 13          | M     | Family   | Medium      | C1    |
| 14          | M     | Luxury   | Extra Large | C1    |
| 15          | F     | Luxury   | Small       | C1    |
| 16          | F     | Luxury   | Small       | C1    |
| 17          | F     | Luxury   | Medium      | C1    |
| 18          | F     | Luxury   | Medium      | C1    |
| 19          | F     | Luxury   | Medium      | C1    |
| 20          | F     | Luxury   | Large       | C1    |

======================================================================================

## Homework assignment #3
### 1. Consider data set 'ecoli.txt' to perform the following tasks.

* (a) Perform naive Bayesian classifier to classify instances when continous attributes are assumed to be normally distributed or transformed by equal-width with ten bins. equal-frequency with ten bins, or the entropy-based discretization. The evaluation method is 5-fold cross validation.

* (b) Discuss the result obtained in (a)

### 2. When the number of folds equals the number of instances in a data set, it is called leave-one-out cross validation. Propose a method to compare the accuracies of two classification algorithms evaluated by leave-one-out cross validation.

* [Performance evaluation of classification algorithms by k-fold
and leave-one-out cross validation](https://ac.els-cdn.com/S0031320315000989/1-s2.0-S0031320315000989-main.pdf?_tid=53173eb4-b513-48e2-801e-b9f6548e408d&acdnat=1525615491_22e15bbf53174961a0d78bb438ca6a76)

* [Cross-Validation](http://leitang.net/papers/ency-cross-validation.pdf)

* [Approximate Statistical Tests for Comparing. Supervised Classification Learning Algorithms](http://sci2s.ugr.es/keel/pdf/algorithm/articulo/dietterich1998.pdf)

### 3. As addressed in Dietterich (1998), the k accuracies obtained from k-fold cross validation for a data set are not independent because any pair of training sets are overlap.<br>
### Argue whether you agree with this statement or not.

* [Dependency Analysis of Accuracy Estimates
in k-Fold Cross Validation](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8012491)

======================================================================================

## Term Paper Report
