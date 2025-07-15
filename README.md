Theft Detection using YOLO + PVT
This project is a real-time theft detection system using a combination of YOLO (You Only Look Once) and PVT (Pyramid Vision Transformer). It is capable of detecting suspicious activity in video streams or from CCTV footage.
Features
- Real-time detection using YOLO + PVT
- Works with webcam or pre-recorded video
- Modular and easy-to-read code
- Supports `.mp4` input files
Requirements
Install the required Python packages using:
bash
pip install -r requirements.txt
Project Structure
-yolopvt/               
-README.md              
-.gitignore             
- requirements.txt      
Usage:
To run the detection on a video:
bash
python main.py --video path/to/video.mp4
Or use your webcam:
bash
python main.py --webcam

