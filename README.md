To determine the length of a sentence, the number of words, and the number of vowels character by character, you can follow this algorithm:

1. Initialize three variables as counters: `length` for the length of the sentence, `wordCount` for the number of words, and `vowelCount` for the number of vowels.
2. Prompt the user to enter a sentence that ends with a period.
3. Read the input sentence and assign it to a variable, let's say `sentence`.
4. Initialize a loop to iterate through each character in the sentence, excluding the last character (the period).
5. For each character in the sentence:
   a. Increment the `length` counter by 1.
   b. Check if the character is a space (' '):
    i. If it is, increment the `wordCount` counter by 1 to count a new word.
   c. Check if the character is a vowel ('a', 'e', 'i', 'o', 'u', case-insensitive):
    i. If it is, increment the `vowelCount` counter by 1 to count a vowel.
6. After the loop finishes, add 1 to the `wordCount` counter to account for the last word in the sentence.
7. Display the results: the length of the sentence, the number of words, and the number of vowels.