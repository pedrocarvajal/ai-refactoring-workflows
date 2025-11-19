# Task Execution Standard

## Execution Process

To execute a task, you need to follow these steps:

1. Understand the objective: First, you must clearly understand what needs to be achieved.

2. Break down the task: Like a project manager, you should divide the main task into smaller, more manageable portions.

3. Define each subtask: Each step or phase must be defined and recorded using the available tools:

   - If you're executing with Cursor editor, use `todo_write`
   - If it's with Claude or another platform, use the corresponding task management method

4. Load into task list: All identified steps or phases must be added to your task list before starting execution.

## Task Structure Example

When breaking down a task, you should create a hierarchical list like this:

```
- Task 1: Refactor authentication module
  - Task 1.1: Extract validation logic to separate class
  - Task 1.2: Update unit tests for new structure
  - Task 1.3: Update module documentation
- Task 2: Optimize database queries
  - Task 2.1: Identify slow queries
  - Task 2.2: Add necessary indexes
- Task 3: Implement new reporting functionality
```

Note: Main tasks (1, 2, 3) represent high-level steps. Subtasks (1.1, 1.2, etc.) are the specific steps that compose each main task. All of these must be registered in your task management system before starting execution.

## User Confirmation

Before starting execution, it's important to ask the user:

- Do you prefer that between each task there's a pause to obtain human confirmation or configuration?
- Or do you prefer that I execute all tasks sequentially without intermediate confirmations?

This decision will determine the workflow during execution.
