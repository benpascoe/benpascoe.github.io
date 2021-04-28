---
title: Surfcrunch
date: 2021-04-28 11:37:00 Z
---

Summary: There wasn't a perfect way to log my surf sessions, so I made my own mobile friendly web app and a companion Garmin watch face.

Skills and technologies I learned creating surfcrunch.com:

**Programming languages**
* Python - popular programming language with many uses
* HTML - Hyper Text Markup Language, for laying out webpages
* Monkey C - programming language for creating apps and watch faces for Garmin watches and devices

**Frameworks and libraries**
* Flask - micro framework for building websites using Python
* Jinja2 - templating system
* Xarray - reading and manipulating multi dimensional arrays (often used for meteorological data)

**Development tools**
* Docker & Docker Compose - container system
* Jupyter Notebooks - interactive notebook that allows you to run pieces of code in chunks, I like using Google Colaboratory, but there are many different types
* PyCharm - IDE (integrated development environment) for Python

**Hosting**
* Digital Ocean - IaaS (Infrastructure as a service) provider

**Database**
* PostgreSQL - relational database
* PostGis - extension for PostgreSQL to handle spatial data

**Hardware**
* Raspberry Pi 4 - A single board computer


What I want in a surf logging system:

* Easily record the date, time and duration of a surf session
* Automatically add swell, wind and tide data to a current or past session
* Optionally add extra details to the session, e.g. photos, rating, gear, notes, costs, crowd details
* Record surf spots for easy reference

The most similar option out there currently is the Rip Curl GPS watch and accompanying web app.

I've tried out the first generation Rip Curl GPS watch and used the web app to view my sessions, but it's lacking some of the features I wanted for my own logging system.

It has some social features that aren't interesting to me, and it lacks some of the basic features that I think are most useful when logging your surf sessions.

The main reason I want to log a session is because nearly every wave I surf is fickle.

The tidal range of my local spots is about 6m (20 feet). I live on a headland that theoretically offers shelter for three directions, but various factors mean swell direction can kill an otherwise promising forecast.

I want to check what conditions were like for the session, including tide, multiple swell sizes and directions, and wind, even if it was 10 years ago.





