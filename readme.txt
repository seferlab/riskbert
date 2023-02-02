--first, a csv file from Kogan and Levin collection is constructed with docname, real volatility value, previous volatility value and year
--later2007.csv file is the data after 2006 with text, year and volatility values

-- after above data files are constructed, embedding extraction is made (see embedding extraction.ipynb)
-- also, closer words are found using closest distance to the embedding vectors (see embedding extraction.ipynb)
--then, ML models and tf, tf-idf featured models are tested (see ML Text regression.ipynb)