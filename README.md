# React
Created with CodeSandbox
Babel : Babel is a JavaScript compiler that transform the latest JavaScript features, which are not understandable to every browser, into a backward compatible version of JavaScript in current and older browsers or environments.

JSX : JSX is a syntactical extension to JavaScript.

https://reactjs.org/docs/introducing-jsx.html

Introducing JSX Consider this variable declaration:

const element =

Hello, world!
; This funny tag syntax is neither a string nor HTML.
It is called JSX, and it is a syntax extension to JavaScript. We recommend using it with React to describe what the UI should look like. JSX may remind you of a template language, but it comes with the full power of JavaScript.

JSX produces React “elements”. We will explore rendering them to the DOM in the next section. Below, you can find the basics of JSX necessary to get you started.

JSX vs ES6

Utilizing JSX allows us to write HTML elements in JavaScript, which is then rendered to the DOM. ES6 (aka: ECMAScript 6, JavaScript 6, or ECMAScript 2015) is the “6th version” of JavaScript, released in 2015.

Why JSX? React embraces the fact that rendering logic is inherently coupled with other UI logic: how events are handled, how the state changes over time, and how the data is prepared for display.

Instead of artificially separating technologies by putting markup and logic in separate files, React separates concerns with loosely coupled units called “components” that contain both. We will come back to components in a further section, but if you’re not yet comfortable putting markup in JS, this talk might convince you otherwise.

Warning:

Since JSX is closer to JavaScript than to HTML, React DOM uses camelCase property naming convention instead of HTML attribute names.

For example, class becomes className in JSX, and tabindex becomes tabIndex.
