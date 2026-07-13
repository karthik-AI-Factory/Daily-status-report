# Python Task Manager

A small command-line mini-project for Day 3 Advanced Python.

## Run

```powershell
cd task_manager
py -m pip install -r requirements.txt
py main.py
```

The app stores tasks in `tasks.json` and writes actions to `task_manager.log`.

## Concepts demonstrated

- OOP, classes, objects, constructors, inheritance, polymorphism
- Encapsulation (`_title`) and abstraction (`Task` abstract class)
- Iterator (`TaskManager`) and generator (`pending_tasks`)
- Decorator (`@log_action`) and context manager (`open_data_file`)
- Logging and JSON handling
- REST API consumption using `requests` (`show_quote`)
