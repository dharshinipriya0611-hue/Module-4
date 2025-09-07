# File Handling in Python: Count the frequency of each character.

## 🎯 Aim
Write a Python program to read a file and count the frequency of each character in it.

## 🧠 Algorithm
1. Start and import defaultdict from collections.
2. Define create_file(file_path, content) to write given text into a file.
3. Define char_frequency(file_path) to count character occurrences.
4. Open the file in read mode.
5. Initialize a defaultdict(int) to store frequency counts.
6. For each line, iterate through its characters and increment the count in the dictionary.
7. Return the dictionary containing character frequencies.

## 🧾 Program
~~~
from collections import defaultdict


def create_file(file_path, content):
    with open(file_path, 'w') as file:
        file.write(content)

# Function to calculate character frequencies
def char_frequency(file_path):
    freq = defaultdict(int)
    with open(file_path,'r') as file:
        for line in file:
            for char in line:
                freq[char]+=1
    return freq
~~~

## Output
<img width="1226" height="298" alt="image" src="https://github.com/user-attachments/assets/a5a9051e-1d3d-44f5-90a4-aa068a408919" />


## Result
Thus the output is Verified.
