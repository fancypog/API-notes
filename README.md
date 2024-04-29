# API Notes

## What are APIs for?
- APIs are for programmers to use and extend in their applications.
- They provide access to data and abstract the implementation details.

## Types of APIs

mostly people talk about web APIs when referring to APIs
- **String API:** Example: `.toUpperCase()` - Converts a string to uppercase.

  Example usage:
  ```javascript
  const str = "hello";
  const upperCaseStr = str.toUpperCase();
  console.log(upperCaseStr); // Output: HELLO

- **to make code work in different operating systems**

  For example:
  ```python
  """ Lists files and directories in the current working directory. """
  import os
  current_dir = os.getcwd()
  for entry in os.listdir(current_dir):
    print(entry)

frameworks offer API for you to extend stuff

## REST API
- REST: representational state transfer
- APIs that meet the REST architectual style contraints are "RESTful"
- Constraints: Client-Server Architecture, Statelessness, Cacheability, Layered System, Code on Demand, Uniform Interface

- the programme sends a stateless HTTP request to the server (to request a resource), so the server won't remember who the client is
- do that using a header
- then the server respond with data and all HTTP headers (JSON)
- HTTP Verbs are used in REST API requests (GET, POST, PUT, PATCH, DELETE)

  # JSON
  ## What is JSON
  - JSON (JavaScript Object Notation) is a data representation format commonly used for APIs and Configs
  - JSON is valid JavaScript

  ## Why you should know JSON
  - Most languages allow you to parse JSON strings into object/ classed into that language
  - JSON is essential for creating and consuming an API

  ## JSON TYPES
  - Strings  "Hello World" "Eyyy" "I"
  - Numbers 32 5.2 -50 1.2e10
  - Booleans true false
  - null null
  - Arrays
    ```JSON
    [1, 2, 3] ["Hello", "World"]
  - Objects
  - ```JSON
    {"key": "value"} {"year": 2000}
  
