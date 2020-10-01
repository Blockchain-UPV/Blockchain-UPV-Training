# My roadmap to web development

First we need to understand some basic in web development.

### Frontend
This is the part that we interact with through the browser. It is the so-called graphic interface of our application, everything that is displayed in your web browser is frontend.
The frontend communicates with the other parts of the application through an [API](https://www.youtube.com/watch?v=GZvSYJDk-us&t=761s).

### Backend
This is the part that is used to operate with data. Normally it offers an [API](https://www.youtube.com/watch?v=GZvSYJDk-us&t=761s) that is used by the frontend (and possibly by other services). It is highly recommended to understand the [REST protocol](https://en.wikipedia.org/wiki/Representational_state_transfer) which is implemented in the most basic backend services. 



## Technology used in web development

#### Programming Languages & Document formats
**JavaScript**. This programming language was conceived to run on the web browser and make dynamic webpages.

**HTML**. This is a markup language, it has content between tag marks like: ```<h1>This is a header</h1>``` . I would not suggest to spend to much time learning HTML as you can learn more complex things as you go but it is important to know the basics and having a good understanding of what a basic html file looks like.

**JSON** 

### Frontend
Currently, React or Vue.js are the most popular web frameworks to develop frontend applications.

Two fundamental concepts for this two frameworks are the modularization/components and the state managment (which actually is a software pattern) **Redux** for React and Veu

### Backend
Altough there are loads of possible choices for backend applications here I will focuse on Node.js which is a JavaScript framework for backend applications.

As the backend have to communicate with other parts of the application or even with third party services it has to expose an API, normally using the REST protocol. I recommend to use two 
Node.js libraries **KOA** or **Express** to develop Rest APIs. Notice that Koa is an evolution of express and is more lightweight and probably more convenient to use in small projects. Before deciding which one to chose be aware of the differences and strengths and weeknesses of each one.

As mentioned previously, the backend operates with data therefore we need to integrate databases into this part of the application. The two most common paradigms or models of databases are relational and non-relational.

For non-relational databases MongoDB is widly used and for relational databases I particularly like PostgrSQL. For relational databases we often use an ORM, for PostgreSQL I recommend [Sequelize](https://sequelize.org/master/).

Notice that Python or Java are perfectly valid choices for backend applications and also have libraries to develop API, etc. I particularly recomend to play with [Flask](https://flask.palletsprojects.com/en/1.1.x/) if you are interested with Python.

