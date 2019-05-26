MyComponent contains a boolean in its state which tracks whether you want to display some element in the UI or not. The button toggles the state of this value. Currently, it renders the same UI every time. Rewrite the render() method with an if/else statement so that if display is true, you return the current markup. Otherwise, return the markup without the h1 element.

Note: You must write an if/else to pass the tests. Use of the ternary operator will not pass here.

Passed
MyComponent should exist and render.
Passed
The render method should use an if/else statement to check the condition of this.state.display.
Passed
When display is set to true, a div, button, and h1 should render.
Passed
When display is set to false, only a div and button should render.