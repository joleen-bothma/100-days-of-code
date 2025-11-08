# #100DaysOfCode Log - Round 1

The log of my #100DaysOfCode challenge. 

Round 1.

Started on Monday, November 3, 2025.

## Log

### Day 1: Monday, November 3

**Today's Progress**:
- Started working on [My Family Recipes](https://github.com/joleen-bothma/my-family-recipes): learning about HTML, CSS, 11ty, and JavaScript by building a website that shows my own family recipes. The goal will be to browse our favourite recipes with additional organisational elements like tags and categories. 

**Link(s) to work:**
1. [Today's commits - My Family Recipes](https://github.com/joleen-bothma/my-family-recipes/commits/main/?since=2025-11-03&until=2025-11-03)

### Day 2: Tuesday, November 4

**Today's Progress**:
- Started working on [My First Django App](https://github.com/joleen-bothma/django-polls): learning about backend web development with Django by following the offical tutorial.
- Downloaded and installed Postgresql to use with Django in later projects.

**Link(s) to work:**
1. [Today's commits - Django Polls](https://github.com/joleen-bothma/django-polls/commits/main/?since=2025-11-04&until=2025-11-04)

### Day 3: Wednesday, November 5

**Today's Progress**:
- Abandoned previous Django project (My First Django App) and started working on a ToDo App using a combination of 2 resources:
  - [YouTube video by Dennis Ivy](https://www.youtube.com/watch?v=llbtoQTt4qw)
  - [RealPython Tutorial](https://realpython.com/django-todo-lists)

**Link(s) to work:**
1. [Today's commits - Django ToDo App](https://github.com/joleen-bothma/django-todo-app/commits/main/?since=2025-11-05&until=2025-11-05)

### Day 4: Thursday, November 6

**Today's Progress**:
- Continued working on my ToDo app
  - Encountered an issue when adding a view to create a new task: URL for `reverse_lazy` returns an error. I think I am running into problems because I am not using good naming conventions between my views, models, and url paths. Commited the code but need to fix this.

**Link(s) to work:**
1. [Today's commits - Django ToDo App](https://github.com/joleen-bothma/django-todo-app/commits/main/?since=2025-11-06&until=2025-11-06)

### Day 5: Friday, November 7

**Today's Progress**:
- Still working on resolving some issues with the ToDo app. While I no longer get an error when using `reverse_lazy` for  `get_success_url`, the URLs are not working as intended. My app has multiple lists, each containing their own tasks, but my views are not setup to do this. After reading [this mozilla tutorial](https://developer.mozilla.org/en-US/docs/Learn_web_development/Extensions/Server-side/Django/Models), I think the issue is that I need to define a `get_absolute_url` function in my models. More research and testing needed. 

**Link(s) to work**:
None - bugs and issues not resolved.