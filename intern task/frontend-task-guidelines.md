# Front-End Practice Task: Task Manager

## Objective
Build a small browser-based application that helps a user manage a list of personal tasks.

This exercise is intended to practice core front-end skills. Focus on writing clear, organized code and making the application easy to use.

## Requirements

### 1. Page Structure
- Create a clear, well-organized interface.
- Include a meaningful page title and a section where the user's tasks are displayed.
- Provide an easy-to-understand way for users to enter a new task.
- Use semantic HTML elements where appropriate.

### 2. Styling
- Use CSS to create a clean, readable layout.
- Make the interface usable on both desktop and smaller screens.
- Provide visible hover, focus, and interaction states where appropriate.
- Keep spacing, typography, and visual styling consistent.

### 3. Core Functionality
Users should be able to:
- Add a task.
- See the current tasks in a list.
- Mark a task as completed and change it back to incomplete.
- Remove a task.
- Receive sensible feedback when they try to submit an empty task.

### 4. Persistence
- Tasks must remain available after the page is refreshed or reopened in the same browser.
- Keep the displayed task list synchronized with the saved data.
- Handle the case where no saved tasks exist yet.
- Avoid breaking the application if saved browser data is missing or cannot be parsed.

### 5. Technical Constraints
- Use **HTML, CSS, and vanilla JavaScript** only.
- Use JavaScript DOM APIs to create, update, and remove interface elements.
- Use browser `localStorage` for persistence.
- Do not use front-end frameworks, UI libraries, or third-party task-management packages.
- Keep HTML, CSS, and JavaScript in separate files.
- Avoid inline event-handler attributes in HTML.
- Use meaningful variable and function names, and keep the code reasonably modular.

## User Experience Expectations
- The application should be straightforward to understand without instructions.
- The page should update immediately after a user action.
- Completed tasks should be visually distinguishable from incomplete tasks.
- Interactive controls should have clear labels and be keyboard accessible.
- The layout should remain usable at different viewport widths.

## Suggested Workflow
1. Review the requirements and decide how the interface should be organized.
2. Set up the project files.
3. Build the static page structure.
4. Add the styling.
5. Implement interactions with JavaScript DOM APIs.
6. Add browser persistence.
7. Test each feature manually.
8. Review the code for readability and remove unnecessary duplication.

## Acceptance Checklist
- [ ] A user can add a non-empty task.
- [ ] Empty submissions are handled appropriately.
- [ ] Tasks are displayed clearly.
- [ ] A task can be marked complete and incomplete.
- [ ] A task can be removed.
- [ ] Changes remain after refreshing the page.
- [ ] The interface works when the saved list is empty.
- [ ] Existing saved data is handled safely.
- [ ] The page is usable on desktop and mobile-sized screens.
- [ ] The code uses vanilla JavaScript and DOM APIs, with no frameworks.
- [ ] HTML, CSS, and JavaScript are separated into their own files.

## Deliverables
Submit:
- The complete source files.
- A short README explaining how to run the project.
- A brief note describing the main features and any issues or limitations.

## Important
This is a learning exercise. You may consult documentation, but write and understand the implementation yourself. Be prepared to explain how the interface updates, how data is saved, and how the application restores its state when it opens.
