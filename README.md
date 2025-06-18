# FastApi-Project1
This is a full-stack authentication system built using **FastAPI** (backend) and **Streamlit** (frontend) with **PostgreSQL** as the database. It allows users to register and log in securely with hashed passwords.


---

## 🚀 Tech Stack

| Layer        | Technology       |
|--------------|------------------|
| Frontend     | Streamlit        |
| Backend      | FastAPI          |
| Database     | PostgreSQL       |
| Password Hashing | bcrypt       |
| API Testing  | Swagger UI       |
| Environment  | Python, VS Code  |

---

## 📁 Project Structure

fastapi-auth-app/
│
├── log.py # FastAPI backend with register/login API
├── streamlit.py # Streamlit frontend UI for user auth
└── README.md


---

## ⚙️ Setup Instructions

### 🔧 1. Clone the Repository

```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd fastapi-auth-app
🐍 2. Create and Activate Virtual Environment (Recommended)
python -m venv venv
source venv/bin/activate  # For Linux/Mac
venv\Scripts\activate     # For Windows
📦 3. Install Required Libraries
pip install fastapi uvicorn streamlit psycopg2-binary bcrypt requests
🛢️ 4. PostgreSQL Setup

Make sure PostgreSQL is installed and running. Create a database named demo:

CREATE DATABASE demo;
Ensure your credentials match the following in log.py:

conn = psycopg2.connect(
    dbname="demo",
    user="postgres",
    password="root",
    host="localhost",
    port="5432"
)
🚀 How to Run the App

▶️ Run the FastAPI Backend
uvicorn log:app --reload
Visit API docs: http://127.0.0.1:8000/docs
💻 Run the Streamlit Frontend
Open a new terminal:

streamlit run streamlit.py
Visit frontend: http://localhost:8501
✨ Features

✅ User Registration with email, password, name, address, and Aadhar
✅ Passwords are hashed using bcrypt
✅ Secure Login with validation
✅ Streamlit UI for ease of use
✅ PostgreSQL as backend DB
✅ API testing via Swagger UI


Pull requests are welcome! Feel free to open issues and suggest features or improvements.

📃 License

This project is licensed under the MIT License.

🙋‍♀️ About Me

Nupur Shivani
Aspiring AI/ML Developer | Learning FastAPI & Full-Stack Development

Connect with me on LinkedIn 🌐 https://www.linkedin.com/in/nupur-shivani-150b96262


---

<img width="1470" alt="Screenshot 2025-06-18 at 7 12 42 PM" src="https://github.com/user-attachments/assets/35e08ed6-edfa-4659-8382-c063c27c084e" />
<img width="1470" alt="Screenshot 2025-06-18 at 7 12 30 PM" src="https://github.com/user-attachments/assets/8586b887-ea5f-46aa-8aba-78fa0328fe99" />
<img width="1470" alt="Screenshot 2025-06-18 at 7 11 22 PM" src="https://github.com/user-attachments/assets/745d3261-4945-4aa6-976f-362ea74a614c" />
<img width="1470" alt="Screenshot 2025-06-18 at 7 11 19 PM" src="https://github.com/user-attachments/assets/addf23dc-ffec-465e-8eca-cf331692b1ab" />
<img width="1470" alt="Screenshot 2025-06-18 at 7 09 04 PM" src="https://github.com/user-attachments/assets/63fb3ef0-0612-4dd1-8354-0f6a549c5980" />
<img width="1470" alt="Screenshot 2025-06-18 at 7 08 59 PM" src="https://github.com/user-attachments/assets/c70a540a-bee8-4b4e-88a8-384912d78884" />
<img width="1470" alt="Screenshot 2025-06-18 at 7 08 50 PM" src="https://github.com/user-attachments/assets/41a6c5de-6e7d-4dce-a1b7-9ef6b8885e62" />

