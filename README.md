# TO-DO CLI APP

Following a Real Python tutorial, I've built this CLI app that lets you add tasks to a to-do list and set them as complete to follow on your daily deadlines.

## Usage

To use it (after cloning the repo), you must first initialize the database with:

```
python -m rptodo init
```

By default, this will create a .json file on your user's home folder, but you can select other path.

With that done, you can make use of the app with the following commands:

- add: Add a new to-do with a description.
- clear: Remove all to-dos
- complete: Complete a to-do by setting it as done, using its ID
- list: List all to-dos.
- remove: Remove a to-do using its id.

And here goes and example of syntax:

```
python -m rptodo add <task_description> -p <task_priority_max3>

python -m rptodo list

python -m rptodo complete <task_id>

python -m rptodo remove <task_id>

python -m rptodo clear
```