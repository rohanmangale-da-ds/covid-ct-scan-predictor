Project Description
COVID-CT Scan Predictor is a web-based deep learning application that predicts COVID Positive or COVID Negative from lung CT scan images using a fine-tuned ResNet18 model in PyTorch.

🧠 Backend: Flask + PyTorch (Deep Learning Model for Image Classification)

🌐 Frontend: HTML + TailwindCSS + JavaScript for a simple, responsive UI

🔮 Prediction: Classifies CT images and shows confidence probabilities


Key Features
Upload lung CT scan images (JPG/PNG).

Get instant prediction (COVID Positive / Negative).

Displays model confidence probabilities.

Gives actionable advice for positive/negative results.

Fully responsive frontend with TailwindCSS.


Technologies Used

Python 3.10+
PyTorch
Flask
Torchvision
Pillow (PIL)
Flask-CORS
HTML, TailwindCSS, JavaScript


Project Structure
covid-ct-scan-predictor/
│
├── app.py                     # Flask backend with PyTorch model
├── resnet18_covid_ct_scans_classification.pth  # Trained model file
├── static/                    # Optional for frontend assets
├── templates/                 # Optional if using Jinja2
├── frontend.html              # Frontend HTML page
├── requirements.txt           # Python dependencies
└── README.md                  # Project documentation












