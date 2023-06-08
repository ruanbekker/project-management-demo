# project-management-demo
Managing Day-to-Day things with Github

## Motivation

I use a private github repository as my "todo" app. I create all the things I need to do as issues, and label them according to what category they fit in. I often use these issues for blog post drafts as it supports markdown, and whenever I need to post them it's a easy copy/paste.

I also use github's projects to view the todo's I want to work on in a kanban form. I've been using this for the last 4 years and it works for me, so I wanted to share how I use it.

## Usage

Create a new project:

![image](https://github.com/ruanbekker/project-management-demo/assets/567298/28947012-3bb3-4f8c-aeb1-1c766151faef)


Then select issues, then labels:

![image](https://github.com/ruanbekker/project-management-demo/assets/567298/2a7b0a33-44bb-4a6b-b964-a1978ffafd8f)


Here we will see a list of labels:

![image](https://github.com/ruanbekker/project-management-demo/assets/567298/490a02b4-9b08-4e21-acf9-4540f8b5b236)


I will be deleting all the labels:

![image](https://github.com/ruanbekker/project-management-demo/assets/567298/37950902-cafa-489d-a8fb-1b2ea1f8739d)


For my workflow, I would like to categorize my things as:
- blogging
- research
- maintenance
- travel
- education

Then adding more labels, for things like when I want to learn about terraform, docker, aws:
- terraform
- docker
- aws

Then we end up with these labels:

![image](https://github.com/ruanbekker/project-management-demo/assets/567298/e321c654-7086-49fe-bc80-0421595b0ae0)


Now when we head back to issues, and we create a issue, in this case a reminder to "Take a course on AWS":

![image](https://github.com/ruanbekker/project-management-demo/assets/567298/344f86bd-bf1f-4426-8c08-80dfd0b7a9dd)


We can then provide the information about the item, label it as `aws` and `education`, when we create the issue it will look like the following:

![image](https://github.com/ruanbekker/project-management-demo/assets/567298/0c58f0fe-e27d-4002-9062-c1f459d31332)

Lets create another one, let's say a blog post that I want to write, and I have some info already, which we will label under `blogging` and `docker`:

![image](https://github.com/ruanbekker/project-management-demo/assets/567298/b5b5dad0-3724-432a-95cc-49c029a9267c)

And then a last issue, which will be a `maintenance` labeled todo, where we need to replace a garage door battery:

![image](https://github.com/ruanbekker/project-management-demo/assets/567298/05a8f425-8afa-4aed-bb8e-d8d0378bd6d6)

Now when we go back to the issues view and the filter will be selected by default `is:issue is:open` which shows all open issues:

![image](https://github.com/ruanbekker/project-management-demo/assets/567298/378e35f3-a9c3-45bc-832d-5a667a885bff)

We can no view issues only labeled with `education`, by selecting the Label dropdown and selecting your label (or use the expression in the filter section `is:open is:issue label:education`):

![image](https://github.com/ruanbekker/project-management-demo/assets/567298/164d4432-aa4c-4c1a-bb25-3069908d5663)

Now you should only see the one issue, as we only have one issue or todo in my case labeled with education:

![image](https://github.com/ruanbekker/project-management-demo/assets/567298/c5eea90e-dc6e-46e4-96af-90072eb5412f)

Now lets say we have completed the course of AWS, we can comment or just close the issue:

![image](https://github.com/ruanbekker/project-management-demo/assets/567298/7ad6afb8-b59e-4220-9bec-d0121b48b98a)

You should now see that the issue has been closed:

![image](https://github.com/ruanbekker/project-management-demo/assets/567298/b26749d9-8207-42d6-b699-ecc0e760315b)

When you head back to issues, the default filter will show open issues, so you should only see the two open issues:

![image](https://github.com/ruanbekker/project-management-demo/assets/567298/c69a0472-1c29-4a2f-ade2-deb31bbe3eae)

If you want to see all the issues, you can remove `is:open` from the filter:

![image](https://github.com/ruanbekker/project-management-demo/assets/567298/2f5c2d42-4b37-4ad5-a064-44105919e75d)

This is nice and all, but lets say you want to manage these todo's in a more visual way, like a kanban board. This we can do with "Projects".

Select the "Projects" tab, which should look like this:

![image](https://github.com/ruanbekker/project-management-demo/assets/567298/1b5d7fb8-7ee4-45b1-b3f1-1a6bb4422380)

Select the dropdown and select "New project":

![image](https://github.com/ruanbekker/project-management-demo/assets/567298/546e97dd-e6ce-495b-8d80-8f85d3f59d31)

I have selected "Board" on the left and gave it a name:

![image](https://github.com/ruanbekker/project-management-demo/assets/567298/86b6c4c6-6c2c-41a5-a1d7-16986ec01d30)

This is how it should look like:

![image](https://github.com/ruanbekker/project-management-demo/assets/567298/5a7d8c01-3d5a-40e0-9288-9fa3e41a5bcb)

At the top you will see your views, I will be renaming "View 1" to "Kanban", and I will create a "New View" and select "Table" to see a list of items. It will now look like this:

![image](https://github.com/ruanbekker/project-management-demo/assets/567298/62c4b1e5-ab92-450d-b6db-0be9bca0dba1)

If I would like to add a item to my board I have twooptions:
- Adding a item
- Adding a issue by linking the issue to the project

If you are just adding a item, you can select the "+ Add item" at the bottom, start typing what you want to add and select enter, this will then appear on your todo column:

![image](https://github.com/ruanbekker/project-management-demo/assets/567298/e49eeb04-4da9-4d23-b7ed-f1e3e43e50b8)

When we click on the item, we can then convert it to a issue, add assignees, etc:

![image](https://github.com/ruanbekker/project-management-demo/assets/567298/b2bbc364-57e5-4102-a987-0d5b5d153ba9)

The other way is to link an existing issue to the board, and this can be done in two ways, either from the project view or from the issues view.

First we are going to look at the project view. 

- Select "+ Add Item"
- Select the "+"
- Here you will find "Create Issue" and "Add from Repository", Select "Add item from repository"
- Browse for the repository, in my case "project-management-demo"

Which will look like this:

![image](https://github.com/ruanbekker/project-management-demo/assets/567298/65caa394-2256-402c-9cfc-30ddb012d779)

Now that I have selected the issue and linked it to the project, we can see it on the project view:

![image](https://github.com/ruanbekker/project-management-demo/assets/567298/7be83c62-3bde-4f9e-986b-f901fdf2f00b)

And here we can view the issue that we created earlier:

![image](https://github.com/ruanbekker/project-management-demo/assets/567298/1a7443e6-80ff-446e-a6ab-da0c704adf21)

Let's say we start working on this blog post item, then we can move it to "In Progress":

![image](https://github.com/ruanbekker/project-management-demo/assets/567298/493ea958-f445-4063-baa9-22fccb71bd1c)

Once it's completed, we can close the issue and move it to the "Done" column, it should then look like this:

![image](https://github.com/ruanbekker/project-management-demo/assets/567298/6957249e-c57f-4ae9-86f2-09b165d28610)

The other way of linking a issue to a project is from the issue view, select the issue or create a new issue, then underneath labels on the right hand side, we have a "Projects" section, select that and link it to your project:

![image](https://github.com/ruanbekker/project-management-demo/assets/567298/99ea3749-6b7e-41e7-acef-866b077e1bdf)

We can then also select the status which it should be in, in my case "Todo":

![image](https://github.com/ruanbekker/project-management-demo/assets/567298/4435d84e-757f-4294-9169-dea90442968a)

If we head back to the projects view we can see the issue on our todo column:

![image](https://github.com/ruanbekker/project-management-demo/assets/567298/ac465258-0384-4b51-8b91-6b7b49c29297)

We can also view the items on our "List" view from the top, which will look like this:

![image](https://github.com/ruanbekker/project-management-demo/assets/567298/fe259c1a-a77a-4334-9725-8b34dc477ba4)
