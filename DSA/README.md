# 🚀 Java Programming Solutions - Engaging Algorithms! 🎉

Welcome to my Java coding playground! Here, you'll find my solutions to various algorithmic challenges that I have tackled. Dive in to explore how I solved these problems with the power of Java. Let's break down each one with a friendly approach!

---

## 📝 Q1: Pascal's Triangle Generator

**Approach:**
Pascal's Triangle is a classic example of combinatorial mathematics. Each number in the triangle is the sum of the two numbers directly above it. For this problem, we used a 2D List in Java to represent the triangle, where each row is dynamically generated based on the previous one.

- **Steps:**
  1. We iterate through each row `i` and for each row, create a list that contains the appropriate number of elements.
  2. The first and last element of each row is always `1`.
  3. For the other elements, we calculate the sum of the two elements directly above them (from the previous row).
  
📌 **Code Execution:** We print the first `n` rows of Pascal's Triangle in a neat list format.

---

## 📝 Q2: Climbing Stairs

**Approach:**
This problem is a well-known dynamic programming challenge! It's based on the Fibonacci sequence—where each step to reach the top is a sum of the ways to reach the two previous steps.

- **Steps:**
  1. We use recursion to solve this problem. If `n` is 1 or less, we return 1 (base case).
  2. Otherwise, for each `n`, the number of ways to climb the stairs is the sum of ways to climb `n-1` and `n-2` stairs.

⚡ **Code Execution:** Given `n`, it returns the number of ways to climb to the top of the staircase.

---

## 📝 Q3: Search for a Range

**Approach:**
In this problem, the task is to find the starting and ending positions of a target number in a sorted array. We used **binary search** to achieve an efficient solution. Binary search helps narrow down the search space by halving it each time.

- **Steps:**
  1. Perform two binary searches—one for the left boundary and one for the right boundary.
  2. The left search continues until it finds the first occurrence of the target, while the right search continues until it finds the last occurrence.
  3. If the target isn't found, return `-1, -1`.

🚀 **Code Execution:** We return the indices of the first and last occurrence of the target.

---

## 📝 Q4: String Compression

**Approach:**
This problem involves compressing a string by counting consecutive repeating characters. For instance, "aaabbccc" becomes "a2b2c3". The task is to modify the input character array in-place and return the new length of the compressed array.

- **Steps:**
  1. Use two pointers: one for reading the array (`readIndex`) and another for writing the compressed version (`writeIndex`).
  2. For each sequence of repeating characters, write the character followed by its count (if greater than 1).
  3. Continue this until all characters are processed.

🔥 **Code Execution:** The function compresses the array and returns the new size, showing the compressed form of the input.

---

🛠️ **Tools Used:**
- Java
- IDE: IntelliJ IDEA

Feel free to check out the code and let me know your thoughts. Happy coding! 😄
