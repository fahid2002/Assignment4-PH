Answers to Questions

1. What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?
ans-1.getElementById()- It selects one element by its ID.
2.getElementsByClassName()- It selects all elements that have the same class name.
3.querySelector()-It selects the first element that matches a CSS selector (like .class, #id, div).
4.querySelectorAll()- It selects all elements that match a CSS selector.

2. How do you create and insert a new element into the DOM?
ans-First, create the element. Then add text. Finally, insert it into the page.

const newElement = document.createElement("p");
newElement.textContent = "Fahid";
document.body.appendChild(newElement);

3. What is Event Bubbling? And how does it work?
ans- Event Bubbling means when you click on an element, the event also goes to its parent elements.

4. What is Event Delegation in JavaScript? Why is it useful?
ans-Event Delegation means adding the event listener to the parent instead of adding it to every child.
Event delegation is useful because we don’t need to add an event to every single child element.
Instead, we just add one event to the parent, and it handles everything.
This makes the code simpler, faster, and easier to manage, especially when new elements are added later.

5. What is the difference between preventDefault() and stopPropagation() methods?
ans-preventDefault() → stops the browser’s default action
stopPropagation() → stops the event from going to parent elements
