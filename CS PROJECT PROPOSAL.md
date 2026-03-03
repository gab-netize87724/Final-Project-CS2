> **PROJECT** **PROPOSAL** **(DRAFT)**
>
> **Project** **P.A.S.S.** **(Presence** **and** **Attendance**
> **Smart** **System)**

Team 6: Attendance 8 - Dahlia Villarico

> Dulla Lim Tria Valle

**Problem** **Statement**

Project P.A.S.S. aims to solve inconsistencies with attendance tracking
in schools; inconsistencies such as unrecorded absences or mistakenly
labelled types of absences. It does so with a more refined and organized
version of the task. This program gives the teachers an easier time with
tracking student attendance.

**Project** **Objectives**

Project P.A.S.S. aims to:

> 1\. Develop a system that records and analyzes student attendance
> data; 2. Create automated features that calculate attendance insights;
>
> 3\. And design a user-friendly interface that allows users to easily
> input, retrieve, and display attendance information.

**Planned** **Features**

Our program is able to display or do the following:

> 1\. On average, how many students are present per day? (Starter idea);
> 2. Which date had the lowest attendance overall? (Starter idea);
>
> 3\. Find the total number of unexcused and excused absences per
> student. (Own idea); 4. Count how many times a student was tardy
> (excused or unexcused). (Own idea);
>
> 5\. Display if excused or unexcused based on attendance status and
> reason for said status (Own idea).

**Planned** **inputs** **and** **Outputs**

Inputs

> \- The user shall input the following:
>
> \- Student information (name or ID number)
>
> \- Date
>
> \- Attendance status (any of the following) - Present
>
> \- Excused Absence
>
> \- Unexcused Absence - Tardy

Outputs

> \- The resulting output of the program should be one of the
> following: - If you were tardy, be it excused or unexcused
>
> \- If you were absent, be it excused or unexcused - If you were on
> time

**Logic** **Plan**

START

> **PRINT** **“Please** **input** **your** **student** **ID.”**
> **INPUT** **student_ID**
>
> **PRINT** **”Please** **input** **your** **name.”** **INPUT** **name**
>
> **PRINT** **“Please** **input** **the** **date.”** **INPUT** **date**
>
> **PRINT** **“Please** **input** **status:** **1.** **Tardy,** **2.**
> **Absent,** **3.** **Present.”** **INPUT** **status**
>
> **If** **status** **=** **1** **THEN**
>
> **PRINT** **“1.** **I** **came** **to** **school** **earlier**
> **than** **7:40** **am”** **PRINT** **“2.** **I** **came** **to**
> **school** **later** **than** **7:40** **am.”** **INPUT**
> **tardy_reason**
>
> **IF** **tardy_reason** **=** **1** **THEN**
>
> **PRINT** **“Your** **tardiness** **is** **excused.”** **ELSE** **IF**
> **tardy_reason** **=** **2** **THEN**
>
> **PRINT** **”Your** **tardiness** **is** **unexcused.”** **ELSE**
>
> **PRINT** **“Invalid** **input** **for** **tardiness.”**
>
> **END** **IF**
>
> **ELSE** **IF** **status** **=** **2** **THEN**
>
> **PRINT** **“1.** **The** **reason** **for** **absence** **was**
> **an** **illness,** **medical** **appointment,** **family**
> **emergency.”**
>
> **PRINT** **“2.** **The** **reason** **for** **absence** **was**
> **no** **valid** **excuse** **letter** **or** **medical**
> **certificate** **submitted** **after** **returning,** **personal**
> **reasons** **not** **school-approved,** **cutting** **classes,**
> **dress** **code** **violations,** **etc.?”**
>
> **INPUT** **absence_reason**
>
> **IF** **absence_reason** **=** **1** **THEN**
>
> **PRINT** **“Your** **absence** **is** **excused.”** **ELSE** **IF**
> **absence_reason** **=** **2** **THEN**
>
> **PRINT** **“Your** **absence** **is** **unexcused.”** **ELSE**
>
> **PRINT** **“Invalid** **input** **for** **absence** **END** **IF**
>
> **ELSE** **IF** **status** **=** **3** **THEN** **PRINT** **“Noted.”**
>
> **Else**
>
> **PRINT** **“** **Invalid** **status.”**
>
> **END** **IF**

END

**GitHub** **Repository** **Link**

The link below leads to the Final Project CS 2 repository for Team 6
(8-Dahlia):
[<u>https://github.com/gab-netize87724/Final-Project-CS2</u>](https://github.com/gab-netize87724/Final-Project-CS2)
