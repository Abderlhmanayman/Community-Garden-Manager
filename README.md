# Community-Garden-Manager

## 📌 Project Overview
A comprehensive full-stack web application developed following the complete Software Development Life Cycle (SDLC). The project implements the **MVC (Model-View-Controller)** architecture to ensure a clean separation of concerns and scalable code.

## 🏗️ System Architecture & Design
This project is heavily documented with complete Software Engineering artifacts. The `docs/` folder contains:
- **Software Requirements Specification (SRS)**
- **System Architecture Diagram**
- **Design Patterns applied:** [اكتب هنا لو استخدمت حاجة زي Singleton أو Factory، لو مفيش امسح السطر ده]
- **UML Diagrams:**
  - Class Diagram (Multiple iterative versions)
  - Use Case Diagram
  - Sequence Diagram
  - Activity Diagram
  - Communication Diagram
  - Package Diagram
- **Entity-Relationship Diagram (ERD)**

## 💻 Technologies Used
- **Frontend:** HTML5, CSS3, JavaScript
- **Backend:** PHP
- **Database:** MySQL
- **Architecture:** MVC Pattern

## 📁 Project Structure
The source code is organized following the MVC design pattern:
- `/Models` - Handles database connections and data logic.
- `/Views` - Contains HTML/CSS templates for the user interface.
- `/Controllers` - Manages the flow of data between Models and Views.
- `/docs` - Contains all system diagrams and SRS documentation.
- `/database` - Contains the `.sql` export file.

## ⚙️ How to Run the Project
1. Clone this repository or download it as a ZIP file.
2. Move the project folder to your local server directory (e.g., `htdocs` for XAMPP).
3. Open your database manager (e.g., phpMyAdmin) and import the `.sql` file located in the `/database` folder.
4. Update the database connection variables in your Model/Config files if necessary.
5. Run the project through your localhost browser.
