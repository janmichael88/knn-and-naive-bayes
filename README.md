# knn-and-naive-bayes Quiz

This quiz was one that was given to us early on in our education at graduate school. It is a simple lesson is creating synthetic data, and using that data to run Naive-Bayes and KNN classification models. The instructions for the synthetic data creation are as follows:

* Use MS Excel to generate a random number between one and one million. Now use the generated random number as the random state for the synthetic data.
* Use class separator parameter to be between 0.1 and 0.8.
* Use flip_y parameter to be between 0.05 and 0.2.
* The response variable is binary. Choose any class weights of your choice except that the difference between class weights should be at least 0.2 (i.e. 0.6 and 0.4)
* Create 10 features, with four informative, two redundant and the remaining useless. Make sure there are no repeated features.
* Create five new categorical features from the existing continuous ones, with three binary and two tertiary (three categories) features. In the end, your data should have one y-response, ten continuous features and five categorical features. Name these features as y, cont1 – cont10, cat1-cat5
* The models also had constraints defined by the assignment, which were defined by a .csv file. The constraints are highlighted in the code as the values used when creating the multiple models for Naive-Bayes and KNN. The output file of the program (the final .csv) is formatted to show the different constraints as well.


