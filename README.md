# Project: Employee Tasks Export API (ALU Intranet)

## Overview
This project involves creating a Python script that extracts, organizes, and exports employee task data into a JSON format. The data includes details such as user IDs, usernames, task titles, and completion statuses.

## Purpose
The main goal is to generate a comprehensive JSON file that records all tasks for each employee, making it easy to analyze or integrate with other systems.

## Key Features
- Collects task data for all employees.
- Organizes tasks in a nested JSON structure, grouped by user IDs.
- Each user entry includes tasks with a username, task title, and completion status.
- Output file named `todo_all_employees.json`.

## Example Output Format
```json
{
  "USER_ID": [
    {
      "username": "USERNAME",
      "task": "TASK_TITLE",
      "completed": TASK_COMPLETION_STATUS
    },
    ...
  ],
  ...
}
```

## Usage
- Run the Python script to extract data.
- The script outputs the data into the specified JSON file.
- Example command:
```bash
python3 your_script.py
cat todo_all_employees.json
```

---
