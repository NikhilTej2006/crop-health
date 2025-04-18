Crop Health Management System
This project is designed to monitor crop health using real-time camera feeds, machine learning-based disease detection, and IoT sensors. It helps detect plant diseases and update inventory automatically.

Features
Real-time plant disease detection via ESP32-CAM

Machine learning model for disease classification

Inventory update system for tracking diseased plants

Flask-based backend server for data processing

SQLite database for storing inventory data

Tech Stack
Machine Learning: TensorFlow, Keras

IoT: ESP32-CAM

Backend: Flask

Database: SQLite

Computer Vision: OpenCV

Getting Started
1. Clone the Repository
bash
Copy
Edit
git clone https://github.com/your-username/crop-health-management.git
cd crop-health-management
2. Install Requirements
bash
Copy
Edit
pip install -r requirements.txt
3. Run Flask Server
bash
Copy
Edit
cd server
python app.py
4. Upload Image or Stream from ESP32-CAM
Ensure that the ESP32-CAM is sending images to the Flask server.

Project Structure
bash
Copy
Edit
crop-health-management/
│
├── model/                 # ML model and preprocessing code
├── server/                # Flask server and database integration
├── esp32/                 # ESP32-CAM firmware code
├── utils/                 # Helper scripts
└── README.md              # Project documentation
Future Scope
Integrate weather and soil data

Deploy on Raspberry Pi for edge inference

Add mobile app support for real-time alerts

License
This project is licensed under the MIT License.
