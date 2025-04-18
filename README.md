# Diagnosify AI

*Diagnosify AI* is a web-based healthcare platform that uses Machine Learning and Django to predict diseases based on user-input symptoms and provides doctor consultation in real-time. The project is designed to assist patients in early diagnosis and enable healthcare professionals to offer timely support online.

---

## Features

•⁠  ⁠Disease prediction using ML algorithms with up to *94.78% accuracy*
•⁠  ⁠Role-based login for Patients and Doctors
•⁠  ⁠Input symptom interface for patients
•⁠  ⁠Doctor suggestion based on predicted disease
•⁠  ⁠Real-time chat consultation system
•⁠  ⁠Responsive UI built with HTML, CSS, Bootstrap & JavaScript
•⁠  ⁠Secure authentication and PostgreSQL database integration

---

## Technologies Used

•⁠  ⁠*Backend*: Django (Python)
•⁠  ⁠*Machine Learning*: Scikit-learn, Pandas, NumPy, Joblib
•⁠  ⁠*Frontend*: HTML, CSS, Bootstrap, JavaScript, Jinja2
•⁠  ⁠*Database*: PostgreSQL
•⁠  ⁠*IDE*: VS Code / Jupyter Notebook
•⁠  ⁠*Dataset*: Symptom-disease dataset (4,900+ records, 132 features)

---

## Installation

1.⁠ ⁠Clone the repository:
  git clone https://github.com/B-S-Praveen-Kumar/Diagnosify-AI.git
  cd Diagnosify-AI

2. Create a virtual environment and activate it:
   python -m venv venv
   source venv/bin/activate
   # On Windows:
   venv\Scripts\activate

3. Install dependencies:
   pip install -r requirements.txt

4. Set up PostgreSQL and update youur database settings in 'settings.py'.

5. Run migrations:
   python manage.py makemigrations
   python manage.py migrate

6. Run the server:
   python manage.py runserver

---

## Usage

•⁠  ⁠Visit ⁠ http://127.0.0.1:8000/ ⁠ in your browser.
•⁠  ⁠Register as a patient or doctor.
•⁠  ⁠Patients can input symptoms and get disease predictions.
•⁠  ⁠Doctors can consult with patients via chat.

---

## Screenshots

(Include screenshots of home page, symptom input, prediction results, and chat)

---

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

---

## License

This project is open-source and available under the [MIT License](LICENSE).

---

## Author

•⁠  ⁠*Praveen Kumar B.S* – [LinkedIn](https://www.linkedin.com/in/your-profile) | [GitHub](https://github.com/yourusername)

---

## Acknowledgements

•⁠  ⁠Dataset sourced from Kaggle and medical data repositories
•⁠  ⁠Inspired by the need for accessible, smart healthcare solutions
