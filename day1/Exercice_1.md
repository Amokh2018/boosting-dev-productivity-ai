
## Exercise 1: Prompt Playground 



**Tool**: 
- [ChatGPT](https://chat.openai.com/)

---

## Part 1 – Code Generation 

### Basic Prompting

**Prompt**:
```
Write a Python function that takes a string of text and returns the frequency of each word. The output should be a dictionary.
```

**Modify**:
```
Refactor the code to ignore punctuation and make it case-insensitive.
```



---

## Part 2 – Explanation & Debugging 

### A- Code Explanation

Use this function:
```python
def flatten(nested_list):
    return [item for sublist in nested_list for item in sublist]
```

**Prompt**:
```
Explain what this function does to a beginner Python developer. Use a visual representation if possible.
```

**Rephrase**:
```
Act as a Python instructor. Use a 3-step explanation, with an example.
```

### B- Bug Fix & Testing

Use this broken code:
```python
def divide_numbers(a, b):
    return a / b if b != 0 else "Can't divide by zero"
```

**Prompt**:
```
Fix the code to raise an exception instead of returning a string for division by zero. Add proper type hints.
```

**Follow-up**:
```
Write unit tests using `pytest` for this function.
```

---

## Part 3 – Documentation & Formatting (15 minutes)

### Auto-Generate README

Use the following script:
```python
import os

def rename_files(folder_path):
    for count, filename in enumerate(os.listdir(folder_path)):
        dst = f"file_{count}.txt"
        os.rename(os.path.join(folder_path, filename),
                  os.path.join(folder_path, dst))
```

**Prompt**:
```
Write a professional `README.md` file for this script with sections: Description, Usage, Arguments, Example.
```


## Part 4 – Prompt Remix & Reflection

### Task A: Role Prompt

Choose a previous code and try:
```
You are a senior Python architect with 10 years of experience. Rewrite this code to follow clean architecture principles and explain why each change was made.
```

### Reflection

Answer:
- Which tool gave the most helpful response?
- What was your best prompt?
- What surprised you about GenAI's output?
- One prompt you'll keep using in the future?

