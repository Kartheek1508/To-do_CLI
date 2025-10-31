# To-Do List CLI

A simple command-line to-do list app in Python.

## Installation

Requires Python 3.6+. No external dependencies needed.

## Usage

Run the app:
```bash
python todo.py
```

### Commands

- `add <task>` - Add a new task
- `list` - Show all tasks
- `complete <id>` - Mark task as done
- `delete <id>` - Remove a task
- `help` - Show help
- `exit` - Exit

### Example

```
> add Buy groceries
✓ Added: Buy groceries

> list
📋 Your To-Do List:
------------------------------------------------------------
○ [1] Buy groceries
------------------------------------------------------------

> complete 1
✓ Completed: Buy groceries

> exit
Goodbye!
```

## Storage

Tasks are saved to `todos.json` in the same directory.
