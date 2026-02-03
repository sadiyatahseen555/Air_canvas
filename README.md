**Air Canvas - Hand Gesture Drawing Application**

Air Canvas is an interactive computer vision application that lets you draw on the screen using only your hand gestures. 
It uses **MediaPipe** for real-time hand tracking and **OpenCV** for drawing, allowing you to create art in the air using your index finger—no touchscreen or mouse needed!

---

## 🎯 Features

- 🎨 Draw with your index finger in real-time
- 🖐️ Switch between 5 colors using gesture-based selection
- 🧼 Clear the canvas instantly with a simple gesture
- 👆 Interactive color palette and UI controls
- 🖼️ Real-time webcam feedback with gesture overlays
- ⚡ Lightweight and runs on most systems with a webcam

---

## 🛠️ Requirements
Install the required Python libraries with:
```
pip install -r requirements.txt
```

## 🚀 How to Run
<p>1.Ensure your webcam is connected.<br>
2.Run the Python script:
python air_canvas.py<br>
3.Allow access to your webcam if prompted.<br>
4.Use gestures to draw and interact!</p>

## ✋ Gesture Controls
<p>Gesture	Action<br>
☝️ Index finger up---	>Start drawing<br>
✌️ Index + Middle fingers up---	>Select color / Clear<br>
✋ Hover over "CLEAR" box--- >Clear the canvas<br>
👉 Hover over a color box	--- >Change brush color<br>
⌨️ Press q key---> Quit the application</p>

## 🎨 Color Palette
<p>The top bar displays these color options:<br>
🔵 BLUE<br>
🟢 GREEN<br>
🔴 RED<br>
🟡 YELLOW</p>

## 📁 File Structure
<p>air_canvas.py — Main Python script<br>
requirements.txt — List of Python dependencies<br>
README.md — This documentation</p>

## ❗ Troubleshooting
<p>-Make sure your webcam is properly connected.<br>
-Run the app in a well-lit environment for better gesture detection.<br>
-If you encounter errors, try updating opencv-python or mediapipe.</p>

# 📜 License
This project is free to use for personal, educational, and non-commercial purposes.

# 🙏 Acknowledgements
<p>Air Canvas is a group project created by a team of undergraduate students as part of our coursework,
emphasizing teamwork and creativity in applying computer vision concepts.<br>

This project was developed by the following team members:

- @Ruhetarannum (https://github.com/Ruhetarannum)
- @sadiyatahseen555 (https://github.com/sadiyatahseen555)  
- @AmreenNeema (https://github.com/AmreenNeema)
- @Shahid110604 (https://github.com/Shahid110604) 

MediaPipe by Google<br>
OpenCV</p>
