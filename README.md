# LeetCode Solutions 🐍

Welcome to my LeetCode practice repository!

I am a beginner learning Python programming and solving coding problems to improve my problem-solving skills.

## 📌 Problem 1: Two Sum

**Difficulty:** Easy  
**Language:** Python 3

### Problem Description
Given an array of integers `nums` and an integer `target`, return the indices of the two numbers such that they add up to the target.

### Example

**Input:**
```python
nums = [2, 7, 11, 15]
target = 9
```

**Output:**
```python
[0, 1]
```

**Explanation:**

The numbers `2` and `7` add up to `9`.

- Index of `2` = 0
- Index of `7` = 1

Therefore, the answer is `[0, 1]`.

### Python Solution

```python
class Solution:
    def twoSum(self, nums, target):
        for i in range(len(nums)):
            for j in range(i + 1, len(nums)):
                if nums[i] + nums[j] == target:
                    return [i, j]
```

### Concepts Learned
- Python Lists
- For Loops
- If Conditions
- Array Indexing
- Functions and Classes
- Problem Solving

### Complexity Analysis
- **Time Complexity:** O(n²)
- **Space Complexity:** O(1)

### My Goal 🎯
My goal is to solve LeetCode problems regularly, improve my Python skills, and become a better programmer.

### Platform
[LeetCode](https://leetcode.com/)

---

⭐ This is my first step toward learning Data Structures and Algorithms (DSA).
