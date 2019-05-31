1.  Name 3 JavaScript Array/Object Methods that do not produce side-effects? Which method do we use to create a new object while extending the properties of another object? 

map, reduce, filter


1.  Describe `actions`, `reducers` and the `store` and their role in Redux. What does each piece do? Why is the store known as a 'single source of truth' in a redux application? 
the State of the whole app is stored within a single 'store'
the only way to change aforementioned state is to emit an object describing what happened or, 'action'
To specify the ways in which the state tree is transformed by aforementioned actions, you write 'reducers'
the store is known as the single source of truth as it holds the entirety of the app tree

1.  What is the difference between Application state and Component state? When would be a good time to use one over the other?
App state is store globally while component state is stored locally. for data that will change rapidly, component would be best suited, while for data that persists the entire time the user is on the page, app state would be best suited
1.  What is middleware?
software that acts as a connection between an os or database and apps, especially on a network
1.  Describe `redux-thunk`, what does it allow us to do? How does it change our `action-creators`? it is a middleware that lets one call action creators that return a function instead of an action object, it is used to dispatch regular synchronous actions insidr the body of a function once the asynchronous operations are complete
1.  Which `react-redux` method links up our `components` with our `redux store`
provider