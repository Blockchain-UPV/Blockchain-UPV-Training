# Roadmap for web development

This is some sort of guide for web developing beginners. The intention is to give some direction on your first steps in this field. You will find some resources that from our understanding and/or experience were particularly useful.

Take it as it is, a guide but not a dogma. We are all different kind of learners and what we found useful or interesting may not be useful for you. In any case, we wrote this guide in our best intention, let us know about improvements on this guide or any resources you may find useful.

## Basic Technology used in web development

#### Programming Languages & Document formats
* **JavaScript**. This programming language was conceived to run on the web browser and make dynamic webpages.
There are great resources for learning this programming language for free such as [freecodecamp](https://www.youtube.com/watch?v=PkZNo7MFNFg&list=PLWKjhJtqVAbleDe3_ZA8h3AO2rXar-q2V) and if you want to dig deeper I recommend [this book](http://www.r-5.org/files/books/computers/languages/escss/fp/Nicholas_C_Zakas-The_Principles_of_JavaScript-EN.pdf). We should also mention [this web channel](https://www.youtube.com/channel/UCmXmlB4-HJytD7wek0Uo97A) with some interesting hands-on content.

    For practising javaScript with some job interview like problems I suggest the online platform [codewars](https://www.codewars.com/).

* **HTML**. This is a markup language, it has content between tag marks like ```<h1>This is a header</h1>```. I would not suggest spending too much time learning HTML as you can learn more complex things as you go but it is important to know the basics and having a good understanding of what a basic HTML file looks like.

    More as a reference than a course we would recommend [w3schools](https://www.w3schools.com/html/default.asp) and there are good step by step tutorials in [codeacademy](https://www.codecademy.com/learn/learn-html).

* **JSON** this is simply a document format, you can learn more about it [here](https://www.w3schools.com/js/js_json_intro.asp).

## There's Two Sides to Every Story

### Frontend
This is the part that we interact with through the browser. It is the so-called graphic interface of our application, everything that is displayed in your web browser is frontend.
The frontend communicates with the other parts of the application through an [API](https://www.youtube.com/watch?v=GZvSYJDk-us&t=761s).

Currently, React or Vue.js are among the most popular web frameworks for frontend development. I found particularly useful the [freecodecamp](https://www.youtube.com/watch?v=DLX62G4lc44) guides and projects, the [old Traversy media content](https://www.youtube.com/watch?v=sBws8MSXN7A). If you want to dig deeper you may want to take a look at [this video](https://www.youtube.com/watch?v=Q9Qx2Xef0do).

Two fundamental concepts for this two frameworks are the modularization/components and the state management (which actually is a software pattern) **Redux** for React, find more [here](https://www.youtube.com/watch?v=93p3LxR9xfM). At this point, you should have been building some small applications so you will find different kinds of information or tutorials for state management, again feel free to explore.

### Backend
This is the part that is used to operate with data. Normally it exposes an [API](https://www.youtube.com/watch?v=GZvSYJDk-us&t=761s) that is used by the frontend (and possibly by other services). It is highly recommended to understand the [REST protocol](https://en.wikipedia.org/wiki/Representational_state_transfer) which is implemented by the most basic backend services.

Although there are loads of possible choices for backend applications here we will focus on Node.js which is a JavaScript framework for backend applications.

We do not have a particular course or resource to learn node from start to finish because we learnt it by building small applications. If we had to choose some resources we would go back to [freecodecamp](https://www.freecodecamp.org/news/tag/nodejs/) and also its [youtube channel](https://www.youtube.com/channel/UC8butISFwT-Wl7EV0hUK0BQ) for guides for total beginners. We also found that [The coding train](https://www.youtube.com/user/shiffman) has some great content for learning, building or just have fun, although is not a good place if you are looking for a structured tutorial.

As the backend have to communicate with other parts of the application or even with third-party services it has to expose an API, normally using the REST protocol. We recommend to using two
Node.js libraries **KOA** or **Express** to develop Rest APIs. Notice that Koa is an evolution of express and is more lightweight and probably more convenient to use in small projects. Before deciding which one to chose, be aware of the differences and strengths and weaknesses of each one.

As mentioned previously, the backend operates with data therefore we need to integrate databases into this part of the application. The two most common paradigms or models of databases are relational and non-relational.

For non-relational databases, MongoDB is widely used and for relational databases I particularly like PostgreSQL. For relational databases, we often use an ORM, for PostgreSQL I recommend [Sequelize](https://sequelize.org/master/).

We also suggest this course about node.js in [coursera](https://www.coursera.org/programs/addf2bd7-cb7e-49d2-83d7-4ff7e1efd883/browse?productId=pn1erK4cEeaP-Q4_2QdcFg&productType=course&query=node.js&showMiniModal=true) that walk through basic authentication and CORS in node.js.

Although we have not post many resources for this last part the idea is that if you have gone through the basics you will find loads of resources on those matters and probably you will have your own source of resources at this point. In any case, we wanted to emphasis those technologies for data management and rapid API development.

Notice that Python or Java are perfectly valid choices for backend applications and also have libraries to develop API, etc. I particularly recomend to play with [Flask](https://flask.palletsprojects.com/en/1.1.x/) if you are interested with Python.
