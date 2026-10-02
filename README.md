# Java-Placement-Forge
This repository contains 20 Java programs based on medium-level placement questions. The programs cover arrays, strings, numbers, searching, frequency counting, mathematical operations, and basic problem-solving techniques.
---

🛠️ Technologies Used

- Java
- Scanner
- Arrays
- Conditional Statements
- For Loop
- While Loop
- String
- StringBuilder
- Character Methods
- Mathematical Operations
- Array Manipulation

---

📚 Programs

🔢 Array Programs

1. Second Largest Element in an Array

Description

Find the second largest element in an array without sorting the array.

Sample Input

10 25 5 40 30

Sample Output

Second Largest: 30

How to Run

javac Problem01_SecondLargest.java
java Problem01_SecondLargest

---

2. Find Duplicate Elements

Description

Identify and print all elements that appear more than once in an array.

Sample Input

10 20 30 20 40 10 50

Sample Output

Duplicate elements:
10
20

How to Run

javac Problem02_FindDuplicates.java
java Problem02_FindDuplicates

---

3. Remove Duplicate Elements

Description

Remove duplicate elements from an array while keeping only the first occurrence of each value.

Sample Input

10 20 10 30 20 40

Sample Output

Array after removing duplicates:
10 20 30 40

How to Run

javac Problem03_RemoveDuplicates.java
java Problem03_RemoveDuplicates

---

4. Frequency of Array Elements

Description

Count and print how many times each distinct element occurs in an array.

Sample Input

10 20 10 30 20 10

Sample Output

10 occurs 3 times
20 occurs 2 times
30 occurs 1 times

How to Run

javac Problem04_ArrayFrequency.java
java Problem04_ArrayFrequency

---

5. Find Missing Number

Description

Find the missing number in an array that should contain all integers from 1 to N.

Sample Input

1 2 3 5 6
n = 6

Sample Output

Missing Number: 4

How to Run

javac Problem05_MissingNumber.java
java Problem05_MissingNumber

---

6. Move All Zeros to the End

Description

Move all zeros to the end of an array while keeping the relative order of the non-zero elements.

Sample Input

0 5 0 3 8 0 2

Sample Output

5 3 8 2 0 0 0

How to Run

javac Problem06_MoveZeros.java
java Problem06_MoveZeros

---

7. Rotate an Array by K Positions

Description

Rotate an array to the right by K positions.

Sample Input

1 2 3 4 5
k = 2

Sample Output

4 5 1 2 3

How to Run

javac Problem07_RotateArray.java
java Problem07_RotateArray

---

8. Maximum Subarray Sum

Description

Find the maximum possible sum of a contiguous subarray using Kadane's Algorithm.

Sample Input

-2 1 -3 4 -1 2 1 -5 4

Sample Output

Maximum Subarray Sum: 6

How to Run

javac Problem08_MaximumSubarray.java
java Problem08_MaximumSubarray

---

9. Find Pair with Given Sum

Description

Find all pairs of elements in an array whose sum equals the given target value.

Sample Input

2 7 4 5 3
target = 9

Sample Output

(2, 7)
(4, 5)

How to Run

javac Problem09_PairWithGivenSum.java
java Problem09_PairWithGivenSum

---

10. Merge Two Sorted Arrays

Description

Merge two arrays that are already sorted in ascending order into a single sorted array.

Sample Input

a = 1 3 5 7
b = 2 4 6 8

Sample Output

1 2 3 4 5 6 7 8

How to Run

javac Problem10_MergeSortedArrays.java
java Problem10_MergeSortedArrays

---

🔤 String Programs

11. Check Whether Two Strings Are Anagrams

Description

Check whether two given strings are anagrams of each other.

Sample Input

listen
silent

Sample Output

Anagram

How to Run

javac Problem11_Anagram.java
java Problem11_Anagram

---

12. First Non-Repeating Character

Description

Find the first character in a string that does not repeat anywhere else.

Sample Input

swiss

Sample Output

First non-repeating character: w

How to Run

javac Problem12_FirstNonRepeatingCharacter.java
java Problem12_FirstNonRepeatingCharacter

---

13. Remove Duplicate Characters from String

Description

Remove duplicate characters from a string while keeping only the first occurrence of each character.

Sample Input

programming

Sample Output

