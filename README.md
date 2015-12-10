# CS109finalproject 
### Adam Gilfix, Matt Goldberg, Nathaniel Ver Steeg and Steven Rachesky


Purpose: Predict NFL offensive play-calling in order to aid in defensive play-calling. We analyzed data from the 2003-2014 NFL seasons from [Pro-Football Reference](http://www.pro-football-reference.com) in order to create seven classifiers to help predict whether the offense will pass or run depending on the game situation. 


Our project's contents are contained in the Matt's git repository linked [here](https://github.com/mdgoldberg/cs109finalproject). The CSV's "0204plays.csv", "0507plays.csv", "0810plays.csv" and "1114plays.csv" contain all of the plays for the 2002-2014 seasons. We needed to include the 2002 season to calculate lag features for our 2003 season. We merge these CSV's in the beginning of our notebooks. First, open the [Index.ipynb](https://github.com/mdgoldberg/cs109finalproject/blob/master/Index.ipynb) Notebook, which will serve as our controller throughout the project. This will guide the reader in a specific order to our [Scraping.ipynb](https://github.com/mdgoldberg/cs109finalproject/blob/master/Scraping.ipynb), Data Cleaning Notebook titled [proj.ipynb](https://github.com/mdgoldberg/cs109finalproject/blob/master/proj.ipynb), Exploratory Data Anlayis (EDA) titled [Some EDA.ipynb](https://github.com/mdgoldberg/cs109finalproject/blob/master/Some%20EDA.ipynb), Notebook Model Development and Findings Notebook titled [proj_func.ipynb](https://github.com/mdgoldberg/cs109finalproject/blob/master/proj_func.ipynb) and our Conclusion section at the end of the [Index.ipynb](https://github.com/mdgoldberg/cs109finalproject/blob/master/Index.ipynb) Notebook. The file [scrapingScript.py](https://github.com/mdgoldberg/cs109finalproject/blob/master/scrapingScript.py) simply contains the same material as the [Scraping.ipynb](https://github.com/mdgoldberg/cs109finalproject/blob/master/Scraping.ipynb) Notebook. We include an "images" folder, which contains the relevant images linked from our Notebooks, and we provide an "old_work" folder, which contains some spare files we used for early stage analysis. The "old_work" file is largely unpolished and should be disregarded, however, we opted to include it to show the evolution of our project. 
