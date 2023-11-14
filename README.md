# Recursion Checkpoint

> The algorithm iterates over the first half of the string, comparing characters from the beginning and the end and checks for palindrome.

## Steps

1. Initialize a boolean variable isPalindrome to true.

2. Iterate through the string word from index 0 to index N - 1:

   > For each index i, compare the character at word[i] to the character at word[N - i - 1].
   > If the characters are equal, continue to the next iteration.
   > If the characters are not equal, set isPalindrome to false and break out of the loop.

3. If the loop completes without isPalindrome being set to false, then the string is a palindrome. Return true.

4. Otherwise, the string is not a palindrome. Return false.
