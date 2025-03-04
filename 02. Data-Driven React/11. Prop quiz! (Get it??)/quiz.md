1. What do props help us accomplish?
   make the component more reusable.


3. How do you pass a prop into a component?
<MyAwesomeHeader title="???" />


4. Can I pass a custom prop (e.g. `blahblahblah={true}`) to a native
   DOM element? (e.g. <div blahblahblah={true}>) Why or why not?
   No, because the JSX we use to describe native DOM elements
   will be turned into REAL DOM elements by React. And real DOM elements
   only have the prooperties/attributes specified in the HTML
   (which doesn't include properties like `blahblahblah`)]


5. How do I receive props in a component?
function Navbar(propsName) {
    return (
        <header>
            {propsName.PropsValue}
        </header>
    )
}


6. What data type is `props` when the component receives it?
