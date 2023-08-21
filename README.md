# Effectiveness of using blind relevance feedback to improve on retrieval of results


This system is composed of four python programs: index.py, query.py, parameters.py and porter.py. 
Index.py is run first and indexes each word in the document corpus, indicating which document the term appears in and how many times it appears. 
Porter.py accounts for stemming, which was turned off for this experiment as it did not yield significantly different results. 
Parameters.py contains configurable parameters for the simple extended Boolean search engine. 
Query.py takes as input the query the user wants to search and the name of the document corpus which the user wants to query.

To run this code you will need to install NLTK. 

This can be done through running: pip install nltk
