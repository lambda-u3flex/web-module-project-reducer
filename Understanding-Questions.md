# Understanding Questions:

1. What are the steps of execution from the pressing of the 1 button to the rendering of our updated value? List what part of the code excutes for each step.

- The user presses the 1 button.
- User triggers a change to state (handleAddOne dispatches addOne() onClick)
- An action object is created.
- Current state & Object are passed into reducer.
- Action is processed and a new state is created.
- TotalDisplay shows the total plus 1.
