# 🥁 AI-Based Virtual Drumset 🎵

A real-time virtual drumset built using Python and OpenCV that allows you to play drums using colored objects (like sticks or markers) tracked by your webcam. When a colored object enters predefined zones on the screen, the system triggers keyboard events to simulate drum hits.

---

## 🚀 Features

- 🎯 **Color-based object tracking** using HSV masking.
- 🎥 **Live webcam feed** processing with OpenCV.
- ⌨️ **Keyboard simulation** using PyAutoGUI to trigger drum sounds.
- 📏 **Interactive hit zones** detected using contour analysis.
- ⚡ **Real-time response** with optimized video frame handling.

---

## 🧠 How It Works

1. Capture webcam video using OpenCV.
2. Convert frames to **HSV color space** to isolate specific colors (e.g., red or blue).
3. Track motion of colored objects (drumsticks) by detecting contours.
4. Define **zones on the screen** where a hit triggers a specific keypress.
5. Use `pyautogui.press()` to simulate keypress events (e.g., mapped to drums in a DAW or online drum kit).

---

## 🛠️ Technologies Used

- Python 3.x
- OpenCV
- NumPy
- PyAutoGUI
- Imutils

---

## 📸 Screenshots

> 
![github](https://github.com/YeswanthVelugoti/Virtual-DrumSet---AI/blob/main/virtualdrumsoutput.jpg)
---

## 🧪 How to Run

### 1. Clone the repository:
```bash
git clone https://github.com/your-username/AI-virtual-drumset.git
cd AI-virtual-drumset
```

### 2. Install dependencies:
```bash
pip install opencv-python numpy pyautogui imutils
```

### 3. Run the script:
```bash
python virtual_drumset.py
```

Make sure your webcam is active. Use a red/blue colored object to simulate a drumstick.

---

## 🎯 Applications

- Virtual musical instrument interfaces
- Interactive music education tools
- Gesture-controlled interfaces
- Fun AI/Computer Vision projects for students and beginners

---

## 🙋‍♂️ Author

**Yeswanth Sai Kumar Velugoti**  
[Email](mailto:yeswanthvelugoti@gmail.com) • [LinkedIn](https://www.linkedin.com/in/yeswanth-velugoti-4290741a0/)

