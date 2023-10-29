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


![277521040-23f6eaf1-d3a1-4364-8701-d49b5d12ef6e](https://github.com/MuhammadAlmursii/ITI_Examination_System/assets/140438093/b4886ccf-8d17-431d-b8b7-4c24e62d2620)


### How to Explore the Mapping
![277521639-2b6de7dc-deaa-4668-b249-5804b32dc9e7](https://github.com/MuhammadAlmursii/ITI_Examination_System/assets/140438093/a6dc9787-226f-45a9-97c7-b2c5ebb5dd00)

## ETL Process with SSIS

The Comprehensive Examination System relies on a robust ETL (Extract, Transform, Load) process facilitated by SSIS (SQL Server Integration Services). This process ensures the efficient movement and transformation of data, enhancing data quality and accessibility for analysis and reporting.

## ETL Process with SSIS

Our Comprehensive Examination System relies on SSIS (SQL Server Integration Services) to efficiently Extract, Transform, and Load data. This process ensures data accuracy, quality, and accessibility for analysis and reporting.

### ETL Workflow

1. **Data Extraction:** We collect data from various sources, including databases with information about students, instructors, courses, exams, and questions.

2. **Data Transformation:** Using SSIS, we cleanse, enrich, and restructure data to match our data model.

3. **Data Loading:** Transformed data is loaded into destination tables, maintaining data consistency.

4. **Validation and Quality Assurance:** SSIS incorporates checks to verify data accuracy and integrity.

5. **Scheduled Execution:** SSIS packages run at intervals, ensuring up-to-date data.

6. **Monitoring and Logging:** We monitor the ETL process, logging issues and errors.

7. **Error Handling:** SSIS handles data inconsistencies or errors with notifications and alerts.

### ETL Benefits

- **Efficiency:** SSIS streamlines the ETL process, optimizing data transfer and transformation.

- **Data Accuracy:** Validation and quality checks ensure accurate and reliable data.

- **Automation:** Scheduled SSIS packages reduce manual intervention.

- **Scalability:** SSIS can handle large data volumes, supporting our growing system.


![image](https://github.com/MuhammadAlmursii/ITI_Examination_System/assets/140438093/ad771cb3-e8fe-4abf-8880-afdd24a614cf)

![image](https://github.com/MuhammadAlmursii/ITI_Examination_System/assets/140438093/cefa03f9-7ee1-41ca-8316-d0c488e97dd8)


