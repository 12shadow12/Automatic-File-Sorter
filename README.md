# 🗃️ Automatic File Sorter

A Python-based script that helps you organize thousands of files by file type — directly from a Jupyter Notebook. Perfect for cleaning up cluttered directories like your Downloads folder or desktop.

---

## 📌 Description

This tool scans a given directory, detects the file types (based on their extensions), and automatically:

- Creates folders for each file type (e.g., `PDF`, `JPG`, `MP4`)
- Moves files into their corresponding folders
- Works on Windows, macOS, and Linux
- Built with Python using only standard libraries

---

## 📸 Example

**Before sorting:**

```
Downloads/
├── report.pdf
├── image1.jpg
├── movie.mp4
├── notes.txt

arduino
Copy
Edit

**After running the script:**

Downloads/
├── PDF/
│ └── report.pdf
├── JPG/
│ └── image1.jpg
├── MP4/
│ └── movie.mp4
├── TXT/
└── notes.txt
```

yaml
Copy
Edit

---

## 🚀 How to Use

1. **Open the Jupyter Notebook** (`.ipynb` file).
2. Set the `source_dir` variable to the folder you want to organize.
3. Run all the cells in the notebook.
4. Watch as your files are automatically sorted into clean, labeled folders.

---

## 🛠️ Requirements

- Python 3.x
- Jupyter Notebook
- No third-party libraries needed (`os`, `shutil`, etc.)

---

## ✅ Features

- Fully automated sorting
- No setup needed — run instantly in Jupyter
- Easy to customize or expand (e.g., group by file size or date)
- Cross-platform compatible

---

## 💡 Future Ideas

- Add GUI for drag-and-drop folder selection
- Filter files by last modified date
- Add undo option or dry-run preview
- Integration with Task Scheduler / cron jobs

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

Made by 12shadow12.  
Feel free to use and contribute!
