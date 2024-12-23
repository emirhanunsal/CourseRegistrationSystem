
# Course Registration System

## 📖 Overview
The **Course Registration System** is a Python-based application designed to streamline the management of course enrollments, schedules, and interactions between students and staff. The system provides distinct functionalities for various user roles, including students, advisors, department heads, and department schedulers.

### 💻 Key Technologies and Concepts
- **Object-Oriented Programming (OOP)**: The system leverages OOP principles, encapsulating behaviors and attributes in classes such as `Student`, `Advisor`, `Course`, and `Transcript`.
- **Modular Design**: Each feature is implemented in dedicated modules, ensuring clean and maintainable code.
- **JSON-Based Persistence**: Data for students, courses, and staff are stored and manipulated in JSON files, ensuring portability and flexibility.
- **Abstraction and Inheritance**: Classes like `User` and `Staff` provide a foundation for more specialized roles through inheritance.

## 🚀 Features
### 👩‍🎓 Students
- Request courses.
- View notifications.
- Display course schedules.

### 🧑‍🏫 Advisors
- View and manage course requests.
- Approve or reject course requests.

### 🏛️ Department Heads
- Add and update courses.
- Display all available courses.

### 🕒 Department Schedulers
- Update course sections (time, place, etc.).
- Reset course sections individually or entirely.

### 📂 JSON Data Handling
- Persistent storage of data for students, courses, advisors, and more.
- Integration with JSON files for dynamic data loading and saving.
