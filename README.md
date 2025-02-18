# OOPs-Project--Timetable-Maker
Building a Timetable for OOPs project
TimeTableBuilder/
│── data/                         # 📂 CSV Storage
│   ├── classrooms.csv
│   ├── courses.csv
│   ├── instructors.csv
│   ├── timetable.txt              # Custom format for timetable
│
│── src/                           # 📂 Source Code
│   │── database/                   # 📂 File Handling
│   │   ├── CSVHandler.java
│   │   ├── TimetableHandler.java
│   │── model/                      # 📂 Data Models
│   │   ├── Classroom.java
│   │   ├── Course.java
│   │   ├── Instructor.java
│   │── scheduler/                  # 📂 Conflict Checking & Auto-Scheduling
│   │   ├── ConflictChecker.java
│   │   ├── BITSRules.java
│   │── ui/                         # 📂 Swing GUI
│   │   ├── MainWindow.java         # Main UI Window
│   │   ├── ClassroomForm.java      # Classroom Entry Form
│   │   ├── CourseForm.java         # Course Entry Form
│   │   ├── InstructorForm.java     # Instructor Entry Form
│   │   ├── TimetableUI.java        # Timetable Display & Editing
│
│── tests/                         # 📂 Unit & Integration Tests
│   ├── ConflictCheckerTest.java
│   ├── CSVHandlerTest.java
│
│── resources/                     # 📂 Icons, Logos, and Styling
│   ├── logo.png
│   ├── styles.css (Optional for UI theming)
│
│── README.md                      # 📜 Project Overview & Setup Instructions
│── .gitignore                      # 🚫 Ignore unnecessary files
│── TimeTableBuilder.iml            # IDE Config (IntelliJ/VS Code)
│── pom.xml (If using Maven)        # Dependencies
│── build.gradle (If using Gradle)  # Dependencies
