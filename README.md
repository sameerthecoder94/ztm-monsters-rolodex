# Monsters Rolodex Concepts Flow
## Class Components
- Component State
- `setState()`
- States and Shallow Merge
- setState() and __Secondary Callback__
- Mapping Arrays to Elements ( using `map()` method)
- Keys for Mapping
- Single Page Applications (SPAs)
- Lifecycle Method: `componentDidMount()`
- [__Promise__](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise)
  ```js
    const myPromise = new Promise((resolve, reject) => {
      if (true) {
        setTimeout(() => {
          resolve('I have succeeded');
        }, 1000);
      } else {
        reject('I have failed');
      }
    });

    myPromise
        .then((value) => console.log(value))
        .catch((rejectValue) => console.log(rejectValue));
    ```
- Renders & Re-renders flow in React
- Input Search Box Component
- Searching & Filtering Monsters (using `filter()` method and `includes()` method)
- Storing Original Data
- Optimizations & Best Practices
- Understanding Components
  - [__React__](https://reactjs.org/docs/components-and-props.html)
  - CardList Component
    - Component Props
  - SearchBox Component
- __Rendering and Re-rendering part 2__
  - __Note__: Components re-render based on two conditions:
    - When `setState()` gets called
    - States are changed or Props are updated
    This is how primarily React determines you want to re-render.
- __CSS in React__
- Finishing Touches
---
## Functional Components
- Pure & Impure functions
- `useState()` Hook
- Functional Component Re-rendering
- Infinite Re-rendering
- `useEffect()` Hook
- Refactoring Class Components to `Functional Components` Completed