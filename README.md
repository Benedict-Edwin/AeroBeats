# AeroBeats
# Gesture-Controlled Music Player 🎵✨  

A hands-free music player that uses **hand gestures** to control playback. Built with Python, OpenCV, MediaPipe, and Pygame.  

## Features  

🎶 **Gesture Controls:**  
- 👍 **Right Thumb Up** → Play/Pause  
- ✋ **Left Palm Open** → Stop  
- ↔️ **Right Hand Swipe** → Next/Previous Track  

📂 **File Management:**  
- Load multiple audio files (MP3, WAV, OGG)  
- Visual feedback of current track and status  

🖥️ **Real-Time UI:**  
- Displays hand landmarks and gesture recognition  
- Shows current track name and playback status  

## Requirements  

- Python 3.6+  
- OpenCV (`pip install opencv-python`)  
- MediaPipe (`pip install mediapipe`)  
- Pygame (`pip install pygame`)  
- Tkinter (usually included with Python)  

## How to Use  

1. **Run the script:**  
   ```bash
   python gesture_music_player.py
   ```
2. **Select audio files** when prompted (file dialog will appear).  
3. **Perform gestures** in front of the camera:  
   - Raise your **right thumb** to play/pause.  
   - Show your **left open palm** to stop.  
   - **Swipe right hand left/right** to change tracks.  
4. Press **'Q'** to quit.  

## Customization  

⚙️ **Adjustable Parameters (in code):**  
- `swipe_threshold`: Sensitivity for swipe detection.  
- `swipe_cooldown`: Delay between swipe actions.  
- `gesture_cooldown`: Prevents accidental double-triggering.  

🎚️ **Supported Audio Formats:**  
- MP3, WAV, OGG (add more in Pygame if needed).  

## Future Improvements  

🔮 **Possible Upgrades:**  
- Volume control via hand height ✋⬆️⬇️  
- Playlist management 🗒️  
- Air-drumming mode 🥁 (trigger sound effects)  

---  

**Note:** Works best in good lighting with clear hand visibility. 
🚀 **Rock on—without touching a thing!** 🤘
