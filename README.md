Task Manager with State Management
Objective:
Build a Task Manager application using Angular that has reusable components, a clean UI, and leverages RxJs.
________________________________________
Requirements:
1. Task List Display:
Create a component TaskListComponent to display a list of tasks. Each task should have:
•	Title
•	Description
•	Due date
•	Status (e.g., "Pending", "In Progress", "Completed")
•	Priority (Low, Medium, High)
2. Task Management:
Implement a TaskFormComponent for creating and editing tasks.
•	Include input fields for Title, Description, Due date, Status, and Priority.
•	The form should be reusable for both task creation and editing.
•	Form validation (e.g., required fields, maximum length for description).
•	Use selectors to get tasks by status (e.g., Pending, In Progress).
4. Task Filters:
Add filter options to filter tasks by:
•	Status (All, Pending, In Progress, Completed)
•	Priority (All, Low, Medium, High)
Implement a reusable filter component TaskFilterComponent that interacts with the task list.
5. Styling and Design:
Apply SCSS for styling. The design should be simple yet clean with modern UI elements such as:
•	Use Primeng or Material UI library to design for buttons, input fields, and cards.
•	A responsive layout for both mobile and desktop views.
6. API Integration:
Integrate localStorage or json-server to mock a backend API to persist tasks (bonus point for using an API).
7. Git Workflow:
Ensure that the project is versioned using Git. Commit changes incrementally and provide a meaningful commit history.
________________________________________
Deliverables:
1.	A Git repository with the Angular project.
2.	Well-structured and documented code.
3.	Clear separation of concerns (components, services, state management).
4.	Test cases for components and services(Optional).
________________________________________
Bonus:
1.	Implement lazy loading for task-related features (i.e., lazy-load modules for Task-related components).
2.	Add unit tests for components and services.
________________________________________