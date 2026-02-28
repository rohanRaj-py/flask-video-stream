# 🎥 Flask Video Streaming Application

A real-time webcam streaming web application built using Flask and OpenCV.
This project captures live video from your system camera and streams it directly to a web browser.

##🚀 Features

Live webcam streaming

Flask backend server

OpenCV integration

Real-time frame rendering in browser

Clean project structure

Dependency management using requirements.txt

##🛠️ Tech Stack

Python 3.x

Flask

OpenCV

HTML


Git & GitHub

##📂 Project Structure
flask-video-stream/

├── app.py  
├── requirements.txt  
├── .gitignore  
├── README.md  

├── templates/  
│   └── index.html  
 
⚙️ Installation Guide
1️⃣ Clone the Repository
git clone  https://github.com/rohanRaj-py/flask-video-stream.git
cd flask-video-stream
2️⃣ Create Virtual Environment
py -m venv venv

Activate (PowerShell):

.\venv\Scripts\Activate.ps1
3️⃣ Install Dependencies
pip install -r requirements.txt
4️⃣ Run the Application
python app.py

Now open your browser and go to:

http://127.0.0.1:5000/
📸 How It Works

OpenCV captures frames from your webcam.

Frames are encoded into JPEG format.

Flask streams frames using multipart HTTP response.

The browser continuously receives and displays frames.

👨‍💻 Author

Rohan Kumar Raj

⭐ If you like this project, consider giving it a star!
