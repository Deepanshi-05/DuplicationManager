
# 🧠 Intelligent Application Manager

**Project Code:** JP-001  
**Technologies:** Java, Hashing Libraries, Rule Engine , Apache Commons IO 

## 📌 Project Overview

This project is an **intelligent application management tool** that identifies and eliminates duplicate applications based on **content analysis**, not filenames or timestamps. It also **organizes applications** into categories using a **rule-based system**.

> 🧠 Duplicate detection is based on SHA-256 content hashing, and categorization is performed using user-defined rules from a `rules.json` file.

---

## ✨ Key Features

- ✅ **Content-Based Duplicate Detection**
  - Identifies duplicates even if filenames, types, or timestamps differ
  - Uses cryptographic hash functions (e.g., SHA-256) to compare files

- 🧠 **Rule-Based Categorization**
  - Automatically organizes applications into categories using rules defined in `rules.json`
  - Rules can be based on metadata, paths, or file descriptions

- 🧹 **Duplicate Removal Options**
  - CLI/GUI interface to select and remove duplicates
  - Optional backup or quarantine before deletion

- 📁 **Configuration Management**
  - Users can define which directories to scan
  - Easy-to-edit `rules.json` file

- 📜 **Logging and Reporting**
  - Actions are logged to `log.txt`
  - Summary reports in `report.txt`

---

## 🚀 Advanced & Innovative Features (Optional Additions)

- 🤖 **AI-Based Similarity Detection** (Beyond exact hash match)
- 💬 **GPT-Based Categorization Assistant**
- 🗣️ **Voice-Controlled Duplicate Management**
- 📊 **Visual Heatmap of Duplicate Locations**
- 📦 **Cloud Integration for Backup**
- 🔁 **Real-Time Monitoring Daemon**

---

## 📂 Project Structure

```
/ibm2
│
├── rules.json          # Contains user-defined categorization rules
├── command.txt         # Command history or saved input
├── log.txt             # Logging of duplicate detection/removal
├── report.txt          # Final report of categorized/removed files
├── .git/               # Git history (optional)
└── (src/)              # Java or Python source code (not included here)
```

---

## ⚙️ How It Works

1. Scans the target directory recursively.
2. Generates hash for each application file.
3. Identifies and lists duplicates.
4. Applies categorization rules from `rules.json`.
5. Logs results and optionally deletes duplicates.

---

## 📌 Dependencies

### Java Version:
- JDK 17+
- Apache Commons IO
- Apache Commons Codec (for SHA-256)
---

## 📘 How to Use

### Java
```bash
javac AppScanner.java
java AppScanner
```


## 📝 To-Do / Future Enhancements

- [ ] GUI Interface (JavaFX )
- [ ] Rule-based suggestion engine
- [ ] Integration with cloud backup
- [ ] Visual reports (PDF/HTML)

---

## 👥 Authors
- Nandini  & Team
- IBM Hackathon Round 2 Submission

## 📃 License
MIT License - free to use and modify

