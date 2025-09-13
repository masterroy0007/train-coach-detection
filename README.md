# Train Coach Detection and Reporting

## 🟢 Overview
This project processes a video of a train from the side view and counts the number of coaches using YOLOv5 object detection. It extracts frames from the video and generates a PDF report containing selected frames covering the entire train.

## 📂 Setup Instructions
1. Open the provided Jupyter Notebook in Google Colab.
2. Upload your train video file in the `/content/` folder.
3. Run all the cells step by step.
4. The model uses the YOLOv5 library, which is downloaded and set up in the notebook.
5. The final report PDF will be generated at `/content/train_report.pdf`.

## ✅ Key Features
- Splits the train video into frames.
- Detects and counts coaches using YOLOv5.
- Annotates frames with bounding boxes.
- Selects representative frames to cover the full train.
- Generates a PDF report with images and captions.
- Provides a downloadable link to the report.

## ⚙ Technologies Used
- Python 3.12
- OpenCV
- YOLOv5 (object detection)
- img2pdf (for report generation)
- Google Colab

## 🟠 Limitations
- Accuracy depends on the quality and angle of the video.
- YOLOv5 model needs properly annotated data for best results.
- Works with side-view videos only.

## 📦 Submission Files
- Jupyter Notebook
- train_report.pdf
- README.md# train-coach-detection
