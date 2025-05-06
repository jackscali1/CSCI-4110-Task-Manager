# 📂 Task Manager with Team Collaboration – Iteration 3

**Team Members:** Jack Scali, Sherif Bodundrin, Cole Blaikner, Mohamed Diallo  
**Course:** CSCI 4110 – Software Design & Development

---

## 📌 Project Description
This project is a simple, client-side prototype of a **Task Manager with Team Collaboration**, implemented using HTML, CSS, and JavaScript. It simulates a system where users can manage tasks, comment on them, attach files, and track progress — all designed for easy collaboration in a team setting.

This repository contains the **Iteration 3 deliverables**, including new use cases and fully integrated navigation between pages from Iteration 1 through Iteration 3.

---

## ✅ Features Implemented in Iteration 3

### 1. **Comment on Task**  
Users can add time-stamped comments to specific tasks. Comments are appended below the task for group visibility.

### 2. **Upload File to Task**  
Users can attach files to tasks (simulated). The uploaded filename and time are displayed under the task.

### 3. **Mark Task as Complete**  
Users can change a task’s status to “Completed” with a button, and the interface reflects this change in real-time.

---

## 🧠 Use Cases

Each implemented feature corresponds to a formal use case:

- **Comment on Task:** Post and view a thread of messages tied to a task.
- **Upload File to Task:** Attach supporting files to tasks.
- **Mark Task as Complete:** Toggle task status and reflect on the dashboard.

Full descriptions are documented in our Iteration 3 Submission file.

---

## 💡 User Stories

- A team member types a comment in a text box and sees it appear in a live thread.
- A manager uploads a wireframe PDF to a design task and sees it listed.
- A developer finishes work and marks their task complete, with an instant UI update.

---

## 📁 File Structure

| File Name           | Purpose                                             |
|---------------------|-----------------------------------------------------|
| `index.html`        | Main homepage navigation for all features           |
| `login.html`        | User login simulation                               |
| `dashboard.html`    | Task list view (Iteration 2)                        |
| `create-task.html`  | Basic form to create a new task                     |
| `assign-role.html`  | Dropdowns to assign user roles                      |
| `edit-task.html`    | Edit task details (Iteration 2)                     |
| `message.html`      | Task message thread (Iteration 2)                   |
| `comment-task.html` | Commenting system (Iteration 3)                     |
| `upload-file.html`  | File attachment simulation (Iteration 3)            |
| `mark-complete.html`| Toggle task status to complete (Iteration 3)        |
| `iteration3_domain_model.png` | UML class diagram (domain model)          |

All files are written using **vanilla HTML/CSS/JS** with no backend required.

---

## 🔧 Tech Stack
- **Frontend:** HTML, CSS, JavaScript
- **No frameworks or libraries used** – All logic is native JS
- **Deployment:** GitHub Pages

---

## 🌐 Live Demo
> GitHub Pages Link: **[https://jackscali1.github.io/CSCI-4110-Task-Manager/](https://jackscali1.github.io/CSCI-4110-Task-Manager/)**

---

## 📝 How to Run Locally
1. Clone the repository:
```bash
git clone https://github.com/jackscali1/CSCI-4110-Task-Manager.git
```
2. Open any of the `.html` files in your browser
3. Use `index.html` to navigate the entire system interactively

---

## 📦 Future Work (Iteration 4 Ideas)
- Backend support (Node.js, MongoDB)
- Real authentication and user sessions
- Database for tasks, comments, and uploads
- Group dashboard and role-based permissions

---

## 📄 License
This project is for educational use only. All team members have collaborated on the design and implementation of this system as part of SUNY Oneonta's CSCI 4110 course.

---

Thanks for visiting our project!

— Team Jack, Sherif, Cole, Mohamed
