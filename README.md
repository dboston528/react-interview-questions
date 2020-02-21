# 1. What's the difference between Real DOM & Virtual DOM?
 • Real DOM
 Updates slow
 can directly update HTML
 creates a new DOM if elements update
 DOM manipulation is very expensive
 Too much of memory wastage
 ## Virtual DOM
 Updates faster 
 Can't directly update HTML
 Update the JSX if element upadtes
 DOM manipulation is very easy
 No memory wastage
 
 # What is react?
 Frontend Javascript library developed by Facebook in 2011
 It follows the component based approcah which help ehen building reusable UI components
 It is used got developing complex and interactiv web and moile UI
 Even though it was open-sourced only in 2015, it has one the largest communities supporting it. 
 
 # 3. What are the features of React?
 It uses the virtual Dom instead of the real DOM
 It used server side rendering
 It follows uni-directional data flow or data binding.
 
 # 4 List some major advantages of React
 Increases applications preformance
 It can be conveniently used on the client as well as serv er side
 JSX makes code more readable
 Easy to integrate with other frameworks like Mateor and Angular
 Writing UI test cases is easy
 
 # 5 What are react limitations?
 It's just a library, not a framework
 The libray is very large and takes time to understand
 It can be a little difficult for a novice to pick up.
 Inline templating and JSX could get confusing
 
 #  6 What the heck is JSX
 JSX is shorthand for JavaScxript  XML. This is a type of file used by React which utilizes the epressiveness of JavaScript  alonf with HTML like syntax. T
 
 # 7 What do you understand about the Vurtual DOM? Explain its working. 
 A virtual DOM is a lightweight JavaScript object which originally is just a copt of the real DOM. 
 
 # 8 Why can't browsers read JSX?
 Browsers can only read JavaScript objects but JSX in not regular JavaScript object. Thus to enable a browser to read JSX, first , we need to transform JSX file into a jjavascript object using JSX transformers like Bable and then pass it to the browser.
 
 # 9 How different is React's ES6 syntx when compared to ES6?
 Require vs import
 ```
 //ES5
 var React  = require('react');
 
 //ES6 
 import React from 'react';
```
exporting
```
//es5
module.exports = Component;

//ES6 
export default Component;
```
Component and Function
```
//ES5 
var MyComponent = React.createClass({
    render: function() {
        return
        <h1>Hello World</h1?
    }
});

//ES6
class MyComponent extends React.Component {
      render(){
      return <h1>Hello World!</h1> 
      }
}
```
# 10. How is React different from Angular
React is like the view of a model view controller architecture
React is performs server-sie rendering.
React used the virtual DOM
React uses one-way data binding.
React uses compile time debugging.
Facebook created React
Anglar is a complete MVC
... client side rendering
... uses real DOM
... Two-way data binding
... runttime debugging
.... google
# 11. What is a component?
Components are the building blocks of a React application ui. Components are meant to be small and reusable.
# 12. What is the purpose of render() in React?
The render() method is the only required method in a class component. 
# 13. How can you embed  two or more components into one?
# 14. What are Props?
Props are short for properties.
# 15. What is State in React and how is it used?
# 16. What is th  difference betweem state an props?
# 17. How can you update the state of a component?
# 18. What is an arrow function in React? How is it used?
# 19. What's th difference between stateful and stateless compinents?
# 20. What are differnt phases of React components lifecycle?
# 21. Explain the lifecycle methods of React components in detail.
# 22. What is an even in React? 
# 23. How do you create an event in React?
# 24. What are the synthetic events in React?
# 25. What d you understand by refs in React
# 26. When should you use Refs?
# 27. How do you modularize code in React?
# 28. How are forms create in react?
# 29. What do you know about controlled and uncontrolled comonents?
# 30. What are higher order components?
# 31. What can you do with an HOC(Higher Order Component)?
# 32. What are pure components?
# 33. What's the signifigance of keys in React?
# 34. What are the major problemd with MVC frameworks ?
# 35. Explain Flux
# 36. What's Redux
State manangement
# 37. What are the three principles that Redux follows?
# 38. What do you understand about "Single source of truth"
# 39. List down the components of Redux
# 40. Show how the data flows through Redux?
# 41. How are actions defined in redux?
# 42. What is the role a reducer?
# 43. What's the significance of Store in Redux
# 44. How is redux different from flux?
# 45. What are some of the advanbtages of Redux
# 46. What is react Router?
# 47. Why is the switch keyword used in React Router v4?
# 48. Why do we need a router in React
# 49. Advatages of React Router.
# 50. How is React Router different from conventional routing?
 
