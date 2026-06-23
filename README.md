# EduTrack – Smart School Attendance System

EduTrack is a modern, responsive, and user-friendly School Attendance Management System designed to help teachers manage daily student attendance effortlessly. It features a clean UI with real-time statistics, progress tracking, and detailed historical records.

## 🚀 Live Demo / How to Run
Since this is a lightweight frontend application, you can run it instantly without any installations:
1. Download or clone this repository.
2. Open the `index.html` file directly in any modern web browser (Chrome, Edge, Firefox, Safari).

---

## 🛠️ Tech Stack Used

* **Frontend Library:** React.js (v18.2 via CDN)
* **Compiler:** Babel Standalone (for JSX compilation)
* **Styling & Design:** Clean HTML5 & Semantic CSS3 (with custom keyframe animations)
* **Typography:** Google Fonts (Poppins & Nunito)

---

## ✨ Key Features

* **Dynamic Dashboard:** Displays real-time statistics including Total Students, Present, Absent, and Pending counts.
* **Interactive Attendance Screen:** Allows teachers to mark students as Present/Absent with a single click or use the **"All Present"** bulk action button.
* **Live Search Bar:** Quickly filter students by their Name or Roll Number.
* **Visual Progress Bar:** Features a dynamic progress bar that updates in real-time as attendance is filled.
* **Attendance History (Records View):** A date-wise log that saves previous attendance sessions with breakdown percentages and student status tags.
* **Add New Student:** A clean modal form to seamlessly inject new students into the class list with automatic custom profile avatars.

---

## 📸 Project Architecture & Views

The application relies purely on **React State Management** (`useState`, `useEffect`, `useRef`) to handle UI changes and data flow dynamically without needing a heavy backend database.

1. **Dashboard View:** Quick summary of the day.
2. **Mark Attendance View:** Core interaction panel for the teacher.
3. **Records View:** Summary of past attendance data.

Built with ❤️ for Teachers.
