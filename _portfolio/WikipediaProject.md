---
title: Wikipedia Versions Reporter
subtitle: see which weirdo wrote that wikipage you are reading
image: assets/wiki_logo.png
alt: Shirts on a hanger

caption:
  title: WikiRevisions
  subtitle: find out who wrote the wiki articles
  thumbnail: assets/wiki_logo.png
---

# What?
This little gem of a project, supplied with a wiki article title, will reach out to the wikipedia api and give you back it's editing history.

# Challenges?
This project intoduced me to planning my projects :). as there was a lot of problems to solve. 
- How will we test it?
- How do I turn json into a Java object
- How should I seperate concerns?
- How should a revision be formatted

The major problem involved was trying to architect this project in a clean way. Up until this point, my projects were in a crowded main method.
To remedy this problem I went with a Model View Controller (MVC) approach.

# Stack?
- lang: Java
- frameworks/libraries: [javafx](https://openjfx.io/), [gradle](https://gradle.org/),[JsonPath](https://github.com/json-path/JsonPath)

{:.list-inline}
- Date: March 2020
- Client: Ball State University

