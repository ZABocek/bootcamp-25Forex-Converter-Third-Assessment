### Conceptual Exercise

Answer the following questions below:

- What are important differences between Python and JavaScript? JavaScript is run only on the front end and is what the client sees. Python is only meant to be seen by the back end server side, and is set up to process http requests.

- Given a dictionary like ``{"a": 1, "b": 2}``: , list two ways you
  can try to get a missing key (like "c") *without* your programming
  crashing. You could use get() or setdefault().

- What is a unit test? It can occur when you test only one function or method of an application.

- What is an integration test? It refers to testing how well all functions of an application work together.

- What is the role of web application framework, like Flask? It makes it much easier to create routes using simple route decorators, instead of taking much longer to do the same thing with only Python.

- You can pass information to Flask either as a parameter in a route URL
  (like '/foods/pretzel') or using a URL query param (like
  'foods?type=pretzel'). How might you choose which one is a better fit
  for an application? If a client is creating a webpage dynamically, a URL query parameter might work best. For a static page, a parameter in a route URL might work best.

- How do you collect data from a URL placeholder parameter using Flask? First, you need to import request from flask. Then, save a request for a variable using request.args[].

- How do you collect data from the query string using Flask? Import request from flask. Then use request.args.get() to collect data from a query string.

- How do you collect data from the body of the request using Flask? You use request.args.get().

- What is a cookie and what kinds of things are they commonly used for? It gives a state to an http request, but it is much more limited than a session. It can be used to remember many different variables that apply to a visitor of a webpage, such as whether they click or hover over an advertisement.

- What is the session object in Flask? It stores data about a visiting client to a webpage permanently in a browser by signing it.

- What does Flask's `jsonify()` do? It turns data that can be used by json into a json format. A set, for example, must be converted to a list before it is jsonified.
