# LESSON 1-PYTHON
## File Handling in Python 
### What is File Handling?
File Handling allows programs to save, retrieve, and modify persistent data. File handling is an important part of any web application. For example, we see it in a web server, Datasets, or video games. 
Text files: txt, csv
binary files: image
### Why use File Handling?
- To store data permanently
- To handle a large amount of data
- To keep data even after the program exits

| FILE MODES |
| --- |
| Read Mode = r |
| Write Mode = w |
| Append Mode = a |
| Create Mode = x |
| Binary Mode(Read) = rb |
| Binary Mode(Write) = wb |
| Binary Mode(append) = ab |

## SAVE USERNAME
```python
username = input("Enter your username:")
with open("user.txt", "w") as file:
    file.write(username)
print("Username saved!")
```
Output
```python
Enter your username: (write any username)
Username saved!
```
## Save High Scores
```python
high_score = input("Enter your score: ")

with open("game_scores.txt", "a") as file:
    file.write(high_score + "\n")

print("Score saved!")
```
## game_scores.txt
```python
220
100
440
```








