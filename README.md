# Todo App

The **Todo App** is a simple web application that allows users to manage their tasks and to-do lists. It is built using the **Atlas template of PHP**, and it integrates with a **React frontend** for a seamless user experience.

## Features

- Create, edit, and delete tasks.
- Mark tasks as completed.
- Filter tasks based on their status (completed or pending).
- User-friendly interface with a responsive design.

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/umarasghar/todo-app.git
   ```

2. **Navigate to the project directory**:
   ```bash
   cd todo-app
   ```

3. **Install dependencies**:
   ```bash
   composer install
   ```

4. **Configure the database**:
   - Create a new MySQL database.
   - Update the `.env` file with your database credentials.

5. **Run migrations**:
   ```bash
   php artisan migrate
   ```

6. **Start the development server**:
   ```bash
   php artisan serve
   ```

## Usage

1. **Access the app**:
   Open your web browser and navigate to `http://localhost:8000`.

2. **Register or log in**:
   - If you are a new user, create an account.
   - If you already have an account, log in.

3. **Add tasks**:
   - Click the "Add Task" button to create a new task.
   - Enter the task details and save it.

4. **Manage tasks**:
   - View your tasks on the dashboard.
   - Mark tasks as completed by clicking the checkbox.
   - Edit or delete tasks using the provided options.

5. **Filter tasks**:
   - Use the filter options to view completed or pending tasks.

## Technologies Used

- **Backend**: PHP (Laravel)
- **Frontend**: React
- **Database**: MySQL

## Contributors

- **Umar Asghar**
- **SF Qaiser**

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Happy coding! 🚀📝