# Task Report Generator for Terminal

Now that I need to create daily reports detailing all of my tasks, I figured I'd make a quick tool that I can access from the terminal.

I found that when I need to keep record of my activities in a separate application, I lose track of what I did. This simple script allows me to create this report directly from the terminal. This way, after every pull request or even commit, I can add a task to my daily list.

Currently supported commands:

- `task`: Reads the report
- `task add [task description]`: Adds the task description to the list of tasks
- `task clear`: Clears the list to begin a new day's report

Make sure to add the repository to your PATH so you can access the daily report from anywhere.
