# 🧠 CSS Selectors Quick README

## 🔗 Selectors Simplified

| Selector Type        | Trick to Remember                      | Snippet Example          |
|----------------------|----------------------------------------|--------------------------|
| **Universal (`*`)**  | “Catch-All Star” ⭐                     | `* { margin: 0; }`       |
| **Element**          | “Tag Target” 📛                        | `p { color: blue; }`     |
| **ID (`#id`)**       | “One and Only” 🆔                      | `#main { font-size: 18px; }` |
| **Class (`.class`)** | “Reusable Styles” 🎨                  | `.card { border: 1px solid; }` |
| **Descendant**       | “Nested Target” 🪆                    | `div p { ... }`          |
| **Child (`>`)**      | “Direct Kid” 👶                       | `ul > li { ... }`        |
| **Sibling (`~`)**    | “Neighbor All” 🏠                     | `h2 ~ p { ... }`         |
| **Adjacent (`+`)**   | “Next-Door One” 🧍→🧍                | `h2 + p { ... }`         |
| **Attribute**        | “Has This?” 🔖                        | `input[type="text"]`     |
| **Pseudo-class**     | “State Styler” 🎭                     | `a:hover { color: red; }` |
| **Pseudo-element**   | “Part Styler” 🧩                      | `p::first-line { ... }`  |
| **Cascading/Specificity** | “Who Wins?” 🥇                 | IDs > Classes > Elements |
| **!important**       | “Override Button” 🚨                 | `color: red !important;` |
| **Inheritance**      | “Pass It Down” 📥                    | Some properties pass from parent to child |

