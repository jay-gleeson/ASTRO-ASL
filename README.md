<p align="center">
  <img alt="GitHub License" src="https://img.shields.io/github/license/isliese/ASTRO-ASL">
  <img src="https://img.shields.io/badge/Python-3776AB?logo=python&amp;logoColor=fff" alt="Python">
  <img src="https://img.shields.io/badge/-scikit--learn-%23F7931E?logo=scikit-learn&amp;logoColor=white" alt="Scikit-learn">
  <img src="https://img.shields.io/badge/NumPy-4DABCF?logo=numpy&amp;logoColor=fff" alt="NumPy">
  <img src="https://img.shields.io/badge/TensorFlow-ff8f00?logo=tensorflow&amp;logoColor=white" alt="TensorFlow">
  <img src="https://img.shields.io/badge/MediaPipe-4285F4?logo=mediapipe&logoColor=white" alt="MediaPipe Badge">
  <img src="https://img.shields.io/badge/HTML-%23E34F26.svg?logo=html5&logoColor=white" alt="HTML Badge">
  <img src="https://img.shields.io/badge/CSS-639?logo=css&logoColor=fff" alt="CSS Badge">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=000" alt="JavaScript Badge">
  <img src="https://img.shields.io/badge/Flask-000?logo=flask&logoColor=fff" alt="Flask Badge">
  <img src="https://img.shields.io/badge/Vercel-%23000000.svg?logo=vercel&logoColor=white" alt="Vercel Badge">
  <br>
   <div><img alt="ASTRO ASL logo" src="https://github.com/user-attachments/assets/e89141a7-9766-471d-bcea-59eec2efe7cd"></div>
</p>

# 👽 ASTRO ASL
A live ASL letter transcription tool using Python and MediaPipe. 💫

ASTRO ASL (American Sign Language) is an artificial intelligence-powered sign language alphabet transcriber. Using a image detection model, this project detects what letters are presented to the webcam, outputting the translated message to the console. Using a trained model and a free sign language dataset, the project works offline.

Built, developed, and presented at [Fullyhacks 2025](https://fullyhacks.acmcsuf.com/), put on by [ACMCSUF](https://acmcsuf.com/).

This project was awarded Most Technical! 🏆

## 🚀 Steps to Use

1. **Clone the Repository**:
  ```bash
  git clone https://github.com/isliese/astro-asl.git
  cd astro-asl
  ```
2. Set Up Virtual Environment:
  ```
  python -m venv venv
  .\venv\Scripts\activate
  ```
3. Install Dependencies:

Ensure you have Python 3.10 or 3.9 installed.
Install the necessary packages from requirements.txt:

  ```
  pip install -r requirements.txt
  ```
4. Train the Model:

Use your own dataset or the sample dataset to train the model. Note: This project has only been tested with the following dataset, so additional customization may be needed for your own dataset.
Download the dataset from Kaggle - [American Sign Language Dataset](https://www.kaggle.com/datasets/ayuraj/american-sign-language-dataset). Then run the model training script:

  ```
  python training_model.py
  ```

6. Run the Application:
  ```
  python app.py
  ```

## 🤝 Contributing
We welcome contributions! Please follow these steps:
1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Submit a pull request with a detailed description of your changes.

## 👥 Team
| Role | Member |
|------|--------|
| Backend / Research | Owin |
| Backend / Research | Jay |
| Frontend / Design | Isla |
| Frontend / Design | Sema |

## 🙏 Credits  

This project uses the following technologies, libraries, and datasets:

### Tech Stack
- Frontend: **HTML+CSS, JavaScript**
- Backend: **Python**

### Libraries:
- **Flask** – A micro web framework for Python.
- **TensorFlow** – An open-source library for numerical computation and large-scale machine learning.
- **Scikit-learn** – A machine learning library, used for building the Random Forest model.
- **NumPy** – A library for numerical operations.
- **MediaPipe** – A library for real-time computer vision.

### Acknowledgements:
[American Sign Language Dataset](https://www.kaggle.com/datasets/ayuraj/american-sign-language-dataset) – A dataset used for training the the model.

## License  
MIT License
