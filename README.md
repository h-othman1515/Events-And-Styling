# JS Task Dashboard — DOM, Events & Styling

This project is a comprehensive practice suite for **JavaScript DOM manipulation**, **Event Handling**, and **Dynamic CSS styling**. It demonstrates how to build interactive UI components using vanilla JavaScript without relying on external libraries or inline event handlers.

---

## 🚀 Features

The dashboard is divided into six core interactive tasks, each focusing on a specific JavaScript concept:

### 🟢 Task 1 — Smart Button
A toggle-state button that tracks clicks.
* **Behavior:** On the first click, the text changes from "Unclicked" to "Clicked!".
* **Logic:** Uses a conditional check to toggle the text back and forth.

### 🟢 Task 2 — Live Input Preview
A real-time text synchronization tool.
* **Behavior:** As you type into the input field, the paragraph below updates instantly to mirror your input.
* **Focus:** Utilizing the `input` event and `event.target.value`.

### 🟢 Task 3 — Interactive List
A dynamic list with deletion capabilities.
* **Behavior:** Users can add new items to a list via an input field.
* **Focus:** **Event Delegation** is used on the parent `<ul>` to handle the "Delete" button clicks for all list items.

### 🟢 Task 4 — Color Changer Cards
An interactive grid of color swatches.
* **Behavior:** Clicking a card activates its specific background color based on its `data-color` attribute.
* **Focus:** Iterating through elements to reset styles so only one card is active at a time.

### 🟢 Task 5 — Toggle Visibility
Demonstrating two distinct ways to hide and show elements.
* **Method A:** Using `classList.toggle` with a `.hidden` CSS class.
* **Method B:** Directly manipulating the `style.display` property between "none" and "block".

### 🟢 Task 6 — Counter with Dynamic Styling
A functional counter with conditional color logic.
* **Behavior:** Increase or decrease the number using `+` and `−` buttons.
* **Visual Logic:** * **Positive:** Green (via `.positive` class).
    * **Negative:** Red (via `.negative` class).
    * **Zero:** Black (via `.zero` class).

---

## 🛠️ Technical Rules Followed

To ensure high-quality, modern code, this project adheres to the following constraints:
* **No Inline Events:** All interactions are handled via `addEventListener`.
* **No Libraries:** Built with 100% Vanilla JavaScript.
* **No :root Variables:** Styles are defined using standard CSS properties to meet specific project constraints.
* **Class Management:** Uses `classList` to manage element states.

---
Link: 
