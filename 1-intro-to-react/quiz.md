# Quiz

What must JavaScript expressions be wrapped with to add them to the JSX?
 curly braces

DOM represents the page as:  tree

What is the output of this code?

```javascript
    function Test(props) {
        return <p>{"A"+props.title}</p>
    }

    const el = <Test title="X"/>

    ReactDOM.render(
        el,
        document.getElementbyId('root');
    );
```

You can use a component in other components multiple times. tru or false?

useState() hook can be used in class Components? true or false? false, they can only be used in functional components.