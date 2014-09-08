**Soci 950 - Words to Numbers: Quantitative Text Analysis 
**  
Fall 2014  
Hamilton Hall 150  
Monday, Wednesday 1-2:15pm  
Neal Caren <neal.caren@unc.edu>


There's nothing new about sociologists using text as data. Traditionally, source materials have come from things like primary sources (_e.g._ interviews) or secondary sources (_e.g._ newspapers). Scholars use programs like NVivo or ATLAS.ti to assist them in making sense of the data. Over the last decade, however, researchers from a variety of disciplines have increasingly turned to a more algorithmic analysis of texts. This new focus on the quantitative analysis of text  (along with network analysis and agent based modeling) forms the basis of [computational social science](http://www.ncbi.nlm.nih.gov/pmc/articles/PMC2745217/). Not coincidentally, the ability of social scientists to collect text corpuses has also grown over the last decade. This combination of new methods and new sources of data presents a unique opportunity for social scientists to find new answers to old questions and start asking new questions.

The primary learning goal for this course if for students to develop the ability to employ appropriate quantitative textual analysis techniques to a social scientific question. In other words, you should be able to write a publishable paper that involves the quantitative analysis of text. Specifically, I expect that by the end of the semester you will be:  

* Able to collect, store and manipulate data from text files, web pages, and web application programming interfaces (APIs);
* Familiar with the major methods of text analysis;
* Knowledgeable of relevant machine learning techniques;
* Able to apply relevant analytic methods to appropriate social scientific questions.

Between most class meetings you will have to do some combinations of the following things. First, you will be reading contemporary examples of social scientific research that employs the relevant methods. Second, you will be reading code of worked examples. Quite often, this code will be in the form of IPython notebooks. Third, you will have to produce some code yourself. For the first few days, this code will take advantage of the codecademy Python MOOC. After that, you'll be writing your own code that you will either bring to class or email to me ahead of class. Finally, we'll spend the last section of the course working on a pair of studies. For each, you and your partner are responsible for presenting your code and findings.

Half of you grade will be based on the daily homework. They are marked with a **H** on the syllabus.  The other half of your grade is based on the two projects. For each project, you will be expected to present your findings and hand in a well-commented IPython notebook so that someone can replicate your findings. The first project involves an analysis of political emails. The second involves contemporary newspaper data. In both cases, you will develop an interesting sociological puzzle, get/collect the appropriate raw data, and then analyze the data to explore your puzzle. You may work with a partner, but you can't have the same partner. Depending on the flow of the course and student interest, we might end up doing something else for one or both of these projects.

I've put together a [list](http://nealcaren.github.io/python-tutorials/) of online Python tutorials that are accessible to social scientists. You might find some helpful when looking for additional information about a topic.

Wednesday 8/20 -  Introductions

Monday, 8/25 - The Basics 

