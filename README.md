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

| Customer ID | Gender| Car Type | Shirt Size  |
| :---:       | :---: | :---:    | :---:       |
| 1           | M     | Family   | Small       |
| 2           | M     | Sports   | Medium      |
| 3           | M     | Sports   | Medium      |
| 4           | M     | Sports   | Large       |
| 5           | M     | Sports   | Extra Large |
| 6           | M     | Sports   | Extra Large |
| 7           | F     | Sports   | Small       |
| 8           | F     | Sports   | Small       |
| 9           | F     | Sports   | Medium      |
| 10          | F     | Luxury   | Large       |
| 11          | M     | Family   | Large       |
| 12          | M     | Family   | Extra Large |
| 13          | M     | Family   | Medium      |
| 14          | M     | Luxury   | Extra Large |
| 15          | F     | Luxury   | Small       |
| 16          | F     | Luxury   | Small       |
| 17          | F     | Luxury   | Medium      |
| 18          | F     | Luxury   | Medium      |
| 19          | F     | Luxury   | Medium      |
| 20          | F     | Luxury   | Large       |

======================================================================================
