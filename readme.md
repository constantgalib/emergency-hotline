Answer to the questions 6:

1. Difference between getElementById, getElementsByClassName and querySelector / querySelectorAll

Answer:

getElementById: returns one element by ID.
getElementsByClassName: returns a live list of elements by class.
querySelector: returns the first element matching a CSS selector.
querySelectorAll: returns all matches as a static list.

2. How to create and insert a new element into the DOM

Answer:

Use document.createElement() to create and appendChild() or prepend() to insert into the DOM.

3. What is Event Bubbling and how does it work?

Answer:

Event bubbling means an event starts at the target element and then moves up through its parent elements.

4. What is Event Delegation in JavaScript? Why is it useful?

Answer:

Event delegation uses one parent listener to manage events on its children. It’s efficient and works for dynamic elements.

5. Difference between preventDefault() and stopPropagation()

Answer:

preventDefault(): stops the browser’s default action.
stopPropagation(): stops the event from bubbling to parents.