* Read [The Need for Openness in Data Journalism](http://nbviewer.ipython.org/github/brianckeegan/Bechdel/blob/master/Bechdel_test.ipynb) by [Brian Keegan](https://twitter.com/bkeegan)
* [Download](http://continuum.io/downloads) and install the [Continuum](http://www.continuum.io) Python distribution.
* [Codecademy](http://www.codecademy.com/learn). Sign up for the Python course. Do the first six lessons -- up to, and including, PygLatin. Note: Feel free to skip the Boolean Operators section. 
* **H** Email me your "Great job finishing" certificate from codecademy.


Wednesday, 8/27 - More Python

* Read [Light, Ryan. "From Words to Networks and Back: Digital Text, Computational Social Science, and the Case of Presidential Inaugural Addresses." Social Currents (2014)](http://scu.sagepub.com/content/1/2/111)
* [Codecademy](http://www.codecademy.com/learn). Next two sections: Functions (Functions & Taking a Vacation) and Lists & Dictionaries (Python Lists and Dictionaries and A Day at the Supermarket). 
* **H** - Email me your "Great job finishing" certificate from codecademy. 
		 
Wednesday, 9/3 - Even more Python

* [Codecademy](http://www.codecademy.com/learn). A few more sections: Lists and Functions (Lists and Functions and Battleship!); Loops (Loops and Practice makes Perfect); Exam Statistics; and Advanced Topics in Python (feel free to skip the Lambdas section). 
* **H** - Email me your "Great job finishing" certificate from codecademy.  


Monday, 9/8 - Getting Data when they want to give it to you

* [Codecademy](http://www.codecademy.com/learn). Take the Placekitten API course. Then, pick another API class that uses Python, such as NPR, Sunlight Foundation, or NHTSA. Take that one. 
* **H** - Email me your "Great job finishing" certificate from codecademy.  


Wednesday, 9/10 - More on APIs

* [Sushi Bars and Yelp](http://nealcaren.github.io/sushi_bars.html). Sign up to be a developer on Yelp. 
* **H** - Bring an IPython notebook to class that lists the coffee bars in your home town. Feel free to copy and paste from me. Note: You might need to install oauth2.

Monday, 9/15 - Twitter API

* [Mining Twitter](http://nbviewer.ipython.org/github/ptwobrussell/Mining-the-Social-Web-2nd-Edition/blob/master/ipynb/Chapter%201%20-%20Mining%20Twitter.ipynb). 
* Get your own consumer key, consumer secret, access token, and access token secret from [Twitter](https://dev.twitter.com). 
* **H** - Bring an IPython notebook to class that does something cool with [tweepy](http://www.tweepy.org).


Wednesday, 9/17  - Getting Data when they may not want to give it to you

* [Web Scraping in Python](http://nbviewer.ipython.org/url/www.unc.edu/~ncaren/Lax-1.ipynb.json). 
* **H** - Bring an IPython notebook to class that downloads a web page.

Monday, 9/22 - More web scraping 

* [Pinterest Analysis about the NYFW Fall 2014](http://nbviewer.ipython.org/github/rosariomgomez/fashion/blob/master/pinterest/pinterest_analysis.ipynb)
* **H** - Bring in an IPython notebook that scrapes the UNC sociology [faculty](http://sociology.unc.edu/people/faculty) emails. 

Wednesday, 9/24 - Counting words

* Read [Ryan C. Black, Sarah A. Treul, Timothy R. Johnson, and Jerry Goldman. Emotions, oral arguments, and Supreme Court decision making. The Journal of Politics, 73(2):572–581, April 2011.](http://www.polisci.umn.edu/~tjohnson/MyPapers/JOP2011.pdf)
* Read [Monroe, Burt, Michael Colaresi, and Kevin Quinn. 2008. “Fightin’ Words: Lexical Feature Selection and Evaluation for Identifying the Content of Political Conflict”. Political Analysis 16(4)](https://www.law.berkeley.edu/files/MonroeColaresiQuinn.pdf)
* [Using Python to see how the Times writes about men and women](http://nbviewer.ipython.org/gist/nealcaren/5105037)
* **H** - Bring an IPython notebook to class that loads a corpus and tokenizes the texts.

Monday, 9/29 - Sentiment Analysis

* Read [Golder, Scott A., and Michael W. Macy. "Diurnal and seasonal mood vary with work, sleep, and daylength across diverse cultures." Science 333.6051 (2011): 1878-1881.](ntent/333/6051/1878.short)
* Read [Dodds, Peter and Christopher Danforth. 2009. “Measuring the Happiness of Large- Scale Written Expression: Songs, Blogs, and Presidents”. *Journal of Happiness Studies* 11, 4. 441-456](http://www.uvm.edu/~cdanfort/research/dodds-danforth-johs-2009.pdf)
* [Sentiment analysis](http://nbviewer.ipython.org/github/nealcaren/workshop_2014/blob/master/notebooks/3_Sentiment.ipynb) 
* **H** - Bring an IPython notebook with a function that returns the sentiment of a text.


Wednesday, 10/1 - Classification

* [Basic principles of machine learning](http://nbviewer.ipython.org/github/jakevdp/sklearn_pycon2014/blob/master/notebooks/03_basic_principles.ipynb)
* [Predicting customer churn with scikit-learn](http://blog.yhathq.com/posts/predicting-customer-churn-with-sklearn.html)
* [Text Classification with Naïve Bayes](http://nbviewer.ipython.org/github/gmonce/scikit-learn-book/blob/master/Chapter%202%20-%20Supervised%20Learning%20-%20Text%20Classification%20with%20Naive%20Bayes.ipynb)
* **H** - Bring an IPython notebook that predicts text categories based on given dataset.
 

Monday, 10/6 - Feature Selection  

* [Testing and Validation in Scikit-Learn](http://nbviewer.ipython.org/gist/sarguido/8969894)
* [Machine Learning with Scikit-Learn: Validation and Model Selection](http://nbviewer.ipython.org/github/jakevdp/sklearn_pycon2014/blob/master/notebooks/06_validation.ipynb)
* **H** - Bring an IPython notebook that improves on your classification machine using validation methods.


Wednesday, 10/8 - Machine Learning Algorithms   

* Read [D’Orazio, Vito, et al. "Separating the Wheat from the Chaff: Applications of Automated Document Classification Using Support Vector Machines." Political Analysis 22.2 (2014): 224-242.](http://pan.oxfordjournals.org/content/22/2/224.abstract)
* [Supervised Learning In-Depth: SVMs and Random Forests](http://nbviewer.ipython.org/github/jakevdp/sklearn_pycon2014/blob/master/notebooks/04_supervised_in_depth.ipynb)
* [Basic Random Forest Model](http://nbviewer.ipython.org/github/treycausey/thespread/blob/master/notebooks/basic_random_forest_wp_model.ipynb?create=1)
* **H** - Bring an IPython notebook that improves on your classification machine using different classification algorithms. 


Monday, 10/13 - Review


* [Diving into Open Data with IPython Notebook & Pandas](http://nbviewer.ipython.org/urls/raw.githubusercontent.com/jvns/talks/master/pycon2014/bike_paths.ipynb?create=1)
* [Is Seattle Really Seeing an Uptick In Cycling?](http://jakevdp.github.io/blog/2014/06/10/is-seattle-really-seeing-an-uptick-in-cycling/) 

Wednesday, 10/15 - Review

Monday, 10/20 - Text clustering

* [https://de.dariah.eu/tatom/working_with_text.html](https://de.dariah.eu/tatom/working_with_text.html)
* [Unsupervised Learning In-depth: PCA and K-Means](http://nbviewer.ipython.org/github/jakevdp/sklearn_pycon2014/blob/master/notebooks/05_unsupervised_in_depth.ipynb) 
* **H** - Text clustering homework. 

Wednesday, 10/22 - Topic Models in Mallet

* Read [Quinn, Kevin M., et al. "How to analyze political attention with minimal assumptions and costs." American Journal of Political Science 54.1 (2010): 209-228.](http://www.law.berkeley.edu/files/TopicModel.pdf)
* Read [DiMaggio, Paul, Manish Nag, and David Blei. "Exploiting affinities between topic modeling and the sociological perspective on culture: Application to newspaper coverage of US government arts funding." Poetics 41.6 (2013): 570-606.](http://www.sciencedirect.com/science/article/pii/S0304422X13000661)
* **H** Topic modeling homework I

Monday, 10/27 - Topic Models in Python

* Read [Bail, Christopher A. "The cultural environment: measuring culture with big data." Theory and Society (2014): 1-18.](http://www.soc.ucsb.edu/ct/pages/MC2/Our_Papers/Bail-Measuring%20Culture%20with%20Big%20Data%20Final%20November%2029.pdf)
* Read [Bonilla, Tabitha, and Justin Grimmer. "Elevated threat levels and decreased expectations: How democracy handles terrorist threats." Poetics 41.6 (2013): 650-669.](http://stanford.edu/~jgrimmer/terror.pdf)
* **H** Topic modeling homework II


Wednesday, 10/29 - Project I - Analzying Political Discourse

Monday, 11/3

* Read [Bail, Christopher A. "The Fringe Effect Civil Society Organizations and the Evolution of Media Discourse about Islam since the September 11th Attacks." American Sociological Review 77.6 (2012): 855-879.](http://asr.sagepub.com/content/77/6/855.short)

Wednesday, 11/5

* Read [Spirling, Arthur. "US treaty making with American Indians: Institutional change and relative power, 1784–1911." American Journal of Political Science 56.1 (2012): 84-97.](https://www.princeton.edu/~pcglobal/conferences/methods/papers/Spirling.pdf)


Monday, 11/10

* Read [Grimmer, Justin, and Brandon M. Stewart. "Text as data: The promise and pitfalls of automatic content analysis methods for political texts." Political Analysis (2013): mps028.](http://stanford.edu/~jgrimmer/tad2.pdf)


Wednesday, 11/12

* Student presentations

Monday, 11/17 - Project II - Realtime Sociology

* Install [storytracker](http://storytracker.readthedocs.org/en/latest/index.html). 


Wednesday, 11/19 

* Read [Grimmer, Justin. "Measuring Representational Style in the House: The Tea Party, Obama and Legislators’ Changing Expressed Priorities." (2014).](http://web.stanford.edu/~jgrimmer/house.pdf)


Monday, 11/24

* Read [Levy, Karen EC, and Michael Franklin. "Driving Regulation: Using Topic Models to Examine Political Contention in the US Trucking Industry." Social Science Computer Review (2013): 0894439313506847.](http://ssc.sagepub.com/content/32/2/182)



Monday, 12/1

* TBA

Wednesday, 12/3

* Student presentations


