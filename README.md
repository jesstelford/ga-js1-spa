# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Unit Project #3: Single Page App

For the final project, you'll be designing and building a web app of your
choice. This project will test your knowledge of JavaScript and ask you to apply
everything you've learned in this course. The result will be a web app that you
can add to your portfolio. You could create anything from: a blog users can
comment on; an app that allows users to search for social media posts; or even
an application that logs users geolocations. Work with your instructor to create
project goals that are realistic given the scope and timing of the class.

## Overview

### SPA Architecture

Single Page Applications (SPA) are all the rage today. The single page aspect of
a SPA refers to a single page coming from the server, such as our `index.html`
page.  Once loaded, the SPA changes views by using _client-side_ routing, which
loads partial HTML snippets called templates. The goal for you implementing a
SPA is to not make users have to refresh the entire DOM every time they need a
new piece of data to be represented in the UI.

![SPA Architecture](https://cloud.githubusercontent.com/assets/25366/8970635/896c4cce-35ff-11e5-96b2-ef7e62784764.png)

### Potential Project Ideas

**Idea 1**

Movie forum site where users can post their favorite movies and rate them.

**Idea 2**

Celebrity follower app that allows users to easily pull all social media data
from their favorite celebrities.

**Idea 3**

Friend locator site that allows users to see how far away they are from their
friends.

### Suggested Ways to Get Started

- Think of a problem in the world, or even in your personal life, and apply what
  you've learned to build an application that can help solve the issue.
- Research different social media APIs (eg; twitter) and see what kind of
  information you can use from them.
- Look at different online [video games](http://phaser.io/examples) for
  inspiration.

---

## Technical Requirements

### Your core application rules:

Use JavaScript to correctly structure the code for a web application:

- Structure your application to be a SPA (single page application)
- Make HTTP requests to your own Firebase URL
- Make at least one HTTP request to a third-party server
- CRUD functionality should be present
- Perform DOM manipulation via JS (either directly, or with view templates)
- Listen for events and add interactivity based on user input

**Hosting**

App must be hosted on a third party server. Examples include `now`, GitHub
Pages, Firebase, and Heroku.

### Best Practices

Your instructor will provide feedback on how well you execute best practices.
Even though it is not part of the requirements, you should keep these in mind:

- __Clean And Readable Code__. The instructor should be able to read and follow
  your code easily. Maintain clean and readable code including: consistent
  indentation, code commenting and use of proper and consistent naming
  conventions.

- __Object Oriented and/or Functional__. Implement function closures, keep code
  modular, maintain a separation of concerns, only put code on the global scope
  when absolutely necessary, favour composition over inheritance (or use
  prototypal inheritance when you feel appropriate).

---

## Getting Started

Begin by "forking" this starter code repository. You can do so by clicking the
"Fork" icon on the top right of [this
page](https://github.com/jesstelford/ga-js1-spa). Once complete, clone the
repository to your computer by running the following commands:

```
git clone https://github.com/<your-username-here>/ga-js1-spa.git
cd ga-js1-spa
```

The `ga-js1-spa` directory now contains a copy of this repository.

As you accomplish a feature, be sure to commit it to Git and push to GitHub.

---

## Necessary Deliverables

* A **production ready web application**, SPA, hosted live on the web.
* A **new git repository hosted on Github** where codebase is maintained.
* A 3-5 minute **presentation** including at least 3 technical hurdles, 2 new
  things you learned, and what you'd like to do next with your app.

### Due Date

Presentations will be held Wednesday July 27th in class.

Your project must be submitted before class starts on Wednesday 27th July (class
starts at 6pm).

---

## Project Feedback + Evaluation

Students will fork the "ga-js1-spa" application and commit their code as they
complete pieces of functionality.

The instructional team will grade each technical requirement and provide a
numeric grade on a scale.

- **Technical Requirements**: Did you deliver a project that met all the
  technical requirements? Given what the class has covered so far, did you build
  something that was reasonably complex?
- **Creativity**: Did you add a personal spin or creative element into your
  project submission? Did you deliver something of value to the end user (not
  just a hello world response)?
- **Code Quality**: Did you follow code style guidance and best practices
  covered in class, such modularity and semantic naming? Did you comment your
  code as your instructors have in class?
- **Total**: Your instructors will give you a total score on your project.

Each category is scored according to the below, where a `1` is a _pass_.

Score | Expectations
----- | ------------
**0** | _Does not meet expectations._
**1** | _Meets expectactions, good job!_
**2** | _Exceeds expectations, you wonderful creature, you!_

The total will serve as a helpful overall gauge of whether you met the project
goals, but __the more important scores are the individual ones__ above, which
can help you identify where to focus your efforts for the next project!
