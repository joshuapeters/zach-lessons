# Plan For July 24th, 2023

1. Merge my PR and make me a contributor to Todoist :)
2. Lets add some good VSCode extensions
   1. ESLint
   2. indent-rainbow
   3. Material Icon Theme
   4. Prettier - Code Fromatter
   5. Total Typescript
   6. Auto Close Tag
   7. Auto Rename Tag
   8. GitLens
   9. HTML CSS Support
3. Quick Primer On Some Of Our Stack
   1. Typescript (Language)
      1. https://www.typescriptlang.org/
   2. React (Front-End Framework)
      1. https://www.w3schools.com/whatis/whatis_react.asp
      2. https://react.dev/
   3. Radix UI (Component Framework)
      1. https://www.radix-ui.com/docs/primitives/overview/getting-started
   4. Styled Components (CSS-In-JS Framework)
      1. https://styled-components.com/
4. Lets Add Some Dependencies
   1. Install StyledComponents
   2. Install RadixUI
5. Lets Render A List Of Todos
   1. React Components
   2. React Hooks/`useState`
   3. Modeling Data
      1. A todo needs
         1. An ID
         2. Some Text
         3. A Status (Complete/Incomplete)
6. Lets Make A Button That Adds A Todo
   1. We'll use a [Javascript Prompt](https://www.w3schools.com/js/js_popup.asp) for now!

# Homework
1. Wire up deleting a todo
   1. We had to update state when we added a todo, and we'll need to do it again!
   2. Our state is represented as an [array](https://www.w3schools.com/js/js_arrays.asp) of Todos, you'll need to know which todo you're deleting in order to remove it from the array.
   3. Hint: we already have a `TodoItem` component that knows about an individual Todo... maybe we should add a [callback](https://legacy.reactjs.org/docs/faq-functions.html) to it that takes some parameters...

# Stretch Goals
1. Wire up checking off a todo
   1. We should have a list of Todos rendering and the ability to add them. Lets make it so you can check them off.
   2. Checking a Todo should render it's name with it's text struck through ~like this~
   3. Helpful concepts:
      1. [Conditional Rendering](https://react.dev/learn/conditional-rendering)
   4. Hints:
      1. CSS can be used to style (or _decorate_) text. See [W3Schools](https://www.w3schools.com/css/css_text.asp) pages on text and css for more.
      2. We had to update our state when we added a todo. We'll need to update our state again here as well, but what do we actually need to change? Our todo's have a status on them...
