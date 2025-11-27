# CGPA-CALCULATOR
CGPA Calculator (Java)  The CGPA Calculator is a Java-based application designed to help students accurately compute their Cumulative Grade Point Average (CGPA) with ease. Instead of performing manual calculations, this tool automates the entire process by allowing users to enter subject grades and their corresponding credit hours.
🎓 CGPA Calculator - Java Project

A robust, desktop-based application developed to automate the calculation of Semester Grade Point Average (SGPA) and Cumulative Grade Point Average (CGPA) for university students.

👥 The Team: Eternal Coders

This project was developed as part of the academic curriculum at Galgotias University.

|

| Role | Name |
| Team Leader | Tausif Hassan |
| Team Member | Anjali Kumari |
| Team Member | Dipra Khurana |

🚀 Project Overview

Manual calculation of CGPA is often time-consuming and prone to arithmetic errors. The CGPA Calculator solves this by providing a clean, user-friendly graphical interface where students can input their course details and get instant, accurate results based on credit weightage.

Key Features

Dynamic Course Entry: Add as many subjects/rows as needed for a specific semester.

Auto-Grading Logic: Automatically converts letter grades (O, A+, A, B, etc.) into numerical grade points.

Weighted Average Calculation: Uses the standard formula: Σ (Credit × Grade Point) / Σ Credits.

Input Validation: Prevents entry of invalid credits (e.g., negative numbers) or undefined grades.

Real-time Reset: Clear all data instantly to start a new calculation.

📸 Screenshots

| Main Dashboard | Calculation Result |
|  |  |
| Clean Input Interface | Accurate GPA Display |

🛠️ Technology Stack

Programming Language: Java (JDK 17+)

GUI Framework: Java Swing (javax.swing)

IDE Used: IntelliJ IDEA / Eclipse

💻 Getting Started

Follow these instructions to get a copy of the project running on your local machine.

Prerequisites

Ensure you have Java Development Kit (JDK) 8 or higher installed.

Verify by typing java -version in your terminal.

Git installed on your machine.

Installation & Execution

Method 1: Command Line (Terminal/CMD)

Clone the repository:

git clone [https://github.com/EternalCoders/Java-CGPA-Calculator.git](https://github.com/EternalCoders/Java-CGPA-Calculator.git)



Navigate to the project directory:

cd Java-CGPA-Calculator



Compile the source code:

javac src/*.java



Run the application:

java -cp src Main



Method 2: Using an IDE (IntelliJ IDEA, Eclipse, NetBeans)

Open your IDE.

Select File > Open Project (or Import Project).

Navigate to the cloned folder Java-CGPA-Calculator and select it.

Locate Main.java inside the src folder.

Right-click on the file and select Run 'Main'.

📂 Project Structure

Java-CGPA-Calculator/
├── src/
│   ├── Main.java           # Entry point (launches the GUI)
│   ├── Calculator.java     # Logic for mathematical calculations
│   ├── Course.java         # Object model for a single course
│   └── Student.java        # Object model for student details
├── docs/
│   ├── UML_Diagram.png     # Class structure diagram
│   └── Flowchart.png       # Logic flow visual
├── LICENSE                 # License file
└── README.md               # Project documentation



🔮 Future Enhancements

$$$$

 Database Integration: Connect with MySQL to save student records permanently.

$$$$

 PDF Export: Generate a downloadable PDF transcript of the results.

$$$$

 Graph Visualization: Add bar charts to visualize performance trends over semesters.

🤝 Contributing

Contributions are welcome! If you have suggestions for improvements:

Fork the Project

Create your Feature Branch (git checkout -b feature/AmazingFeature)

Commit your Changes (git commit -m 'Add some AmazingFeature')

Push to the Branch (git push origin feature/AmazingFeature)

Open a Pull Request

📄 License

This project is licensed under the MIT License - see the LICENSE file for details.
