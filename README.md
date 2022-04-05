# Redux Quiz

<img src="https://chriscourses.com/img/blog/redux/redux.jpg" height="400px"/>

## Getting Started

- Fork and Clone

## Questions

1. What is Redux?

```
Redux is a state management tool.
```

2. What packages do we install to use Redux?

```
npm install redux react-redux
```

3. In your own words, describe the flow of how Redux is used to manage state.

```
The flow of redux managing state is uni-directional, only one way. When an action is done, it is dispatched into the store, then to the reducer, then the provider updates the states and its components and sends it to the Users Interface.
```

4. What do we use in order to manage different pieces of state?

```
The first step is to setup a store component. Then you have to setup the actions and reducers component. Then you dispatch the changes in the component.
```

5. What do we use to perform an update to state?

```
To update state, we must dispatch an action and define the reducers function to do something when the action is performed. Like  a setState()
```

6. How do we access state from Redux?

```
I believe to access the state from Redux is to use the connect() function.
```

7. In your own words, describe how to set up Redux for a React App.

```
You have to cd into directory, and do npm i redux react-redux. Navigate to the index.js and import { create store } from 'redux'. Then make a const store and set it equal to createStore(). Now we import the { Provider } from 'react-redux'. Now in the index.js we  call the Provider and have store={store} and have the App in between the Provider. Like so, <Provider store={store}><App></Provider>. Now we make a reducers component. Then make a function that takes in the state and action ( You put this in the parenthesis). Then you return the state, and have another function that is giving it a default value, like an empty array or an empty string. Then export the first function we made , and navigate back to the index.js and import that function. Now we import that function and put it into the createStore() parenthesis to tell the computer how we're interacting with the store. This will be passing the function to the Provider which will be passed into oru App.js because App is in between our Provider from when we first called it.
```

## Submission

Pull Request due by **9AM EST** following the [PR Submission Guidelines](https://github.com/SEI-R-2-22/template_pull_request).
