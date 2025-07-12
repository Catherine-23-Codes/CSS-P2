# 🧠 CSS Selectors Quick README


| Selector Type        | Description                                      | Syntax Example                     |
|----------------------|--------------------------------------------------|------------------------------------|
| **Universal (`*`)**  | Selects all elements on the page.                | `* { margin: 0; }`                 |
| **Element**          | Targets all instances of a specific HTML tag.    | `p { color: blue; }`               |
| **ID (`#id`)**       | Targets a unique element by its ID attribute.    | `#main { font-size: 18px; }`       |
| **Class (`.class`)** | Selects elements sharing a common class.         | `.card { border: 1px solid; }`     |
| **Descendant**       | Selects all elements nested within a parent.     | `div p { ... }`                    |
| **Child (`>`)**      | Selects direct child elements only.              | `ul > li { ... }`                  |
| **Sibling (`~`)**    | Selects all siblings following the element.      | `h2 ~ p { ... }`                   |
| **Adjacent (`+`)**   | Selects the immediate next sibling element.      | `h2 + p { ... }`                   |
| **Attribute**        | Targets elements with specific attributes.       | `input[type="text"]`              |
| **Pseudo-class**     | Applies styles based on the element's state.     | `a:hover { color: red; }`          |
| **Pseudo-element**   | Styles specific parts of an element.             | `p::first-line { ... }`            |
| **Specificity**      | Determines which rule takes precedence.          | `ID > Class > Element`             |
| **`!important`**     | Forces a rule to override others.                | `color: red !important;`           |
| **Inheritance**      | Certain properties are inherited by child elements. | Example: `font-family` from `<body>` |


