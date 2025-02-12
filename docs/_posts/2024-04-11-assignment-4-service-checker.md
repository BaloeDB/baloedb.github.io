---
layout: post
title:  "Assignment 4: Service Checker"
date:   2024-04-11 15:00:00 +0200
categories: itvitae bonustrack
---

## Description
In this exercise I have created a service checker in python.
It periodically sents get requests to web services for their status.
The tools that I have used for this project are: flask, requests, turbo-flask and jinja.
I used html and bootstrap for the frontend.
I also needed to implement multi-threading for this exercise.

This project is not visible online yet. I will try to deploy it later.

## Objectives
This exercise has two objectives:
1. Learn how to use flask and requests to make a simple web app.
2. Learn how to periodically sent a get request to an endpoint / multi-threading.

## Resources
Official documentation:
1. https://jinja.palletsprojects.com/
2. https://flask.palletsprojects.com/
3. https://turbo-flask.readthedocs.io/
4. https://pypi.org/project/requests/
5. https://getbootstrap.com/

Special acknowledgment to:
- https://blog.miguelgrinberg.com/post/dynamically-update-your-flask-web-pages-using-turbo-flask

Forums & Blogs:
1. https://www.reddit.com/
2. https://stackoverflow.com/
3. https://medium.com/
4. https://realpython.com/

Further Reading:
1. https://stackoverflow.com/questions/15721679/update-and-render-a-value-from-flask-periodically
2. https://medium.com/@thujuli/how-to-schedule-tasks-using-celery-in-flask-application-c004dd3c5e5c
3. https://blog.miguelgrinberg.com/post/dynamically-update-your-flask-web-pages-using-turbo-flask
4. https://medium.com/greedygame-engineering/an-elegant-way-to-run-periodic-tasks-in-python-61b7c477b679
5. https://flask.palletsprojects.com/en/2.3.x/patterns/celery/
6. https://stackoverflow.com/questions/9508667/reload-flask-app-when-template-file-changes

## Developer notes
- I have a feeling I got stuck too long in solving this exercise.
  I should have been able to complete this exercise faster.
- The biggest challenge for me is: learning how to use tools that you don't really know yet.
  How much should I read before I start making projects? How to avoid copy-pasting?
- There are many other ways I could have tackled this problem:
  * Separting client & server (ajax)
  * Figuring out how celery works
  * And many others, see further reading
- The teacher also asked to implement the same exercise using Go. A language I have never touched.
  * I should do this later. Again, the same problem: learn how to use a tool that you don't know yet.
