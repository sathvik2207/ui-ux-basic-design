# Low-Fidelity Wireframes

## Project Title

**TaskFlow – A Smart Task Management Mobile Application**

---

# Introduction

Low-fidelity wireframes are simple visual representations of an application's layout and functionality. They focus on structure, navigation, content hierarchy, and user flow without emphasizing colors, typography, or detailed visual styling.

The purpose of these wireframes is to validate the user experience before creating high-fidelity designs.

---

# Wireframing Goals

The wireframes were designed to:

* Define the application's structure.
* Organize information effectively.
* Simplify navigation.
* Minimize user effort.
* Identify usability issues early.
* Establish a clear user flow.
* Prepare for high-fidelity UI design.

---

# Navigation Structure

The application uses a bottom navigation bar with five primary sections:

1. Home
2. Calendar
3. Add Task
4. Statistics
5. Profile

This navigation keeps frequently used features easily accessible with one-handed mobile interaction.

---

# Screen 1 – Splash Screen

## Purpose

Introduce the application and display branding while the app loads.

## Components

* App logo
* Application name
* Tagline
* Loading indicator

## Layout

```
+----------------------------------+
|                                  |
|                                  |
|          TASKFLOW LOGO           |
|                                  |
|           TaskFlow               |
|                                  |
|     Organize Your Day Better     |
|                                  |
|         Loading...               |
|                                  |
+----------------------------------+
```

---

# Screen 2 – Login Screen

## Purpose

Allow users to access their account.

## Components

* Welcome message
* Email field
* Password field
* Login button
* Forgot Password link
* Google Sign-In button
* Sign Up link

## Layout

```
+----------------------------------+
| Welcome Back                     |
|                                  |
| Email                            |
| [_______________]                |
|                                  |
| Password                         |
| [_______________]                |
|                                  |
| Login Button                     |
|                                  |
| Forgot Password                  |
|                                  |
| Continue with Google             |
|                                  |
| Don't have an account? Sign Up   |
+----------------------------------+
```

---

# Screen 3 – Home Dashboard

## Purpose

Display today's tasks and quick actions.

## Components

* Greeting
* Search bar
* Today's tasks
* Upcoming tasks
* Floating Add Task button
* Bottom navigation

## Layout

```
+----------------------------------+
| Hello Rahul                      |
| Good Morning                     |
|                                  |
| Search Tasks                     |
| [_______________]                |
|                                  |
| Today's Tasks                    |
|----------------------------------|
| Math Assignment                  |
| UI Project                       |
| Coding Practice                  |
|----------------------------------|
|                (+)               |
|----------------------------------|
| Home Calendar Add Stats Profile  |
+----------------------------------+
```

---

# Screen 4 – Add Task

## Purpose

Enable users to create a new task.

## Components

* Task title
* Description
* Category
* Priority
* Due date
* Reminder
* Save button

## Layout

```
+----------------------------------+
| Create Task                      |
|                                  |
| Task Title                       |
| [_______________]                |
|                                  |
| Description                      |
| [_______________]                |
|                                  |
| Category                         |
| [Dropdown]                       |
|                                  |
| Priority                         |
| High Medium Low                  |
|                                  |
| Due Date                         |
| Calendar Picker                  |
|                                  |
| Reminder                         |
| Time Picker                      |
|                                  |
| Save Task                        |
+----------------------------------+
```

---

# Screen 5 – Calendar

## Purpose

Display tasks by date.

## Components

* Monthly calendar
* Highlighted task dates
* Daily task list
* Add Task shortcut

## Layout

```
+----------------------------------+
| Calendar                         |
|                                  |
| July 2026                        |
| Mo Tu We Th Fr Sa Su             |
|                                  |
| Calendar Grid                    |
|                                  |
| Today's Tasks                    |
|----------------------------------|
| Assignment                       |
| Client Meeting                   |
| Workout                          |
+----------------------------------+
```

---

# Screen 6 – Statistics

## Purpose

Show productivity insights.

## Components

* Completed tasks
* Pending tasks
* Weekly progress
* Productivity score
* Charts

## Layout

```
+----------------------------------+
| Productivity                     |
|                                  |
| Completed Tasks                  |
| 42                               |
|                                  |
| Pending Tasks                    |
| 8                                |
|                                  |
| Weekly Progress Chart            |
|                                  |
| Productivity Score               |
| 92%                              |
+----------------------------------+
```

---

# Screen 7 – Profile

## Purpose

Allow users to manage account settings.

## Components

* Profile photo
* Name
* Email
* Theme settings
* Notification settings
* Logout

## Layout

```
+----------------------------------+
| Profile                          |
|                                  |
| (Profile Photo)                  |
| Rahul Sharma                     |
| rahul@email.com                  |
|----------------------------------|
| Edit Profile                     |
| Notifications                    |
| Dark Mode                        |
| Privacy                          |
| Help                             |
| Logout                           |
+----------------------------------+
```

---

# Screen 8 – Task Details

## Purpose

Display complete information about a selected task.

## Components

* Task title
* Description
* Due date
* Reminder
* Priority
* Category
* Edit button
* Delete button
* Mark Complete button

## Layout

```
+----------------------------------+
| Task Details                     |
|                                  |
| Mobile UI Assignment             |
|                                  |
| Description                      |
| Complete login screen            |
|                                  |
| Due Date                         |
| 15 July 2026                     |
|                                  |
| Priority: High                   |
| Category: College                |
|                                  |
| Edit                             |
| Delete                           |
| Mark Complete                    |
+----------------------------------+
```

---

# User Flow

```
Splash Screen
      │
      ▼
Login / Sign Up
      │
      ▼
Home Dashboard
      │
      ├──────────────┐
      ▼              ▼
Add Task         Calendar
      │              │
      ▼              ▼
Task Details   Statistics
      │
      ▼
Complete Task
      │
      ▼
Dashboard Update
```

---

# Wireframing Principles Applied

* Clear visual hierarchy.
* Consistent spacing.
* Minimal cognitive load.
* Mobile-first layout.
* Accessible touch targets.
* Simple navigation.
* Reduced number of user actions.
* Prominent primary actions.

---

# Design Decisions

The wireframes prioritize speed and usability by:

* Placing the **Add Task** action within easy reach.
* Keeping the bottom navigation persistent across screens.
* Displaying today's tasks immediately after login.
* Using search for quick task retrieval.
* Reducing task creation to a single focused form.

---

# Conclusion

The low-fidelity wireframes establish the foundation of TaskFlow's user experience. They validate navigation, content organization, and interaction flow before visual styling is introduced in the high-fidelity design phase. These wireframes ensure that usability remains the primary focus throughout the design process.

