- [ ] Why would you use class component over function components (removing hooks from the question)?

You would choose class components over function components if you needed to refactor legacy code and to have more control over state and what happens in the app's lifecycle.

- [ ] Name three lifecycle methods and their purposes.

componentDidMount(): is invoked immediately after a component is mounted (inserted into the tree). Creates the app and loads components.
componentDidUpdate(): is invoked immediately after updating occurs. This method is not called for the initial render.
componentWillUnmount(): is invoked immediately before a component is unmounted and destroyed. This will cleanup any ongoing tasks.

- [ ] What is the purpose of a custom hook?

Custom hooks are reusable, keeps our code dry, and clean.

- [ ] Why is it important to test our apps?

Testing is a good way to find errors before you get too deep in a project and helps you find issues faster.
