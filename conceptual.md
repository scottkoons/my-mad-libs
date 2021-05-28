### Conceptual Exercise

Answer the following questions below:

- **What is React? When and why would you use it?**

	*-React is a popular and powerful front end framework based in JavaScript. React breaks up code into small, individual "components" which allows code to be more easily written, understood, maintained & reusable.*

- **What is Babel?**

	*-Babel is a JavaScript transpiler that converts edge JavaScript into plain old ES5 JavaScript that can run in any browser. It makes available all the syntactical sugar that was added to JavaScript with the new ES6 specification, including classes, fat arrows and multiline strings.*

- **What is JSX?**

	*-JSX is an extension of JavaScript that is used for writing React UI components. The scripts must be transpiled into valid JS before it can be run in the browser.*

- **How is a Component created in React?**

	*-Components are independent and reusable bits of code. They serve the same purpose as JavaScript functions, but work in isolation and return HTML via a render() function.*

- **What are some difference between state and props?**

	*-"props" (short for "properties") is an object of arbitrary inputs a React function component accepts as the first argument. "state" is data that changes over the lifetime of a specific instance of a React component.*

- **What does "downward data flow" refer to in React?**

	*-This refers to the passing down of data from parent components to its children. This includes state and prop variables.*

- **What is a controlled component?**

	*-This is a component that takes its values from props and affects changes through callbacks. The parent component controls is by handling the callback and its own state.*

- **What is an uncontrolled component?**

	*-This a component that stores its own state internally and interacts with the DOM using a ref.*

- **What is the purpose of the `key` prop when rendering a list of components?**

	*-Key props are used in component lists to help React identify when and which component has changed and manage them accordingly .*

- **Why is using an array index a poor choice for a `key` prop when rendering a list of components?**

	*-Using an array index is a poor choice because it can lead to unstable behavior from the component, for instance if the array is altered by reordering it or adding/removing from it, it can impact the desired performance of the component.*

- **Describe useEffect.  What use cases is it used for in React components?**

*-useEffect is a React hook that allows the user to run "side effects" such as calling an API, starting a timer, or manually changing the DOM.*

- **What does useRef do?  Does a change to a ref value cause a rerender of a component?**

*-useRef creates a mutable reference object whose value is set to whatever is passed to it. The object persists throughout the life of the parent component & does not cause a rerender of the component if the ref value is changed.*

- **When would you use a ref? When wouldn't you use one?**

*-A ref is used when making changes directly to a DOM element without causing a rerender, such as managing focus. You would not want to use refs when using class-based components.*

- **What is a custom hook in React? When would you want to write one?**

*-A custom hook is a user-defined hook similar to useState or useEffect that can be used across multiple components. You would write one any time you have shared functionality across components that can be broken out into its own hook and then called later by the various components.*
