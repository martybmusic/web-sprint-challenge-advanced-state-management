# Interview Answers
Be prepared to demonstrate your understanding of this week's concepts by answering questions on the following topics. These will not be counted as a part of your sprint score but will be helpful for preparing you for your endorsement interview, and enhancing overall understanding.

1. What problem does the context API help solve?

Context API allows us to avoid prop drilling and the potential for errors that comes from managing props across multiple components.

2. In your own words, describe `actions`, `reducers` and the `store` and their role in Redux. What does each piece do? Why is the store known as a 'single source of truth' in a redux application?

Action objects specify what to do with our data and are dispatched to our reducers, who then update our state.

Reducers receive our actions and ultimately submit new state objects to our store, while maintaining the immutablity of our state.

Store in redux is a JavaScript object that contains state for entire application.

3. What does `redux-thunk` allow us to do? How does it change our `action-creators`?

Redux-thunk is a piece of middleware that allows inner functions to interact with our code, particularly useful for making asynchronous API calls.

4. What is your favorite state management system you've learned and this sprint? Please explain why!

Although it's the latest system we've learned, I'm excited about context API - it's intuitive to use and also seems to produce much leaner, cleaner code.