**8 Queens Problem**

------

The [eight queens problem](https://en.wikipedia.org/wiki/Eight_queens_puzzle) involves placing 8 queens on a chess board in such a way that none are attacked.

![queens](./problem/img/queens.jpg)

A solution to the eight queens problem in JS can be modularized by designing it as a standard [model-view-update](https://guide.elm-lang.org/architecture/) web application.

+ The **model** represents the **state** of the application;
+ the **view** is a function that maps a model to an appropriate visualization (an HTML element) of the model;
+ and **update** is a function that maps an old model to a new model.

This software design pattern, called the [Elm Architecture](https://guide.elm-lang.org/architecture/), is a refinement or advancement on the older design pattern called [model view controller](https://en.wikipedia.org/wiki/Model%E2%80%93view%E2%80%93controller). The model-view-update design can and should be used for almost all web applications.