1. What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?

Ans: getElementById is used to select a single element by its unique ID and returns that element directly. getElementsByClassName returns a live HTMLCollection of all elements that have a specific class name, which automatically updates if the DOM changes. querySelector allows selecting the first element that matches any CSS selector, while querySelectorAll returns a static NodeList of all matching elements, supporting IDs, classes, tags, and even complex selectors.

2. How do you create and insert a new element into the DOM?

Ans: To create a new element in the DOM, you first use document.createElement to create the element, then set its content, classes, or attributes as needed. After that, you insert it into the document using methods like appendChild to add it at the end, prepend to add it at the beginning, or insertBefore to place it before a specific existing element.

3. What is Event Bubbling? And how does it work?

Ans: Event Bubbling is the process where an event triggered on a child element propagates upward through its parent elements in the DOM. For example, clicking a button inside a div will first trigger the button’s click event and then bubble up to trigger the div’s click event, allowing multiple elements to respond to the same event.

4. What is Event Delegation in JavaScript? Why is it useful?

Ans: Event Delegation is a technique where you attach a single event listener to a parent element to handle events on its child elements, even if they are added later dynamically. This approach reduces the number of event listeners needed, saves memory, and ensures that all current and future child elements can respond to the event.

5. What is the difference between preventDefault() and stopPropagation() methods?

Ans: preventDefault() is used to stop the browser’s default behavior for an event, such as preventing a link from navigating or a form from submitting. stopPropagation() stops the event from bubbling up the DOM, preventing parent elements from receiving or responding to the same event, which is useful for controlling event flow.
