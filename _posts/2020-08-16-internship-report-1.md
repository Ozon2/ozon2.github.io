---
layout: post
title: First year internship report
date: 2020-08-16 21:40 +0100
---

# Introduction

This year I wanted to find the right internship to improve my technical skills in software development with either Python or Java.

I was very lucky to find an internship at [LAAS](https://www.laas.fr/public/en), a research unit of the CNRS. I was given three small projects during the two months I worked there, and I dedicated approximately three weeks to each of them. Sadly, I was only able to work remotely because of COVID.

# My work at LAAS

## Educational robots

[Thymio](https://www.thymio.org/) is an educational robot created for teachers and students from primary school to university, it allows students to discover the universe of robotics and learn a robot's language. 

During the first project I had to create a work environment on a Rasberry Pi so students could program Thymio robots easily. The goal was also to make it easy for teachers to monitor their student's computers. I also made a game to allow teams of students to compete in a Thymio race.

This project allowed me to learn **cross-compilation** and to discover software development with **Qt** using **Python** to make a game.

## Dashboard

When I finished my first project I was then charged to work on the lab's dashboard, a Django app which essentially centralizes projects from both Gitlab and Github, CI results and other useful information about all the activities done at LAAS.

The main problem I had to solve was that the repositories were hosted on Github but the CI had to be done on Gitlab, so I was tasked to mirror every commit on Github to Gitlab, let the CI run on Gitlab and get the CI status back to Github. I also had to synchronize issues on both repositories and display them on the dashboard.

This was challenging because I didn't work with **Django** before, but I really enjoyed learning it. It also made me discover working with REST APIs.

## Python packages

Création de wheels Python manylinux pour plusieurs projets du LAAS

After theses projects I still had some time left, so I was given a third project. I was tasked to package some Python apps so they could be published on [PyPi](https://pypi.org). I used [manylinux](https://github.com/pypa/manylinux) to produce packages that are compatible with the vast majority of desktop and server Linux distributions.

I enjoyed this project because it made me work with **Docker**.

# Conclusion

I really liked this internship, it was my first work experience and it made me confident that I chose the right path for my career. I enjoy software development and system administration and I hope I will find work in this field after my studies. The only downside of this internship is that I wish I was able to work at LAAS because always working remotely can be a little depressing sometimes.
