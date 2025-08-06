## Real-Time Cat Face Detection with OpenCV

This Python project uses **OpenCV** and the **`haarcascade file`** classifier to detect cat faces in real time using your device's camera. It runs a simple, lightweight detection loop and draws bounding boxes around any detected cat faces.

> **Note:** This tool is for educational, experimental, or pet-monitoring purposes. It's not intended for commercial or veterinary diagnostics.

---

## Project Overview

- Language: **Python 3**
- Library: **OpenCV (cv2)**
- Method: **Haar Cascade Classifier**
- Input: Live webcam feed
- Output: Real-time video with detected cat faces highlighted

---

## How It Works

This project uses OpenCV's pre-trained Haar cascade classifier for frontal cat faces. The webcam feed is analyzed frame-by-frame, and rectangles are drawn around detected cat faces.

---

## How to Run the Project

1. **Clone this repository**:

```bash
git clone https://github.com/your-username/cat-face-detector.git
cd cat-face-detector
````

2. **Install dependencies**:

```bash
pip install opencv-python
```

3. **Download the Haarcascade file** (if not already included):

You can get it from OpenCV's GitHub:
[haarcascade\_frontalcatface.xml](https://github.com/opencv/opencv/blob/master/data/haarcascades/haarcascade_frontalcatface.xml)

Place it in the project folder.

4. **Run the script**:

```bash
python cat_face_detector.py
```

---

## Output Screen
![WhatsApp Image 2025-08-06 at 12 02 53_a206ed67](https://github.com/user-attachments/assets/24aa4f19-ff6c-4f55-ac02-207fb20c979b)



---

## File Structure

```
cat-face-detector/
├── haarcascade_frontalcatface.xml
├── main.py
├── README.md
```

---


## References
* Augmented AI Tutorial:[2022 Learn OpenCV in 5 Hours | Python | 6 x Computer Vision Projects](https://www.youtube.com/watch?v=Oj5wHECTlzo)
* OpenCV Haarcascades: [https://github.com/opencv/opencv/tree/master/data/haarcascades](https://github.com/opencv/opencv/tree/master/data/haarcascades)
* Haar Cascade Documentation: [https://docs.opencv.org/3.4/db/d28/tutorial\_cascade\_classifier.html](https://docs.opencv.org/3.4/db/d28/tutorial_cascade_classifier.html)

---

Made with paws🐾 and OpenCV.
