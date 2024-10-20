# Rt-02
React using Rendering Conditional statement
## What is JSX Interpolation?

In React, JSX Interpolation is the process of embedding JavaScript expressions into JSX. This is done by wrapping the expression in curly braces `{}`. It allows you to dynamically insert values into your JSX.

### Embedding Variables

You can embed JavaScript variables into JSX to dynamically change what’s displayed.

**Example:**

```jsx
const name = "Alice";
const element = <h1>Hello, {name}</h1>;

```

Here, `{name}` is the variable being interpolated into the JSX.

### Expressions

You can also embed more complex JavaScript expressions.

**Example:**

```jsx
const element = <h2>The result is {1 + 2}</h2>;

```
