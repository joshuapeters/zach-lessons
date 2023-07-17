# Plan For July 17th, 2023

1. Fork And Clone This Repo!
2. Make Repo For Our App "Todoist"
3. Init NextJS Project W/ Typescript And React And Push To Github
4. Quick Primer On Our Stack (For Now)
   1. Typescript (Language)
      1. https://www.typescriptlang.org/
   2. React (Front-End Framework)
      1. https://www.w3schools.com/whatis/whatis_react.asp
      2. https://react.dev/
   3. Radix UI (Component Framework)
      1. https://www.radix-ui.com/docs/primitives/overview/getting-started
   4. Styled Components (CSS-In-JS Framework)
      1. https://styled-components.com/
   5. NextJS (Back-End Framework)
      1. https://nextjs.org/learn/foundations/about-nextjs/what-is-nextjs
   6. Vercel (CI/CD)
      1. https://vercel.com/blog/what-is-vercel
5. What Are We Building?
   1. A Todo app!
   2. More specifically: we're building a client-side only todo app.
   3. This app will have one screen
      1. You can have a list of todos.
      2. You can click a + button to add a new one, and type in it's title.
      3. Each todo can have a checkbox that marks that todo as done
      4. Each todo has a trashcan icon that lets you delete that todo
   4. We won't be saving this to a database yet, this will only live client-side
6. Lets Add Some Dependencies
   1. Install StyledComponents
   2. Install RadixUI
7. Lets Render A List Of Todos
   1. React Hooks/`useState`
   2. React Components
   3. Modeling Data
      1. A todo needs
         1. An ID
         2. Some Text
         3. A Status (Complete/Incomplete)
8. Lets Make A Button That Adds A Todo
   1. We'll use a [Javascript Prompt](https://www.w3schools.com/js/js_popup.asp) for now!

# Homework
1. Read [Thinking In React](https://react.dev/learn/thinking-in-react)
   1. Some of this might go over your head a little bit, that's okay! The important bit is that you understand how to break down a design into a set of components well. It takes time to do so, and you can under or over index on how to best break things down. (You don't need a component per word, but the whole thing shouldn't be in one component either.)

# Stretch Goals
1. Wire up checking off a todo
   1. We should have a list of Todos rendering and the ability to add them. Lets make it so you can check them off.
   2. Checking a Todo should render it's name with it's text struck through ~like this~
   3. Helpful concepts:
      1. [Conditional Rendering](https://react.dev/learn/conditional-rendering)
   4. Hints:
      1. CSS can be used to style (or _decorate_) text. See [W3Schools](https://www.w3schools.com/css/css_text.asp) pages on text and css for more.
      2. We had to update our state when we added a todo. We'll need to update our state again here as well, but what do we actually need to change? Our todo's have a status on them...
