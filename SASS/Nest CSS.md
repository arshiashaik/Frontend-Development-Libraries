# Nest CSS with Sass

Sass allows nesting of CSS rules, which is a useful way of organizing a style sheet.

For a large project, the CSS file will have many lines and rules. This is where nesting can help organize your code by placing child style rules within the respective parent elements:

```
nav {
  background-color: red;

  ul {
    list-style: none;

    li {
      display: inline-block;
    }
  }
}
```
