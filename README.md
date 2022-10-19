<div align="center">
  <h1>ReactJs-Interview-Questions</h1>

> Click :star: if you like the project. Pull Request are highly appreciated. Follow me [@iamkoushik1999](https://twitter.com/iamkoushik1999) for technical updates.

</div>

### Table of Contents

| No. | Questions                                                                                                              |
| --- | ---------------------------------------------------------------------------------------------------------------------- |
| 1.  | [Why do we use React?](#why-do-we-use-react)                                                                           |
| 2.  | [What is JSX?](#what-is-jsx)                                                                                           |
| 3.  | [What is a component in react?](#what-is-a-component-in-react)                                                         |
| 4.  | [What is the virtual DOM?](#what-is-the-virtual-dom)                                                                   |
| 5.  | [What is the use of render() in React?](#what-is-the-use-of-render-in-react)                                           |
| 6.  | [How is routing done in react components?](#how-is-routing-done-in-react-components)                                   |
| 7.  | [How do you update the state of a component?](#how-do-you-update-the-state-of-a-component)                             |
| 8.  | [What are Axios? Why is it used?](#what-are-axios-why-is-it-used)                                                      |
| 9.  | [Why are props used?](#why-are-props-used)                                                                             |
| 10. | [What do you understand by refs in React?](#what-do-you-understand-by-refs-in-react)                                   |
| 11. | [How is React Router different from Conventional Routing?](#how-is-react-router-different-from-conventional-routing)   |
| 12. | [Why do we use Hooks?](#why-do-we-use-hooks)                                                                           |
| 13. | [Why do we use useRef?](#why-do-we-use-useref)                                                                         |
| 14. | [Why do we use useEffects?](#why-do-we-use-useeffects)                                                                 |
| 15. | [What is Lifting State Up in React?](#what-is-lifting-state-up-in-react)                                               |
| 16. | [What are the different phases of the component lifecycle?](#what-are-the-different-phases-of-the-component-lifecycle) |
| 17. | [Explain lifecycle methods in react class component.](#explain-lifecycle-methods-in-react-class-component)             |
| 18. | [What are the lifecycle methods of React?](#what-are-the-lifecycle-methods-of-react)                                   |
| 19. | [What are Higher-Order components (HOC)?](#what-are-higher-order-components-hoc)                                       |
| 20. | []()                                                                                                                   |

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
