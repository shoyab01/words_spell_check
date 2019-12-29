# words_spell_check
To find the words which are wrongly spelt in a text file and to correct the wrongly spelt words and save in another file using python3.

# TextBlob

TextBlob is a Python (2 and 3) library for processing textual data. 

It provides a simple API for diving into common natural language processing (NLP) tasks such as part-of-speech tagging, noun phrase extraction, sentiment analysis, classification, translation, and more.

Install TextBlob in Anaconda Navigator or Anaconda Prompt using the following commmand:

With conda
    
    $ conda install -c https://conda.anaconda.org/sloria textblob
    $ python -m textblob.download_corpora

# os module

The os module is a part of the standard library, or stdlib, within Python 3. 

This means that it comes with your Python installation, but you still must import it.

The main purpose of the OS module is to interact with your operating system.

The primary use I find for it is to create folders, remove folders, move folders, and sometimes change the working directory.

# misspelled_words.txt

This text file contains some of the common misspelled words.

# corrected_words.txt

This file contains words after spelling correction using TextBlob library.
