# Spotify Downloader for Google Colab

An interactive Google Colab widget that allows users to download Spotify tracks using [spotDL](https://github.com/spotDL/spotify-downloader), and optionally save the output as a ZIP file to Google Drive or download it locally.

🚀 Features

- Paste any Spotify URL to download music.
- Automatically zips the downloaded files.
- Optional Google Drive upload.
- Optional local download.
- Simple, user-friendly Colab widget interface.

🧠 Why Use Google Colab?

- Using Google Colab has several benefits:
- No Installation Required – Everything runs in your browser.
- Free Cloud Resources – No stress on your local computer.
- Google Drive Integration – Directly save downloads to the cloud.
- Cross-Platform – Works on Windows, macOS, Linux, and mobile.
- Temporary & Safe – Storage is reset on every session; you decide what to save.

📦 Installation

This tool is designed to be used within [Google Colab](https://colab.research.google.com/). Simply run the notebook and follow the interface.

🛠 Usage
- 📂 Open the Colab notebook here: [🔗 View in Colab](https://colab.research.google.com/drive/1O4GAzwLuOOGF9GfP5reXUIsoTXXQ4iRx?usp=sharing)
- Mount your Google Drive.
- Paste the Spotify track, album, or playlist URL.
- Select whether to: (Upload the ZIP to Google Drive | Download the ZIP to your local device)
- Click "Download & ZIP".
- Enjoy your music 🎶

📁 Output
- All music is downloaded to a folder called music/.
- A timestamped ZIP archive (e.g., music_20250509_153045.zip) is created.
- Depending on selected options, the ZIP is uploaded to Google Drive and/or downloaded to your computer.

🧾 License
- This project uses spotDL, which is licensed under the MIT License.

🙏 Credits
- Music downloading powered by spotDL.
- Interface built using ipywidgets in Google Colab.

⚠️ Please respect copyright laws. This tool is intended for personal use only.

Required packages:
```python
!pip install -q spotdl ipywidgets
