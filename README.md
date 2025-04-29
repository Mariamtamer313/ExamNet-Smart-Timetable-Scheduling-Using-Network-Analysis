Smart-Timetable-Scheduling-Using-Network-Analysis

Exam Timetable Scheduling using NetworkX
 Project Overview
This project applies network analysis to solve a real-world scheduling problem — generating an exam timetable for a university term. Using Python and the NetworkX library, a conflict graph is built from student registration data, where each course is represented as a node and edges indicate shared enrollments. A graph coloring algorithm is then applied to assign time slots such that no two courses taken by the same student occur at the same time.

 Objectives
Model course conflicts as a graph.

Apply graph coloring to minimize exam time slot conflicts.

Visualize course statistics and graph properties.

Compare different coloring strategies based on efficiency.

Respect real-life constraints (e.g. number of students per day, number of periods).

🧩 Dataset
Student registration data is loaded from an Excel sheet.

Each row represents a student and the courses they are registered in.

🛠️ Tools & Technologies
Python

NetworkX

Matplotlib

Pandas

Excel (.xlsx)

📈 Steps Performed
Conflict Graph Construction

A graph is constructed where each node is a course.

An edge is drawn between two courses if they are taken by the same student.

analysis

Number of students per course.

Degree (conflict level) of each course in the graph.

Other useful statistics such as the most conflicting courses.

Graph Coloring (Timetabling)

Several graph coloring algorithms are tested (e.g., greedy coloring).

Time slots are assigned based on the coloring result.

Performance Evaluation

Compare algorithms in terms of number of periods and execution time.

Optional Constraint Handling

Exam committee capacity.

Maximum students or exams per day.

Fixed slots for some courses (e.g., capstone).

📊 Visualizations
Bar plots for number of students per course.

Network graph showing course conflicts.

Degree distribution.

Colored timetable representing exam slots.
