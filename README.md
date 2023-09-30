This C++ project is about sentiment analysis using a hash table-based approach. Here's an overview of your project and the purpose of each file:

-  HashTable.cpp and HashTable.h:
HashTable is a class that represents a hash table used to store words and their associated scores.
It includes methods for computing a hash, inserting words with scores, checking if a word is in the table, and getting the average score for a word.
The hash table is implemented as an array of linked lists (each list contains WordEntry objects).

-  WordEntry.cpp and WordEntry.h:
WordEntry is a class that represents an entry in the hash table.
It includes methods for initializing a word entry, adding new appearances of a word with scores, getting the word itself, and calculating the average score for the word.

-  main.cpp:
This is the main program that performs sentiment analysis on movie reviews.
It reads movie reviews and their associated scores from an input file ("movieReviews.txt") and inserts them into the hash table.
Users can input their own movie reviews, and the program calculates the sentiment of each review based on the average scores of individual words.
Sentiment is categorized as "Positive Sentiment," "Somewhat Positive Sentiment," "Somewhat Negative Sentiment," or "Negative Sentiment" based on the calculated average sentiment score.

The overall purpose of this project is to analyze movie reviews for sentiment. It allows users to input movie reviews, and based on the words in those reviews and their associated scores, it calculates an average sentiment score for the entire review. This score is then categorized to determine the overall sentiment of the review. The project employs a hash table data structure to efficiently store and retrieve word scores during sentiment analysis.
