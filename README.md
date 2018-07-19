## 📝 Author
[<img src="https://media.licdn.com/dms/image/C5103AQE3SdZqmIyW0A/profile-displayphoto-shrink_200_200/0?e=1533168000&v=beta&t=reTZbwaCbB9R9V47Q9XiBGgGpY6_dS0KSK_gA8WsVCc" align="right" height="70" width="70">](http://armanbhuiyan.com)

##### Arman Bhuiyan <kbd>[Github](https://github.com/arman37) / [LinkedIn](https://www.linkedin.com/in/arman-bhuiyan) / [Facebook](https://www.facebook.com/arman.it37) / [Site](http://armanbhuiyan.com) /  [E-Mail](mailto:arman.it37@gmail.com)</kbd>

# Learning React

[ <br />
&nbsp; :diamond_shape_with_a_dot_inside: Component Driven Development <br />
&nbsp; :diamond_shape_with_a_dot_inside: Functional Components <br />
&nbsp; :diamond_shape_with_a_dot_inside: Declarative API <br />
&nbsp; :diamond_shape_with_a_dot_inside: Composable <br />
&nbsp; :diamond_shape_with_a_dot_inside: Reactive Updates <br />
&nbsp; :diamond_shape_with_a_dot_inside: Virtual Dom <br />
&nbsp; :diamond_shape_with_a_dot_inside: Simplicity <br />
&nbsp; :diamond_shape_with_a_dot_inside: Modular <br />
&nbsp; :diamond_shape_with_a_dot_inside: Unidirectional/One Directional Data Flow <br />
&nbsp; :diamond_shape_with_a_dot_inside: Explicit App State <br />
&nbsp; :diamond_shape_with_a_dot_inside: Separation Of Concerns <br />
&nbsp; :diamond_shape_with_a_dot_inside: Server-side Rendering(SSR) <br />
&nbsp; :diamond_shape_with_a_dot_inside: Reduce Coupling <br />
&nbsp; :diamond_shape_with_a_dot_inside: Increase Cohesion <br />
]

## :hash: Why React:
* React allows developers to break down the complex UI into **simpler components** and reuse the codes to complete their projects faster. <br />
* React is very a **simple** and **lightweight** library that only deals with the **view layer**. <br />
* React provides such a beautiful **declarative API** which enables developers to declaratively describe their User Interfaces and model the state of those interfaces. <br />
* React is just JavaScript. When writing code in React we don’t have to do that much react-ish things at all. There is a very small API to learn, just a few functions and how to use them. <br />
* It is quite **un-opinionated**, so we are free to choose the tools and technologies we prefer to use with it. <br />
* React has **Unidirectional**/**One directional** data flow, so data changes is more predictable and easy to debug. <br />
* React components can easily be **reused**. <br />
* Components can easily get unit-tested so by definition we can deliver well-structured, more safe and robust code. <br />
* With React we can **reduce coupling** and **increase cohesion**. <br />
* Components are the future of web development. <br />
* React is SEO-friendly. <br />
* React support server side rendering (**SSR**). <br />
* React uses **Virtual DOM** that makes the app really fast. <br />
* React is Fast when it comes to displaying a big amount of components. <br />
* Debugging is getting much easy with specialized Chrome extension. <br />
* React is maintained by Facebook and Instagram but also has a great open-source community. The brains behind Facebook are maintaining this project. <br />

## :hash: Basics:
&nbsp; :arrow_right: React works like a **Javascript engine for UI rendering**(like other Javascript engines used for game development). <br />
&nbsp; :arrow_right: React is used for **composable user interface** using JS & XML. <br />
&nbsp; :arrow_right: In React app everything is made of **components**. Components are **self contained**, **concern-speific** building blocks(easy to reuse, extend & maintain). <br />
&nbsp; :arrow_right: A React component is simply a JavaScript class with a render method that returns a description of the components UI.<br />
&nbsp; :arrow_right: React components lead to a **separation of concerns** not technologies. <br />
&nbsp; :arrow_right: React's components are written in plain JavaScript. <br />
&nbsp; :arrow_right: In React app 'Virtual DOM' is an in-memory, lighweight representation of the real DOM. <br />

## :hash: States:
&nbsp; :arrow_right: State is a plain JavaScript object which is managed within the component (similar to variables declared within a function).<br />
&nbsp; :arrow_right: React's components can have mutable data inside `this.state`. <br />
&nbsp; :arrow_right: `this.state` is private to the component and can be changed by calling `this.setState()` method. <br />
&nbsp; :arrow_right: When the state is updated, the component triggers the reactive rendering, and the component itself and its children will be re-rendered. <br />
&nbsp; :arrow_right: Calls to `this.setState` are asynchronous. This ensures, for example, that if both Parent and Child call `setState` during a click event, Child isn’t  re-rendered twice.<br />
&nbsp; :arrow_right: `setState` calls are batched, Pass an updater function instead of an object if you need to compute values based on the current state.<br />

## :hash: Props:
&nbsp; :arrow_right: Props are plain JavaScript objects which get passed to the component (similar to function parameters). <br />
&nbsp; :arrow_right: Props plays as an key factor in data flow from parent to child components. <br />
&nbsp; :arrow_right: Props are passed and owned by the parent component. <br />
&nbsp; :arrow_right: props can't be changed from inside the child component. <br />
&nbsp; :arrow_right: props are provided as tag attributes much like in HTML. <br />
&nbsp; :arrow_right: props are received by the component and are **immutable**. <br />

## :hash: Container/Smart Component:
&nbsp; :arrow_right: Concerned with how things work. <br />
&nbsp; :arrow_right: Takes care of  data fetching and state changing concerns. <br />
&nbsp; :arrow_right: Renders its corresponding sub-component. <br />
&nbsp; :arrow_right: Fetching data and presenting it in the same container reduces re-usability. <br />
&nbsp; :arrow_right: Usually doesn’t have any DOM markup of its own except for some wrapping divs, and never should have any styles. <br />
&nbsp; :arrow_right: Tends to serve as data sources. <br />

## :hash: Presentational/Dumb Component:
&nbsp; :arrow_right: Concerned with how things look. <br />
&nbsp; :arrow_right: Takes care of only rendering concern. <br />
&nbsp; :arrow_right: Works as a simple JS function. <br />
&nbsp; :arrow_right: Reusable, testable. <br />
&nbsp; :arrow_right: Follows single responsibility principle. <br />
&nbsp; :arrow_right: Has no dependencies on the rest of the app. <br />
&nbsp; :arrow_right: Receive data and callbacks exclusively via props. <br />
&nbsp; :arrow_right: Don’t specify how the data is loaded or mutated. <br />

## :hash: Component Lifecycle:
![lifecycle](/images/component-lifecycle.jpeg)

## :hash: Defining Component Hierarchy:
&nbsp; :arrow_right: Components should be small & have a **single concern**. <br />
&nbsp; :arrow_right: A component should ideally only do one thing well. <br />
&nbsp; :arrow_right: If a component ends up growing, it should be broken into smaller subcomponents. <br />
&nbsp; :arrow_right: Analyse the project's wireframes and layout when designing component hierarchy. <br />

## :hash: References:
&nbsp; :link: [React philosophy](https://reallifeprogramming.com/react-philosophy-e8cdea991599) [read] <br />
&nbsp; :link: [The Minimal React + Webpack 4 + Babel Setup](https://www.robinwieruch.de/minimal-react-webpack-babel-setup) [read] <br />
&nbsp; :link: [componentDidMakeSense — React Component Lifecycle Explanation](https://levelup.gitconnected.com/componentdidmakesense-react-lifecycle-explanation-393dcb19e459) [read] <br />
&nbsp; :link: [Presentational and Container Components - Dan Abramov](https://medium.com/@dan_abramov/smart-and-dumb-components-7ca2f9a7c7d0) [read] <br />
&nbsp; :link: [How to Structure Components in React](https://reallifeprogramming.com/how-to-structure-components-in-react-54fc43e71546) [read] <br />
&nbsp; :link: [The React Philosophy](http://nayaabkhan.me/react/the-react-philosophy) [read] <br />
&nbsp; :link: [Handling State in React: Four Immutable Approaches to Consider](https://medium.freecodecamp.org/handling-state-in-react-four-immutable-approaches-to-consider-d1f5c00249d5)<br/>
&nbsp; :link: [How to Organize a Large React App and Make It Scale](https://react.statuscode.com/link/34475/e61f1ec611) [read] <br />
&nbsp; :link: [React State vs. Redux State: When and Why?](https://react.statuscode.com/link/34483/e61f1ec611) [read] <br />
&nbsp; :link: [Why ReactJS is so popular?](https://www.quora.com/Why-is-ReactJS-is-so-popular) [read] <br />
&nbsp; :link: [Yes, React is taking over the front-end development. The question is why?](https://medium.freecodecamp.org/yes-react-is-taking-over-front-end-development-the-question-is-why-40837af8ab76) <br />
&nbsp; :link: [How to Greatly Improve Your React App's Performance](https://react.statuscode.com/link/34485/e61f1ec611) [read] <br />
&nbsp; :link: [React Bits: A Compilation of React Patterns and Tips](https://react.statuscode.com/link/34486/e61f1ec611) [read] <br />

### Contributing
If you like the project, shoot a :star2: and feel free to fork & send PR.

### License

[MIT licensed](./LICENSE)
