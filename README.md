# **movie_recommender**

### Association Rule learning <p>
Association rule learning is a rule-based machine learning method for discovering interesting relations
between variables in large databases. It is intended to identify strong rules discovered in databases using
some measures of interestingness.</p>

### Apriori algorithm <p>
Apriori uses a breadth-first search strategy to count the support of itemsets and 
uses a candidate generation function which exploits the downward closure property of support.  
In simple terms, it proceeds by identifying the frequent individual items in 
the database and extending them to larger and larger item sets as long as those item sets appear sufficiently often in the database.</p>

#### Support <p>
Support is an indication of how frequently the itemset appears in the dataset</p>
![](/res/support.png)

#### Confidence <p>
Confidence is an indication of how often the rule has been found to be true.</p>
![](/res/confidence.png)

#### Lift <p>
It is defined as :
![](/res/lift.png) </p>

If the lift is > 1, that lets us know the degree to which those two occurrences are dependent on one another, and makes those rules potentially useful for predicting the consequent in future data sets.

If the lift is < 1, that lets us know the items are substitute to each other. This means that presence of one item has negative effect on presence of other item and vice versa.

