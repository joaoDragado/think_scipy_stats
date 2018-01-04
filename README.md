## Companion Code for Allen Downey's [Think Stats](http://www.greenteapress.com/thinkstats/) 2nd Edition.
- an alternative approach to solving the book's exercises, utilising popular libraries from python's "scientific universe", namely **numpy, scipy, statsmodels, pandas, matplotlib, seaborn, etc.**

---
### Introduction

First off, **Think Stats** is a great book ; short and sweet, with interesting real-life test studies that keep the reader interested & engaged. While there are paid versions, **one can acquire a free version of the book**. The author, 
**Allen B. Downey**, has continuously revised & updated the book's material and supporting code (with the aid of numerous contributors).

Per the book's description :
> *"**Think Stats** is an introduction to Probability and Statistics for Python programmers. *Think Stats* is based on a Python library for probability distributions (PMFs and CDFs). Many of the exercises use short programs to run experiments and help readers develop understanding. "*

The code contained in the book, follows an idiomatic object-oriented (OOP) approach ; the author's idea is to build a simple core library that defines discrete & continuous distributions, and then gradually extend that library to explain the various statistical concepts that the book covers. 

This approach has drawn a fair bit of critisism (mostly from coders with experience in python ; the arguments can be easily found in a cursory search for reviews of the book). 

My main difficulties with working with the book's code were :

- *OO design favours encapsulation (in OOP you start small , and extend functionality by adding more features on top)*.
    
    While i was progressing through the book, to fully understand what a code snippet was doing, i had to chase down each class method/function, usually across multiple python files. This is actually what one does when trying to use any third-party python library, it's just felt less than ideal in this setting, when the reader's primary focus is on understanding the statistical concepts.

- *The book's master code exists in a vaccum.*
    
    This of course has clear benefits (zero dependencies to third party libraries ; no need to keep the code up-to-date.)
    And yet, if the reader (like myself) has already ventured in Python's scientific libraries (**numpy, scipy, scikit-learn, pandas, matplotlib, etc.**), the book's approach feels a bit like backtracking, and after covering the book, one is at a loss on how to incorporate the code written/reviewed, much less on how to extend it for their own ideas/projects.       

By using python's scientific libraries to build and execute the book's exercises, one can get an introduction on computational statistics, while learning the mechanics and workflow of said libraries ; this way, when one decides to venture in more computational intensive fields (like bayesian analysis, machine learning), the use of the libraries feels less daunting & the transition (to a more functional programming style) less abrupt.
 
---

### Dependencies - Libraries used

* [Python 3.6](https://docs.python.org/3.6/) *(code should also work for Python 2.7)*
* [Anaconda](https://www.anaconda.com/)  *Python Data Science Distribution* ; the easiest way to install & manage all scientific libraries used in this repo.

---

### Reference Links

- Book's Main Site (along with linkd to all of the author's books) [Think Stats](http://www.greenteapress.com/thinkstats/)
- Github Repository for the book's [original code](https://github.com/AllenDowney/ThinkStats2)
- Allen B. Downey's personal blog [Probably Overthinking It](http://allendowney.blogspot.com/) ; contains observations on computational statistics , mini projects , and much more.

- [Computational Statistics | SciPy 2017 Tutorial](https://www.youtube.com/watch?v=He9MCbs1wgE) - Hands-on Tutorial by Allen Downey from the Scipy 2017 Conference