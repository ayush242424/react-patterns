# react-patterns

1. State hoisting - function-component don't hold state (as the name implies).Events are changes in state. Their data needs to be passed to stateful container components parents. This is called "state hoisting". It's accomplished by passing a callback from a container component to a child component.

2. Controlled input - It's hard to talk about controlled inputs in the abstract. Let's start with an uncontrolled (normal) input and go from there.

3. Higher-order component - A higher-order function is a function that takes and/or returns a function. It's not more complicated than that. So, what's a higher-order component?
