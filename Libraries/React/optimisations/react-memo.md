# React Memo

## About

- React Memo is a wrapper around a functional component that is an optimisation technique used to reduce the unnecessary re-renders of the child compoinent.


```
const ChildComponent = React.Memo(() => {
      return <div>Child Component</div> 
  })
  
  <Parent>
    <input />
   <ChildComponent />
  </Parent>
```

Child component doesn't rerender unless its internal property changes
