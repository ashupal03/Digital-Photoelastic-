# Digital Photoelastic Dashboard

This project is a web dashboard for advanced photoelastic image analysis using Python (Flask, OpenCV) and React.

## How to Run

1. **Backend setup:**  
    - `cd backend`
    - `python -m venv venv`
    - `source venv/bin/activate` (or `venv\Scripts\activate` on Windows)
    - `pip install -r requirements.txt`
    - `python app.py`

2. **Frontend setup:**  
    - Open a new terminal  
    - `cd frontend`
    - `npm install`
    - `npm start`

3. **Usage:**  
    - Visit `http://localhost:3000` in your browser.
    - Upload and analyze photoelastic images!

## Features

- Upload photoelastic images
- Process images to extract fringe order, principal stress, and orientation
- ROI and line profile selection
- Download stress data (CSV/NumPy)