CSE 601: Data Mining and Bioinformatics
Project 3: Classification Algorithms

Submitted By: Karan Manchandia | karanman | 50290755
              Divya Srivastava | divyasri | 50290383
              Varsha Lakshman  | varshala | 50288138

Folder Hierarchy: 
> project3
   > Code
      > KNN.ipynb
      > Decisiontree.ipynb
      > Naive Bayes.ipynb
      > Randomtrees.ipynb
      > Kaggle.ipynb
      > README.txt
   > Report
      > Project3_report.pdf
      

Requirements: Python3.6

*********************************Part1: K-Nearest Neighbor******************************************

How to run the code:

The following would be required to execute KNN on jupyter notebook:
1) Find the KNN.ipynb file inside the Code folder. The Code folder can be found inside the submitted Project folder.
2) Note that in order to run the code you need to place the data files (project3_dataset1.txt, project3_dataset2.txt) inside the same folder in which the KNN.ipynb is placed. 
3) Open the KNN.ipynb file in the Jupyter Notebook.
4) Run all the cells to see the outputs.
   [Note that for some cells in the jupyter notebook you need to enter the data-file names and K(nearest neighbor) and number of folds as input,
    These inputs are to be added in correct format for example datafile = project3_dataset1.txt, K=9, folds=10]  

The input parameters can be changed as per the requirement keeping the input format same.


**************************Part2: Decision Tree*******************************

How to run the code:

1) Copy Proj3_DecisionTree.py and the dataset files i.e. project3_dataset1.txt and project3_dataset2.txt into the same directory.
2) Execute the cells on jupyter notebook.
3) Path to input_dataset corresponds to the dataset on which you want to run the code.
4) Required input parameters:   
   Is it a demo code? Enter Y or N: N
   Enter the name of the data file:(project3_dataset1.txt or project3_dataset2.txt)
5) Output:
   Accuracy, Precision, Recall, F1-Measure are printed upon completion of the script to depict the various metrics on which the script was evaluated on.
   The final tree is printed
   The node values along with the split values and indexes and gini index are printed.



*********************************Part3: Naive Bayes**************************************

How to run the code:

1) Copy NaiveBayes.py and the dataset files i.e. project3_dataset1.txt and project3_dataset2.txt into the same directory.
2) Execute the cells on jupyter notebook.
3) Path to input_dataset corresponds to the dataset on which you want to run the code.
4) Required input parameters:
   Enter the name of the data file:(project3_dataset1.txt or project3_dataset2.txt)
5) Output:
   Accuracy, Precision, Recall, F1-Measure are printed upon completion of the script to depict the various metrics on which the script was evaluated on.


*************************************Part4: Random Forest************************************

How to run the code:

1) Copy RandomForest.py and the dataset files i.e. project3_dataset1.txt and project3_dataset2.txt into the same directory.
2) Execute the cells on jupyter notebook.
3) Path to input dataset corresponds to the dataset on which you want to run this code.
4) Required input parameters:
   Enter the name of the data file:(project3_dataset1.txt or project3_dataset2.txt)
   Enter the number of trees: An integer
   Enter the number of Features: An integer
5) Output:
   Accuracy, Precision, Recall, F1-Measure are printed upon completion of the script to depict the various metrics on which the script was evaluated on.


********************************Part5: Kaggle Competition*******************************

How to run the code:

The following would be required to execute Kaggle on jupyter notebook:
1) Find the kaggle.ipynb file inside the Code folder. The Code folder can be found inside the submitted Project folder.
2) Note that in order to run the code you need to place the data files (test_features.csv, train_features.csv and train_label.csv) inside the same folder in which the kaggle.ipynb is placed. 
3) Open the Kaggle.ipynb file in the Jupyter Notebook.
4) Run all the cells to generate the Excel result file.
5) You can find the generated result excel file in the same folder in which code is placed.
6) Submit the generated excel file on kaggle to check the performance measure.
