# Two Sum - Python

## 📌 Problem
Given an array of integers `nums` and an integer `target`, return the indices of the two numbers such that they add up to `target`.

---

## 💡 Approach
We use a hash map (dictionary) to store previously seen numbers.

For each element:
- Compute the complement: `target - num`
- Check if it exists in the dictionary
- If yes → return indices

---

## ⚡ Complexity
- Time complexity: O(n)
- Space complexity: O(n)

---

## 🧠 Code
See `two_sum.py`

---

## 🧪 Example
Input: nums = [2,7,11,15], target = 9  
Output: [0,1]

---

## 👤 Author
NB
