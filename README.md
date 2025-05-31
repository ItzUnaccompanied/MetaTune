# 🎵 MetaTune

**MetaTune** is a simple and powerful Python-based tool for extracting metadata (like title and artist) from MP3 files and automatically renaming them accordingly.

> 🎧 Perfect for music collectors, DJs, and anyone who wants clean, consistent file names for their music library.

---

## ✨ Features

- Extracts MP3 metadata (Title, Artist, Duration, Bitrate)
- Automatically renames files to match: `Artist - Title.mp3`
- Prevents overwriting by checking for existing files
- Sanitizes filenames to remove illegal characters
- Cool ASCII intro just for fun 😎

---

## 🔧 Requirements

- Python 3.6+
- [`mutagen`](https://mutagen.readthedocs.io/en/latest/) library

Install the required dependency with:

```bash
pip install mutagen
````

---

## 🚀 Usage

1. Place `Maim.py` in the folder with your `.mp3` files.
2. Run the script:

```bash
python Main.py
```

3. Enter the name of the MP3 file (without `.mp3`).
4. MetaTune will display the metadata and rename the file accordingly.

---

## 📂 Example

```
File name (no .mp3) > my_song

Duration: 212.45 seconds  
Bitrate: 192000 bps  
Queen - Bohemian Rhapsody  
Renamed to: Queen - Bohemian Rhapsody.mp3
```

---

## ⚠️ Notes

* Make sure your MP3 files have valid ID3 tags (`Artist` and `Title`) or the script may not work as expected.
* Avoid using this tool on read-only files or directories where you don't have permission to rename files.
* Files that already exist with the target name won't be overwritten.

---

## 💡 Planned Features

* Batch mode for renaming multiple files at once
* Album art display/download

---

## 📄 License

This project is open-source under the [MIT License](LICENSE).

---

## 🧠 Credits

Created by **unaccompanied**

