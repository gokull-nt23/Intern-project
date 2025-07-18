

# 🗂️ File Organizer Script

This Python script automatically organizes files in a specified folder into categorized subfolders based on file extensions.

---

## 📁 Features

- Automatically scans and organizes files by type:
  - **Images** (.jpg, .jpeg, .png, .gif)
  - **Videos** (.mp4, .mkv, .mov)
  - **Documents** (.pdf, .docx, .txt, .xls, .xlsx)
  - **Audio** (.mp3, .wav)
  - **Executables** (.exe, .msi)
  - **Archives** (.zip, .rar)
  - **Scripts** (.py, .js, .sh, .bat)
- Creates folders automatically if they don't exist
- Skips folders and unsupported file types
- Easy to configure and customize

---

## 🔧 Requirements

- Python 3.x
- No external libraries required (uses `os` and `shutil`)

---

## 🚀 How to Use

1. **Clone or Download the Script**

2. **Set the Directory Path**
   
   Open the script and change the following line to the folder you want to organize:
   ```python
   path = "C:/Users/hp/OneDrive/Desktop/organizer"

    Run the Script

    python file_organizer.py

    ✅ Your files will be sorted into folders like Images/, Documents/, Videos/, etc.

✏️ Customization

Want to support more file types? Simply add them to the file_types dictionary in the script:

file_types = {
    'NewCategory': ['.ext1', '.ext2'],
    ...
}

🛑 Notes

    This script moves files — not copies them.

    Unknown file extensions are skipped (not deleted).

    Make sure the folder you organize does not contain important subdirectories, as it skips folders but doesn’t protect them in any way.

🧑‍💻 Author

Created by Gokull NT
💬 Feedback welcome!
