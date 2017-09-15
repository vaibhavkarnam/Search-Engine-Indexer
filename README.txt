INTRODUCTION:
------------
:Implementing your own inverted	indexer.Text processing	and corpus statistics.

DESIGN CHOICES:
--------------
The data structure used to implement the parser is a Tree Map. Two tree maps are used in the porgram to obtain the term frequencies and the document frequencies. 
Tree Maps were used because they provide an efficient method to sort records within a Map.

PRE-REQUISITS:
-------------
JRE 1.8.101 or higher

EXTERNAL LIBRARIES USED:
-----------------------
jsoup-1.10.2

ITEMS INCLUDED IN THE ZIP FOLDER
--------------------------------
jsoup-1.10.2 external JAR which is used in our program.

Java source files for the program in the folder src

Executable JAR file hw3

Unigram- zipfian curve for unigram frequency
 
Bigram- zipfian curve for Bigram frequency

Trigram- zipfian curve for Trigram frequency

stoplist - stoplist words and explanation

INSTRUCTIONS TO RUN:
-------------------
This is a platform independent applivation and can be run on Windows, Linux or Mac OS.
PLEASE USE THE LATEST VERSION OF JAVA JRE 1.8.101 or higher.

Running the JAR file on Windows, Linux and Mac OS	
		- Download and install JRE 1.8.101 or higher.
		- Use the following command on the terminal to run java -jar hw3.jar


RESULTS:
----------
UnigramTF - Term frequency table for unigram
BigramTF - Term frequency table for bigram
TrigramTF - Term frequency table for trigram
UnigramDocFreq - Document frequency table for unigram
BigramDocFreq - Document frequency table for bigram
TrigramDocFreq - Document freqeuncy table for trigram

CITATIONS:
----------------
https://jsoup.org/                            // used JSOUP library for fetching the html from the URLs
https://jsoup.org/cookbook/                   // used for information on retrieving data from html
https://jsoup.org/apidocs/                    // used for information on retrieving data from html
Search Engines Information Retrieval in Practice  by W.BruceCroft DonaldMetzler TrevorStrohman   // for web crawling concepts
An Introduction to Information Retrieval Christopher D. Manning Prabhakar Raghavan Hinrich Schütze // for web crawling concepts
http://www.mkyong.com/java/jsoup-basic-web-crawler-example/                    // Example for how to use jsoup in java
http://www.advancedinstaller.com/               // for creating the installer for the web crawler on windows system.
microsoft excel for generating the graphs for zipf's law curves