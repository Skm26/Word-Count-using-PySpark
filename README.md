# Word-Count-using-PySpark
A simple word count program using PySpark from a text file
Here are the brief steps for writing the word counting program:
1.	Create a base RDD from text file.
2.	Use RDD transformation to create a long list of words from each element of the base RDD.
3.	Remove stop words from your data.
4.	Create pair RDD where each element is a pair tuple of ('w', 1)
5.	Group the elements of the pair RDD by key (word) and add up their values.
6.	Swap the keys (word) and values (counts) so that keys is count and value is the word.
7.	Finally, sort the RDD by descending order and print the 10 most frequent words and their frequencies.

# Note 
Stop words in the current program are removed with the help of NLTK package , a predefined data structure
with stop words in a variable can also be used 

Incase of NLTK please install the package before hand
