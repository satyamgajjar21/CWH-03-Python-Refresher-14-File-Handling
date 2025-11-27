# Python File Handling Project

This project demonstrates essential Python file handling operations, including reading, writing, appending, creating, and manipulating files.  
It serves as a beginner-friendly guide to understanding how Python interacts with the file system.

---

## 📌 Features
- Read content from files  
- Write new data into files  
- Append content to existing files  
- Create new files programmatically  
- Delete files (if implemented)  
- Basic error handling using try-except  
- Demonstrates opening files using different modes (`r`, `w`, `a`, `x`)  

---

## 📁 Project Structure
```
project/
│── 14_file_handling.ipynb
│── data/
│    ├── example.txt
│
│── README.md
```

---

## 🛠️ Technologies Used
- Python  
- Jupyter Notebook  

(No additional external libraries detected)

---

## 🚀 What This Notebook Covers

### ✔ Opening Files
```python
file = open("sample.txt", "r")
```

### ✔ Reading Files
- `read()`
- `readline()`
- `readlines()`

### ✔ Writing Files
```python
with open("new.txt", "w") as f:
    f.write("Hello World")
```

### ✔ Appending to Files
```python
with open("log.txt", "a") as f:
    f.write("New entry")
```

### ✔ File Handling with `with` Statement
Ensures files automatically close after use.

### ✔ Working with File Paths (if included)
Handling relative/absolute paths.

---

## ▶️ Usage
Run the notebook:

```
jupyter notebook 14_file_handling.ipynb
```

Modify file names inside the notebook as needed.

---

## 📊 Output
- File content displayed in cells  
- New files created in working directory  
- Updated/modified text inside files  

---

## 📜 Documentation
Detailed explanation and code examples are inside the notebook.

---

## 🤝 Contributing
Pull requests are welcome.  
For major changes, open an issue first.

---

## 📝 License
This project is licensed under the MIT License.

---

## 👨‍💻 Author
Satyam Gajjar
