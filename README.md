# react-patterns

1. State hoisting - function-component don't hold state (as the name implies).Events are changes in state. Their data needs to be passed to stateful container components parents. This is called "state hoisting". It's accomplished by passing a callback from a container component to a child component.
