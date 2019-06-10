1. What are PropTypes used for? Please describe why it's important to type check our data in JavaScript.

1a) PropTypes are used for data validation. Its important to use prototypes because without some form of type checking , we run into the risk of passing in a wrong data type to a component. I could cause a crash or some unexpected behavior in your application.

2. Describe a life-cycle event in React?

2a) Every React Component has a lifecycle of its own, lifecycle of a component can be defined as the series of methods that are invoked in different stages of the component. A React Component can go through four stages. Initialization,Mounting,Updating, and Unmouting

3. Explain the details of a Higher Order Component?

3a) A higher-order component is an advanced technique in React for reusing component logic. HOCs are not part of the React API, per se. They are a pattern that emerges from React’s compositional nature. a higher-order component is a function that takes a component and returns a new component.Whereas a component transforms props into UI, a higher-order component transforms a component into another component.

4. What are three different ways to style components in React? Explain some of the benefits of each.

4a)

CSS StyleSheet
Simply import css file import so you can have a separate css file for each component.

Inline styling
We can create a variable that stores style properties and then pass it to the element.

styled Components
a library for react that allows you to use component-level styles in your application that are written with a mixture of JS and CSS
