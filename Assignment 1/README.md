README

File Structure of submission folder:
CECZ4045Part1/
	- SourceCode/
		- Assignment 1 3-1.ipynb  -> Source code for Part 3.1
		- Assignment 1 3-2.ipynb  -> Source code for Part 3.2
		- Assignment 1 3-3.ipynb  -> Source code for Part 3.3
		- Web Scraping Yelp.ipynb -> Code to scrape Yelp data for Part 3.2 & 3.3
		- data/ -> dataset used in Part 3.1
			- nlp/ -> dataset with research paper related to NLP
			- optometry/  -> dataset with research paper related to optometry
			- petroleum/  -> dataset with research paper related to petroleum
		- corpus.txt -> cleaned dataset used in Part 3.2 & 3.3
		- yelp_Clinton_Street_Baking Company_&_Restaurant_scrapped.csv -> scraped data from Part 3.2
		- yelp_Clinton_Street_Baking Company_&_Restaurant_scrapped.xlsx -> annontated scraped data from Part 3.2
	- Report.pdf
	- Readme.txt

- A *link* to download the third-party library if you used any in your assignment.
* NLTK (https://www.nltk.org/)
* Matplotlib (https://matplotlib.org/)
* Random (https://docs.python.org/3/library/random.html)
* Numpy (https://numpy.org/)
* Pandas (https://pandas.pydata.org/)
* Re (https://docs.python.org/3/library/re.html)
* Operator (https://docs.python.org/3/library/operator.html)
* Textblob (https://textblob.readthedocs.io/en/dev/)


- A guide on how to setup your system, and how to use your system (e.g. command lines, input format, parameters).
* The system is coded in python and stored as a juypter notebook file .ipynb. 
* To use the files, you have to mount the relevant datasets into the drive.
* Tweak the file directories accordingly in your own google drive.


- Explanations of sample output obtained from your system 
-- THE FIGURES STATED BELOW CORRESPONDS TO THE FIGURES IN OUR REPORT

Assignment 3.1

- Figure 3.1.2: tokens_lib output of the NLP dataset
	- refers to the tokens generated from the NLP dataset using the tokenize_library() function.

- Figure 3.1.4: Output of stemm_dict
	- refers to the output of the stemmed dictionary generated. It contains a dictionary of stemmed tokens.

- Figure 3.1.5: Comparison of total unique tokens before/after stemming 
	- refers to the comparison of the number of unique tokens before and after stemming.
	
- Figure 3.1.7: Length Distribution of Tokens Before/After Stemming
	- refers to the bar chart of the length distribution of the tokens.
	
- Figure 3.1.11: Sentence Distribution
	- refers to the sentence distribution of the sentence tokens. It distributes according to the count of sentences by the number of words found in that sentence.

- Figure 3.1.14: POS Tagging of Three Random Sentences
	- refers to the POS tagging of three random sentences.


Assignment 3.2

- Figure 3.2.1: Output of txt
	- refers to the output of cleaned text generated from the food review dataset.

- Figure 3.2.2: Tagged List
	- refers to the list of tagged words after POS tagging has been applied to them.
	
- Figure 3.2.3: Paired Adjective-Noun Dictionary ranked in descending order
	- refers to the dictionary of paired adjectives and nouns ranked in descending order.


Assignment 3.3

- Figure 3.3.2 : List of cleaned sentences
	- refers to the list of sentences that is split and cleaned from the dataset.
	
- Figure 3.3.6 & 3.3.7: Sentimental Analysis of each Sentence
	- refers to the sentimental analysis of each sentence.