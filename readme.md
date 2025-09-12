1. getElementById selects one element by ID, getElementsByClassName returns a live HTMLCollection of elements, querySelector returns the first match, and querySelectorAll returns a static NodeList of all matches.

2. Create with document.createElement("tag"), set attributes or text, then insert using methods like appendChild(), prepend(), or insertBefore().

3. Event Bubbling is when an event starts from the target element and propagates upward through its ancestors until reaching the document.

4. Event Delegation is attaching one event listener to a parent to handle events for its child elements. It’s useful for performance and dynamically added elements.

5. preventDefault() stops the default browser behavior. stopPropagation() stops the event from bubbling up or capturing down the DOM.