# 🌱 Plant Disease Prediction Web App 

This project is a web application built with Flask that predicts plant diseases from uploaded images. It leverages a pre-trained Keras model to identify diseases and provides users with detailed information about the predicted disease, including its causes and prevention/cure methods. This application aims to help farmers and gardeners quickly identify and address plant diseases, promoting healthier plant growth and reducing crop loss.

🚀 **Key Features**

*   **Image Upload:** Allows users to upload images of plant leaves or stems. 🖼️
*   **Disease Prediction:** Uses a pre-trained Keras model to predict the disease present in the image. 🧠
*   **Detailed Information:** Provides comprehensive information about the predicted disease, including its causes, symptoms, and treatment options. ℹ️
*   **User-Friendly Interface:** Offers a simple and intuitive web interface for easy interaction. 🖱️
*   **Vercel Deployment:** Configured for easy deployment on the Vercel platform. ☁️

🛠️ **Tech Stack**

*   **Frontend:** HTML, CSS, JavaScript (basic templating via Flask)
*   **Backend:** Python, Flask
*   **Machine Learning:** TensorFlow, Keras, Pillow (PIL), NumPy
*   **Deployment:** Vercel
*   **Other:** `markupsafe`, `io`

📦 **Getting Started**

### Prerequisites

*   Python 3.x installed
*   `pip` package installer
*   TensorFlow, Keras, Pillow, NumPy, Flask installed

### Installation

1.  **Clone the repository:**
    ```bash
    git clone <repository_url>
    cd <repository_directory>
    ```

2.  **Install the required Python packages:**
    ```bash
    pip install flask tensorflow keras pillow numpy markupsafe
    ```

3.  **Download the pre-trained model:**
    Download the `trained_plant_disease_model.keras` file and place it in the directory specified in `model.py` (C:\\Users\\V\\Downloads\\).  You may need to adjust the path in `model.py` if you place it elsewhere.

💻 **Running Locally**

1.  **Run the Flask application:**
    ```bash
    python app.py
    ```

2.  **Open your web browser and navigate to `http://0.0.0.0:10001/` to access the application.**

📂 **Project Structure**

```
plant-disease-prediction/
├── app.py           # Main Flask application file
├── model.py         # Plant disease prediction model
├── utils.py         # Dictionary containing disease information
├── templates/       # HTML templates
│   ├── index.html   # Home page
│   └── display.html # Display prediction results
├── static/          # Static assets (CSS, JavaScript, images)
├── vercel.json      # Vercel deployment configuration
└── README.md        # Project documentation
```



🤝 **Contributing**

Contributions are welcome! Please feel free to submit pull requests with bug fixes, new features, or improvements to the documentation.

📝 **License**

This project is licensed under the [Specify License] License - see the [LICENSE.md](LICENSE.md) file for details.


