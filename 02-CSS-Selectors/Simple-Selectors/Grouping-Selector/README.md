The grouping selector selects all the HTML elements with the same style definitions.

Look at the following CSS code (the h1, h2, and p elements have the same style definitions):

h1 {
  text-align: center;
  color: red;
}

h2 {
  text-align: center;
  color: red;
}

p {
  text-align: center;
  color: red;
}

It will be better to group the selectors, to minimize the code.

Eg.>> https://man575.github.io/CSS-Notes/02-CSS-Selectors/Simple-Selectors/Grouping-Selector/

To group selectors, separate each selector with a comma.
h1, h2, p {
  text-align: center;
  color: red;
}
