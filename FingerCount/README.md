# ✋ Finger Count

This project detects and **counts the number of fingers** shown in front of your webcam using **OpenCV**.  
It uses color segmentation, contours, convex hull, and basic geometry to identify fingers.

---

## 📌 Features

- Detects a hand using color masking (HSV)
- Finds contours and convex hull to identify fingers
- Displays the finger count live on the webcam feed
- Simple & beginner-friendly logic

---

## 📂 Files

- [`HandGesture based finger_count.ipynb` ](https://github.com/Vaishnavi-Dhane/ComputerVision-MiniProjects/blob/main/FingerCount/HandGesture%20based%20FingerCount.ipynb)— Jupyter Notebook with full code
-[ `finger-count-output.mp4`](https://github.com/Vaishnavi-Dhane/ComputerVision-MiniProjects/raw/refs/heads/main/FingerCount/fingercount-opencv.mp4) — Demo video showing it in action

---

## ▶️ How to Run

1. Clone this repo.
2. Open the notebook `finger_count.ipynb` in Jupyter Notebook.
3. Run all cells step by step.
4. Show your hand in front of your webcam — see the finger count live!

---

## ⚙️ Requirements

- Python 3.x
- OpenCV  
  Install with:
  ```bash
  pip install opencv-python

---

##✨ What I Learned
How to use OpenCV for hand detection

Finding contours and convex hull

Using defects to calculate finger gaps

Drawing on webcam feed in real-time
