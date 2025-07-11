# 🎨 Virtual Paint

This project lets you **draw in the air** using a colored marker tracked via your webcam and OpenCV!

---

## 📌 Features

- Track multiple colors (e.g., blue, yellow markers)
- Draw in real-time on the screen
- Uses HSV masking + contours
- Adjustable ranges for different markers

---

## 📂 Files

- [`color_detection.ipynb`](https://github.com/Vaishnavi-Dhane/ComputerVision-MiniProjects/blob/f962dae168930cac81533f9b050f6c0ac4f082de/VirtualPaint/color_detection.ipynb) — Jupyter Notebook with the full code
  
- `virtual-paint-opencv.mp4` — Demo video showing it in action

---

## ▶️ How to Run

1. Clone this repo.
2. Open the notebook `color_detection.ipynb` in Jupyter Notebook.
3. Run all cells step by step.
4. Bring your colored marker in front of your webcam — start drawing!

---

## ⚙️ Requirements

- Python 3.x
- OpenCV  
  Install with:
  ```bash
  pip install opencv-python

---

## 🧩 What I learned

While building this Virtual Paint project, I learned:
- How to capture webcam feed with OpenCV
- How to convert BGR to HSV for better color detection
- How to create color masks
- How to find contours and detect the largest object
- How to draw shapes and lines on frames in real-time

This helped me understand real-time computer vision basics!

---

