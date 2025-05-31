# MetaTune

MetaTune is a simple Python tool that reads MP3 metadata and renames your MP3 files to the format:

```

Artist - Title.mp3

````

## Features

- Reads and displays MP3 title, artist, duration, and bitrate  
- Renames files automatically to `Artist - Title.mp3`  
- Prevents overwrites and sanitizes filenames  
- Runs easily in the terminal with no complex setup  

## Requirements

- Python 3.6 or higher  
- [mutagen](https://mutagen.readthedocs.io/en/latest/) library (`pip install mutagen`)

## Installation & Usage

1. Download `MetaTune.py`  
2. Place it in the same folder as your MP3 files  
3. Run the script with:
   ```bash
   python MetaTune.py
``

4. Enter the file name (without `.mp3`) when prompted
5. The script will rename your MP3 file based on its metadata

## Website

For more info and downloads, visit:
[http://metatune.getenjoyment.net/](http://metatune.getenjoyment.net/)

## License

This project is licensed under the MIT License.

---

*Created by unaccompanied*
