# 💰 Expense Management System

This project is an **end-to-end Expense Management System** consisting of a **Streamlit frontend application** and a **FastAPI backend server**.  
It allows users to record daily expenses, update entries, and view insightful analytics by **category** and **month** — all powered by a MySQL database.

---

## 🧩 Key Features

- 📅 Add & update expenses for a selected date
- 🗃️ Store expense records in a MySQL database
- 📊 Analytics dashboard
  - Expense breakdown by **category**
  - Monthly expense trend visualization
- 🔗 REST API powered by FastAPI
- 🖥️ Interactive UI built with Streamlit
- 🧪 Includes test structure for validation
- 📝 Structured logging for backend events

---


## Project Structure

- **frontend/**: Contains the Streamlit application code.
- **backend/**: Contains the FastAPI backend server code.
- **tests/**: Contains the test cases for both frontend and backend.
- **requirements.txt**: Lists the required Python packages.
- **README.md**: Provides an overview and instructions for the project.

---

## Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/DEVANSH-KUMAR-SINGH/Expense-Tracker-Web-Application.git
   cd Expense-Tracker-Web-Application
   ```
   
2. **Install dependencies:**:
   
   ```commandline
    pip install -r requirements.txt
   ```
   
3. **Run the FastAPI server:**:
   
   ```commandline
    uvicorn server.server:app --reload
   ```
   
4. **Run the Streamlit app:**:
   
   ```commandline
    streamlit run frontend/app.py
   ```
---

## 🧠 Learnings & Concepts Gained

✔️ Building a full-stack Python application (Frontend + Backend + DB)
✔️ Designing and consuming REST APIs
✔️ Implementing CRUD operations with MySQL
✔️ Data aggregation and analytics queries
✔️ Structuring a modular Streamlit application
✔️ Using Pydantic models for data validation
✔️ Implementing logging for debugging & monitoring
✔️ Working with virtual environments & dependency management
✔️ Writing test-ready and scalable project architecture

---

## 🤝 Contributions

Contributions and ideas are welcome!
Feel free to submit an issue or open a pull request.

---

## 📜 License

This project is open-source and available under the MIT License.

---

## 🙌 Acknowledgements

Built using:
- FastAPI ⚡
- Streamlit 📊
- MySQL 🗄️
- Python 🐍
