## express-locallibrary-tutorial
This Web Application develops a website which is used to manage catalog for a
local library.

## What is Model View Controller?
In a typical application you will find these three fundamental parts:

- Data (Model)
- An interface to view and modify the data (View)
- Operations that can be performed on the data (Controller)

The MVC pattern, in a nutshell, is this:

1. The model represents the data, and does nothing else. The model does NOT depend on the controller or the view.

2. The view displays the model data, and sends user actions (e.g. button clicks) to the controller. The view can:

- be independent of both the model and the controller; or

- actually be the controller, and therefore depend on the model.

3. The controller provides model data to the view, and interprets user actions such as button clicks. The controller depends on the view and the model. In some cases, the controller and the view are the same object.

## REFERENCES
[tomdalling blog](https://www.tomdalling.com/blog/software-design/model-view-controller-explained/)
