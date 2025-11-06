# 🧩 Functional Description — University Event & Workshop Management System

The system connects all key parts of the university — **Users, Students, Lecturers, Events, Locations, Registrations, Workshops, Departments, and Notifications** — into one cohesive structure built on Microsoft Dataverse.

It ensures smooth coordination between lecturers who organize events and workshops, students who register, and administrators who track participation.

---

## 🔄 How the System Works
1. Students register for events such as workshops, guest lectures, or sessions through a Power Pages website.  
2. Each event is managed by a lecturer and hosted at a specific location or online.  
3. The registration table records student sign-ups and attendance.  
4. Lecturers manage workshops and events, tracking student participation.  
5. Departments manage users and workshops under their faculty.  
6. Locations store details of venues and capacities.  
7. Notifications automatically confirm registrations and send reminders.  
8. Users serve as the identity base for access and roles (Admin, Lecturer, Student).  
9. The Copilot Studio Agent provides an AI-powered way to register or ask questions about events.

---

## 🧱 Functional Overview of Each Table

| **Table** | **Function / Role in the System** |
|------------|------------------------------------|
| **User** | Central identity record for all users (lecturers, students, and admins). Controls security roles. |
| **Lecturer** | Stores lecturers who create workshops and events. Linked to departments. |
| **Student** | Holds student records for event registration and attendance tracking. |
| **Workshop** | Represents themed training or learning sessions created by lecturers. |
| **Event** | Specific sessions students register for, tied to locations and lecturers. |
| **Location** | Stores venue or online platform details and capacity information. |
| **Registration** | Links students to the events they attend, including attendance status. |
| **Department** | Represents university faculties or academic units. |
| **Notification Log** | Tracks all system-generated emails or alerts for audit and follow-up. |

---

## ⚙️ End-to-End Flow
1. Lecturer creates a workshop and adds events.  
2. Students view and register via Power Pages.  
3. System logs registration and sends notifications.  
4. Attendance is updated after each event.  
5. Lecturers review participation data.  
6. Admins monitor performance across departments.

---

Crafted with ❤️ by **Natovate**
