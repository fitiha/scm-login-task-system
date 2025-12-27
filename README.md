# SCM Login & Task Management System

## 1. Project Overview

The SCM Login & Task Management System is a simple web-based application developed to demonstrate Software Configuration Management (SCM) principles.
The project focuses on version control, change management, branching, and release management using GitHub.

The system allows a user to:
*   Log in to the system
*   View a dashboard with assigned tasks
*   See task status, priority, and due dates

## 2. Technologies Used

*   **HTML5** – Structure of the application
*   **CSS3** – Styling and layout
*   **JavaScript (Vanilla)** – Client-side logic
*   **JSON** – Task data storage
*   **Git & GitHub** – Version control and SCM processes

## 3. System Features

### 3.1 Login Page
*   Simple login form with username and password
*   Redirects authenticated users to the dashboard

### 3.2 Dashboard
*   Displays a list of tasks
*   Shows:
    *   Task title
    *   Status (Pending, In Progress, Completed)
    *   Priority (High, Medium, Low)
    *   Due date

### 3.3 Task Management
*   Tasks are loaded dynamically from a JSON file
*   Clean, card-based UI for readability

## 4. Project Structure

```
scm-login-task-system/
│
├── src/
│   ├── login.html
│   ├── dashboard.html
│   └── tasks.json
│
├── docs/
│   ├── CI-Register.docx
│   ├── CR-Form.docx
│   └── Configuration-Audit-Report.docx
│
└── README.md
```

## 5. Software Configuration Management Practices

This project demonstrates the following SCM concepts:

### 5.1 Version Control
*   Git was used to track all changes
*   Meaningful commit messages were applied

### 5.2 Branching Strategy
*   `main` branch used as the stable baseline
*   Feature branches used for development
*   Changes merged via Pull Requests

### 5.3 Change Management
*   Change Requests were formally documented
*   Approved changes were implemented and merged
*   Change history is traceable in GitHub

### 5.4 Release Management
Two official releases were created using GitHub Releases:
*   **v1.0** – Initial release of the system
*   **v1.1** – Release after implementing an approved change request

## 6. How to Run the Project

1.  Clone the repository:
    ```bash
    git clone https://github.com/fitiha/scm-login-task-system.git
    ```

2.  Navigate to the project folder:
    ```bash
    cd scm-login-task-system/src
    ```

3.  Open `login.html` in a web browser.

## 7. Limitations

*   Authentication is simulated (no backend)
*   Data is stored locally in JSON
*   No database or server-side logic

These limitations are acceptable given the academic focus on SCM concepts.

## 8. Conclusion

This project successfully demonstrates key Software Configuration Management practices, including configuration identification, version control, change control, and release management. It serves as a practical example of applying SCM concepts to a small web-based system.

## 9. Author

**Group Members:**
1.  Mikias Goitom (ETS1080/14)
2.  Natnael Fisseha (ETS1231/14)
3.  Natnael Necho (ETS1266/14)
4.  Tamirat Dejene (ETS1518/14)
5.  Temesgen Abebayehu (ETS1534/14)

**Course:** Software Configuration Management
**Institution:** AASTU
