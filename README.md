Step 1: Styling the Navigation Menu

- Open your CSS file (e.g., App.css) where you're adding your styles.
- Create a style for the .nav-menu class. Set its properties to make
it sticky, position it at the top of the screen, and give it
a background color, padding, and a shadow.
- Inside the .nav-menu style, create a style for the button (button tag).
- Adjust properties like background color, text color, border,
border radius, and cursor to style the button.

Step 2: Update the App Component

- Open your main component file (App.js).
- At the top of the file, import the necessary components and 
styles using import statements.
- Inside the App component, declare the state variables
(deletedHabits, showDeletedHabits) using the useState hook.
- Define the toggleDeletedHabits function using the
setShowDeletedHabits function and the showDeletedHabits
state variable.
- In the returned JSX, add a div element with a class name
of nav-menu. Inside this div, place a button element for
"Deleted Habits". Use the onClick attribute to call the
toggleDeletedHabits function.
- Below the navigation menu, you can render the other components
and pass any necessary props.

Step 3: Create the Deleted Habits Component 

- Create a new JavaScript file in the same directory as your
main App.js file. You can name it something like DeletedHabits.js.
- In DeletedHabits.js, define the DeletedHabits component using
the function component syntax.
- Inside the component, you'll receive props like deletedHabits
and onClose. Use these props to display the deleted habits
and handle the closing of the modal.
- Inside the component's JSX, you can use the deletedHabits array
to map through the deleted habits and display them as desired. 
- Apply CSS classes or styles to the different elements within 
the DeletedHabits component to control its appearance.
Export the DeletedHabits component at the end of the file.


