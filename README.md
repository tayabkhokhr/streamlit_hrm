# Streamlit HRM App

![Streamlit](https://img.shields.io/badge/Made%20with-Streamlit-ff4b4b?style=for-the-badge&logo=streamlit&logoColor=white)
![Python](https://img.shields.io/badge/Python-3.9+-blue?style=for-the-badge&logo=python&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Active-success?style=for-the-badge)

## 📋 Description

**Streamlit HRM App** is a simple, user-friendly Human Resource Management system developed in Python using the [Streamlit](https://streamlit.io/) framework. This app helps small organizations and HR teams to manage:

- Employee records  
- Leave tracking  
- Authentication-based access (Admin & HR roles)  
- CSV-based file storage (no SQL/database required)

## ✨ Features

- Secure Login System (Admin and HR roles)  
- Add, Edit, and Delete Employee Records  
- Apply and Manage Employee Leaves  
- Real-time updates stored in CSV files  
- Full Streamlit UI for interactivity  
- Deployable on Streamlit Cloud

## 🛠️ Built With

- [Python 3.9+](https://www.python.org/)  
- [Streamlit](https://streamlit.io/)  
- [Pandas](https://pandas.pydata.org/)

## 🔐 Default Login Users

| Role  | Username | Password  |
|-------|----------|-----------|
| Admin | admin    | admin123  |
| HR    | hr       | hr123     |

You can update these in the `hrm_app.py` file.

## 📁 Project Structure

```
streamlit-hrm-app/
├── hrm_app.py          # Main Streamlit application
├── requirements.txt    # Python dependencies
├── employees.csv       # Employee records (auto-created if missing)
├── leaves.csv          # Leave records (auto-created if missing)
└── README.md           # Project documentation
```

## 🚀 Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/streamlit-hrm-app.git
   cd streamlit-hrm-app
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the app:
   ```bash
   streamlit run hrm_app.py
   ```

## ☁️ Deploy on Streamlit Cloud

1. Push your project to a public GitHub repository  
2. Go to: [https://streamlit.io/cloud](https://streamlit.io/cloud)  
3. Click "New app", select your repo, set the file to `hrm_app.py`  
4. Click Deploy — and you're live!

## 📃 License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

## 🙋 Contact

Made by [Tayyab Khokhar](https://github.com/tayabkhokhr).  
Open to feedback, collaboration, and improvements.
