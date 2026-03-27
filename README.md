📂 File Organizer Script (Python)
📌 Overview

This project is a simple Python-based file organizer that automatically sorts files in a directory into categorized folders based on their file extensions.

It helps keep your workspace clean by organizing files like Excel sheets, images, text files, and CSVs into separate folders.

🚀 Features
Automatically scans a given directory
Creates folders if they don’t already exist
Moves files into categories:
📊 Excel files (.xlsx)
🖼️ Image files (.jpg, .png, etc.)
📄 Text files (.txt)
📑 CSV files (.csv)
Prevents duplicate file moves



🛠️ Technologies Used
Python
Built-in modules:
os
shutil
📁 Folder Structure (After Running Script)
Your Directory/
│
├── excel files/
├── csv files/
├── text files/
├── image files/
├── your_script.ipynb / .py




⚙️ How It Works
Specify the directory path:
path = r"D:/Python Files/"
The script:
Reads all files in the directory
Creates category folders (if missing)
Moves files based on their extensions



▶️ How to Run
Option 1: Jupyter Notebook
Open the .ipynb file
Run all cells
Option 2: Python Script
Convert to .py (if needed)
Run:
python file_organizer.py



⚠️ Important Notes
Ensure the path exists before running
Use correct path formatting (r"path" recommended for Windows)
The script will move files permanently (not copy)
🔧 Possible Improvements
Add support for more file types (PDF, videos, etc.)
Add logging system
Add GUI (Tkinter / PyQt)
Add undo functionality
Allow dynamic folder creation based on extensions



💡 Example Use Case

If your folder looks like this:

report.xlsx
data.csv
notes.txt
image.png

After running the script:

excel files/report.xlsx
csv files/data.csv
text files/notes.txt
image files/image.png
