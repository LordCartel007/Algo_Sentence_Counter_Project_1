READ A SENTENCE AND GET VOWELS
Description

The read_a_sentence and get vowel algorithm reads a sentence from the user and performs the following tasks:

Calculates the length of the sentence.

Counts the number of words in the sentence.

Counts the number of vowels in the sentence.

Variables

sentence: A string variable that holds the input sentence.

sentence_length: An integer variable to store the length of the sentence.

spaces_count: An integer variable to count the number of spaces in the sentence.

word_count: An integer variable to calculate the number of words in the sentence.

vowel_count: An integer variable to count the number of vowels in the sentence.

Algorithm Steps

Read the Sentence:

The algorithm begins by reading a sentence from the user and storing it in the sentence variable.

Calculate Sentence Length:

Determine the length of the sentence and store it in sentence_length.

Count Words:

Initialize spaces_count to 0.

Loop through each character in the sentence:
If the character is a space (" "), increment the spaces_count by 1.
Calculate the number of words as spaces_count + 1 and store this value in word_count.

Count Vowels:

Initialize vowel_count to 0.
Loop through each character in the sentence:
If the character is a vowel ("a", "e", "i", "o", or "u"), increment the vowel_count by 1.

Output Results:

Print the sentence_length, word_count, and vowel_count.
