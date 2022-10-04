# Database Management System For Hamarey Bachchey NGO
# Course
CS2005	Database Systems <br />

# Objective:
Enable the student to design and develop a database. In this project, the student are required to show their abilities of: <br />
1. Analyzing the System Requirement <br />
2. Represent the requirement into logical design using Entity Relationship (ER) or/and Enhanced Entity Relationship (EER) model <br />
3. Mapping the designed model into relational schemas <br />
4. Transform the relational schemas into normalized tables <br />
5. Writing SQL statements to creates the tables including all applied integrity constraints <br />
6. Writing SQL statements to populate the initial records of each table <br />
7. Front End Development of Forms/ Reports <br />

# Introduction
Hamarey Bachchey is a NGO with the goal to reform education for children. They offer weekly classes for children below the age of 15. They wish to develop a database system. <br />
<br />
The NGO is organized in the following ways.
<br />
After signing up, each student has to register for a course, and can only be registered to one course at a time. Once the course is completed, the student can register for a new course. After registration, the student is split into different classes based on their age (eg 3-4 years to class 1, 4-6 years to class 2, etc). Each class will be taught the same subjects, in a manner best suited to their age group. Each class can have multiple sections, depending on the need. Classes can also be further separated into roups based on students’ gender. Classes can also be given a custom title. <br />
<br />
Each students’ personal information will be saved, including photos which may need to be updated every year. The most crucial information will be that of the parents/guardians. The Email, phone number, address and CNIC of both parents need to be recorded for each student. In the event of any incident where the parents will be unavailable, a guardian also needs to be available, in which case their details and relation to the students also need to be recorded. A history needs to be maintained for whenever base information of students/parents/guardians is changed. <br />
<br />
For the earlier classes with very young students, the mother needs to be present with the child. If for whatever reason the mother cannot come, a female guardian must be present instead. In such cases, the NGO needs to be informed ahead of time of the individual accompanying the child, and other such information, including whether the individual is pregnant and/or needs assistance in any way. <br />
<br />
The fee each student has to pay is different, depending on their class. If a parent admits more than 3 children, they may be offered a discount. Moreover, if the parents can’t pay for legitimate reasons, they will be offered a discount. There will be no fee for a child of a Hamarey Bachchey staff member. Payment of fee is made before admission to a third-party which provides the parents a challan or voucher number, which the parents then enter during admission process. <br />

# Following reports / queries are needed

1. A list of all students <br />
2. A list of all mothers and their spouses <br />
3. A list of all guardians, grouped by relation to students (show students as well) <br />
4. A list of parents and their children <br />
5. A list of all students with siblings taking classes, grouped by class <br />
6. A list of all students who have been assigned to a new class in the given time span (use check for including or ignoring new admissions) <br />
7. A list of all new students in given time span grouped by class <br />
8. A list of all new parents in given time span (include children info) <br />
9. A list of all parents who are early introducers (enroll their children into courses as soon as the children are old enough) <br />
10. Class change history of given student <br />
11. A report of a list of students grouped by classes along with add, search, delete, and edit student features. Search can be performed using student name or id. <br />
12. A report of a list of classes with number of students per class and student count per gender. Search can be performed using class name. <br />
13. A report of a list of all students who have been dormant for given number of months/years. Search can be performed using months or years. <br />
14. A report of all info on a given student (parents, guardians, siblings, class history). Search can be performed using student name or id. <br />
15. A report of all info on a given parent (all children, claasses of each child, designated guardian). Search can be performed using parent name or id. <br />

# Languages
1. HTML
2. MySQL
3. PHP

# Note
The Description.pdf contains the detailed description of this repository.
