---
title: D&D Character Generator
subtitle: make a dnd character sheet like magic
image: assets/dnd_logo.png

caption:
  title: Make the character for your next campaign lickedy-split!
  subtitle: How do I get in my campaign faster?
  thumbnail: assets/img/portfolio/02-thumbnail.jpg
---

# What?
If you have played a good bit of D&D like I have, making your character is very tedious.
Me and three other students decided to make that step a lot easier for a school project.
This little program provides a nice Gui to making a character. Everything from the Race, to the armor class will be provided. At the end you will get an official charactersheet pdf with the boxes filled out for you.

# Challenges?

I have to say that D&D is a difficult domain to program for. 
The biggest hurdle to overcome on this project was the sheer size of the character business logic.
There is a lot of things that goes into a character such as
- Race
- Skills
- Subraces
- Each race can modify your stats so that has to be changed inrementally
- Backgrounds
- Vitality
- Armor class
- Etc
- Random dice rolling etc.

We solved all of these problems by using hard-coding in a bunch of D&D data. Then really spending time on planning and testing the Character.java class.
The funny part is I found a database api on dnd that we could have pulled from. 

# Stack?
- lang: Java
- frameworks/libraries: [javafx](https://openjfx.io/), [gradle](https://gradle.org/) 


{:.list-inline}
- Date: January 2017
- Client: Explore
- Category: Graphic Design

