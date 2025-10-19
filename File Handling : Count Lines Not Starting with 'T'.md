# File Handling in Python: Count Lines Not Starting with 'T'

## 🎯 Aim
To write a Python program that counts the number of lines in a text file story.txt that do *not* start with the alphabet 'T'.

## 🧠 Algorithm
1. Open the file story.txt in *read mode*.
2. Initialize a counter count to zero.
3. Iterate through each line of the file:
   - Check if the first character of the line is *not* 'T'.
   - If the line does not start with 'T', increment the count by 1.
4. After processing all lines, print the count value, which represents the number of lines that do not start with 'T'.

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
![WhatsApp Image 2025-10-19 at 19 59 11_9591ab14](https://github.com/user-attachments/assets/e09b5b09-bb61-4213-b59a-ce087bb41fe1)


## Result
The program successfully counts the number of lines in text file
