This app shows how to create a standard error dialog that can be used to display errors from anywhere in a React application. 

We use contexts in this app. A context is basically like a storage space for data and functions. We use them as a way to add to each component's environment. 

The context is available to all the component's children and no passing around is required.

1) Create a special context for the error handler callback function
2) Next, create a provider which will be wrapped in an error container
3) The error container is where the callback function and the UI code is that displays the error dialog
