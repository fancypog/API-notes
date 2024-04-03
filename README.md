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
