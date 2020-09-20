Use GitHub Issues/Projects to manage household chores

# User Story

As a forgetful person, I want to use GitHub project boards to manage chores because I'm already on GitHub a lot, and
hopefully I'll be reviewing my TODO lists more frequently.

# Features

* GitHub Actions used to automatically created GitHub Issues representing chores that need to be completed.

![Issues List](household-chores/docs/assets/Issues-List.png)

* Author a list of chores that need to be created every month, as well as a list of chores for a specific month.

* Issues are automatically assigned to a Milestone to track due date.

* Issues may be authored using [Markdown Syntax](https://guides.github.com/features/mastering-markdown/) to allow for checkbox, links, etc.

![Issues with Markdown](household-chores/docs/assets/Issues-With-Markdown.png)

* Issues are automatically assigned to a `Chores` project to manage using project boards.

* GitHub Actions used to automatically to close Issues moved to the `Done` column (and reopen Issues moved out of it).

![Project Board In-Progress](household-chores/docs/assets/Project-Board-In-Progress.png)
