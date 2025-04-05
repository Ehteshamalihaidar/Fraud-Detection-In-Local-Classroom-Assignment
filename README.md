# 🎓 Fraud Detection in Local Classroom Assignment Project

A smart, role-based web platform for detecting and visualizing assignment fraud in educational environments. It supports authentication, plagiarism and collusion detection, notifications, and detailed analysis for students and teachers.

---

## 🚀 Features

### ✅ Authentication & Authorization
- Secure login/registration for teachers and students
- Role-Based Access Control (RBAC)
- Password reset functionality

### 📂 Assignment Workflow
- Teachers can create, edit, and delete assignments
- Students can upload .txt assignment files for submission


### 🕵 Fraud Detection
- *Plagiarism Detection*:
  - Compares newly uploaded .txt assignments against existing ones
  - Displays plagiarism percentage
  - First-time uploads get a 0% score
- *Collusion Detection*:
  - Clusters students with similar plagiarism scores
  - Highlights suspected collusion groups

### 📊 Visualization
- Interactive graphs showing plagiarism trends
- Clustering visualizations of students
- Scorecards and fraud analytics for teachers

### 🔔 Notification System
- Real-time pop-up notifications:
  - When assignments are added by teachers
  - When students upload submissions
  - For activities like course edits or deletions
- Notification history panel
- Bell icon integrated into the UI