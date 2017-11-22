Take a look at this example from the facebook react docs:

https://codepen.io/alexgriff/pen/VrxaZv?editors=0010

A <Clock /> component is rendered to the DOM every second by calling ReactDOM.render in a callback to setTimeout. This works...

"However, it misses a crucial requirement: the fact that the Clock sets up a timer and updates the UI every second should be an implementation detail of the Clock.

Ideally we want to write this once and have the Clock update itself:
```
ReactDOM.render(
  <Clock />,
  document.getElementById('root')
);
```
"

Use your knowledge of component *state* and with your group research two component *life cycle methods* `componentDidMount` and `componentWillUnmount` to solve this challenge in a more sensible way
