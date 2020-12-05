MSBD5001 Kaggle
===============
Liu Yingjie 20711100
--------------------

This is my code for the in-class kaggle competition.

I use random forest model provided by xgboost.

How to produce an output:
-------------------------

    Make sure train.csv and test.csv are in the same folder as xgb_traffic.ipynb

    Install the python packages I use in the notebook:

        pip install Chinese-holiday
        pip install workalendar
        pip install xgboost
    
    Maybe make sure CUDA is installed correctly (not necessary)

    Run xgb_traffic.ipynb, it will produce four files:
        xgb_train.txt
        xgb_val.txt
        xgb_test.txt
        submit.csv
    
    The file for submission is submit.csv

My last two submission files:
-----------------------------
    submit12.csv
    submit13.csv
These two files are inside this repository

>Note that everytime you run the notebook, the output will not be exactly the same