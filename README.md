# omr_evaluator_opencv

# 📝 OMR Sheet Evaluation using Python & OpenCV

This project automates the detection and grading of Optical Mark Recognition (OMR) sheets used in multiple-choice exams. It processes a scanned image of the answer sheet, identifies marked bubbles, and compares them with an answer key to calculate scores.

## 📷 Sample Input
- Scanned OMR sheet image (`.jpg` or `.png` format)
- Bubbles arranged in a fixed format (e.g., 4 options per question)

## ⚙️ Features
- Preprocesses image (grayscale, blur, threshold)
- Detects filled bubbles using contour detection
- Filters valid bubbles by size and shape
- Maps answers to choices (A, B, C, D)
- Compares with the answer key and calculates total score
- Displays result and marked bubbles

## 🛠 Technologies Used
- Python 3
- OpenCV (cv2)
- NumPy

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/omr-evaluator.git
cd omr-evaluator
