#Answers

###**1. Name 3 JavaScript Array/Object Methods that do not produce side-effects? Which method do we use to create a new object while extending the properties of another object?**

.map(), .filter(), and .reduce() are the 3 array methods that do not produce side-effects. We use Object.create() to create a new object while extending the properties of another.

###**2. Describe `actions`, `reducers` and the `store` and their role in Redux. What does each piece do? Why is the store known as a 'single source of truth' in a redux application?**

An action takes actions and routes it to a reducer which then takes the data and does what it needs to do in order to pass it to the store. The store is the 'single source of truth' because it holds all of the data of our application.

###**3. What is the difference between Application state and Component state? When would be a good time to use one over the other?**

Application state is a global state for the entire application whereas component state is more local and is passed around to different components as props. When an app is extremely large, application state would be the best option because it is more difficult to pass component state to different components since they have to inherit it.

###**4. What is middleware?**

Middleware intercepts data when it leaves the actions and before it reaches the reducers which can allow us to do something to the data if we need to.

###**5. Describe `redux-thunk`, what does it allow us to do? How does it change our `action-creators`?**

Redux thunk is another name for a special function that we use to make the action -> reducer link asynchronous.

###**6. Which `react-redux` method links up our `components` with our `redux store`?**

.connect()
