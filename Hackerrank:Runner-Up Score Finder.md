# 🏆 Hackerrank:Runner-Up Score Finder in Python

## 🎯 AIM:
To write a Python program that takes a list of scores from participants and finds the **runner-up score** (i.e., the second-highest score), eliminating any duplicates.

---

## 🧠 ALGORITHM:

1. **Start**
2. Create a variable `n` and get its value from the user (number of participants)
3. Read the list of `n` scores from the user using `input().split()` and convert them to integers
4. Store the scores in a list
5. Use `set()` to remove any duplicate scores
6. Convert the set back to a list and sort it in ascending order
7. Print the second-last element of the sorted list (i.e., the runner-up score)
8. **Stop**

---

## 💻 PROGRAM:
```python
n = int(input())

scores = list(map(int, input().split()))

scores = list(set(scores))
scores.sort()

print(scores[-2])
```

## OUTPUT:
<img width="473" height="179" alt="image" src="https://github.com/user-attachments/assets/8d19a5ce-4e33-4ffa-9487-4cb5eb8c99b6" />


## RESULT:
Thus,the program is executed successfully.
