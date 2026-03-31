# Air Canvas 🎨

## Description  📌
A Python-based Air Canvas project that uses hand tracking and finger gestures to draw in the air using OpenCV and MediaPipe.

---

## Features ✅
- Draw in the air using your index finger
- Real‑time hand tracking with MediaPipe
- Multiple drawing colors
- Gesture‑based color switching
- Clear‑canvas gesture
- Smooth stroke tracking using deque lists
- Live preview window + drawing canvas window

---

## Tech Used  🛠️ 
- Python  
- OpenCV  
- MediaPipe  
- NumPy  
- Deque (for stroke buffering)

---

## How It Works
- The webcam tracks your hand in real time.  
- MediaPipe detects hand landmarks and identifies finger positions.  
- If the index finger is raised alone → drawing starts.  
- If index + middle finger are raised together → color selection or clear action.  
- Strokes are drawn smoothly onto a virtual canvas using line tracking.  

---
