# coursera-react-basics-toggle-app
This app will demo reusable React components, arrow functions with implicit returns, pass data between components using props, using ternary operator, and style components with CSS.
## Goal
The goal of this lab is to build a React application that dynamically generates random numbers, passes them to child components using props, and displays different messages based on the generated number using conditional rendering.
# Lab Notes
Command to create a _(this)_ React app, `npx create-react-app toggle_app` and start the browser preview of the app, `npm start`.
    **Note:** The `create-react-app` command is deprecated.
## Card Component Explanation
1. **Function Definition:** The Card component is a functional React component that takes props as its argument to receive data.
2. **Container Element:** It returns a `<div>` element with the class card, serving as the main container for the component.
3. **Dynamic Heading:** Inside the `<h1>` tag, it dynamically displays the num value passed through props.
4. **Conditional Rendering:** The `<p>` tag uses a conditional expression to display "High" if props.num is greater than 50, or "Low" otherwise.
5. **Exporting Component:** The Card component is exported as the default export, allowing it to be imported and used in other parts of the application.