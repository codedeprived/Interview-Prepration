
# React Interview Questions and Answers

This file contains common React interview questions and structured answers to help you in your preparation.

---

## Table of Contents

1. [How does React work?](#how-does-react-work)
2. [What is React?](#what-is-react)
3. [How would you write an inline style in React?](#how-would-you-write-an-inline-style-in-react)
4. [What is the use of refs?](#what-is-the-use-of-refs)
5. [What are props in React?](#what-are-props-in-react)
6. [What are the advantages of ReactJS?](#what-are-the-advantages-of-reactjs)
7. [What are the major features of ReactJS?](#what-are-the-major-features-of-reactjs)
8. [What is Context API in ReactJS?](#what-is-context-api-in-reactjs)
9. [What are React Hooks?](#what-are-react-hooks)
10. [What are refs used for in React?](#what-are-refs-used-for-in-react)

---

### Q1: How does React work?
React creates a virtual DOM to improve performance by:
- Updating only the parts of the DOM that need changing.
- Comparing the virtual DOM with the actual DOM and applying only the necessary updates.

### Q2: What is React?
React is a JavaScript library for building user interfaces. It allows developers to create reusable UI components that manage their own state.

### Q3: How would you write an inline style in React?
You can write inline styles in React using the `style` attribute with a JavaScript object:
```javascript
const style = {
  color: "blue",
  fontSize: "20px"
};

function StyledComponent() {
  return <div style={style}>Hello, World!</div>;
}
```

### Q4: What is the use of refs?
`refs` are used to:
- Access and manipulate DOM elements directly.
- Manage focus, text selection, or media playback.
- Trigger animations or measure the size and position of elements.

### Q5: What are props in React?
Props (short for "properties") are read-only inputs passed from parent components to child components. They allow data to flow between components in a React application.

### Q6: What are the advantages of ReactJS?
- **Reusable Components**: Write components once and reuse them anywhere in the app.
- **Virtual DOM**: Optimizes DOM updates and improves app performance.
- **Declarative**: Makes code predictable and easier to debug.
- **Large Ecosystem**: Vast library support and active community.

### Q7: What are the major features of ReactJS?
| Feature          | Description |
|------------------|-------------|
| **JSX**          | JavaScript syntax extension for defining UI components. |
| **Components**   | Reusable, independent pieces of UI. |
| **Virtual DOM**  | Optimized DOM rendering for better performance. |
| **Unidirectional Data Flow** | Simplifies data tracking and debugging. |
| **Hooks**        | Functions to handle state and lifecycle in functional components. |

### Q8: What is Context API in ReactJS?
The Context API is a way to:
- Pass data through the component tree without manually passing props.
- Manage global state such as theme, language, and user authentication.

### Q9: What are React Hooks?
React Hooks are functions that let you use state and other React features in functional components. Examples include:
- **useState**: Manages state in functional components.
- **useEffect**: Handles side effects (e.g., data fetching, event listeners).
- **useContext**: Accesses values from a context provider.

### Q10: What are refs used for in React?
Refs are used for:
- Direct DOM manipulation.
- Triggering animations.
- Managing focus and media playback.

---
