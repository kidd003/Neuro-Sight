🧠 Neuro-Sight: Brain Tumor Classification with Deep Learning

A deep learning-powered web application to detect and classify brain tumors from MRI scans using a custom CNN model. Built with PyTorch and deployed with Streamlit.

📌 Project Highlights

🧠 4-Class Classification of brain conditions from MRI:

Glioma Tumor

Meningioma Tumor

Pituitary Tumor

No Tumor Detected

🎯 High Accuracy: Custom CNN model achieving ~98% validation accuracy

🎛️ Intuitive Interface: Streamlit-powered web interface for easy upload and prediction

⚡ Fast Inference: Optimized for quick predictions (under 1 second)

🏥 Medical Prototype: Designed as a proof-of-concept for clinical decision support

🛠 Tech Stack
Core Technologies

Python 3.9+

PyTorch 2.0

Streamlit 1.25

Torchvision

Pillow (PIL)

Model Architecture
# Custom CNN Architecture
Input: 1x64x64 Grayscale MRI
Architecture: Conv2D → ReLU → MaxPool → Dropout → FC → Softmax
Parameters: ~1.2M trainable parameters

🚀 Deployment
Cloud Deployment

The application is currently deployed on Streamlit Cloud:
🔗 Live Demo

Local Installation
# Clone repository
git clone https://github.com/kidd003/Neuro-Sight.git
cd Neuro-Sight

# Install dependencies
pip install -r requirements.txt

# Launch application
streamlit run app.py

📊 Dataset & Training

Source: Kaggle Brain Tumor Dataset

Preprocessing: Grayscale conversion, normalization, 64x64 resizing

Training: 50 epochs with Adam optimizer

Validation Accuracy: ~98%

Model File: brain_tumor_model.pth

🌐 Connect With Me

Let's collaborate or chat about AI/ML projects!






📝 Usage Guide

Access the web app via the live demo
 or local installation

Upload a brain MRI scan in JPG/PNG format

View the model's prediction and confidence scores

(Optional) Toggle advanced options for detailed analysis

🤝 Contributing

Contributions are welcome! Please open an issue or PR for:

Model improvements

UI enhancements

Additional documentation

📜 License

MIT License - See LICENSE
 for details.

Created with ❤️ by Shaikh Emad
