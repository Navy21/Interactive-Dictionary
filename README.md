PROJECT DESCRIPTION:

This python application lets user enter an English word and returns its meaning (definition) as output. 
If we enter a random word that doesn't have any meaning, then the program displays that the word doesn't exist.
If user misspelt the word, then the program suggests few similar words and asks the user if he/she is looking for that word. 
This program has command lines interface through which you input the word.
data.json file contains vocabulary which will be extracted by the program.
data.jason is a dataset which contains words and definitions.
Load data into python as a specific datatype (in this case as python dictionary) and then access the data from that datatype.



PROJECT IMPLEMENTATION:
•	Built a Python application which takes an English word as the input and returns definition of that word as the output.
•	Loaded the dataset into python as python dictionary which contains words as keys and their definitions as values.
•	Implemented a function that takes in a dictionary key (i.e. word) as input and returns the definition as output.
•	Calculated the similarity ratio between the word entered and all the other keys in the dictionary using “ratio()” method of the “SequenceMatcher” class if the word entered is misspelt.
•	Displayed 3 similar words to the misspelt word with a similarity ratio greater than or equal to 0.6 using “get_close_matches()” method and prompted the user to verify if the word he/she is looking for, is in the words suggested. If yes, then the definition for that word is retrieved.
