# Hogwarts Simulation - Advanced Programming Project

## 📌 Introduction
This project is a **Windows Forms application** developed in **C#** as part of an advanced programming university course. The goal is to simulate aspects of the **Hogwarts School of Witchcraft and Wizardry** from the Harry Potter universe, focusing on **object-oriented programming (OOP) principles** and advanced C# concepts.

## 🎯 Features Implemented
### 🔹 Main Menu
- A **main form** with a **background image** inspired by the Harry Potter films.
- Three buttons for user role selection:
  - **Admin**
  - **Master (Professor)**
  - **Student**
- Buttons highlight when hovered over.

![Main Menu](https://github.com/Mahdi-Rahbar/Hogwarts-Simulation---Advanced-Programming-Project/blob/main/Screenshots/Screenshot%202025-01-28%20211013.png?raw=true)

### 🔹 Admin Panel
- A login form for administrators (**Username & Password validation**).
- If credentials are correct, the **Admin Panel** opens with a different background.
- Three main functionalities:
  1. **Send Letter**: Allows the admin to send letters.
     - Opens a small form inside the main admin panel.
     - Requires a recipient username; if empty, the letter is sent to all students.
     - Letter content must not be empty.
  2. **Teacher List**: Displays a list of teachers with **ID, name, surname, and type**.
  3. **Student List**: Displays similar details for students.

![Admin Panel](https://github.com/Mahdi-Rahbar/Hogwarts-Simulation---Advanced-Programming-Project/blob/main/Screenshots/Screenshot%202025-01-28%20211111.png?raw=true)
![Send Letter](https://github.com/Mahdi-Rahbar/Hogwarts-Simulation---Advanced-Programming-Project/blob/main/Screenshots/Screenshot%202025-01-28%20211529.png?raw=true)
![Teacher List](https://github.com/Mahdi-Rahbar/Hogwarts-Simulation---Advanced-Programming-Project/blob/main/Screenshots/Screenshot%202025-01-28%20211546.png?raw=true)
![Student List](https://github.com/Mahdi-Rahbar/Hogwarts-Simulation---Advanced-Programming-Project/blob/main/Screenshots/Screenshot%202025-01-28%20211553.png?raw=true)

### 🔹 Master (Professor) Panel
- A form where professors can **select courses to teach**.
- Clicking **Select Unit** opens another form inside the panel.
- Professors can choose from a list of courses and save their selection.
- **Error handling** ensures no **time conflicts** between selected courses.

![Master Panel](https://github.com/Mahdi-Rahbar/Hogwarts-Simulation---Advanced-Programming-Project/blob/main/Screenshots/Screenshot%202025-01-28%20212541.png?raw=true)
![Select Unit](https://github.com/Mahdi-Rahbar/Hogwarts-Simulation---Advanced-Programming-Project/blob/main/Screenshots/Screenshot%202025-01-28%20212615.png?raw=true)

### 🔹 Student Panel
- The student dashboard has **three buttons**:
  1. **View Letters**: Allows students to check received invitation letters.
  2. **Get Ticket**: Generates a ticket for the Hogwarts Express, including **departure time**.
  3. **Go to Hogwarts**: Students can enter Hogwarts **only if they have received an invitation letter and a ticket**.
- All three actions work together to simulate the **entry process**.

![Student Panel](https://github.com/Mahdi-Rahbar/Hogwarts-Simulation---Advanced-Programming-Project/blob/main/Screenshots/Screenshot%202025-01-28%20212710.png?raw=true)

## 📂 Data Handling
- The project reads user data from a **JSON file**, which contains:
  - Usernames, passwords, names, roles (Admin, Teacher, Student)
  - Other necessary details
- Data is handled using **Newtonsoft.Json (v13.0.3)**.

## 🛠 Technologies & Libraries Used
- **C# .NET (Windows Forms)** for UI and logic.
- **Newtonsoft.Json 13.0.3** for JSON data handling.
- **Object-Oriented Programming (OOP) principles** like **inheritance** and **encapsulation**.

## 🚀 How to Run
1. Clone this repository.
2. Open the project in **Visual Studio**.
3. Make sure the required **JSON file** is present.
4. Run the project.

## 🔮 Future Enhancements
- Adding **more interactions** and **events** from the Hogwarts world.
- Implementing a **database** instead of JSON for data storage.
- Expanding gameplay mechanics (e.g., adding classes, grading, and spells).

---
Developed for the **Advanced Programming Course - University Project**.

