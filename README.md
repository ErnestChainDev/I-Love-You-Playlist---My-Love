# 💕 I Love You – Interactive Photo Gallery with Music Playlist

A romantic **3D spinning photo gallery** with an integrated **music playlist** — perfect for creating a special gift or memory showcase for your loved one.

---

## ✨ Features

- 🎠 **3D Spinning Photo Gallery** – Interactive carousel displaying your favorite photos  
- 🎵 **Music Playlist** – Auto-playing music player with multiple songs  
- 🖱️ **Click-to-Play Songs** – Select any song from the playlist  
- ⏭️ **Auto-Next Feature** – Automatically plays the next song when the current one ends  
- 💫 **Smooth Animations** – Beautiful transitions and hover effects  
- 📱 **Mobile Responsive** – Works on both desktop and mobile devices  
- ✅ **User Interaction Compliance** – Respects browser autoplay policies  

---

## 🎶 Current Playlist

1. **Bubbly** – Colbie Caillat  
2. **Realize** – Colbie Caillat  
3. **Walang Iba** – Ezra Band  
4. **When I Met You** – Justin Vasquez  

---

## 📁 Project Structure

```
project-folder/
│
├── index.html              # Main HTML file
├── main.css                # Stylesheet for gallery
├── main.js                 # JavaScript for 3D gallery
├── icon.png                # Favicon
├── README.md               # This file
│
├── img/                    # Photo gallery images
│   ├── img1.jpg
│   ├── img2.jpg
│   ├── img3.jpg
│   ├── img4.jpg
│   ├── img5.jpg
│   ├── img6.jpg
│   ├── img7.jpg
│   └── img8.jpg
│
└── music/                  # Music files (optional)
    ├── Colbie Caillat - Bubbly (Lyrics).mp3
    ├── Realize - Colbie Caillat (Lyrics).mp3
    ├── Walang Iba.mp3
    └── When I Met You.mp3
```

---

## 🚀 Getting Started

### 🧩 Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- 8 images for your photo gallery
- MP3 music files for the playlist

---

### ⚙️ Installation

1. **Clone or download the project**
   ```bash
   git clone <your-repo-url>
   cd i-love-you-gallery
   ```

2. **Add your photos**
   - Place **8 photos** in the `img/` folder.  
   - Name them `img1.jpg` through `img8.jpg`.  
   - Or update the image paths inside `index.html`.

3. **Add your music**
   - Place your MP3 files in the `music/` folder.  
   - Update the playlist inside `index.html` if you change filenames.

4. **Open the project**
   - Simply open `index.html` in your browser.  
   - Or serve locally for better performance:
     ```bash
     # Using Python 3
     python -m http.server 8000

     # Using PHP
     php -S localhost:8000

     # Using Node.js (http-server)
     npx http-server
     ```

---

## 🎨 Customization

### 🖼️ Changing Photos
Replace images in the `img/` folder or update paths in HTML:
```html
<img src="./img/your-photo-name.jpg" alt="">
```

### 🎧 Adding or Removing Songs
Edit the playlist array in `index.html`:
```javascript
const playlist = [
  { title: "Song Title", artist: "Artist Name", src: "./path/to/song.mp3" },
  { title: "Another Song", artist: "Another Artist", src: "./path/to/song2.mp3" },
];
```

### 🌈 Changing Colors
Modify CSS inside `main.css`:
```css
#playlist-container {
  background: rgba(255, 255, 255, 0.9); /* Background color */
}

.song-item.active {
  background: rgba(233, 30, 99, 0.5); /* Active song highlight */
}
```

### 💌 Changing Text
Update the text inside the spinning container:
```html
<p>My Love</p> <!-- Change this to your preferred text -->
```

---

## 🎮 How to Use

1. Open `index.html` in your browser  
2. Click **▶ Click to Play Music** to start the playlist  
3. Interact with the gallery:  
   - Drag to rotate  
   - Scroll to zoom in/out  
4. Control the music:  
   - Click any song to play  
   - Songs auto-advance and loop at the end  

---

## 🔧 Troubleshooting

### 🎵 Music doesn’t play
- Check MP3 file paths  
- Ensure files exist in the correct folder  
- Click the play button (required by browser autoplay policy)

### 🖼️ Images don’t show
- Verify image names and extensions  
- Make sure they’re in the `img/` folder  
- Confirm paths in `index.html`

### ⏭️ Playlist doesn’t advance
- Ensure `<audio>` tag doesn’t have the `loop` attribute  
- It should look like:
  ```html
  <audio id="bg-music"></audio>
  ```

---

## 🌐 Browser Compatibility

✅ Chrome / Edge (v90+)  
✅ Firefox (v88+)  
✅ Safari (v14+)  
✅ Mobile browsers  

---

## 📄 License

This project is **free for personal use**.  
Feel free to modify and share with your loved ones! 💖  

---

## 💝 Credits

- **Font:** [Dancing Script](https://fonts.google.com/specimen/Dancing+Script) from Google Fonts  
- **Music:** Belongs to respective artists and record labels  

---

## 🤝 Contributing

Want to improve this project? Here are some ideas:
- Add volume control  
- Add play/pause button  
- Add shuffle/repeat modes  
- Add a progress bar  
- Add keyboard shortcuts  
- Add fullscreen mode  

---

## ❤️ Made with Love

> “Created as a special gift to show someone how much you care.”  

Enjoy your romantic photo gallery! 💕🎵
