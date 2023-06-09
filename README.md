# CTFChallenge

You are given a pile of random text, which contains a hidden word that you need to encode with a Caesar Cipher function (which will get you the flag). 
Your task is to find the the only word that has 'c' as its first letter and 's' as its last letter.

Here's how the challenge works:

Input:
You are given a .txt file full of random words, and only one of them is a word that starts with 'c' and ends with 's'

Output:
Your program should output the encoded word of the words you found.

Constraints:

The pile of random text will contain only uppercase letters, lowercase letters, spaces, and punctuation marks.
You will unfortunately guess which one of the 26 possible combinations (of this cipher) is the right flag. Don't worry I will give you a hint in the next line :)
Hint: the number of spaces you need to shift is equal to the amount of letters in the only word that has 'c' as its first letter and 's' as its last letter
