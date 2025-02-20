## 📌 **YouTube Cookies Exporter - Chrome Extension to Export YouTube Cookies**  

**YouTube Cookies Exporter** is a Chrome extension designed to extract and export cookies from `youtube.com`. These cookies can be used with the tool [`yt-dlp`](https://github.com/yt-dlp/yt-dlp) to download videos that require authentication without manually logging in every time.  

## 🚀 **Features**  
✅ Automatically exports cookies from `youtube.com`.  
✅ Generates a Netscape HTTP Cookie file compatible with `yt-dlp`.  
✅ Enables authenticated video downloads.  
✅ Simple and fast—export cookies with a single click into Download directory, overwriting old file if exists.  

## 🔧 **How to Install**  
1. Download or clone this repository.  
2. Open **chrome://extensions/** in your browser.  
3. Enable **Developer Mode** in the top right corner.  
4. Click **"Load unpacked"** and select the project folder.  
5. Done! You can now export your YouTube cookies easily.  

## 🎯 **How to Use with yt-dlp**  
1. Use the extension to export cookies and save the cookies.txt file into Download directory.  
2. In your terminal, run the following command in `yt-dlp`:  
   ```sh
   yt-dlp --cookies path/to/download_folder/cookies.txt https://www.youtube.com/watch?v=VIDEO_ID
   ```
3. Enjoy seamless authenticated downloads!  

📢 **Contributions are welcome**: If you have ideas to improve the extension, feel free to open an issue or submit a pull request. 🚀
