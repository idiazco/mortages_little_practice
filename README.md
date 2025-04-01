# mortages_little_practice
 Training a model to determine if someone gets or not a mortage.


 # DATA
 For this little practice, we have use the dataset hipotecas.csv (attached in the repository).
 The dataset has the following struture:
 - income: quantitative variable, how much money they have each month
 - common expenses: quantitative variable, how much money they spend
 - car payment: quantitative variable, if they have a car, how much money it costs monthly
 - other expenses: quantitative variable, how much they expend in other things
 - savings: quantitative variable, how much money they save
 - housing: quantitative variable, how much money costs the house they want to buy
 - marital status: categorical variable, 0 = single; 1 = married; 2 = divorced
 - children: quantitative variable
 - job: categorical variable, 0 = unemployed; 1 = self-employed; 2 = employee; 3 = business owner; 4 = couple: self-employed; 5 = Couple: employees; 6 = Couple: self-employed and salaried; 7 = Couple: business owner and self-employed; 8 = Couple: two business owners or business owner and employee
 - mortgage: categorical variable, if they already have a mortage, 0 = no; 1 = yes.

# CREATING AND TRAINING A MODEL: DECISION TREE
We aim to create a model that will help us determine if we should give someone a mortage or not. For that means, we will create and train a decision tree. A decision tree is a supervised learning algorithm (which means we will have train and test data) which we will use for classification into "yes" to a mortage or "no" to a mortage. It starts with a node, and the outgoing branches are based on internal decisions based on the data and the correlation among the different variables.

