# Role Based Todo Application

This application is a role-based task management system designed for efficient task handling, with three types of user roles: **Admin**, **Team Manager**, and **Team Member**.

---

## Roles and Authentication

### Admin
- The **Admin** role is predefined in the system and is responsible for managing the application.
- **Credentials:**
  - **Username:** `admin`
  - **Password:** `admin12`
- **Note:** If the Admin Panel does not load and shows a white screen, **please reload the page**.

### Team Manager and Team Member
- To create a **Team Manager** or **Team Member** account:
  1. **Sign Up**: Enter a custom username, password (minimum 6 characters), and specify the role (Team Manager or Team Member).
  2. A success popup will confirm the account creation.
  3. Log in using the credentials you just created.

---

## Features and Dashboard

### Common Features for Team Managers and Team Members:
1. **Add a Task**
   - Enter task title, description, priority (Low, Medium, High), category (General, Personal, Work, Shopping, Health, Study), and due date.
2. **Search and Filter Tasks**
   - Search for tasks by title or filter them by priority and categories.
3. **Statistics Overview**
   - View key task statistics:
     - Total tasks
     - Completed tasks
     - High-priority tasks
     - Tasks due soon
4. **Task Display Formats**
   - View tasks in **List View**, **Grid View**, or **Calendar View**.
5. **Mark Tasks**
   - Mark tasks as **Complete** or delete them.

### Additional Features for Team Managers:
- **Assign Tasks**
  - Team Managers can assign tasks to specific Team Members.

---

## Admin Panel Features

The **Admin Panel** provides comprehensive management capabilities. Below are its key features:

1. **Dashboard Statistics:**
   - **Total Tasks**: Displays all tasks in the system.
   - **Completed Tasks**: Shows the number of tasks marked as completed.
   - **Pending Tasks**: Displays tasks still in progress or not yet started.
   - **Overdue Tasks**: Lists tasks that have passed their due date.
   - **Total Team Managers**: Displays the count of all Team Managers in the system.
   - **Total Team Members**: Shows the count of all Team Members in the system.

2. **Task Priority Distribution:**
   - A visual representation of tasks categorized by priority (High, Medium, Low).

3. **Task Completion Trend:**
   - A graphical chart showing trends of tasks created and completed over time.

4. **Task Management:**
   - View all tasks with detailed information:
     - Task ID
     - Title
     - Created At
     - Assigned To
     - Priority
     - Category
     - Status
     - Due Date
   - Perform the following actions:
     - **View** task details
     - **Delete** tasks

5. **Bulk Actions:**
   - Archive multiple tasks at once or reassign tasks as needed.

**Note:** If the Admin Panel does not load properly (shows a white screen), **reload the page** to fix the issue.

---

## Technical Details

### Local Storage
- The application currently uses **local storage** for saving tasks and user data.

### Tech Stack
- **Frontend Framework:** [Vite](https://vitejs.dev/) with **TypeScript**.

### Repository
- Clone the repository using:
  ```bash
  git clone https://github.com/RDRishabh/Role_Based.git

### Navigate
- Navigate to the project directory:
  ```bash
  cd Role_Based

### Install
- Install Dependencies
  ```bash
  npm install

### Run
- Run the development server
  ```bash
  npm run dev


