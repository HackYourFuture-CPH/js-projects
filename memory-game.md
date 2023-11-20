![](https://media.giphy.com/media/374pcIBVEGb6g/giphy.gif)

# MEMORY GAME

// TODO: add storyline

## Weekly specs:

### `JS2 week1` - Browser environment, DOM manipulation, DOM event listeners

You are provided with a picture and a card backside pattern picture (or pick your own).

- display a single card on the page using DOM manipulation.
- implement the functionality of fliping the card: on click, the card flips from showing the backside pattern to the picture and vice versa.

---

### `JS2 week2` - Array functions, Arrow function

You are provided with an array of picture objects, that have at least an ID, a name, and a picture url.

- generate a new array where each card object is added to it twice, but in a random order. Think about _doubling_ and _shuffling_ an array when you research how to complete this task.
- traverse through the new array of picture objects and display all the cards in a grid.
- apply the functionality from the previous week so that each card should flip from the picture to the backside pattern and back on click.

---

### `JS2 week3` - Callback function, Asynchronicity, Scope

- implement a counter for how many times in total you have clicked on any card (one counter for all the cards).
- implement a timer for how much time has passed since you first clicked on a card.

---

### `JS3 week1` - Json, Apis, Fetch

- refactor your code so that you ditch the static array of objects and instead fetch the cards data from an API (advanced: use the Giphy API).
- ensure all the functionality is working smoothly after refactoring.

---

### `JS3 week2` - Promises, Async/Await

- you used promise chaining last week - now rewrite the fetch in the "async await" approach.
- implement the functionality for it to work like and actual memory game:

At least:

- You can only flip 2 cards at a time.
- If the cards match, they are removed from the DOM.

At most:

- Implement previous tasks.
- Use the counter and timer that you implemented before and stop the game when a certain count or time is reached. The time or count can be hardcoded or user-submitted via an input.

---

### `JS3 week3` - Classes, Promises advanced

- rest, revise, finish, and brush up your project, prepare to present and explain it.
- optionally, make improvements or add additional functionality.

// TODO: add an "am I done, is it working?" checklist
