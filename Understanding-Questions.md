# Understanding Questions:
1. What are the steps of execution from the pressing of the 1 button to the rendering of our updated value? List what part of the code excutes for each step.
* The user presses the 1 button.
* The click handler dispatches an action to the reducer.
* The reducer matches the type with the appropriate case and returns a copy of the original state with the expected action
* The page is re-rendered with the new changes,s
...

* TotalDisplay shows the total plus 1.
