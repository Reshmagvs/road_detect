# 🛣️ Road Lane Detection using OpenCV

This computer vision project detects road lane lines from a dashcam driving video using traditional image processing techniques in OpenCV. It simulates a basic lane-following system, which is an essential component of autonomous driving.

## 🎥 Input vs Output Video

### 🔹 Original Input Video  
<video src="https://github.com/user-attachments/assets/0b14c4a3-f1c7-417f-bb34-58b8f2309ed5" width="400" controls></video>

### 🔸 Output Video with Lane Detection  
<video src="https://github.com/user-attachments/assets/a0d5acb2-529b-40c5-9548-52e2c5852ec6" width="400" controls></video>

## 📹 Input Video

- **File:** `solidWhiteRight.mp4`  
- **Source:** [Udacity Self-Driving Car Dataset](https://github.com/udacity/CarND-LaneLines-P1)
- Clean white-lane driving footage recorded in daylight

---

## ⚙️ How It Works

1. Convert video frame to **grayscale**
2. Apply **Gaussian blur** to reduce noise
3. Use **Canny edge detection**
4. Define **region of interest (ROI)** to mask unwanted parts
5. Apply **Hough Line Transform** to detect straight lines
6. **Average and extrapolate** the left/right lane lines
7. Overlay detected lanes onto the original frame
   
---

## 🔭 Future Enhancements

- Support **curved lanes** using polynomial fitting
- Integrate **real-time webcam lane detection**
- Use **color masks** to detect yellow lanes better
- Deploy in **embedded systems or mobile devices**

---

⭐ If you found this project useful, please consider starring the repository!

