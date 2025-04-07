# Android Task Organizer

This is a simple task organizer Android app written in Java.  
It supports adding, deleting, saving tasks, and searching them on Google.

## ✨ Features

- Add tasks
- Delete tasks with confirmation
- Store tasks between sessions (SharedPreferences + Gson)
- Search task text on Google
- RecyclerView-based list with dynamic "Add Task" button at the end
- Clean modern structure with clear code and comments

## 📦 Technologies

- Java
- RecyclerView
- SharedPreferences
- Gson
- AndroidX

## 🧠 How it works

- Tasks are stored in `ArrayList<String>`
- Tasks are saved as JSON string in SharedPreferences
- RecyclerView shows all tasks + the Add button as the last item
- Long press and confirmation dialog to delete
- Search icon opens Google with the task as a query

## 📂 Project structure

- `MainActivity.java`: main screen, data management
- `AddTaskActivity.java`: form to create a new task
- `TaskAdapter.java`: custom RecyclerView adapter
- `item_task.xml`: layout for each task row
- `item_add_button.xml`: layout for "Add Task" button at the end of list

## 🚀 How to run

1. Open the project in Android Studio
2. Connect an emulator or device
3. Click "Run"

## 💡 Ideas for the future

- Checkboxes (mark as done)
- Task categories or tags
- Notifications
- Beautiful dark/light themes

---

Have Fun ❤️
