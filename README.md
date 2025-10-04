# Vue Lesson 04 - Events

## What I Learned

- **Event Handling with `v-on`**: Binding click, input, and submit events to methods
- **Event Modifiers**: Using `.prevent` to prevent default form submission and `.right` for right-click events
- **Key Modifiers**: Using `.enter` to trigger actions on Enter key press
- **`$event` Object**: Passing the event object to methods with `$event`
- **`v-once`**: Rendering content only once, without reactivity updates
- **Two-way Data Binding**: Using `v-on:input` to update data from user input
- **Methods**: Defining and calling methods to handle events and update state

## Challenges

- **Understanding event modifiers**: It was tricky to understand when and how to use `.prevent` and other modifiers instead of manually calling `event.preventDefault()`.
- **Passing event objects with parameters**: Learning how to use `$event` when I needed to pass both the event object and custom parameters to methods was confusing at first.
- **Key event modifiers**: Figuring out which key modifiers are available and how to chain them with other event handlers took some practice.
