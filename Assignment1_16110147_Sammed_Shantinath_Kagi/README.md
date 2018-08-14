# Assignment 1
This assignment involves basic text processing.
* Calculating Number of Types, Tokens and the Type-Token Ratio(TTR).
* Plotting the rules of Zipf's Law
	* Rank of a word (vs) Frequency of the word.
	* Lenght of a word (vs) Frequency of the word.
	* Number of meanings of a word (vs) Frequency of the word.
* Plotting the Heaps Law, Calculating the parameters in the equation by curve fitting.

## Assumptions made:
1. While calculating the tokens, types and TTR ratio, the punctuation marks are not removed from the data. We can remove them using regular expressions ("re" module of python) or using isalpha() over the dataset.
