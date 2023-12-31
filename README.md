
# Titanic
This is my first guided project that I tried in order to learn Kaggle platform. I followed the tutorial as below. 



## Titanic Tutorial

- [@alexisbcook](https://www.kaggle.com/alexisbcook)
- [tutorial](https://www.kaggle.com/code/alexisbcook/titanic-tutorial)


Please use the link above to learn and read full description. Following contenct is same as the tutorial that Alexis created. I am copying some of the original contents for myself to practice writing 'readme' and to keep track of my process of learning Kaggle projects. 



## The Challenge

The competition is simple: we want you to use the Titanic passenger data (name, age, price of ticket, etc) to try to predict who will survive and who will die.

## The data

To take a look at the competition data, click on the [Dat tab](https://www.kaggle.com/c/titanic/data) at the top of the competition page. Then, scroll down to find the list of files.
There are three files in the data: (1) train.csv, (2) test.csv, and (3) gender_submission.csv.

## (1) train.csv
train.csv contains the details of a subset of the passengers on board (891 passengers, to be exact -- where each passenger gets a different row in the table). To investigate this data, click on the name of the file on the left of the screen. Once you've done this, you can view all of the data in the window.


![](https://i.imgur.com/cYsdt0n.png)
**train.csv** contains the details of a subset of the passengers on board (891 passengers, to be exact -- where each passenger gets a different row in the table).  To investigate this data, click on the name of the file on the left of the screen.  Once you've done this, you can view all of the data in the window.  

![](https://i.imgur.com/cYsdt0n.png)

The values in the second column (**"Survived"**) can be used to determine whether each passenger survived or not: 
- if it's a "1", the passenger survived.
- if it's a "0", the passenger died.

For instance, the first passenger listed in **train.csv** is Mr. Owen Harris Braund.  He was 22 years old when he died on the Titanic.

### (2) test.csv

Using the patterns you find in **train.csv**, you have to predict whether the other 418 passengers on board (in **test.csv**) survived.  

Click on **test.csv** (on the left of the screen) to examine its contents.  Note that **test.csv** does not have a **"Survived"** column - this information is hidden from you, and how well you do at predicting these hidden values will determine how highly you score in the competition! 

### (3) gender_submission.csv

The **gender_submission.csv** file is provided as an example that shows how you should structure your predictions.  It predicts that all female passengers survived, and all male passengers died.  Your hypotheses regarding survival will probably be different, which will lead to a different submission file.  But, just like this file, your submission should have:
- a **"PassengerId"** column containing the IDs of each passenger from **test.csv**.
- a **"Survived"** column (that you will create!) with a "1" for the rows where you think the passenger survived, and a "0" where you predict that the passenger died.

