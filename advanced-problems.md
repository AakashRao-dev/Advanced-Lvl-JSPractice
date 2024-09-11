## Advanced Problems

### 1. Deep Clone an Object with Circular References

- Task: Write a function deepClone(obj) that can clone an object with nested structures and handle circular references.
- Objective: Understand recursion, handling references, and deep object cloning without external libraries.

### 2. Custom Promise.all Implementation

- Task: Write your own version of Promise.all() that takes an array of promises and returns a single promise. It should resolve when all promises in the array have resolved or reject if any promise rejects.
- Objective: Practice asynchronous programming, promises, and error handling.

### 3. LruCache Class

- Task: Implement an LruCache class with get(key) and put(key, value) methods that follows the Least Recently Used (LRU) caching algorithm.
- Objective: Work with data structures like maps and doubly linked lists. Understand caching mechanisms.

### 4. Throttle Function

- Task: Write a function throttle(fn, wait) that returns a throttled version of fn, ensuring that it’s called at most once every wait milliseconds.
- Objective: Gain experience in higher-order functions and event throttling, useful for optimizing web app performance.

### 5. Debounce Function

- Task: Implement a debounce(fn, delay) function. The function should delay the execution of fn until after delay milliseconds have passed since the last time it was invoked.
- Objective: Learn about function control techniques and user input optimization for web apps.

### 6. Event Emitter

- Task: Create a class EventEmitter that can register event listeners, emit events, and remove listeners.
- Objective: Get comfortable working with event-driven architectures.

### 7. Asynchronous Retry Mechanism

- Task: Write a function retry(fn, retries) that calls the asynchronous function fn, and if it fails, retries up to retries times before finally rejecting.
- Objective: Practice error handling and recursion with asynchronous code.

### 8. Flatten Deeply Nested Array

- Task: Write a function flattenArray(arr) that can flatten a deeply nested array of arbitrary depth, e.g., [1, [2, [3, [4]]]] becomes [1, 2, 3, 4].
- Objective: Explore recursion, handling different data structures, and array manipulation.

### 9. Function Currying

- Task: Create a function curry(fn) that converts a function fn of multiple arguments into a curried version.
- Objective: Learn about function composition and partial application, which are fundamental in functional programming.

### 10. Async Parallel Execution with Limit

- Task: Write a function asyncParallelLimit(tasks, limit) that takes an array of asynchronous tasks and runs them in parallel, but no more than limit tasks at a time.
- Objective: Practice controlling asynchronous execution flow and working with promises.

### 11. Memoization

- Task: Implement a memoize(fn) function that caches the result of expensive function calls and returns the cached result when the same inputs occur again.
- Objective: Understand function caching and performance optimization.

### 12. Binary Search Tree Operations

- Task: Implement a BinarySearchTree class with methods to insert, search, and delete nodes.
- Objective: Reinforce your understanding of tree data structures, recursion, and algorithmic efficiency.

### 13. Implement JSON.stringify

- Task: Write your own version of JSON.stringify() that can handle objects, arrays, numbers, strings, booleans, and null values.
- Objective: Understand object serialization and how JavaScript handles data types.

### 14. Lazy Evaluation

- Task: Write a class LazyEvaluator that takes a series of operations to be performed on a value but doesn't execute them until explicitly asked (similar to how a promise chain works).
- Objective: Explore delayed computation, similar to how RxJS or Lodash's \_.chain works.

### 15. Reactive System (like Vue/Reactivity)

- Task: Implement a simple reactive system where you can track changes to an object’s properties and trigger side effects when those properties are updated.
- Objective: Learn the basics of reactive programming and how modern JavaScript frameworks like Vue.js implement reactivity.

### 16. Asynchronous Retry Mechanism

- Task: Implement a function retry(func, retries, delay) that retries an asynchronous function a certain number of times before failing. Each retry should wait a given delay before attempting again.
- Objective: Practice advanced async patterns and error handling in JavaScript.

### 17. Event Emitter Class

- Task: Implement an EventEmitter class that can register event listeners, emit events, and remove listeners. It should have on(event, listener), emit(event, ...args), and off(event, listener) methods.
- Objective: Build a core JavaScript event-driven system similar to Node.js’s EventEmitter.

### 18. Throttle with Leading and Trailing Edge

- Task: Write a throttle(func, delay, {leading, trailing}) function where the leading option ensures the function is called on the leading edge of the timeout, and trailing ensures it’s called at the end of the timeout.
- Objective: Master more complex control over asynchronous behavior and function execution.

### 19. Custom bind Function

- Task: Write a function customBind(func, thisArg, ...args) that works like Function.prototype.bind(), allowing you to bind a function to a specific context and set initial arguments.
- Objective: Deepen understanding of function contexts (this), closures, and function currying.

### 20. Longest Increasing Subsequence

- Task: Write a function longestIncreasingSubsequence(arr) that returns the length of the longest strictly increasing subsequence in an array. Solve this efficiently in O(n log n) time using binary search.
- Objective: Implement dynamic programming and advanced algorithms efficiently.
