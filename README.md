# React Developer Roadmap (2024) (MYSTERY 9807)

A thorough React developer roadmap for 2024 that addresses all aspects of React and beyond.

<details>

<summary>0. Before you start React</summary>

You should know and be comfortable with **all of the following:**

-   **Basic HTML**
    -   HTML Elements, Attributes, Headings, Paragraphs, Colors & Styles
    -   HTML Links, Images, Tables, Lists, Block & Inline, Div, Classes, Id
    -   HTML Forms
    -   HTML Layout, Responsiveness & Semantic

-   **Basic CSS**

    -   CSS Basics - Syntax, Selectors, Colors, Backgrounds, Borders, Margin, Padding, Height/Width, Box Model, Outline, Text, Fonts, Links etc.
    -   CSS More - Lists, Tables, Display, Position, z-index, Overflow, Float, Inline Block, Align, Combinators, Pseudo-classes & elements, Opacity etc.
    -   CSS Forms & Layouts
    -   CSS Flexbox
    -   CSS Grid
    -   Advanced CSS - CSS Units, Shadows, Gradients, Transitions, Animations, Specificity etc.

-   **Basic Tailwind CSS**

    -   Tailwind Utilities
    -   Responsive Variants
    -   Hover, focus and other states
    -   Dark Mode variant
    -   Tailwind Directives
    -   Tailwind Configurations
    -   Theme Configurations
    -   Tailwind cn() utility

-   **Document Object Model (DOM)**

    -   DOM Basics - Basics, Method, Document, Elements, Forms, CSS, Events, Navigation, Nodes and Collections
    -   DOM Advanced

-   **Basic JavaScript**

    -   JS Basics - Statements, Expressions, Syntax, Variables, Operators, Data Types, Functions, Objects, Arrays, Events, Array and String Methods, Object Methods, Date, Conditionals, Error Handling, JavaScript OOP - classes and inheritance and Debugging
    -   JS Web APIs - Forms, History, Geolocation, Storage, Worker and Fetch API
    -   JS JSON

-   **JavaScript Advanced**

    -   Solid JS Concepts - Scope, Hosting, Execution Context, Closures, Prototype, Recursion, Primitive vs Reference Data Types, Currying, Intersection Observer, Memoization, Event Propagation, Debounce etc.
    -   Asynchronous JavaScript - Callbacks, Promises and async-await

-   **Modern JavaScript**

    -   Different ES6+ JS Syntaxes and concepts eg. Arrow function, Truthy/Falsy values, Ternary Operator, Different Array methods like find, filter, map, reduce, slice, splice, push, pop, concat, different looping strategies, Spread & Rest Operator, Array and Object Destructuring, Imports/Exports syntax, Template Literals, Sorting etc.

-   **Git/GitHub**

    -   Basics of Git
    -   Important Git Commands

</details>

<details>
<summary>1. React Fundamentals</summary>

You should know and be comfortable with **all of the following:**

-   **Getting Started with React**
    -   Introduction to React - Why React - Comparison with Vanilla JS
    -   React Installation & Editor Setup with Vite
    -   How React works - Virtual DOM
    -   Basics of React Components
    -   Basics of JSX: React's Markup
    -   JavaScript in JSX
    -   Passing Props to Components
    -   Conditional Rendering
    -   Rendering Lists
    -   Pure Components
    -   How to split larger components into smaller ones
-   **Adding Interactivity**

    -   Responding to Events - Event Handlers
    -   Understanding States - React Component's Memory - useState
    -   How State works in React
    -   How Rendering works in React
    -   Updating complex states immutably in React

-   **React State Management Deep Dive**

    -   Declarative vs Imperative UI
    -   Thinking UI Declaratively
    -   Finding & Structuring React States
    -   Connecting Event Handlers to React
    -   Sharing State between components
    -   Lifting State up
    -   Extracting State Logic into Reducers
    -   useReducer Hook
    -   How to use Immer with React for concised immutable State Update
    -   Passing Data Deeply inside React Components
    -   Avoiding Prop Drilling - Context API & useContext Hook
    -   Combine context and reducer to write scalable code

</details>

<details>
<summary>2. Advanced React</summary>

