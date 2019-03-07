March 7, 2019
Caroline Teicher and Matt Leifer 
APCOMP 221 

This folder contains: 
- a Python Notebook file, identification.ipynb, with code for problem set questions 1-6 and corresponding discussion questions 
- a pdf, 221 due 2.24 .pdf, with sugested quasi-attributes submitted prior to this problem set 
- a configuration file, config_file.txt, with the column numbers, one per line, of each quasi-identifier in the data set
- the data set in csv format, mid_sample_set.csv
- a data dictionary that roughly outlines the data set columns 

Testing:
- identification.ipynb contains various assert statements throughout the notebook that check the vailidity 
of the data set after each manipulation as well as changing column types in the data set. The assert statements, given the dependencies between questions, confirm that the data set is in an appropriate form after pasing through written functions such as suppression, blurring and generalization.
- A mock csv file, test.csv further tests the code. Given its invalid format, the mock csv raises exceptions and 
prevents code from breaking upon processing invalid inputs. 