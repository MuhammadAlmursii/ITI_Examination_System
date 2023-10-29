# ITI_Examination_System
This GitHub repository is dedicated to the ETL (Extract, Transform, Load) processes and data modeling aspects of the Comprehensive Examination System. We specialize in optimizing data workflows and ensuring data accuracy through the use of stored procedures. Our focus is on making data management more efficient and insightful.

# **Tools:**

- ETL (Extract, Transform, Load) Processes
- Data Modeling  
- ERD (Entity-Relationship Diagram)
- SQL Server
- SSIS (SQL Server Integration Services)
- Stored Procedures
- SSRS (SQL Server Reporting Services)
- Red Gate Data Generator
- Power BI

## Data Modeling and ETL Focus

In the development of the Comprehensive Examination System, we paid significant attention to data modeling and ETL (Extract, Transform, Load) processes. Our objective was to create a robust and efficient system to manage and analyze data related to students, instructors, departments, exams, questions, and courses.

### Data Entities and Relationships

Our data model for the system includes the following entities:

- **Students:** Representing the individuals enrolling in different tracks, branches, and intakes. Students study multiple courses and take various exams.

- **Instructors:** These are the educators who work in different tracks and teach multiple courses.

- **Departments:** Departments are responsible for managing tracks and offering a wide range of courses.

- **Tracks:** Each track is overseen by one instructor and encompasses multiple courses.

- **Courses:** Courses are at the core of our system, with each course featuring numerous topics, exams, and questions.

### Key Rules and Relationships

To establish a coherent data model, we defined specific rules and relationships:

- **Student-Course-Exam Interaction:** Each student enrolls in a particular track, branch, and intake. Students study multiple courses and take numerous exams, including up to two trials per course.

- **Instructor-Track-Course Connection:** Instructors work in multiple tracks and teach numerous courses, contributing to the diverse educational landscape.

- **Track Management:** Each track is managed by a dedicated instructor who oversees a variety of courses within that track.

- **Course Composition:** Courses encompass a wide array of topics, exams, and questions, making them the cornerstone of our data model.


