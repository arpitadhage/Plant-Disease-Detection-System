🌿 Plant Disease Detection System
AI-Based Crop Health Monitoring & Disease Classification Engine

Plant Disease Detection System is a deep learning–powered full-stack application that identifies plant leaf diseases from uploaded images and provides accurate classification with confidence scores.

Designed to assist farmers, researchers, and agri-tech platforms in early disease detection, improving crop yield and reducing agricultural losses.

🚀 Key Features

📷 Leaf Image Upload
Upload plant leaf images through an intuitive web interface.

🧠 Deep Learning Disease Classification
CNN-based model detects and classifies plant diseases with high accuracy.

📊 Confidence Score Display
Displays prediction probability for better reliability assessment.

🌱 Multi-Disease Support
Supports multiple plant species and disease categories.

🗂 Image & Prediction Management
Stores uploaded images and prediction results for future reference.

🔐 Secure Backend Integration
Structured backend for handling image processing and model inference.

🏗 System Architecture

Leaf Image Upload
⬇
Image Preprocessing
⬇
Deep Learning Model (CNN)
⬇
Disease Classification
⬇
Confidence Scoring
⬇
Result Display

🛠 Tech Stack
Frontend

React.js / HTML / CSS / JavaScript

Axios (API Calls)

Backend

Python / Flask (or FastAPI if used)

REST API Architecture

Image Processing (OpenCV / PIL)

Machine Learning

TensorFlow / Keras

Convolutional Neural Networks (CNN)

Trained on labeled plant disease dataset

📁 Project Structure
Plant-Disease-Detection-System/
├── backend/
│   ├── model/
│   ├── routes/
│   ├── app.py
│   └── requirements.txt
│
├── frontend/
│   ├── public/
│   ├── src/
│   └── package.json
│
└── README.md
⚙️ Installation & Setup
1️⃣ Clone Repository
git clone https://github.com/arpitadhage/Plant-Disease-Detection-System.git
cd Plant-Disease-Detection-System
2️⃣ Backend Setup
cd backend
python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate
pip install -r requirements.txt

Run backend:

python app.py

Backend runs at:

http://localhost:5000
3️⃣ Frontend Setup

Open new terminal:

cd frontend
npm install
npm start

Frontend runs at:

http://localhost:3000
🔐 Environment Variables
Variable	Description
MODEL_PATH	Path to trained model file
PORT	Backend server port
📊 Model Information

Architecture: Convolutional Neural Network (CNN)

Input: Leaf Image (Resized & Normalized)

Output: Disease Class + Probability

Training Dataset: Labeled Plant Disease Dataset (e.g., PlantVillage)

📌 Roadmap

 Real-time mobile camera integration

 Deploy model on cloud (AWS / Azure)

 Add fertilizer & treatment recommendation engine

 Multi-language farmer support

 Crop yield prediction integration

🎯 Use Cases

Farmers & Agricultural Experts

Smart Farming Applications

Agri-Tech Startups

Research & Educational Projects

Crop Monitoring Systems

🧠 Innovation Highlights

Enables early disease detection

Reduces crop loss and pesticide overuse

Supports precision agriculture

Scalable AI-driven agriculture solution

📜 License

MIT License

👩‍💻 Developed By

Arpita Dhage
B.Tech Computer Science (AI/ML)
