# pnemonia-detection
This is a Flask-based web application that uses a FastAI deep learning model to classify chest X-ray images into three categories: Viral Pneumonia, Bacterial Pneumonia, or Normal. The app predicts the condition and provides detailed information about the disease and its risk factors, making it useful for early screening and educational purposes.
Key Features:
🌐 Web Interface: Upload chest X-ray images easily through the browser.

🧠 Deep Learning Model: Uses a pre-trained FastAI model (export.pkl) for high-accuracy classification.

📋 Interpretive Output:

Displays the predicted condition.

Shows a description and risk factors for the detected class.

🗂️ Handles three classes:

Viral Pneumonia

Bacterial Pneumonia

Normal (Healthy Lungs)

⚙️ Workflow:
User uploads a chest X-ray image.

Image is saved and processed by the FastAI model.

Model predicts the class.

A tailored explanation with medical information is shown on the result page.

🧪 Technologies Used:
Python

FastAI for model training/inference

Flask for web framework

HTML/CSS for frontend

Werkzeug, Pathlib for secure file handling
