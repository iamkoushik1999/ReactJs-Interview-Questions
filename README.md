<div align="center">
  <h1>ReactJs-Interview-Questions</h1>

> Click :star: if you like the project. Pull Request are highly appreciated. Follow me [@iamkoushik1999](https://twitter.com/iamkoushik1999) for technical updates.

</div>

### Table of Contents

| No. | Questions                                                                                                                                            |
| --- | ---------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1.  | [Why do we use React?](#why-do-we-use-react)                                                                                                         |
| 2.  | [What is JSX?](#what-is-jsx)                                                                                                                         |
| 3.  | [What is a component in react?](#what-is-a-component-in-react)                                                                                       |
| 4.  | [What is the virtual DOM?](#what-is-the-virtual-dom)                                                                                                 |
| 5.  | [What is the use of render() in React?](#what-is-the-use-of-render-in-react)                                                                         |
| 6.  | [How is routing done in react components?](#how-is-routing-done-in-react-components)                                                                 |
| 7.  | [How do you update the state of a component?](#how-do-you-update-the-state-of-a-component)                                                           |
| 8.  | [What are Axios? Why is it used?](#what-are-axios-why-is-it-used)                                                                                    |
| 9.  | [Why are props used?](#why-are-props-used)                                                                                                           |
| 10. | [What do you understand by refs in React?](#what-do-you-understand-by-refs-in-react)                                                                 |
| 11. | [How is React Router different from Conventional Routing?](#how-is-react-router-different-from-conventional-routing)                                 |
| 12. | [Why do we use Hooks?](#why-do-we-use-hooks)                                                                                                         |
| 13. | [Why do we use useRef?](#why-do-we-use-useref)                                                                                                       |
| 14. | [Why do we use useEffects?](#why-do-we-use-useeffects)                                                                                               |
| 15. | [What is Lifting State Up in React?](#what-is-lifting-state-up-in-react)                                                                             |
| 16. | [What are the different phases of the component lifecycle?](#what-are-the-different-phases-of-the-component-lifecycle)                               |
| 17. | [Explain lifecycle methods in react class component.](#explain-lifecycle-methods-in-react-class-component)                                           |
| 18. | [What are the lifecycle methods of React?](#what-are-the-lifecycle-methods-of-react)                                                                 |
| 19. | [What are Higher-Order components (HOC)?](#what-are-higher-order-components-hoc)                                                                     |
| 20. | [How to create a props proxy for the HOC component?](#how-to-create-a-props-proxy-for-the-hoc-component)                                             |
| 21. | [What is the lifecycle methods order in mounting?](#what-is-the-lifecycle-methods-order-in-mounting)                                                 |
| 22. | [What is Redux?](#what-is-redux)                                                                                                                     |
| 23. | [What are the components of Redux?](#what-are-the-components-of-redux)                                                                               |
| 24. | [What is an action in Redux?](#what-is-an-action-in-redux)                                                                                           |
| 25. | [What is the difference between mapStateToProps() and mapDispatchToProps()?](#what-is-the-difference-between-mapstatetoprops-and-mapdispatchtoprops) |
| 26. | [Difference between state and props.](#difference-between-state-and-props)                                                                           |
| 27. | [Difference between class components and function components?](#difference-between-class-components-and-function-components)                         |
| 28. | [Difference between controlled components and uncontrolled components?](#difference-between-controlled-components-and-uncontrolled-components)       |
| 29. | [What is the difference between createElement and cloneElement?](#what-is-the-difference-between-createelement-and-cloneelement)                     |
| 30. | [What is the difference between Axios and Fetch](#what-is-the-difference-between-axios-and-fetch)                                                    |
| 31. | []()                                                                                                                                                 |

**[⬆ Back to Top](#table-of-contents)**

1. ### Why do we use React?

> React is an excellent tool with which to create interactive applications for mobile, web, and other platforms.

**[⬆ Back to Top](#table-of-contents)**

2. ### What is JSX?

> JSX is a syntax extension of JavaScript. It is used with React to describe what the user interface should look like. By using JSX, we can write HTML structures in the same file that contains JavaScript code.

**[⬆ Back to Top](#table-of-contents)**

3. ### What is a component in react?

> Components are the building blocks of any React application, and a single app usually consists of multiple components. It splits the user interface into independent, reusable parts that can be processed separately.

**[⬆ Back to Top](#table-of-contents)**

4. ### What is the virtual DOM?

> React keeps a lightweight representation of the real DOM in the memory, and that is known as the virtual DOM. When the state of an object changes, the virtual DOM changes only that object in the real DOM, rather than updating all the objects.

**[⬆ Back to Top](#table-of-contents)**

5. ### What is the use of render() in React?

- React renders HTML to the web page by using a function called render().
  The purpose of the function is to display the specified HTML code inside the specified HTML element.
- In the render() method, we can read props and states and return our JSX code to the root component of our app.
- In the render() method, we cannot change the state, and we cannot cause side effects( such as making an HTTP request to the webserver).

**[⬆ Back to Top](#table-of-contents)**

6. ### How is routing done in react components?

> We have to install a react-router-dom package to do routing

**[⬆ Back to Top](#table-of-contents)**

7. ### How do you update the state of a component?

> We have to use the onclick() function

**[⬆ Back to Top](#table-of-contents)**

8. ### What are Axios? Why is it used?

> Axios is a package with which we can get data or insert data into a database with API

**[⬆ Back to Top](#table-of-contents)**

9. ### Why are props used?

> We use props in React to pass data from one component to another (from a parent component to a child component(s)). Props is just a shorter way of saying properties.

**[⬆ Back to Top](#table-of-contents)**

10. ### What do you understand by refs in React?

> Refs are a function provided by React to access the DOM element and the React element that you might have created on your own. They are used in cases where we want to change the value of a child component, without making use of props and all.

**[⬆ Back to Top](#table-of-contents)**

11. ### How is React Router different from Conventional Routing?

> React Router vs Conventional Routing: React Router is a library for React that provides routing functionality. It is different from conventional routing in a few ways.

- **First**, React Router is declarative. This means that you specify what you want your route to look like, rather than specifying how to get there. This makes it more user-friendly and easier to read.

- **Second**, React Router is modular. This means that you can use only the features you need, rather than having to include everything in the library. This makes it more lightweight and efficient.

- **Third**, React Router is asynchronous. This means that routes can be loaded on-demand, rather than all at once. This makes the application more responsive and efficient.

- **Fourth**, React Router is composable. This means that you can create complex routes by combining multiple routes together. This makes the routing process more flexible.

- **Example:** Now we are going to use React router to add routing in our app. For this, we will create a new ‘pages’ directory in our ‘src’ folder. Inside this newly created directory, we will create two JavaScript files ‘Home.js’ and ‘Data.js’ with the below content.

**[⬆ Back to Top](#table-of-contents)**

12. ### Why do we use Hooks?

> Hooks are functions that let you “hook into” React state and lifecycle features from function components. Hooks don't work inside classes — they let you use React without classes.

**[⬆ Back to Top](#table-of-contents)**

13. ### Why do we use useRef?

> The useRef Hook allows you to persist values between renders. It can be used to store a mutable value that does not cause a re-render when updated. It can be used to access a DOM element directly

**[⬆ Back to Top](#table-of-contents)**

14. ### Why do we use useEffects?

> By using this Hook, you tell React that your component needs to do something after rendering. React will remember the function you passed (we'll refer to it as our “effect”), and call it later after performing the DOM updates.

**[⬆ Back to Top](#table-of-contents)**

15. ### What is Lifting State Up in React?

>

**[⬆ Back to Top](#table-of-contents)**

16. ### What are the different phases of the component lifecycle?

>

**[⬆ Back to Top](#table-of-contents)**

17. ### Explain lifecycle methods in react class component.

>

**[⬆ Back to Top](#table-of-contents)**

18. ### What are the lifecycle methods of React?

**Mounting -**
Mounting means putting elements into the DOM.

**Updating -**
A component is updated whenever there is a change in the component's state or props.

**Unmount -**
The Unmount method is called when the component is about to be removed from the DOM.

**[⬆ Back to Top](#table-of-contents)**

19. ### What are Higher-Order components (HOC)?

> A higher-order component (HOC) is an advanced technique in React for reusing component logic.

**[⬆ Back to Top](#table-of-contents)**

20. ### How to create a props proxy for the HOC component?

**[⬆ Back to Top](#table-of-contents)**

21. ### What is the lifecycle methods order in mounting?

**[⬆ Back to Top](#table-of-contents)**

22. ### What is Redux?

**[⬆ Back to Top](#table-of-contents)**

23. ### What are the components of Redux?

**[⬆ Back to Top](#table-of-contents)**

24. ### What is an action in Redux?

**[⬆ Back to Top](#table-of-contents)**

25. ### What is the difference between mapStateToProps() and mapDispatchToProps()?

**[⬆ Back to Top](#table-of-contents)**

26. ### Difference between state and props.

| PROPS                                                   | STATE                                                                           |
| ------------------------------------------------------- | ------------------------------------------------------------------------------- |
| The Data is passed from one component to another.       | The Data is passed within the component only.                                   |
| It is Immutable (cannot be modified).                   | It is Mutable ( can be modified).                                               |
| Props can be used with state and functional components. | State can be used only with the state components/class component (Before 16.0). |
| Props are read-only.                                    | State is both read and write.                                                   |

**[⬆ Back to Top](#table-of-contents)**

27. ### Difference between class components and function components?

| Functional Components                                                                                                                      | Class Components                                                                                                                                       |
| ------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------ |
| A functional component is just a plain JavaScript pure function that accepts props as an argument and returns a React element(JSX).        | A class component requires you to extend from React. Component and create a render function which returns a React element.                             |
| There is no render method used in functional components.                                                                                   | It must have the render() method returning JSX (which is syntactically similar to HTML)                                                                |
| Functional components run from top to bottom and once the function is returned it can't be kept alive.                                     | Class component is instantiated and different life cycle method is kept alive and being run and invoked depending on the phase of the class component. |
| Also known as Stateless components as they simply accept data and display them in some form, they are mainly responsible for rendering UI. | Also known as Stateful components because they implement logic and state.                                                                              |
| React lifecycle methods (for an example, componentDidMount) cannot be used in functional components.                                       | React lifecycle methods can be used inside class components (for example, componentDidMount).                                                          |
| Constructors are not used.                                                                                                                 | Constructors are used as it needs to store state.                                                                                                      |
| Hooks can be easily used in functional components to make them Stateful.                                                                   | It requires different syntax inside a class component to implement hooks.                                                                              |

```javascript
Functional Components ->
example:
const [name,SetName]= React.useState(‘ ‘)
```

```javascript
Class Components ->
example:
constructor(props) {
   super(props);
   this.state = {name: ‘ ‘}
}
```

**[⬆ Back to Top](#table-of-contents)**

28. ### Difference between controlled components and uncontrolled components?

| Controlled Components                                                             | Uncontrolled Components                                                     |
| --------------------------------------------------------------------------------- | --------------------------------------------------------------------------- |
| The component is under control of the component’s state.                          | Components are under the control of DOM.                                    |
| These components are predictable as are controlled by the state of the component. | Are Uncontrolled because during the life cycle methods the data may be lost |
| Internal state is not maintained                                                  | Internal state is maintained                                                |
| It accepts the current value as props                                             | We access the values using refs                                             |
| Does not maintain its internal state.                                             | Maintains its internal state.                                               |
| Controlled by the parent component.                                               | Controlled by the DOM itself.                                               |
| Have better control on the form data and values                                   | Has very limited control over form values and data                          |

**[⬆ Back to Top](#table-of-contents)**

29. ### What is the difference between createElement and cloneElement?

| createElement                                                                                                  | cloneElement                                                                |
| -------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------- |
| createElement is the code that JSX gets compiled or converted into and is used by reacting to create elements. | cloneElement is used for cloning elements and passing them to new props.    |
| This method is used to describe how the User Interface looks.                                                  | This method is used to manipulate the elements.                             |
| createElement requires a type, props, and children as arguments.                                               | cloneElement requires elements, props, and children as arguments.           |
| It creates and returns a new element with the type as given in the arguments.                                  | It clones and returns a new element with the properties of a given element. |

**[⬆ Back to Top](#table-of-contents)**

30. ### What is the difference between Axios and Fetch?

| Axios                                                                  | Fetch                                                                                                                    |
| ---------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------ |
| Axios is astand-alone third party package that can be easily installed | Fetch is built into most modern browsers; no installation is required as such                                            |
| Axios performs automatic transforms of JSON data                       | Fetch is a two-step process when handling Json data-first, to make the actual requst; second, to call the .json() method |
| Asios requst is ok when status is 200 and statusText is 'OK'.          | Fetch requst is ok when response object contains the ok property                                                         |
| Axios allows canceling requst and request timeout.                     | Fetch doesnot allow cancelling requst and requst timeout                                                                 |
| Fetch has built-in support fordownload progress                        | Fetch doesnot support upload progress                                                                                    |
| Axios has a wide browser support                                       | Fetch only supports limited browser                                                                                      |

**[⬆ Back to Top](#table-of-contents)**
