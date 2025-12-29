# File Handling in Python: Count Lines Not Starting with 'T'

## 🎯 Aim
To write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.

## 🧠 Algorithm
1. Open the file `story.txt` in **read mode**.
2. Initialize a counter `count` to zero.
3. Iterate through each line of the file:
   - Check if the first character of the line is **not** `'T'`.
   - If the line does not start with `'T'`, increment the `count` by 1.
4. After processing all lines, print the `count` value, which represents the number of lines that do not start with `'T'`.

## 🧾 Program
```
def create_file(file_path, content):
    with open(file_path, 'w') as file:
        file.write(content)
def print_lines_with_substring(file_path, substring):
    with open(file_path,'r') as file:
        for line in file:
            if substring in line:
                print(line.strip())
   ```

## Output
<img width="814" height="287" alt="530350629-d40f93b1-defa-41ff-8517-8032bb59af98" src="https://github.com/user-attachments/assets/190b38b3-9712-4ccc-bc8d-47213805dfec" />


## Result
The program successfully counts the number of lines in text file
