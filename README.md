# Blind Assistant AI
Real-time accessibility assistant that combines computer vision, OCR, distance estimation and voice guidance for low-vision users.
## Capabilities
- Detects objects with YOLO.
- Estimates distance and direction from camera frames.
- Reads visible text with Tesseract OCR.
- Announces events with voice output.
- Exposes a FastAPI/WebSocket backend and a React interface.
- Provides configurable danger alerts and pause/resume controls.
## Stack
Python, OpenCV, Ultralytics YOLO, Tesseract OCR, FastAPI, WebSockets, React and Tailwind CSS.
## Project structure
- `modules/`: detection, OCR, distance and speaker services.
- `api/`: FastAPI backend and real-time WebSocket endpoints.
- `web/`: React client.
- `main.py`: desktop entry point.
## Local setup
Install Python 3.8+, Node.js, a webcam and Tesseract OCR. Then install the Python dependencies with `pip install -r requirements.txt`, install the frontend dependencies from `web/`, and start the API and client using the project scripts.
## Safety note
This is an academic assistive-technology prototype. It must not be treated as a certified mobility or emergency system.
## Portfolio note
Collaborative project presented in Yahya Aferdi's portfolio; contributors and project history are preserved.
