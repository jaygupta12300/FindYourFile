# 🔍 FindYourFile

**FindYourFile** is a simple Java-based utility that searches through all directories inside a specified parent folder to locate files whose names contain a keyword you provide and returns the **full path** for each match. ([GitHub][1])

This tool is especially useful when you have large folder structures and need to quickly locate specific files without manually browsing through each directory.

---

## 🚀 Features

✔️ Recursively search through subdirectories
✔️ Match file names based on a keyword
✔️ Shows full directory path for found matches
✔️ Lightweight Java application

---

## 🗂️ Repository Structure

```
/
├── FindFileRep/              # Java source code and resources
├── findfile.jar              # Compiled executable JAR
├── FindFileRep.7z            # Compressed source archive
├── Capture.PNG               # Screenshot of application or results
├── README.md                 # Project documentation
```

---

## 🛠️ How It Works

**FindYourFile** takes two inputs:

1. **Parent Directory Path** — The root folder where the search should start
2. **Keyword** — The text to match against file names

Example:

```
Parent Directory: C:\Users\Documents
Keyword: report
```

The tool will search all subdirectories under `C:\Users\Documents` and list all files whose file name contains *report*, along with their full paths. ([GitHub][1])

---

## 💡 Getting Started

### 📌 Prerequisites

✔ Java Runtime Environment (JRE) installed on your system
✔ Command line or terminal access

---

### ▶️ Using the JAR (No Compilation Needed)

1. Download `findfile.jar` from the repo.
2. Open a terminal / command prompt.
3. Navigate to the folder where `findfile.jar` exists.
4. Run the command:

```bash
java -jar findfile.jar
```

5. Enter the directory path and keyword when prompted.

---

### 🧰 Build from Source

1. Extract `FindFileRep.7z`
2. Open the project in your favorite IDE (e.g., Eclipse, IntelliJ) or compile via command line:

```bash
javac -d bin src/*.java
```

3. Package into a JAR:

```bash
jar cvfm findfile.jar Manifest.txt -C bin .
```

---

## 📸 Screenshot

You can add screenshots to the `/images` directory (for example, `Capture.PNG`) and embed them here:

```md
![FindYourFile Search](images/Capture.PNG)
```

---

## 🧠 Example Use Cases

✔ Quickly find documents by keyword
✔ Locate source code files across large projects
✔ Identify media files that match a given string

---

## 🚀 Why Use This Tool?

Unlike manual browsing and searching, **FindYourFile** automates the process and gives you immediate results with full paths — saving time and effort when navigating large file systems. ([GitHub][1])

---

## 📦 Requirements

* **Java 8+** (runtime needed for executing the JAR)
* No external dependencies

---

## 🧩 Notes

* Searches are **case-sensitive** unless modified in source code
* You can customize the logic to make it case-insensitive or add regex support

---

## 📝 License

*(Add your desired license here, e.g., MIT License.)*

---

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a new branch (e.g., `feature/search-regex`)
3. Make your changes
4. Submit a pull request

---

## 💬 Support

If you have any questions, issues, or feature requests, feel free to **open an issue** on GitHub.

---
