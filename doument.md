Q.1 What is React?
Ans:- React is a JavaScript library for building user interfaces, particularly for web applications.
React is known for its efficiency in creating interactive, reusable UI components.

Q.2 Who made React?
Ans:- React was created by a software engineer at Facebook named Jordan Walke. It was initially     deployed on Facebook's newsfeed in 2011 and later made open-source at JSConf US in May 2013. 

Q.3 What is babel?
Ans:- Babel is like a javascript complier which coverts html like code which is also known as jsx into latest version of javascript code so thats user can write code easily and efficently.

Q.4 How does Babel convert html code in React into valid code?
Ans:- Babel, often used alongside tools like Webpack in React projects, transpiles JSX code into regular JavaScript that browsers can understand. It converts JSX syntax into JavaScript function calls that create and manage the DOM elements without actually mixing HTML and JavaScript.

Q.5 What is ReactDOM used for? Write an example?
Ans:- ReactDOM provides essential methods to render React components into the browser's DOM, enabling users to interact with them.
e.g => 
    <script>

    let element = React.createElement("p",{
        className :"quote",
        children : "I love coding!"
    })
    console.log(element)
    const reactRoot = ReactDOM.createRoot(document.getElementById("root"))
    reactRoot.render(element)
  </script>

Q.6 What are the packages that you need to import for react to work with?
Ans:- To work with react we need these essentail pakages.
1. React: This is the core library for building user interfaces in React.
2. ReactDOM: This package provides methods for interacting with the DOM in React, like rendering components.

Q.7 How do you add react to a web application?
Ans:- For adding react in our web application we must need node and npm in our system. We need a create recat app that sets a react project with compulsory configuration and dependencies.

Q.8 What is React.createElement?
Ans:- React.createElement is a important function in React that is used when you compile our jsx code into javacsript by using babel.

Q.9 What are the three properties that createElement accept?
Ans:- The main three properties of createElemet is:- 
1. Type or element (div,p,h1,h6)
2. properties or attribute we want to give to the element
3. children 

Q.10 What is the meaning of render and root?
Ans:- Render is a method used in React components to define what should be displayed, while "root" typically denotes the DOM element where the top-level React component or element is rendered within the HTML document.