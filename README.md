# Instructions:

## Prerequisite: 
The following is going to assume you have Jupyter or IPython Notebooks installed on your computer. If this is not the case you may want to head over to their [website](http://jupyter.readthedocs.org/en/latest/install.html) and follow the instructions to get a fresh install. 

### Steps:
* First you'll want to either clone this repository via terminal (or command line) onto your computer or download the zip which should be an option above.
* Next navigate into the recently cloned/downloaded directory and then into the xlrd-0.9.4. After that run the following command:
```
python setup.py install
```
* That will install the xlrd dependency. Now navigate back into the root of the project folder and run the following command:
```
jupyter notebook
```
* This should open a page in your default web browser. Then just click on 'PokitDok_Data_Visualization.ipynb' to open it and run the cells for the visualization. 

Note: This isn't perfect and I was hoping to fix the overlapping labels problem but will have to save that for future work. 

UPDATE (2/2/16): I forgot to include the xlrd package in my last push so I've included that and added some additional instruction that should resolve any errors. 
