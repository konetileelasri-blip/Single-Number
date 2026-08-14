Single Number

📌 Problem

Given a non-empty array of integers "nums", every element appears twice except for one element.

Find and return the element that appears only once.

💡 Example

Input: nums = [2,2,1]

Output: 1

Input: nums = [4,1,2,1,2]

Output: 4

💻 Language

Java

📂 File

"SingleNumber.java"

🧠 Approach

This solution uses the XOR ("^") operator.

1. Initialize "result" as "0".
2. XOR every element with "result".
3. Equal numbers cancel each other because "a ^ a = 0".
4. "0 ^ a = a".
5. Therefore, the remaining value is the single number.

⏱️ Complexity

- Time Complexity: O(n)
- Space Complexity: O(1)

🎯 Goal

To practice arrays and bitwise XOR operations in Java.

👨‍💻 Author

K.Leela Sri# Single-Number