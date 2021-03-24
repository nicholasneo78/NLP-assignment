README

File Structure of submission folder:
CECZ4045A2-U1820539F/
	- SourceCode/
		- Question_1_Language_Model/
			- data/   # the folder that stores the raw dataset
				- wikitext-2/
					- README
					- test.txt
					- train.txt
					- valid.txt
			- gen_text/   # the folder that stores the generated text from generate.py
				- model-40-Adam-emsize8-nhid8-word1000.txt
				- model-40-Adam-emsize8-nhid200-word1000.txt
				- model-40-RMSprop-emsize8-nhid8-word1000.txt
				- model-40-RMSprop-emsize8-nhid200-word1000.txt
				- model-40-SGD-emsize8-nhid8-word1000.txt
				- model-40-SGD-emsize8-nhid200-word1000.txt
			- model/   # the folder to store the trained language model
				- model-40-Adam-emsize8-nhid8.pt
				- model-40-Adam-emsize8-nhid200.pt
				- model-40-RMSprop-emsize8-nhid8.pt
				- model-40-RMSprop-emsize8-nhid200.pt
				- model-40-SGD-emsize8-nhid8.pt
				- model-40-SGD-emsize8-nhid200.pt
			- command.txt  # the text file to store the command line commands to train the model and generate the texts from the language models
			- data.py  # the code to load the raw datasets
			- generate.py  # the code to generate text from language models
			- main.py  # the code to build the language models
			- model.py  # the code to configure the model specifications
		
		- Question_2_NER/
			- Part 2-NER/
				- data/   # the folder to store all the files needed for the NER tasks
					- eng.testa
					- eng.testb
					- eng.train
					- eng.train54019
					- glove.6B.100d.txt
					- mapping.pkl
				- evaluation/   # the evaluation (test set) on the model trained
					- temp/
						- pred.test
						- score.test
					- conlleval
				- images/  # folder for some reference images 
					- cnn_model.png
					- crf_mode.png
					- lstm_model.png
				- models/  # folder to store the models
					- pre-trained-model
					- trained-model-cpu
				- data.py   # base code
				- model.py   # base code
				- NER.ipynb  # main file for the analysis
	
	- Report.pdf
	- Readme.txt
	
How to run the code:
Question 1: Use command prompt and go to the respective directory where main.py and generate.py is located, then refer to the commands in command.txt for the respective parts
Question 2: Just run the code on Google Colaboratory
