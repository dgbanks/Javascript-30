### CSS Variables

* entities defined by CSS authors which contain specific values to be reused throughout the document

* declaring a variable:
  - ```element {
    --main-bg-color: black;
  } ```

* using the variable:
  - ```element {
    background-color: var(--main-bg-color);
  } ```

* `:root { }` refers to entire document

* querySelector returns a NodeList, not an Array
  - methods include: forEach, keys, values, ...
