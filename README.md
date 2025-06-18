# BasketballMatchanalysis
This project uses a YOLO segmentation model and a Kalman Filter to **track the basketball** in a video and estimate its **real-time speed**. The output is a video with the tracked trajectory and overlaid speed per frame.
- Loads a basketball match video
- Uses a custom YOLO segmentation model (`best_seg.pt`) to detect the ball
- Tracks the ball's position using a Kalman Filter for smoother prediction
- Calculates and displays the ball’s speed in pixels/second
- Saves:
- An annotated output video
- Individual processed frames
- Requirements

- Python 3.8+
- OpenCV
- NumPy
- PyTorch
- Ultralytics YOLO

Install them with:

```bash
pip install opencv-python numpy torch ultralytics
