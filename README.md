# Longest_Compound_Word

 HOW THE PROGRAM WORKS

# Using a Special Structure for Storing Words (Trie):
The program uses a special tree-like structure called a "Trie" to store words efficiently. In this structure, each part of the tree represents a letter, and a complete path from the start to a point in the tree spells out a word. This setup makes it really quick to search for words or parts of words.

# Reading and Storing Words:
The program reads words from a file named text.1 and text.2 and stores them in the Trie. This way, each word is broken down letter by letter and stored in a way that's easy to search.

# Finding Compound Words:
A "compound word" is a word that's made by putting together shorter words. The program has a special function to find these compound words. It looks at each word and checks if it can be split into two or more smaller words that are also in the list.

# Identifying the Longest Compound Words:
As the program checks each word, it keeps track of which ones are the longest and second-longest compound words.

# Designed for Fast Performance:
The Trie makes the program very fast, even when the list of words is very long. The way the program checks for compound words is also efficient, so it doesn’t waste time on unnecessary checks.

# Measuring Time Taken:
I've also included a feature that measures how long the program takes to find these words, from the moment it starts reading the file to when it finds the longest compound words.

LongestCompoundWord/README.md at
