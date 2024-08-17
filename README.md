# Employee-Leave-Management-System
This project is an online centralized application to automate the workflow of leave applications and their approvals.


## Brief Description

The **Employee Leave Management System** is a web application built with Python and Django, designed to streamline the process of managing employee leave requests. This system provides a centralized platform for employees to submit and manage their leave requests and for administrators to review and approve these requests. It supports functionalities for viewing remaining leave days, generating new leave requests, and managing employee records.

### Key Features:
- **Employee Dashboard:** View remaining leave days, submit new leave requests, and manage existing requests.
- **Administrator Dashboard:** Review and approve leave requests, manage employee details, and update leave balances.

This application uses MySQL for data storage and provides a user-friendly interface for both employees and administrators to efficiently handle leave management tasks.

---

## Instructions to Set Up and Run the Project Locally

### Prerequisites
- Python 3.x
- MySQL database server
- Pip (Python package installer)

### Setup

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Mariyam3912/Employee-Leave-Management-System.git
   cd employee-leave-management-system
   ```

2. **Create a Virtual Environment:**
   ```bash
   python -m venv myenv
   ```

3. **Activate the Virtual Environment:**

   - On Windows:
     ```bash
     myenv\Scripts\activate
     ```

   - On macOS/Linux:
     ```bash
     source myenv/bin/activate
     ```

4. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

5. **Set Up the Database:**
   - Ensure that MySQL is running and create a database for the project.
   - Update the database settings in `project/settings.py` with your MySQL credentials and database name.

6. **Apply Migrations:**
   ```bash
   python manage.py migrate
   ```

7. **Create a Superuser (for Admin Access):**
   ```bash
   python manage.py createsuperuser
   ```

8. **Run the Development Server:**
   ```bash
   python manage.py runserver
   ```

9. **Access the Application:**
   - Open your web browser and go to `http://127.0.0.1:8000/` to access the application.

### Usage
- **Employee Access:** Log in using employee credentials to manage leave requests and view leave balances.
- **Administrator Access:** Log in using admin credentials to review leave requests, manage employees, and update leave balances.