progamin

How to Run

javac Problem13_RemoveDuplicateCharacters.java
java Problem13_RemoveDuplicateCharacters

---

14. Find the Longest Word in a Sentence

Description

Find the longest word in a given sentence.

Sample Input

Java programming is interesting

Sample Output

Longest word: programming

How to Run

javac Problem14_LongestWord.java
java Problem14_LongestWord

---

15. Reverse Words in a Sentence

Description

Reverse the order of words in a sentence while keeping each word itself unchanged.

Sample Input

Java is powerful

Sample Output

powerful is Java

How to Run

javac Problem15_ReverseWords.java
java Problem15_ReverseWords

---

16. Count Vowels, Consonants, Digits and Special Characters

Description

Count the number of vowels, consonants, digits, and special characters in a given string.

Sample Input

Java123@#

Sample Output

Vowels: 2
Consonants: 2
Digits: 3
Special Characters: 2

How to Run

javac Problem16_CountCharacters.java
java Problem16_CountCharacters

---

🔢 Number Programs

17. Palindrome Number Without String

Description

Check whether a given number is a palindrome using mathematical operations without converting it to a string.

Sample Input

12321

Sample Output

Palindrome

How to Run

javac Problem17_PalindromeNumber.java
java Problem17_PalindromeNumber

---

18. Armstrong Numbers in a Range

Description

Print all Armstrong numbers within a given range.

Sample Input

start = 100
end = 1000

Sample Output

153 370 371 407

How to Run

javac Problem18_ArmstrongNumbers.java
java Problem18_ArmstrongNumbers

---

19. Prime Numbers in a Range

Description

Print all prime numbers within a given range along with the total count of prime numbers found.

Sample Input

start = 10
end = 50

Sample Output

Prime numbers:
11 13 17 19 23 29 31 37 41 43 47
Count: 11

How to Run

javac Problem19_PrimeNumbers.java
java Problem19_PrimeNumbers

---

20. Decimal to Binary Without Built-in Methods

Description

Convert a decimal number to its binary representation without using built-in conversion methods.

Sample Input

25

Sample Output

Binary: 11001

How to Run

javac Problem20_DecimalToBinary.java
java Problem20_DecimalToBinary

---

▶️ How to Run the Programs

Step 1 – Install Java

Check whether Java is installed:

java -version

Check the Java compiler:

javac -version

Step 2 – Clone the Repository

git clone YOUR_GITHUB_REPOSITORY_URL

Move into the project directory:

cd Java-Placement-Forge

Step 3 – Compile a Program

For example:

javac Problem01_SecondLargest.java

Step 4 – Run the Program

java Problem01_SecondLargest

Step 5 – Run Other Programs

Change the filename according to the problem:

javac Problem02_FindDuplicates.java
java Problem02_FindDuplicates

---

📂 Project Structure

Java-Placement-Forge/
│
├── README.md
│
├── Problem01_SecondLargest.java
├── Problem02_FindDuplicates.java
├── Problem03_RemoveDuplicates.java
├── Problem04_ArrayFrequency.java
├── Problem05_MissingNumber.java
├── Problem06_MoveZeros.java
├── Problem07_RotateArray.java
├── Problem08_MaximumSubarray.java
├── Problem09_PairWithGivenSum.java
├── Problem10_MergeSortedArrays.java
├── Problem11_Anagram.java
├── Problem12_FirstNonRepeatingCharacter.java
├── Problem13_RemoveDuplicateCharacters.java
├── Problem14_LongestWord.java
├── Problem15_ReverseWords.java
├── Problem16_CountCharacters.java
├── Problem17_PalindromeNumber.java
├── Problem18_ArmstrongNumbers.java
├── Problem19_PrimeNumbers.java
└── Problem20_DecimalToBinary.java

---

🎯 Learning Objectives

Through these 20 programs, the following Java concepts are practiced:

- Arrays
- Strings
- Variables and data types
- User input using "Scanner"
- "if-else" statements
- "for" loops
- "while" loops
- Array traversal
- Duplicate handling
- Frequency counting
- Mathematical operations
- Number manipulation
- String manipulation
- Character methods
- Basic problem-solving

---

📌 Repository

Java Placement Forge

A collection of Java placement-oriented programming solutions for improving coding and problem-solving skills.
