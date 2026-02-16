## AssignMate
# CS2 - Computer Science 2

# Project Description
AssignMate is a simple command-line task management program that helps students keep track of assignments. It allows users to add tasks with subjects and due dates, view all tasks, mark tasks as done, delete tasks, and export tasks to a Markdown file. Tasks are saved locally so progress is not lost when the program is closed.
- This repository was developed by Misty Gean Moreno, Katarah Sabrina Abarca, and Adriann Gabriell Arpilleda.

# Problem Statement
A lot of students end up missing or forgetting their assignments simply because they don’t have a clear and organized way to keep track of them. AssignMate helps solve this problem by providing a simple, easy-to-use system that allows students to manage their tasks and keep an eye on their progress until everything is completed.

# Project Objectives
- Allow users to add assignments with a subject and due date
- Display all tasks with their status (Pending or Done)
- Enable users to mark tasks as completed
- Allow deletion of tasks
- Save tasks automatically for future use
- Export tasks to a readable Markdown file

# Updated Features
- Add task with title, subject, and optional due date
- View all tasks with status (Pending / Done)
- Mark tasks as done
- Delete tasks
- Persistent storage using a JSON file
- Export tasks to a Markdown file
- Simple menu-driven interface

# Inputs and Outputs
Inputs
- Task title
- Subject
- Due date (YYYY-MM-DD or blank)
- Task number (for marking as done or deleting)

Outputs
- Confirmation messages for actions
- List of all tasks with details and status
- Updated task list after changes
- Exported Markdown file (assignmate_tasks.md)

## Methodology
# Core Feature Implementation
- Tasks are stored as dictionaries containing title, subject, due date, and status.
- All tasks are saved in a local tasks.json file using the json module.
- Input validation is applied to ensure correct date format.
- Menu-based navigation allows users to interact with the system easily.

# Technologies Used (with Justification)
- Python – Chosen for its simplicity and suitability for learning programming fundamentals.
- JSON – Used for lightweight, human-readable data storage.
- Datetime Module – Ensures valid due date input.

# Backend–Frontend Communication
Not applicable. This is a standalone, console-based application.

# Design Decisions and Trade-offs
- A command-line interface was used instead of a GUI to focus on logic and core programming concepts.
- Data is stored locally rather than using a database to keep the project simple and beginner-friendly.

# Ethical Considerations
- No personal or sensitive user data is collected.
- Data is stored locally and only accessible to the user.
- The interface is kept simple and readable to support accessibility.
- All learning resources and references are properly credited.

# GitHub Repository Structure
AssignMate/

│── main.py

│── tasks.json

│── README.md

│── CHANGELOG.md

# GitHub Practices
- Commits use clear and descriptive messages
- Changes are tracked logically through version updates
- Repository structure is organized and easy to understand

# Installation and Usage
Clone the repository:
git clone https://github.com/mistifylove/AssignMate.git

Navigate to the folder:
cd AssignMate

Run the program:
python main.py

# Project Status
- The core functionality of AssignMate is complete. Possible future improvements include a graphical user interface and cloud-based storage.

# Programming and Computing Ethics
- This project follows ethical programming practices by respecting intellectual property, protecting user privacy, and considering accessibility. No unnecessary data is collected, and open-source principles are respected. These practices align with the ACM Code of Ethics.

# References (APA Style)
Association for Computing Machinery. (2018). ACM Code of Ethics and Professional Conduct. https://www.acm.org/code-of-ethics

# Contributors
- Misty Gean Moreno
- Katarah Sabrina Abarca
- Adriann Gabriell Arpilleda