-   Referencing values with Refs - useRef hook
-   Manipulating the DOM with Refs
-   Synchronizing with Effects - useEffect hook
-   Separating events from Effects
-   Removing Effect Dependencies
-   Performance optimization with useCallback and useMemo hook
-   Reusing logic with Custom Hooks
-   Calling APIs from Back-end with React

</details>

<details>
<summary>3. Advanced State Management</summary>

-   Using Redux / Toolkit
-   Using Zustand
-   Using Jotai
-   Using Recoil
-   ‹Using MobX

</details>

<details>
<summary>4. Styling Solutions</summary>

-   **Tailwind**
-   **CSS Modules**
-   [**Styled Components**](https://styled-components.com/)
-   React UI Component Library - [Shadcn](https://ui.shadcn.com/)
-   [React UI Component Library - Keep React](https://youtu.be/mVXNUMBtGEA)
-   [**Material UI**](https://mui.com/)
-   [**Chakra UI**](https://chakra-ui.com/)
-   [**Ant Design**](https://ant.design/docs/react/introduce)

</details>

<details>
<summary>5. React Ecosystem & Use Cases</summary>

-   React Router DOM
-   API Request with Axios in React
-   React Suspense & Error Boundaries
-   React Lazy Load
-   React Infinite Scroll
-   Uncommon React Hooks - useDebugValue, useDeferredValue, useId, useImperativeHandle, useInsertionEffect, useLayoutEffect and useTransition
-   **React Authentication**

    -   How to handle user sign in (email, password, JWT)
    -   How to handle access tokens and token refreshes
    -   Social sign in (Google, Facebook, GitHub, etc.)
    -   [Using Supabase](https://supabase.com/)
    -   [Using Firebase](https://firebase.google.com/docs/auth)
    -   [Using Clerk](https://clerk.com/)

-   **Form Handling in React**

    -   How to validate user input in forms (emails, passwords, etc.)
    -   How to send form data to server
    -   How to handle file uploads
    -   [Using React Hook Form](https://react-hook-form.com/)
    -   [Using Formik](https://formik.org/docs/overview)

-   [**Accessibility**](https://developer.mozilla.org/en-US/docs/Learn/Tools_and_testing/Client-side_JavaScript_frameworks/React_accessibility)
    -   Understanding why accessibility is important
    -   Using semantic HTML
    -   How to implement keyboard navigation
    -   How to add aria labels
    -   [Using React Aria](https://react-spectrum.adobe.com/react-aria/)
-   **Testing**
    -   [How to implement unit tests](https://www.freecodecamp.org/news/how-to-write-unit-tests-in-react/)
        -   [Using React Testing Library](https://testing-library.com/docs/react-testing-library/intro/)
        -   [Using Jest](https://jestjs.io/)
    -   [How to implement e2e integration tests](https://youtu.be/6BkcHAEWeTU)
        -   [Using Cypress](https://www.cypress.io/)
        -   [Using Playwright](https://playwright.dev/)

</details>

<details>
<summary>6. React Frameworks</summary>

You should have worked with **one of the following:**

-   [**Vite**](https://vitejs.dev/)
    -   How to run a simple React application
-   [**Next.js**](https://nextjs.org/)
    -   [Understanding file-based routing](https://nextjs.org/docs/app/building-your-application/routing)
    -   [Understanding Next Auth](https://next-auth.js.org/)
    -   [Understanding server components](https://nextjs.org/docs/app/building-your-application/rendering/server-components)
    -   [Understanding server actions](https://nextjs.org/docs/app/building-your-application/data-fetching/server-actions-and-mutations)
-   [**Remix**](https://remix.run/)

</details>

<details>
<summary>7. Beyond React</summary>

-   **Team player**
    -   How to work within a team
    -   How to perform code reviews
    -   How to give and receive feedback
-   **Efficiency**
    -   How to prioritise tasks
    -   How to handle tech debt
    -   How to meet deadlines and goals
-   **Continuous Learning**
    -   How to continuously learn and grow
    -   How to stay up to date with your skills
-   **Networking & Communication** - Going to meetups or events - Contributing to open source projects - Networking within the company you work in
</details>


