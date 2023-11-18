## LLM Dialogue Web App with Django & FastAPI 🌐🐍

Welcome to the LLM Dialogue Web App, an innovative platform combining the robustness of Django with the agility of FastAPI to create an interactive dialogue experience with Large Language Models (LLM). This application serves as a bridge between users and advanced AI, facilitating seamless communication with state-of-the-art language models.

### Features ✨

- **Django-based Web Form**: A user-friendly interface for inputting queries and receiving responses from the LLM.
- **FastAPI Backend**: Efficient and scalable server handling the communication with LLMs.
- **Real-time Interaction**: Quick and responsive interactions with LLMs for a smooth user experience.
- **Easy to Deploy**: Set up and run the application with minimal configuration.

### Getting Started 🚀

![image](https://github.com/DmPanf/Simple_FastAPI_Django_LLM/assets/99917230/cacd6842-93eb-4a5f-b80e-91df0e3da3ae)

---

#### Prerequisites

Ensure you have the following installed:
- Python 3.8 or higher
- pip (Python package manager)
- Virtual environment (recommended)

#### Installation

1. **Clone the Repository**
   ```bash
   mkdir WebLLM && cd WebLLM
   git clone git@github.com:DmPanf/Simple_FastAPI_Django_LLM.git .
   ```

2. **Set up a Virtual Environment** (Optional but recommended)
   ```bash
   python -m venv venv
   source venv/bin/activate  # For Linux/macOS
   venv\Scripts\activate  # For Windows
   ```

3. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

#### Running the Application

1. **Start the Django Web Server**
   ```bash
   cd django_app
   python manage.py runserver
   ```

2. **Launch the FastAPI Server**
   ```bash
   cd fastapi_server
   uvicorn main:app --host 0.0.0.0 --port 5000
   ```

### Usage 🖥️

- Navigate to `http://localhost:8000` in your web browser to access the Django web form.
- Enter your query and submit.
- The FastAPI server processes the request and communicates with the LLM.
- View the response from the LLM on the web interface.

### Contributing 🤝

For major changes, please open an issue first to discuss what you would like to change.

### License 📜

This project is licensed under the [MIT License](LICENSE).

### Contact 📬

- Dmitrii - [📨 e-Mail](bunta.bit@mail3.me)
- Project Link: [https://github.com/DmPanf/Simple_FastAPI_Django_LLM](https://github.com/DmPanf/Simple_FastAPI_Django_LLM.git)
