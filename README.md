This is learning graphQL

What is GraphQL?
  * GraphQL is an open source query language (syntax and rules).
  * It is an alternative for using RESTful API.
  * Under the hood, GraphQL use HTTP and HTTPS requests like RESTful API.

Drawbacks in RESTful API
  * Over fetching - sends too much data than we need
  * Under fetching - sends less data than we need

How GraphQL works
  * Query is sent to a single server endpoint.

We use Apollo server and it creates a GraphQL server

In server typeDefs are definitions of type of data that we want. example : author game , price, description, title. 