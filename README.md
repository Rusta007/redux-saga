# redux-saga

- Redux Saga is a `middleware library` for Redux, A popoular state management library for JS applications.
- It is not a part of redux, but rather then `external library` that can be used in Redux to `manage side effects in your application`.

- `Side Effects typically refer to asynchronous actions.`
 #### Side Effects:
1. Making network requests
2. Interacting with database
3. Handling complex asynchronous operations.

- These asynchronous operations are separate from the typical synchronous `Redux Actions` that update the `Redux Store`.
- Redux itself is primarily designed to handle synchronous state changes, and it can become complex when dealing with asynchronous operations.

## Saga
- Redux saga provides a way to manage these side effects in a more structured and tested manner.
- It uses a concepts called 'saga' to encapsulate and manage the asynchronous behavior of your applications.
- A saga is `Generator Function` that listens for specific actions dispatched in your Redux Store and then performs asynchronous operations in response to those actions.
- It allows you to write asynchronous logic in a more declarative and easy-to-understand way.
- Redux Saga provides a way to handle complex asynchronous flows in your applications while keeping your Redux Store and reducers focoused on handling state changes.
- It's a powerful tool for managing side effects, making your code more maintainable and testable.

`To use Redux Saga in Redux-based application, need to install it separately and configure it as middleware for your Redux Store. it's a separate library that works Redux to enhance it's capabilities.`

























 
