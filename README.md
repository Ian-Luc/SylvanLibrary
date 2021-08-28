A tracker and cataloging tool for competitve Magic the Gathering lists to read and parse lists and return the least played cards of an archetype

This project was really good for learning interfacing with a database on a webservice and the Spring MVC framework. I am still not 100% on the up and up about Spring's idiosyncrasies and quirks, but that is something that will just take time. Getting queries to do what I wanted with the repositories was a real issue and it took a while before I realized that writing my own query was the right idea. 

I designed the website with these user stories in mind:
As a user, I can search the database by Archetype so I can find the least cards
As a user, I can serach the database by Card to find the Archetypes that use it
As a user, I can create an account so that I can access the submit features
As an admin, only users can submit, I can control who is adding to the database

My feelings towards Spring is, generously, mixed and, bluntly, quite negative. The automation of boiler-plate code frustrated me, as I felt that Spring was like a black box and I would be unsure of why something was failing and the errors were unhelpful since I had no idea what the Boilerplate code was or did. A great example of this was near the end of the project when I was implementing my submitCardDetails method and it wanted a beannamed "command". This was a bean that I had never used or a word that appeared in my code. At this point, I opted to not use a Spring form and just default to the HTML form. Also, because I was not using Spring Boot, Spring Security was causing massive problems trying to make it work and I decided that making it work would be too much hassle for what it is worth.

My issues with Spring do not discourage my interest in further study and learning; in fact, I am more motivated to learn new technologies to see how newer technologies compare to Spring. In ernest, the form this project takes is not the original vision for the project. Being able to submit decks to the database was something added because I did not have the time or ability to properly research and design an HTML scraper to gather the data from websites. After this training and inbetween my job search and once I obtained a job/career, I am coming back to SylvanLibrary and will remake it. It will be 3 microservices: one devoted to the HTML Scraper, one for the Database, and one for displaying the information on a webservice.
