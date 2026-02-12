# Student Assignment Tracker – Requirements

## 1. Project Overview
The Student Assignment Tracker provides university students with a centralized, reliable view of academic assignments to support planning and workload management.

## 2. Stakeholders
- Students (primary users)
- Instructors (indirect data providers)
- Academic support staff (secondary stakeholders)

## 3. User Stories
- As a student, I want to view all upcoming assignments so that I can plan my week.
- As a student, I want assignments grouped by course so that I can balance my workload.
- As a student, I want overdue assignments clearly highlighted so that I can prioritize recovery actions.

## 4. Acceptance Criteria
### View Assignments
- Each assignment displays:
  - Course name
  - Assignment title
  - Due date
- Assignments are grouped by course and sorted by due date.
- Overdue assignments are visually distinguished.
- If no assignments exist, the system displays an explanatory empty state.

## 5. Non-Functional Requirements
- The assignment list loads in under 2 seconds on a standard campus network.
- The interface is usable via keyboard navigation.
- The system supports a minimum of 500 concurrent users without degradation.

## 6. Open Questions
- Should students receive deadline reminders?
- How far in advance should assignments be visible?
- Are instructors responsible for data entry, or is data imported?
