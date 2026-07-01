# Components Library

## Project Title

**TaskFlow – A Smart Task Management Mobile Application**

---

# Introduction

The TaskFlow Component Library contains reusable UI elements used throughout the application. These components ensure consistency, scalability, accessibility, and faster development.

Every component follows the design system standards defined in:

* Color Palette
* Typography System
* Spacing System
* Accessibility Guidelines

---

# Design Principles

All components should be:

* Consistent
* Reusable
* Accessible
* Responsive
* Easy to understand
* Mobile-first

---

# Primary Button

## Purpose

Used for important actions.

Examples:

* Login
* Create Task
* Save Changes
* Complete Task

---

## Specifications

| Property      | Value             |
| ------------- | ----------------- |
| Height        | 48 px             |
| Border Radius | 12 px             |
| Background    | #4F46E5           |
| Text Color    | #FFFFFF           |
| Font          | Poppins Semi-Bold |
| Font Size     | 16 px             |

---

## States

### Default

Active state.

### Pressed

Slight opacity reduction.

### Disabled

Background: #9CA3AF

Text: #FFFFFF

---

# Secondary Button

## Purpose

Alternative actions.

Examples:

* Cancel
* Back
* Skip

---

## Specifications

| Property   | Value              |
| ---------- | ------------------ |
| Border     | 1 px solid #4F46E5 |
| Background | Transparent        |
| Text Color | #4F46E5            |

---

# Text Button

## Purpose

Low-priority actions.

Examples:

* Forgot Password
* Learn More
* View Details

---

## Specifications

| Property   | Value   |
| ---------- | ------- |
| Background | None    |
| Border     | None    |
| Text Color | #4F46E5 |

---

# Floating Action Button (FAB)

## Purpose

Quick task creation.

---

## Specifications

| Property   | Value      |
| ---------- | ---------- |
| Size       | 56 × 56 px |
| Shape      | Circle     |
| Background | #4F46E5    |
| Icon Color | White      |

---

## Position

Bottom-right corner.

---

# Input Fields

## Purpose

Collect user information.

Examples:

* Email
* Password
* Task Title
* Description

---

## Structure

```text
Label
[ Input Field ]
Helper Text
```

---

## States

### Default

Normal appearance.

### Focused

Primary border color.

### Filled

Contains user data.

### Error

Red border and error message.

### Disabled

Gray background.

---

# Search Bar

## Purpose

Allow users to find tasks quickly.

---

## Components

* Search Icon
* Input Field
* Clear Button

---

## Layout

```text
[🔍 Search Tasks.............]
```

---

# Task Card

## Purpose

Display task information.

---

## Contents

* Task Title
* Due Date
* Category
* Priority Label
* Completion Status

---

## Layout

```text
+---------------------+
| UI Assignment       |
| Due: July 15        |
| High Priority       |
+---------------------+
```

---

# Category Chips

## Purpose

Display task categories.

---

## Examples

* Work
* Study
* Personal
* Health
* Finance

---

## Specifications

| Property      | Value |
| ------------- | ----- |
| Height        | 32 px |
| Border Radius | 16 px |
| Padding       | 12 px |

---

# Priority Badge

## Purpose

Indicate task importance.

---

## Variants

### High

Color: Red

### Medium

Color: Orange

### Low

Color: Green

---

# Avatar

## Purpose

Represent user identity.

---

## Variants

### Small

32 px

### Medium

48 px

### Large

72 px

---

## Shape

Circular

---

# Bottom Navigation Bar

## Purpose

Navigate between major screens.

---

## Navigation Items

1. Home
2. Calendar
3. Add Task
4. Statistics
5. Profile

---

## Specifications

| Property       | Value   |
| -------------- | ------- |
| Height         | 64 px   |
| Background     | White   |
| Active Color   | #4F46E5 |
| Inactive Color | #6B7280 |

---

# Calendar Component

## Purpose

Display tasks by date.

---

## Features

* Monthly view
* Date selection
* Task indicators
* Current date highlight

---

# Date Picker

## Purpose

Select due dates.

---

## Components

* Calendar Grid
* Month Navigation
* Confirm Button

---

# Time Picker

## Purpose

Schedule reminders.

---

## Components

* Hour Selector
* Minute Selector
* AM/PM Selector

---

# Dialog Component

## Purpose

Display important messages.

---

## Examples

* Delete Confirmation
* Logout Confirmation
* Success Messages

---

## Structure

```text
Title

Description

[Cancel] [Confirm]
```

---

# Bottom Sheet

## Purpose

Display additional options.

---

## Examples

* Sort Tasks
* Filter Tasks
* Category Selection

---

# Snackbar

## Purpose

Provide quick feedback.

---

## Examples

* Task Created
* Task Deleted
* Profile Updated

---

## Duration

3–5 seconds

---

# Progress Indicator

## Purpose

Show loading state.

---

## Types

### Circular Loader

Used during loading.

### Progress Bar

Used for productivity tracking.

---

# Empty State Component

## Purpose

Guide users when content is unavailable.

---

## Example

```text
No Tasks Found

Create your first task to get started.
```

---

# Notification Card

## Purpose

Display reminders and alerts.

---

## Content

* Notification Title
* Description
* Timestamp

---

# Statistics Card

## Purpose

Display productivity metrics.

---

## Examples

* Completed Tasks
* Pending Tasks
* Productivity Score

---

# Error Message Component

## Purpose

Inform users about problems.

---

## Example

```text
Invalid Email Address
Please enter a valid email.
```

---

## Color

#EF4444

---

# Success Message Component

## Purpose

Confirm successful actions.

---

## Example

```text
Task Created Successfully
```

---

## Color

#22C55E

---

# Component Accessibility Guidelines

All components must:

* Support screen readers.
* Maintain sufficient color contrast.
* Have touch targets larger than 44 × 44 px.
* Include visible focus states.
* Avoid relying solely on color.
* Use meaningful labels.

---

# Component States

Every interactive component supports:

| State    | Description         |
| -------- | ------------------- |
| Default  | Normal state        |
| Hover    | Pointer interaction |
| Focus    | Keyboard selection  |
| Active   | User interaction    |
| Disabled | Unavailable         |
| Error    | Invalid input       |
| Success  | Positive feedback   |

---

# Reusability Guidelines

Components should:

* Be reusable across screens.
* Follow naming conventions.
* Use consistent spacing.
* Support theme switching.
* Scale for future features.

---

# Component Inventory Summary

| Component           | Status   |
| ------------------- | -------- |
| Buttons             | Complete |
| Input Fields        | Complete |
| Search Bar          | Complete |
| Cards               | Complete |
| Navigation          | Complete |
| FAB                 | Complete |
| Chips               | Complete |
| Badges              | Complete |
| Dialogs             | Complete |
| Bottom Sheets       | Complete |
| Snackbar            | Complete |
| Progress Indicators | Complete |
| Avatars             | Complete |
| Statistics Cards    | Complete |

---

# Conclusion

The TaskFlow Component Library provides a complete collection of reusable interface elements that ensure consistency, accessibility, and scalability across the application. By standardizing component behavior and appearance, the design system enables efficient design and development while delivering a cohesive user experience.

