# Tok Khemra - TikTok Video Downloader

## 📌 About
**Tok Khemra** is a professional TikTok video downloader that allows you to:
- Download **individual videos** or **all videos from a profile**.
- Choose the **number of videos** to download.
- Save videos **directly to a selected folder**.
- Use a **dark mode toggle** for better visibility.
- Access **quick social media links** (TikTok, Telegram, GitHub).

## 🚀 Features
✅ **Download by Video Link** - Paste a TikTok video URL and download it instantly.  
✅ **Download All Videos from Profile** - Enter a TikTok profile link and download multiple videos.  
✅ **Set Video Count** - Choose how many videos to download (e.g., download the latest 10).  
✅ **Custom Save Folder** - Select where to store the downloaded videos.  
✅ **Dark Mode Toggle** - Easily switch between light and dark themes.  
✅ **Social Media Links** - Quickly access TikTok, Telegram, and GitHub.  
✅ **GUI-Based or CLI-Based** - Choose between GUI mode or run from the terminal.  

## 🛠 Installation & Usage
### **1️⃣ Clone the Repository**
To get started, **clone** the repository and navigate to the project folder:
```sh
git clone https://github.com/KevinKhemra007/Tiktok_Downloads.git
cd Tiktok_Downloads
```

### **2️⃣ Install Required Dependencies**
Before running the tool, install the required Python packages:
```sh
pip install yt-dlp browser-cookie3 tkinter requests
```

### **3️⃣ Run the Application**
You can run the tool in two ways:
#### ✅ **Option 1: Run with GUI**
```sh
python Tiktok_Downloads.py
```
#### ✅ **Option 2: Run in Terminal (CLI Mode)**
For users who prefer a command-line interface, use:
```sh
python Tiktok_Downloads.py --url <TikTok_Link> --save_path <Folder>
```
Example:
```sh
python Tiktok_Downloads.py --url https://www.tiktok.com/@example/video/12345 --save_path "C:/Users/YourName/Downloads"
```

### **4️⃣ Convert to EXE (Optional)**
To generate an EXE file, install `auto-py-to-exe`:
```sh
pip install auto-py-to-exe
```
Then run:
```sh
python -m auto_py_to_exe
```
- Select **Tiktok_Downloads.py**.
- Choose **One File** and **Window-Based**.
- Click **Convert .py to .exe**.

Your EXE file will be in the `dist` folder.

## 🎮 Usage Guide
1️⃣ **Paste a TikTok video/profile link** into the input box.  
2️⃣ **Set the number of videos** to download (if downloading from a profile).  
3️⃣ **Select a folder** to save your downloads.  
4️⃣ Click **"Download"** to start downloading.  

## 🖥 System Requirements
- Python **3.8+**
- Windows, macOS, or Linux

## 📄 License
**Created by Khemra - 2024**. This software is **for personal use only**. Unauthorized distribution or modification is prohibited.

## 🔗 Social Links
📌 **TikTok:** [@raatechofficial](https://www.tiktok.com/@raatechofficial)  
📌 **Telegram:** [@hackisreal007](https://t.me/hackisreal007)  
📌 **GitHub Repository:** [Tiktok_Downloads](https://github.com/KevinKhemra007/Tiktok_Downloads.git)
