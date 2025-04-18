# Expense Management System
A simple full-stack web app to **track daily expenses** with category-wise breakdown and analytics.

- 📊 Built with **Streamlit** (frontend) and **FastAPI** (backend)
- 🗃️ Uses **MySQL** for storing and retrieving expenses
- 📅 Add, update, and analyze expenses by date and category
- 📈 View summarized analytics with interactive charts

Ideal for personal budgeting and daily expense tracking.


## Project Structure

- **frontend/**: Contains the Streamlit application code.
- **backend/**: Contains the FastAPI backend server code.
- **tests/**: Contains the test cases for both frontend and backend.
- **requirements.txt**: Lists the required Python packages.
- **README.md**: Provides an overview and instructions for the project.


## Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/parthm2609/Expense-Management-System.git
   cd Expense-Management-System
   ```
1. **Install dependencies:**:   
   ```commandline
    pip install -r requirements.txt
   ```
1. **Run the FastAPI server:**:   
   ```commandline
    uvicorn server.server:app --reload
   ```
1. **Run the Streamlit app:**:   
   ```commandline
    streamlit run frontend/app.py
   ```
# Output
![Adding data](https://github.com/user-attachments/assets/e6930785-845c-421d-867c-9a5bc3584d89)
![Analytics](https://github.com/user-attachments/assets/5d281c56-9262-4e57-b2c3-9e55cb05c80b)

