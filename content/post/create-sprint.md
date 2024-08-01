+++
title = "Work with sprints in Jira"
date = "2024-07-29T18:34:02+00:00"
draft = false
author = "Mikaela Rodriguez"
+++

A sprint is a set period of time during which your team will attempt to complete development work from a backlog. Sprints are a main component of the agile methodology of project management, called Scrum. Scrum focuses on the continuing delivery of features in bite-sized increments. To learn more, see [What is Scrum?](https://www.scrum.org/resources/what-scrum-module).

Many organizations use [Jira](https://www.atlassian.com/software/jira) software to track the work they complete during sprints. This tutorial will walk you through the steps to create, populate, and complete sprints using Jira.

## Create a project
A project within Jira is a container for tasks that represent an organization, project, or product. First, create a project to organize your tasks.

- Navigate to `Projects` > `Create Project`.
- Select the `Software Development` template, then choose the `Scrum` template, and click `Use Template` to confirm.
- Choose a project type:
  - **Team-managed**: Allows you to control processes in a self-contained space.
  - **Company managed**: Choose this project type to share tasks across teams.
- Enter a name for your project.
- Choose the access for the project:
  - **Private**: Only allows admins and added users to search, view and edit issues.
  - **Limited**: Anyone in your organization can view and comment on the project.
  - **Open**: Anyone in your organization can search, view and edit this project.

- Click `Create Project` to finalize.

*Note: There are many project templates available to choose from. This tutorial demonstrates using Jira with a software development project.*

## Create an epic
An epic is a collection of work focused on a larger goal. An example of an epic is a new feature your team is developing as part of a larger product release. Tasks within an epic are called stories.

- From the project dashboard, click `Backlog`. This is where you can view all the stories your team has created.
- Click `+ Create Epic` to create a new collection of tasks. Enter a name for your epic.
- Click on the epic to see more details on the right side of the page. 

## Create a story
Stories are the small chunks of work that make up your epic. All your team's stories are collected within the backlog.

- Within the `Epic` swimlane, click the epic that you want to assign your story to.
- In the `Backlog` click `+ Create Issue`. 
- Enter a name for the story.

### Manage stories
You can edit stories after you create them. For example, you can add and update a story's point estimation. Story points are a measure of the effort and time it will take your team to complete a task.

- Click a story to display details in the right-hand menu. To view a story in full screen, click the title of the story.
- You can add more information to a story within this view.
- Click `Story point estimate` to enter the story point value for the task. 

## Create and start a sprint
After you have created an epic and populated it with stories, it is time to start a new sprint. Starting a sprint locks in the stories you have chosen to the duration of the sprint. Try not to edit the sprint after you have started it, as a sprint is meant to capture both the work completed and work that isn't completed before the time period ends.

- In the `Backlog`, click `Create Sprint`. 
- Click and drag stories from the `Backlog` section into the new sprint you have created.
- When you are satisfied with the amount of work in the sprint, click the `Start Sprint` button.
- Enter the following information for the sprint:
  - **Duration:** The length of your sprint. You can select a predetermined period of time or define one.
  - **Start date:** The start date of the sprint.
  - **End date:** The end date of the sprint.
  - **Sprint goal:** The goal your team is trying to achieve during the sprint.
- Click the `Start` button.

*Note: You can only have one active sprint at a time, although you can create as many sprints as needed for future planning.*

## Manage the sprint
Part of the usefulness of using sprints is being able to move stories through different statuses as your team progresses through their work. Everyone on your team can view a task's progress by looking at the backlog.

- In the left-hand menu, navigate to `Board`.
- Click and drag tasks to the appropriate swimlane based on their status. For example, drag completed stories to the `Done` swimlane. 

## Additional resources
- [7 Steps to get started in Jira](https://www.atlassian.com/software/jira/guides/getting-started/basics#step-1-create-a-project)
- [Agile epics](https://www.atlassian.com/agile/project-management/epics)
- [Agile manifesto](https://www.atlassian.com/agile/manifesto)