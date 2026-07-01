# Design System

## Project Title

**TaskFlow – A Smart Task Management Mobile Application**

---

# Introduction

The TaskFlow Design System is a collection of reusable design standards, components, styles, and guidelines that ensure consistency across the application. It enables designers and developers to build interfaces faster while maintaining a cohesive and accessible user experience.

---

# Design Principles

The design system is built around the following principles:

* Simplicity
* Consistency
* Accessibility
* Efficiency
* Scalability
* User-Centered Design
* Mobile-First Approach

---

# Brand Personality

TaskFlow represents:

* Reliable
* Clean
* Modern
* Friendly
* Productive
* Professional

The interface should always feel lightweight, organized, and easy to navigate.

---

# Color System

## Primary Colors

| Color          | Hex Code    | Usage                                 |
| -------------- | ----------- | ------------------------------------- |
| Primary Blue   | **#4F46E5** | Primary buttons, links, active states |
| Secondary Cyan | **#06B6D4** | Highlights, secondary actions         |
| Success Green  | **#22C55E** | Success messages, completed tasks     |
| Warning Amber  | **#F59E0B** | Warnings, pending tasks               |
| Error Red      | **#EF4444** | Errors, destructive actions           |

---

## Neutral Colors

| Color          | Hex Code | Usage                 |
| -------------- | -------- | --------------------- |
| Background     | #F8FAFC  | Main background       |
| Surface        | #FFFFFF  | Cards and panels      |
| Border         | #E5E7EB  | Dividers and outlines |
| Text Primary   | #111827  | Main text             |
| Text Secondary | #6B7280  | Supporting text       |
| Disabled       | #9CA3AF  | Disabled elements     |

---

## Dark Theme

| Element        | Color   |
| -------------- | ------- |
| Background     | #111827 |
| Card           | #1F2937 |
| Primary Text   | #F9FAFB |
| Secondary Text | #D1D5DB |
| Border         | #374151 |

---

# Typography

## Font Family

**Primary Font:** Poppins

**Secondary Font:** Inter

---

## Type Scale

| Style      | Size  | Weight    |
| ---------- | ----- | --------- |
| Display    | 36 px | Bold      |
| Heading 1  | 32 px | Bold      |
| Heading 2  | 28 px | Semi-Bold |
| Heading 3  | 24 px | Semi-Bold |
| Heading 4  | 20 px | Medium    |
| Body Large | 18 px | Regular   |
| Body       | 16 px | Regular   |
| Small      | 14 px | Regular   |
| Caption    | 12 px | Regular   |

---

# Spacing System

TaskFlow uses an **8-point grid system**.

| Token | Value |
| ----- | ----- |
| XS    | 4 px  |
| SM    | 8 px  |
| MD    | 16 px |
| LG    | 24 px |
| XL    | 32 px |
| XXL   | 48 px |

Consistent spacing improves readability and alignment.

---

# Grid System

* Mobile Width: **360–390 px**
* Margin: **16 px**
* Column Layout: **4 Columns**
* Gutter: **16 px**

---

# Border Radius

| Component    | Radius       |
| ------------ | ------------ |
| Buttons      | 12 px        |
| Cards        | 16 px        |
| Input Fields | 10 px        |
| Dialogs      | 20 px        |
| Avatars      | 50% (Circle) |

Rounded corners create a modern and approachable visual style.

---

# Elevation

| Level   | Usage                  |
| ------- | ---------------------- |
| Level 0 | Background             |
| Level 1 | Cards                  |
| Level 2 | Floating Action Button |
| Level 3 | Dialog Boxes           |
| Level 4 | Bottom Sheets          |

Shadows should be subtle and used only to indicate hierarchy.

---

# Icons

## Icon Style

* Outlined Material Icons
* Rounded corners
* 24 × 24 px default size

### Common Icons

* Home
* Calendar
* Add
* Notifications
* Search
* Settings
* Profile
* Edit
* Delete
* Check Circle
* Filter
* More Options

---

# Buttons

## Primary Button

Purpose: Main actions such as **Save**, **Login**, and **Create Task**.

Properties:

* Filled background
* White text
* Rounded corners
* Full width on forms

---

## Secondary Button

Purpose: Less prominent actions.

Properties:

* Outline style
* Transparent background
* Primary color border

---

## Text Button

Purpose:

* Forgot Password
* Cancel
* Learn More

Properties:

* No border
* Minimal visual weight

---

# Input Fields

Each input field contains:

* Label
* Placeholder
* Optional helper text
* Validation message
* Leading or trailing icon (where applicable)

States:

* Default
* Focused
* Filled
* Error
* Disabled

---

# Cards

Task cards display:

* Task title
* Category
* Due date
* Priority indicator
* Completion status

Cards use:

* White background
* Rounded corners
* Light shadow
* Consistent internal spacing

---

# Navigation

## Bottom Navigation

Contains:

* Home
* Calendar
* Add Task
* Statistics
* Profile

The active tab is highlighted using the primary color.

---

# Floating Action Button (FAB)

Purpose:

Quick access to **Create Task**.

Specifications:

* Circular shape
* 56 × 56 px
* Primary Blue background
* White Add icon

---

# Components

Reusable components include:

* Buttons
* Cards
* Dialogs
* Chips
* Badges
* Avatars
* Bottom Navigation
* Search Bar
* Calendar Picker
* Date Picker
* Time Picker
* Snackbars
* Progress Indicators

---

# Feedback Components

TaskFlow uses:

* Toast messages
* Snackbar notifications
* Loading indicators
* Empty states
* Success dialogs
* Error dialogs
* Confirmation dialogs

These components provide immediate feedback and improve user confidence.

---

# Accessibility Guidelines

The design system follows accessibility best practices:

* Minimum text size of 16 px for body content.
* High color contrast for readability.
* Touch targets of at least 44 × 44 px.
* Keyboard-friendly navigation (where applicable).
* Descriptive labels for screen readers.
* Icons paired with text when necessary.

---

# Motion Guidelines

Animations should be:

* Fast (200–300 ms)
* Smooth
* Purposeful
* Non-distracting

Common animations include:

* Button press feedback
* Page transitions
* Task completion animation
* Loading indicators
* Modal appearance

---

# Empty States

When no data is available, display:

* Friendly illustration
* Informative message
* Clear call-to-action

Example:

**"No tasks yet. Tap the + button to create your first task."**

---

# Error States

Examples:

* Invalid email address
* Incorrect password
* Empty task title
* Network unavailable

Errors should:

* Explain the issue clearly.
* Suggest corrective action.
* Preserve entered data whenever possible.

---

# Design Tokens Summary

| Category      | Standard        |
| ------------- | --------------- |
| Grid          | 8-point         |
| Font          | Poppins / Inter |
| Primary Color | #4F46E5         |
| Border Radius | 10–20 px        |
| Touch Target  | ≥ 44 × 44 px    |
| Body Text     | 16 px           |
| Animation     | 200–300 ms      |

---

# Conclusion

The TaskFlow Design System establishes a unified visual language that promotes consistency, usability, and accessibility throughout the application. By defining reusable components, standardized styles, and clear interaction guidelines, it enables efficient collaboration between designers and developers while ensuring a polished and user-friendly experience.

