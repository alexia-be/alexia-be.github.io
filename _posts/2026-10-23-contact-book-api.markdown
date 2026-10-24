---
layout: posts_projects
title:  "Contact book REST API"
date:   2026-10-23 10:15:20 +0000
categories: learnings
highlight_home: true
tags: API
description: My first Flask API, a small contact book I built to learn REST APIs with Python.
header:
  overlay_image: /assets/images/contact-book-api-screenshot.png
  teaser: /assets/images/contact-book-api-screenshot.png
---
Flask CRUD API.

My first Flask API: a small contact book I built to learn REST APIs with Python.

![Contact book API](/assets/images/contact-book-api-screenshot.png)

**Code:** [View the project on GitHub](https://github.com/alexia-be/my-learnings/tree/main/contact-book-api){:target="_blank"}

## What it does

It has endpoints to get all contacts, get one contact by id, create, update, and delete a contact. If you ask for an id that doesn't exist, it returns an error message.

## Why I built it

To learn REST APIs and Python. I followed the course *Skill Up with Python: Hands-on Web Development Projects* by Pearson and Shaun Wassell on LinkedIn Learning, and completed it in one day on October 23, 2026.

## Tools

Python, Flask, VS Code, Postman

## What I learned

- What Flask is and how to use it to create API endpoints with Python.
- How to return an error message when a contact doesn't exist.
- How to test requests with Postman.
- The contacts are stored in the Python file, so anything I add through the API is gone after a server restart. This is why real apps use a database.
- How `for` loops work in Python, which I understand better after using them in the endpoints.

## Next steps

Go deeper into Python to understand how apps work in general, and keep building more projects.