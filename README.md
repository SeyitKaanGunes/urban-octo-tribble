# 🗂️ Desktop File Organizer

This Python script helps you organize the files on your desktop by automatically moving them into folders based on their file types (e.g. Images, Documents, Videos, etc.).

## 🚀 Features
- Detects and categorizes files by their extensions
- Skips hidden files and files without extensions
- Avoids moving files that are currently open or in use
- Handles duplicate file names by renaming with incremental suffixes
- Handles permission errors gracefully

## 📂 Categorized Folders
Files are moved into the following folders (created automatically if not present):
- 📷 `Resimler` (.jpg, .png, .gif, etc.)
- 📄 `Belgeler` (.pdf, .docx, .txt, etc.)
- 🎞️ `Videolar` (.mp4, .mkv, etc.)
- 🎵 `Muzikler` (.mp3, .wav, etc.)
- 📦 `Sıkıştırılmış` (.zip, .rar, etc.)
- ⚙️ `Yürütülebilir` (.exe, .bat, etc.)
- 📁 `Diğer` (everything else)
