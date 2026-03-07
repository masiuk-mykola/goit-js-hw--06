# goit-js-hw-06

Homework 06 for the GoIT JavaScript course. Covers object methods and ES6
classes.

## Tasks

### Task 1 — Object Methods (`js/task-1.js`)

Extends a `customer` object with methods to manage balance, discount, and
orders:

- `getBalance()` — returns current balance
- `getDiscount()` — returns current discount
- `setDiscount(value)` — sets a new discount
- `getOrders()` — returns the list of orders
- `addOrder(cost, order)` — deducts cost (after discount) from balance and adds
  the order

### Task 2 — Storage Class (`js/task-2.js`)

A `Storage` class for managing a list of items:

- `getItems()` — returns all items
- `addItem(newItem)` — adds an item to the list
- `removeItem(itemToRemove)` — removes an item from the list

### Task 3 — StringBuilder Class (`js/task-3.js`)

A `StringBuilder` class for string manipulation:

- `getValue()` — returns the current string value
- `padEnd(str)` — appends a string to the end
- `padStart(str)` — prepends a string to the start
- `padBoth(str)` — pads both the start and end with a string
