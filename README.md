Data Science I Final Project
Fall 2017
Sage Hahn

In this project I investigated the
different ways that large unlabeled datasets
can be leveraged for common binary text
classification tasks. In particular I wanted to
improve upon 'naive' strategies like
keyword searches, as well as with
established supervised learning tasks, my
efforts constituting for the most part
'semi-supervised learning' techniques, and
therefore require varying levels of user
input. I present an array of techniques, both
successful, but also unsuccessful, and back
up each attempt with extensive
experimentation. I also provide
insights as to why certain methods succeed
over others.

report_SAHAHN.pdf - Contains the final report in pdf form, where the bulk of the analysis takes place.

slides_SAHAHN.pdf - Contains the presentation slides for the report.

createRedditTextBlocks.ipynb - Jupyter Notebook where I read in and create 'redditTextBlocks',
	which are pickeled arrays of 10,000,000 posts each.

exploringMethods.ipynb - This Jupyter Notebook is where I do the BULK of my research,
	and exploratory measures. In addition, a number of plots are generated in this file.

initialExplore.ipynb - Jupyer Notebook containing a brief initial exploration of the data, and larger question.

preprocessing.ipynb - In this Notebook I run the globally applied preprocessing steps to all of the data,
	and save the output as a pickeled array for future use.

testingDifferentPreProc.ipynb - In this Notebook I explore the different preprocessing steps I might take,
	and explain some of the logic around why I make the choices I do.

word2VecApproach.ipynb - In this Notebook I explore a technique using word embeddings, word2vec, and
	a conv nueral net implemented in Keras.

ideas.txt - A text file containing dated entries of some of my thoughts and ideas along the way
	of completing this project. This document is fairly informal.

html/ - This folder contains saved HTML versions of all of the above notebooks in case they are needed.

data/ - **THESE FILES HAVE BEEN REMOVED DUE TO THEIR > 100 MB SIZE**
	What data/ did contain was, 

	The 'Corpus' files: redditTextBlock1.pkl, redditTextBlock2.pkl, courseraBlogs.txt, 
	courseraNews.txt, courseraTwitter.txt AND a version of each of these renamed to be
	e.g. redditTextBlock2Proc.pkl or courseraTwitterProc.pkl (Add Proc.pkl to end)

	aswell as, glove.6B/ which contained the glove word embeddings for 50, 100, 200 and 300 dimensions.



