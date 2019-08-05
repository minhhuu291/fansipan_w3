![](https://paindoctor.com/wp-content/uploads/2018/01/ted-talks-on-health.png)

# TedTalk Data Analysis
----


# Part 1: Overview 
----

### About TED:

[TED](https://www.ted.com/talks) is a nonprofit devoted to spreading ideas, usually in the form of short, powerful talks (18 minutes or less). TED began in 1984 as a conference where **Technology, Entertainment** and **Design** converged, and today covers almost all topics — from science to business to global issues — in more than 100 languages.

In Vietnam, TED is popular among the youth who seeks for motivation or innovation, with many videos has been translated to Vietnamese. 

----
### Project goal

>* Analyze how TED performs throught time and how to improve it.
>* Find useful insights about the audience - how they think about the talks.
>* Show some other intersting figure about TED.

----
### Useful library for this project:
**`Matplotlib`**

**`Numpy`**

**`Pandas`** 

----

## Project Implement:
----

#### I. Read the dataset using `pandas` library and assign it to a dataframe:

```                                            
                                            import pandas as pd
                                            df = pd.read_csv('ted.csv')
                                            
```
    
* _Note that the dataset should be in the same directory with the Jupyter Notebook, otherwise pasting the address of the dataset between two quotes_ 

#### II. Print the first 5 row of the dataset:
```                                            
                                            df.head()
                                            
```

#### III. Check out some useful information about the dataset using: _`info()`, `describe()`, `mean()`, `min()`, `max()`, ... _
```                                            
                                            df.info()
                                            df.describe()
                                            ..........
                                            
```

#### IV. Replace missing values/NaN or outliers with suitable value: (using `drop()`, `isnull()`, `loc()`,...)
[Usefull Pandas techniques for Data Manipulation](https://www.analyticsvidhya.com/blog/2016/01/12-pandas-techniques-python-data-manipulation/)

#### V. Analyze data statistics using `Pandas` and `Numpy`:
![Numpy Cheatsheet](https://intellipaat.com/mediaFiles/2018/12/Python-NumPy-Cheat-Sheet-1.png)

#### VI. Using those statictics to complete these tasks:
* What are the most welcome topic in TED.
* Evaluate TED performances throught time.
* Find any interesting facts about TED.


https://datastudio.google.com/s/qtQGMx8yYI0
