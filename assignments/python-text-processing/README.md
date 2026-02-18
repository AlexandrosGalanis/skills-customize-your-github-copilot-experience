```markdown
# 📘 Assignment: Python Text Processing

## 🎯 Objective

Work with strings and files to build command-line utilities that parse, analyze, and transform text data.

## 📝 Tasks

### 🛠️ Task 1 — Word Frequency Counter

#### Description
Write a script that reads a text file, counts how many times each word appears (case-insensitive), and prints the top N most frequent words.

#### Requirements
Completed program should:

- Accept a file path as input and handle file-not-found errors gracefully.
- Normalize text by lowercasing and removing basic punctuation.
- Count word frequencies and display the top N words (N configurable, default 10).

### 🛠️ Task 2 — Simple Text Cleaner

#### Description
Create a utility that reads a text file and writes a cleaned version: trimmed whitespace, normalized spaces, and optional stopword removal.

#### Requirements
Completed program should:

- Remove leading/trailing whitespace from lines and collapse multiple spaces into one.
- Optionally accept a list of stopwords to remove from the output.
- Preserve original file encoding where possible and write output to a new file.

## 💡 Example Interaction

```
$ python wordfreq.py sample.txt --top 5
1. the — 123
2. and — 98
3. to — 85
4. of — 80
5. a — 62
```

## 📎 Starter files

- No starter code provided for this assignment. Students should create `wordfreq.py` and `clean_text.py` in the assignment folder.

## ✅ Skills Practiced

- String manipulation and regular expressions
- File I/O and error handling
- Data aggregation (counts) and sorting
- Command-line argument parsing

If you'd like, I can add a minimal `starter-code.py` that includes an argument parser and file loader.
```
