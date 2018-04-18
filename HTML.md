HTML or Hyper Text Markup Language provides structure to a document.

Every HTML document needs boilerplate:
```
<!DOCTYPE html>
<html>
  <head>
    <title></title>
  </head>
  <body>
  </body>
</html>
```
Block-level vs inline elements
Semantic Markup --> MEANINGFUL structure
  - <header>, <footer>, <nav>, <section>, <aside>, <article>
  - <table>, <thead>, <tbody>, <caption>
  - <figure>

Elements are enclosed in tags (some are self-closing)
  - Elements can be nested
  - Elements can take attributes in the form of *key-value pairs*

**<head>** provides metadata
**<body>** holds the content
**<title>** provides the tab & link names from external sites

Comments are notes for devs and will not show on the actual page: <!-- COMMENT -->

Heading elements have *ranks* of different sizes from <h1> to <h6>
Paragraph elements <p>
<em>, <strong>

<div> and <span> are containers for grouping content, and are useful for applying styling; divs are block-level, whereas spans are inline

Lists: <ol>, <ul>, <li>; lists can be nested

<img> - image tag
<a></a> - anchor tag for explicit (http) vs relative paths (file protocol)

<table> creates tables/charts, and styling (including borders) should be done in CSS
  <table>
    <thead>
      <tr>
        <td></td>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td></td>
      </tr>
    </tbody>
  </table>

<form> creates a container for inputs; forms take input data and send it somewhere in a request
- has *action* (where to send data to) and *method* (HTTP method) attributes
<input>
- has *type* attribute: about 30-40 types (text, password, email, radio, checkbox, color, submit)
- *name* attribute is used to group input
- *value* attribute determines data actually sent
- optional: *placeholder* attribute
- optional: *pattern* can dictate validation, *title* can display an instructional message
<label>
- nested format: <label>Name: <input type="text"></label>
- *for/id* attributes: <label for="name">Name: </label><input id="name" type="text">

Other form controls:
- <select> and <option> tags for dropdown menu
- <textarea> has rows + cols attributes

HTML Validation:
- *required* boolean attribute
