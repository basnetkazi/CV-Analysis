# CV-Analysis
CV Analysis

# Problem Definition
In today’s word of competition a company might get lot of applications for job vacancy. And the company personnel might not have enough time to go through all peoples CV so if we can analyses the CV digitally and get the results then it can make whole process simpler.

# Objectives
•	To train the application able to learn the natural language processing
•	To create an application that classifies the sentiments from CV of a person.

# Tools Used
•	Programming language: Python
•	Coding Environment/ IDE: Pycharm
•	Libraries: pyQt for GUI, NLTK

# Task Done
Since the project title says CV Analysis Along with the study and research about relevant projects basic progress are done in projects like basic GUI for the app.
# 1)	Reading CV:
The application is able to read or load the *.docx file from the PC. The file is uploaded to the application using QFileDialog library in pyQT framework.

# 2)	Tokenizing:
The *.docx file of CV uploaded in the application is then converted to the txt file using library docx2txt. The application will be able to read file with *.txt or *.docx extension. The files are passed to process and convert into txt file. Then the words and sentence are tokenized using word_tokenize() and sent_tokenize() function respectively. Here the letters will be in lower and uppercase both and to maintain uniformity all the words are converted to lowercase. 
Then there may be many stops words in the CV of a person which might not contain meaning in the evaluation of CV thus those stops words are filtered using standard corpus of NLTK. 

# 3)	Scoring CV:
After tokenizing the CV the basic task of analyzing the CV was done using scoring method. The Scoring of the CV was done based on the keywords found on the CV after tokenizing. Some special words like which we are searching in an application can be checked if available in CV and provide them score and the person with all qualities we are searching can be done using this method. 
