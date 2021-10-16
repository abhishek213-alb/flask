# Basic Flask App
Flask is a micro web framework written in Python. Extensions exist for object-relational mappers, form validation, upload handling, various open authentication technologies and several common framework related tools.  Applications that use the Flask framework include Pinterest and LinkedIn.

## About the project

```python
First we imported the Flask class. An instance of this class will be our WSGI application.

Next we create an instance of this class. The first argument is the name of the application’s module or package. __name__ is a convenient shortcut for this that is appropriate for most cases. This is needed so that Flask knows where to look for resources such as templates and static files.

We then use the route() decorator to tell Flask what URL should trigger our function.

The function returns the message we want to display in the user’s browser. The default content type is HTML, so HTML in the string will be rendered by the browser.

Save it as hello.py or something similar. Make sure to not call your application flask.py because this would conflict with Flask itself.

To run the application, use the flask command or python -m flask. Before you can do that you need to tell your terminal the application to work with by exporting the FLASK_APP environment variable:

![image](https://user-images.githubusercontent.com/76660005/137589473-3fb392df-243e-43e5-960e-b8003b8b8386.png)
