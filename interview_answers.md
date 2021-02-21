# Interview Answers
Be prepared to demonstrate your understanding of this week's concepts by answering questions on the following topics. These will not be counted as a part of your sprint score but will be helpful for preparing you for your endorsement interview, and enhancing overall understanding.

1. What are the main differences between a stateful and a functional component?

A functional component is just a plain JavaScript function that accepts props as an argument and returns a React element. A class component requires you to extend from React.

2. When does a componentWillMount function be called? What about a componentWillUpdate?

The lifecycle of a component consists of three stages. ComponentWillMount is called in the first state after all the components have rendered. It gets called from the child component upward to the parent in a bubbling fashion.

3. Define stateful logic.

Stateful logic is any logic that depends directly on state, uses state directly, or is affected by state. An example would be storing data into a state variable.

4. What are the three step of creating a successful test? What is done in each phase?

The three steps are Arrange, Act, and Assert. Arrange prepares the testing environmoent, renders the component or App and calls the elements to be tested. Act simulates a user action. And Assert makes statements about what behavior we expect to happen or what we as the user expect to see.