---
title: Articles
subtitle: Here's a searchable list of some of my websites
img_alt: lorem-ipsum
seo:
  title: ''
  description: ''
  robots: []
  extra: []
  type: stackbit_page_meta
layout: page
---




A Collection of my most useful Gist Entries
===========================================

This list is in no particular order!

------------------------------------------------------------------------

### A Collection of my most useful Gist Entries

**This list is in no particular order!**

<a href="https://bgoonz-blog.netlify.app/" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bgoonz-blog.netlify.app/"><strong>Web-Dev-Hub</strong><br />
<em>Memoization, Tabulation, and Sorting Algorithms by Example Why is looking at runtime not a reliable method of…</em>bgoonz-blog.netlify.app</a><a href="https://bgoonz-blog.netlify.app/" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

### Ubuntu Setup:

### Markdown Notes Template:

### Jquery Cheat Sheet:

### Useful Bash Commands:

### Python Cheat Sheet:

### Html Cheat Sheet:

### Git Cheat Sheet:

### Deploy React App To Heroku:

### Bash Aliases:

### JS Cheat Sheet:

### CSS Cheat Sheet:

#### If you found this guide helpful feel free to checkout my github/gists where I host similar content:

<a href="https://gist.github.com/bgoonz" class="markup--anchor markup--p-anchor">bgoonz’s gists · GitHub</a>

<a href="https://github.com/bgoonz" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://github.com/bgoonz"><strong>bgoonz — Overview</strong><br />
<em>Web Developer, Electrical Engineer JavaScript | CSS | Bootstrap | Python | React | Node.js | Express | Sequelize…</em>github.com</a><a href="https://github.com/bgoonz" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

Or Checkout my personal Resource Site:

<a href="https://bgoonz-blog.netlify.app/" class="markup--anchor markup--p-anchor">https://bgoonz-blog.netlify.app/</a>

By <a href="https://medium.com/@bryanguner" class="p-author h-card">Bryan Guner</a> on [March 6, 2021](https://medium.com/p/f4314f3ba3ab).

<a href="https://medium.com/@bryanguner/a-collection-of-my-most-useful-gist-entries-f4314f3ba3ab" class="p-canonical">Canonical link</a>

Exported from [Medium](https://medium.com) on August 31, 2021.

A Comprehensive Deep Dive into React
====================================

An in-depth look into the world of React.

------------------------------------------------------------------------

### React in Depth: A Comprehensive Guide

#### A deep dive into the world of React.

<figure><img src="https://cdn-images-1.medium.com/max/800/0*LnugLVhKbiGfSSHr" alt="Photo by Ferenc Almasi on Unsplash" class="graf-image" /><figcaption>Photo by <a href="https://unsplash.com/@flowforfrank?utm_source=medium&amp;utm_medium=referral" class="markup--anchor markup--figure-anchor">Ferenc Almasi</a> on <a href="https://unsplash.com?utm_source=medium&amp;utm_medium=referral" class="markup--anchor markup--figure-anchor">Unsplash</a></figcaption></figure><a href="https://bryanguner.medium.com/a-list-of-all-of-my-articles-to-link-to-future-posts-1f6f88ebdf5b" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/a-list-of-all-of-my-articles-to-link-to-future-posts-1f6f88ebdf5b"><strong>ALLOFMYOTHERARTICLES</strong><br />
bryanguner.medium.com</a><a href="https://bryanguner.medium.com/a-list-of-all-of-my-articles-to-link-to-future-posts-1f6f88ebdf5b" class="js-mixtapeImage mixtapeImage mixtapeImage--empty u-ignoreBlock"></a>

### Random Things to Remember

-   <span id="1e39">Using `()` implictly returns components.</span>
-   <span id="a547">Role of `index.js` is to *render* your application.</span>
-   <span id="c38f">The reference to `root` comes from a div in the body of your public HTML file.</span>
-   <span id="a364">State of a component is simply a regular JS Object.</span>
-   <span id="d64b">Class Components require `render()` method to return JSX.</span>
-   <span id="fa3d">Functional Components directly return JSX.</span>
-   <span id="4928">`Class` is `className` in React.</span>
-   <span id="e51a">When parsing for an integer just chain `Number.parseInt("123")`</span>
-   <span id="2924">Use ternary operator if you want to make a conditional inside a fragment.</span>

<!-- -->

    { x === y ? <div>Naisu</div> : <div>Not Naisu</div>; }

-   <span id="ccda">Purpose of `React.Fragment` is to allow you to create groups of children without adding an extra dom element.</span>

------------------------------------------------------------------------

### Front-End History

-   <span id="904c">React makes it easier for you to make front-end elements. A front-end timeline</span>
-   <span id="646a">Some noteworthy front end libraries that have been used in the past few years:</span>
-   <span id="febf">2005: Script.aculo.us</span>
-   <span id="d5ae">2005: Dojo</span>
-   <span id="0657">2006: YUI</span>
-   <span id="c1f9">2010: Knockout</span>
-   <span id="e742">2011: AngularJS</span>
-   <span id="ed7b">2012: Elm</span>
-   <span id="06e4">2013: React (Considered the standard front-end library)</span>
-   <span id="4ff0">React manages the creation and updating of DOM nodes in your Web page.</span>
-   <span id="53cd">All it does is dynamically render stuff into your DOM.</span>
-   <span id="c393">What it doesn’t do:</span>
-   <span id="3088">Ajax</span>
-   <span id="54ee">Services</span>
-   <span id="5e4a">Local Storage</span>
-   <span id="a437">Provide a CSS framework</span>
-   <span id="06e5">React is unopinionated</span>
-   <span id="721c">Just contains a few rules for developers to follow, and it just works.</span>
-   <span id="e2c0">JSX : Javascript Extension is a language invented to help write React Applications (looks like a mixture of JS and HTML)</span>
-   <span id="916b">Here is an overview of the difference between rendering out vanilla JS to create elements, and JSX:</span>

<!-- -->

    fetch("https://example.com/api/people")
      .then((response) => response.json())
      .then((people) => {
        const html = "<ul>";
        for (let person of data.people) {
          html += `<li>${person.lastName}, ${person.firstName}</li>`;
        }
        html += "</ul>";
        document.querySelector("#people-list").innerHTML = html;
      });

    function PeopleList(props) {
      return (
        <ul>
          $
          {props.people.map((person) => (
            <li>
              {person.lastName}, {person.firstName}
            </li>
          ))}
        </ul>
      );
    }
    const peopleListElement = document.querySelector("#people-list");
    fetch("https://example.com/api/people")
      .then((response) => response.json())
      .then((people) => {
        const props = { people };
        ReactDOM.render(<PeopleList props={props} />, peopleListElement);
      });

-   <span id="7ea4">This may seem like a lot of code but when you end up building many components, it becomes nice to put each of those functions/classes into their own files to organize your code. Using tools with React</span>
-   <span id="e220">`React DevTools` : New tool in your browser to see ow React is working in the browser</span>
-   <span id="9051">`create-react-app` : Extensible command-line tool to help generate standard React applications.</span>
-   <span id="af96">`Webpack` : In between tool for dealing with the extra build step involved.</span>

<figure><img src="https://cdn-images-1.medium.com/max/800/0*LHVHf7SPZ1t0UVAj" class="graf-image" /></figure>-   <span id="e0ad">HMR : (Hot Module Replacement) When you make changes to your source code the changes are delivered in real-time.</span>
-   <span id="923a">React Developers created something called `Flux Architecture` to moderate how their web page consumes and modifies data received from back-end API's.</span>

<figure><img src="https://cdn-images-1.medium.com/max/800/0*wR-lbD4zf45-IHoQ" class="graf-image" /></figure>-   <span id="b16e">Choosing React</span>
-   <span id="eefd">Basically, React is super important to learn and master.</span>

------------------------------------------------------------------------

### React Concepts and Features

There are many benefits to using React over just Vanilla JavaScript.

-   <span id="8107">`Modularity`</span>
-   <span id="15ac">To avoid the mess of many event listeners and template strings, React gives you the benefit of a lot of modularity.</span>
-   <span id="c1c5">`Easy to start`</span>
-   <span id="90ce">No specials tools are needed to use Basic React.</span>
-   <span id="9ec9">You can start working directly with `createElement` method in React.</span>
-   <span id="dd3c">`Declarative Programming`</span>
-   <span id="d3e6">React is declarative in nature, utilizing either it’s built-in createElement method or the higher-level language known as JSX.</span>
-   <span id="ba8b">`Reusability`</span>
-   <span id="a3c2">Create elements that can be re-used over and over. One-flow of data</span>
-   <span id="27d2">React apps are built as a combination of parent and child components.</span>
-   <span id="6da8">Parents can have one or more child components, all children have parents.</span>
-   <span id="26d8">Data is never passed from child to the parent.</span>
-   <span id="86be">`Virtual DOM` : React provides a Virtual DOM that acts as an agent between the real DOM and the developer to help debug, maintain, and provide general use.</span>
-   <span id="6747">Due to this usage, React handles web pages much more intelligently; making it one of the speediest Front End Libraries available.</span>

### ES6 Refresher

Exporting one item per file

-   <span id="5538">Use `export default` statement in ES6 to export an item. ES6</span>

<!-- -->

    export default class Wallet {
      // ...
    }
    // sayHello will not be exported
    function sayHello() {
      console.log("Hello!");
    }

CommonJS (Equivalent)

    class Wallet {
      // ...
    }
    // sayHello will not be exported
    function sayHello() {
      console.log("Hello!");
    }
    module.exports = Wallet;

Exporting multiple items per file

-   <span id="9a6e">Use just thw `export` keyword (without default) to export multiple items per file. ES6 (Better to export them individually like this, rather than bunching them all into an object)</span>

<!-- -->

    export class Wallet {
      // ...
    }
    export function sayHello() {
      console.log("Hello!");
    }
    export const sayHi = () => {
      console.log("Hi!");
    };
    class Wallet {
      // ...
    }
    function sayHello() {
      console.log("Hello!");
    }
    const sayHi = () => {
      console.log("Hi!");
    };
    export { Wallet, sayHello, sayHi };

CommonJS (Equivalent)

    class Wallet {
      // ...
    }
    function sayHello() {
      console.log("Hello!");
    }
    const sayHi = () => {
      console.log("Hi!");
    };
    module.exports = {
      Wallet,
      sayHello,
      sayHi,
    };

Importing with ES6 vs CommonJS

<figure><img src="https://cdn-images-1.medium.com/max/800/0*7EZESKf0XPbncXAY" class="graf-image" /></figure>-   <span id="18b1">Import statements in ES6 modules must always be at the top of the file, because all imports must occur before the rest of the file’s code runs. ES6</span>

<!-- -->

    import { Wallet } from "./wallet";
    import * as fs from "fs";
    const wallet = new Wallet();

CommonJS

    let { Wallet } = require("./wallet");
    const wallet = new Wallet();
    let fs = require("fs");

Unnamed default imports

-   <span id="75e2">You can name unnamed items exported with export default any name when you import them.</span>

<!-- -->

    // exporting
    export default class Wallet {
      // ...
    }
    // importing
    import Money from "wallet.js";
    const wallet = new Money();

-   <span id="5042">Just remember if you use `export` instead of `export default` then your import is already named and cannot be renamed.</span>

<!-- -->

    // exporting
    export class Wallet {
      // ...
    }
    // importing
    import { Wallet } from "wallet.js";
    const wallet = new Wallet();

Aliasing imports

-   <span id="3535">Use as asterisk to import an entire module’s contents.</span>
-   <span id="3f1c">Keep in mind you must use an `as` keyword to refer to it later.</span>

<!-- -->

    // export
    export function sayHello() {
      console.log("Hello!");
    }
    export const sayHi = () => {
      console.log("Hi!");
    };
    //import
    import * as Greetings from "greetings.js";
    Greetings.sayHello(); // Hello!
    Greetings.sayHi(); // Hi!

-   <span id="bfbc">You can also name identically named functions or items from different files.</span>

<!-- -->

    import { Wallet as W1 } from "./wallet1";
    import { Wallet as W2 } from "./wallet2";
    const w1 = new W1();
    const w2 = new W2();

Browser support for ES6 Modules

-   <span id="69b4">ES6 Modules can only be used when a JS file is specified as a module. `<script type="module" src="./wallet.js"></script>`</span>
-   <span id="4f5c">You can get browser support for ES6 modules by adding module into your script tag.</span>

------------------------------------------------------------------------

### Notes

### JSX In Depth

-   <span id="2a0d">Remember that JSX is just syntactic sugar for the built in `React.createElement(component, props, ...children)`</span>
-   <span id="1532">React Library must always be in scope from your JSX code.</span>
-   <span id="72b2">Use Dot Notation for JSX Type</span>
-   <span id="0cbc">User-Defined Components Must Be Capitalized `<Foo />` vs `<div>`</span>
-   <span id="553a">Cannot use a general expression as the React element type. (`Incorrect`)</span>

<!-- -->

    function Story(props) {
      // Wrong! JSX type can't be an expression.
        return <components[props.storyType] story={props.story} />;
      };

(`Corrected`)

    function Story(props) {
      // Correct! JSX type can be a capitalized variable.
      const SpecificStory = components[props.storyType];
      return <SpecificStory story={props.story} />;
    }

Props in JSX

-   <span id="e549">Several ways to specify props in JSX.</span>
-   <span id="257d">`Javascript Expressions as Props`</span>

<!-- -->

    <MyComponent foo={1 + 2 + 3 + 4} />

-   <span id="57f8">`String Literals`</span>

<!-- -->

    <MyComponent message="hello world" /> <MyComponent message={'hello world'} /> <MyComponent message="&lt;3" /> <MyComponent message={'❤'} />

-   <span id="48df">`Props Default to “True”`</span>

<!-- -->

    <MyTextBox autocomplete /> <MyTextBox autocomplete={true} />

-   <span id="2072">`Spread Attributes`</span>

<!-- -->

    function App1() { return <Greeting firstName="Ben" lastName="Hector" />; } function App2() { const props = { firstName: "Ben", lastName: "Hector" }; return <Greeting {…props} />; }

Children in JSX

-   <span id="2238">`props.children` : The content between opening and closing tag. JavaScript Expressions as Children</span>

<!-- -->

    function Item(props) {
      return <li>{props.message}</li>;
    }
    function TodoList() {
      const todos = ["finish doc", "submit pr", "nag dan to review"];
      return (
        <ul>
          {todos.map((message) => (
            <Item key={message} message={message} />
          ))}
        </ul>
      );
    }

Functions as Children

-   <span id="bf0a">`props.children` works like any other prop, meaning it can pass any sort of data.</span>

<!-- -->

    // Calls the children callback numTimes to produce a repeated component
    function Repeat(props) {
      let items = [];
      for (let i = 0; i < props.numTimes; i++) {
        items.push(props.children(i));
      }
      return <div>{items}</div>;
    }
    function ListOfTenThings() {
      return (
        <Repeat numTimes={10}>
          {(index) => <div key={index}>This is item {index} in the list</div>}
        </Repeat>
      );
    }

Booleans, Null, and Undefined Are Ignored

-   <span id="7017">`false`, `null`, `undefined`, and `true` are all valid children.</span>
-   <span id="5af2">They will not render.</span>
-   <span id="10dc">You can use these to conditionally render items.</span>

<!-- -->

    <div>
      {showHeader && <Header />}
      <Content />
    </div>

-   <span id="fa28">In this example, the component will only render if `showHeader` evals to True.</span>

<!-- -->

    // Before work-around
    <div>
      {props.messages.length &&
        <MessageList messages={props.messages} />
      }
    </div>
    // After work-around
    <div>
      {props.messages.length > 0 &&
        <MessageList messages={props.messages} />
      }
    </div>

-   <span id="3701">Note that certain falsy values such as zero will still be rendered by React, you can work around this by ensuring situations like the above eval. into a boolean.</span>
-   <span id="9586">In the times you want booleans to be rendered out, simply convert it into a string first.</span>

<!-- -->

    <div>My JavaScript variable is {String(myVariable)}.</div>

### Reconciliation

The Diffing Algorithm

-   <span id="76c4">`Diffing` : When the state of a component changes React creates a new virtual DOM tree.</span>
-   <span id="9a73">Elements of Different Types</span>
-   <span id="d680">Every time the root elements have different types, React tears down the old tree and builds the new tree from scratch.</span>
-   <span id="84a6">DOM Elements Of the Same Type</span>
-   <span id="4b94">When comparing two DOM elements of the same type, React keeps the same underlying DOM node and only updates the changes attributes.</span>

<!-- -->

    <div className=”before” title=”stuff” /> <div className=”after” title=”stuff” />

    <div style={{ color: “red”, fontWeight: “bold” }} /> <div style={{color: ‘green’, fontWeight: ‘bold’}} />

-   <span id="0a0c">Component Elements Of The Same Type</span>
-   <span id="cf3a">When components update, instances will remain the same, so that state maintains across renders.</span>
-   <span id="b8ab">React will only update the props, to match the new element.</span>
-   <span id="82f3">Recursing On Children</span>
-   <span id="4a59">React will iterate both lists of children and generate a mutation whenever there’s a difference.</span>
-   <span id="74a8">This is why we use `keys`.</span>
-   <span id="381c">Makes it easier for React to match children in the original tree with children in the subsequent tree.</span>
-   <span id="f1f5">Tradeoffs</span>
-   <span id="e98a">Important to remember that reconciliation algorithm is an *implementation detail*.</span>
-   <span id="7f57">Re-rendering only to apply the differences following the rules stated in the previous sections.</span>

### Typechecking With PropTypes

-   <span id="0bc0">As your application grows, you can use React’s `typechecking` to catch bugs.</span>
-   <span id="638c">`propTypes` is a special property to run typechecking.</span>
-   <span id="e725">exports range of built in validators to ensure your received data is valid.</span>
-   <span id="f590">propTypes is only checked in development mode.</span>

<!-- -->

    import PropTypes from "prop-types";
    class Greeting extends React.Component {
      render() {
        return <h1>Hello, {this.props.name}</h1>;
      }
    }
    Greeting.propTypes = {
      name: PropTypes.string,
    };

Requiring Single Child

-   <span id="e2db">Use `PropTypes.element` to specify only a single child can be passed to a component as children.</span>

<!-- -->

    import PropTypes from "prop-types";
    class MyComponent extends React.Component {
      render() {
        // This must be exactly one element or it will warn.
        const children = this.props.children;
        return <div>{children}</div>;
      }
    }
    MyComponent.propTypes = {
      children: PropTypes.element.isRequired,
    };

Default Prop Values

-   <span id="7d3d">Use `defaultProps` to assign default values for props.</span>

<!-- -->

    class Greeting extends React.Component {
      render() {
        return <h1>Hello, {this.props.name}</h1>;
      }
    }
    // Specifies the default values for props:
    Greeting.defaultProps = {
      name: "Stranger",
    };
    // Renders "Hello, Stranger":
    ReactDOM.render(<Greeting />, document.getElementById("example"));

    class Greeting extends React.Component {
      static defaultProps = {
        name: 'stranger'
      }
      render() {
        return (
          <div>Hello, {this.props.name}</div>
        )
      }

------------------------------------------------------------------------

### Notes

### React Router Introduction

-   <span id="48a7">`React Router` is the answer for rendering different components for different pages.</span>
-   <span id="78b3">A front-end library that allows you to control which components to display using the browser location.</span>
-   <span id="aa2a">`Client-side Routing` Getting started with routing</span>
-   <span id="0940">Install React Router with:</span>
-   <span id="742a">npm install — save react-router-dom@⁵.1.2</span>
-   <span id="f07f">Import `Browser Router` from package.</span>
-   <span id="9e4e">import { BrowserRouter } from “react-router-dom”;</span>
-   <span id="cb01">`BrowserRouter` is the primary component of the router that wraps your route hierarchy.</span>
-   <span id="adfa">Wrap it around components.</span>
-   <span id="0276">Creates a `React Context` that passes routing information down to all its descendant components.</span>
-   <span id="dd45">You can also use `HashRouter`, where it would generate a hash before the endpoint. Creating frontend routes</span>
-   <span id="37c2">React Router helps your app render specific components based on the URL.</span>
-   <span id="54c4">The most common component is `<Route>`</span>
-   <span id="500a">Wrapped around another component, causing the comp. to only render if the a certain URL is matched.</span>
-   <span id="5a94">`Props` : path, component, exact, and \[render\]</span>
-   <span id="9f06">Browser Router can only have a single child component.</span>
-   <span id="6305">The Browser Router wraps all routes within a parent div element.</span>

<!-- -->

    const Root = () => {
      const users = {
        1: { name: "Andrew" },
        2: { name: "Raymond" },
      };
      return (
        <BrowserRouter>
          <div>
            <h1>Hi, I'm Root!</h1>
            <Route exact path="/" component={App} />
            <Route path="/hello" render={() => <h1>Hello!</h1>} />
            <Route path="/users" render={() => <Users users={users} />} />
          </div>
        </BrowserRouter>
      );
    };

-   <span id="c057">component</span>
-   <span id="2dcc">Indicates component to render.</span>
-   <span id="740c">path</span>
-   <span id="3030">Indicates path to render a specific component.</span>
-   <span id="0741">exact</span>
-   <span id="52cb">Tells route to not pattern match and only render a certain route exclusively to it’s associated component.</span>
-   <span id="cb93">render</span>
-   <span id="c702">Optional prop that takes in a function to be called.</span>
-   <span id="594b">Causes extra work for React.</span>
-   <span id="5320">Preferred for inline rendering of simple functional components.</span>
-   <span id="0d3e">Difference between `component` and `render` is that component returns new JSX that be re-mounted, but render returns the JSX that will be mounted only once.</span>
-   <span id="4a08">// This inline rendering will work, but is unnecessarily slow. &lt;Route path=”/hello” component={() =&gt; &lt;h1&gt;Hello!&lt;/h1&gt;} /&gt; // This is the preferred way for inline rendering. &lt;Route path=”/hello” render={() =&gt; &lt;h1&gt;Hello!&lt;/h1&gt;} /&gt;</span>
-   <span id="a2d3">Also useful if you need to pass in specific props to a component.</span>
-   <span id="e09f">// \`users\` to be passed as a prop: const users = { 1: { name: “Andrew” }, 2: { name: “Raymond” }, }; &lt;Route path=”/users” render={() =&gt; &lt;Users users={users} /&gt;} /&gt;;</span>

Route path params

-   <span id="3d09">Your component’s props can hold information about URL’s parameters.</span>
-   <span id="52f3">Will match segments starting at `:` to the next `/`, `?`, `#`.</span>

<!-- -->

    <Route
      path="/users/:userId"
      render={(props) => <Profile users={users} {...props} />}
    />

-   <span id="f2b4">`{...props}` spreads out the router's props.</span>
-   <span id="1edb">`props.match.params` is used to access the match prop's parameters.</span>
-   <span id="b6a9">Useful keys on the `match` object:</span>
-   <span id="290f">`isExact` : boolean that tells you whether or not the URL exactly matches the path.</span>
-   <span id="27ea">`url` : the currentURL</span>
-   <span id="b979">`path` : Route path it matched against (w/o wildcards)</span>
-   <span id="6c59">`params` : Matches for the individual wildcard segments.</span>

------------------------------------------------------------------------

### Navigation

React Router Navigation

-   <span id="a548">`Link`, `NavLink`, `Redirect`, `history` props of React Router are used to help your user navigate routes. Adding links for navigation</span>
-   <span id="643f">Issues on-click navigation event to a route defined in app.</span>
-   <span id="949d">Usage renders an anchor tag with a correctly set `href` attribute.</span>

<!-- -->

    import { BrowserRouter, Route, Link } from "react-router-dom";

-   <span id="b5a5">`Link` takes two properties: `to` and `onClick`.</span>
-   <span id="995b">`to` : route location that points to an absolute path.</span>
-   <span id="978c">`onClick` : clickHandler.</span>
-   <span id="b8c0">`NavLink` works just like `Link` but has a bit of extra functionality.</span>
-   <span id="6334">Adds extra styling, when the path it links to matches the current path.</span>
-   <span id="07b8">As it’s name suggests, it is used to Nav Bars.</span>
-   <span id="8a33">Takes three props:</span>
-   <span id="e501">`activeClassName` : allows you to set a CSS class name for styling. (default set to 'active')</span>
-   <span id="81da">`activeStyle` : style object that is applied inline when it's `to` prop. matches the current URL.</span>
-   <span id="8c71">`exact` prop is a boolean that defaults to false; you can set it to true to apply requirement of an exact URL match.</span>
-   <span id="755b">exact can also be used as a flag instead of a reg. property value.</span>
-   <span id="dd12">benefit of adding this is so that you don’t trigger other matches. Switching between routes</span>
-   <span id="4fb6">`<Switch>` : Component allows you to only render one route even if several match the current URL.</span>
-   <span id="7be7">You may nest as many routes as you wish but only the first match of the current URL will be rendered.</span>
-   <span id="3f8a">Very useful if we want a default component to render if none of our routes match.</span>

<!-- -->

    <Switch>
      <Route path="some/url" component={SomeComponent} />
      <Route path="some/other/url" component={OtherComponent} />
      <Route component={DefaultComponent} />
    </Switch>

-   <span id="b901">`DefaultComponent` will only render if none of the other URLs match up.</span>
-   <span id="21a3">`<Redirect>` : Helps redirect users.</span>
-   <span id="ee88">Only takes a single prop: `to`.</span>

<!-- -->

    <Route
      exact
      path="/"
      render={() => (this.props.currentUser ? <Home /> : <Redirect to="/login" />)}
    />

History

-   <span id="6456">`History` allows you to update the URL programmatically.</span>
-   <span id="bac6">Contains two useful methods:</span>
-   <span id="9b00">`push` : Adds a new URL to the end of the history stack.</span>
-   <span id="d539">`replace` : Replaces the current URL on the history stack, so the back button won't take you to it.</span>

<!-- -->

    // Pushing a new URL (and adding to the end of history stack):
    const handleClick = () => this.props.history.push("/some/url");
    // Replacing the current URL (won't be tracked in history stack):
    const redirect = () => this.props.history.replace("/some/other/url");

------------------------------------------------------------------------

### Nested Routes

Why nested routes?

-   <span id="6403">Create routes that tunnel into main components vs getting rendered on the main page as it’s own thing. What are nested routes?</span>

<!-- -->

    const Profile = (props) => {
      // Custom call to database to fetch a user by a user ID.
      const user = fetchUser(props.match.params.userId);
      const { name, id } = user;
      return (
        <div>
          <h1>Welcome to the profile of {name}!</h1>
          <Link to={`/users/${id}/posts`}>{name}'s Posts</Link>
          <Link to={`/users/${id}/photos`}>{name}'s Photos</Link>
          <Route path="/users/:userId/posts" component={UserPosts} />
          <Route path="/users/:userId/photos" component={UserPhotos} />
        </div>
      );
    };

Alt. version using `props.match`

    // Destructure `match` prop
    const Profile = ({ match: { url, path, params }) => {
      // Custom call to database to fetch a user by a user ID.
      const user = fetchUser(params.userId);
      const { name, id } = user;
      return (
        <div>
          <h1>Welcome to the profile of {name}!</h1>
          <Link to={`${url}/posts`}>{name}'s Posts</Link>
          <Link to={`${url}/photos`}>{name}'s Photos</Link>
          <Route path={`${path}/posts`} component={UserPosts} />
          <Route path={`${path}/photos`} component={UserPhotos} />
        </div>}
      );
    };

-   <span id="03fb">As you can see above, our end URL isn’t even defined until we apply those flexible values in.</span>

------------------------------------------------------------------------

### React Builds

-   <span id="0fae">`Build` : Process of converting code into something that can actually execute or run on the target platform.</span>
-   <span id="6fdb">In regards to React, the minimum a build should do is convert JSX to something that browsers can understand. Reviewing common terminology</span>
-   <span id="779d">`Linting` : Process of using a tool to analyze your code to catch common errors, bugs, inconsistencies etc...</span>
-   <span id="f1e5">`Transpilation` : Process of converting source code, like JS, from one version to another.</span>
-   <span id="9f9f">`Minification` : Process of removing all unnecessary characters in your code.</span>
-   <span id="57df">`Bundling` : Process of combining multiple code files into a single file.</span>
-   <span id="d052">`Tree Shaking` : Process of removing unused or dead code from your application before it's bundled. Configuration or code?</span>
-   <span id="ce13">`Configuration` allows developers to create build tasks by declaring either JSON, XML, or YAML without explicitly writing every step in the process.</span>
-   <span id="16a6">`Coding` or `Scripting` simply requires code. Babel and webpack (yes, that's intentionally a lowercase 'w')</span>
-   <span id="4363">`Babel` : Code Transpiler that allows you to use all of the latest features and syntax wihtout worrying about what browsers support what.</span>
-   <span id="804b">`webpack` : Allows developers to use JS modules w/o requiring users to use a browser that natively supports ES modules.</span>
-   <span id="77f2">Create React App uses webpack and Babel under the hood to build applications. The Create React App build process</span>
-   <span id="222f">What happens when you run `npm start`:</span>

1.  <span id="d245">.env variables are loaded.</span>
2.  <span id="6209">list of browsers to support are checked.</span>
3.  <span id="1c34">config’d HTTP port checked for availability.</span>
4.  <span id="950b">application compiler is configured and created.</span>
5.  <span id="8e30">`webpack-dev-starter` is started</span>
6.  <span id="48cc">`webpack-dev-starter` compiles app.</span>
7.  <span id="68ad">`index.html` is loaded into browser</span>
8.  <span id="e670">file watcher is started to watch for changes. Ejecting</span>

-   <span id="428b">There is a script in Create React App called `eject` that allows you to 'eject' your application and expose all the hidden stuff. Preparing to deploy a React application for production</span>
-   <span id="eb79">Defining Env Variables</span>

<!-- -->

    REACT_APP_FOO: some value
    REACT_APP_BAR: another value

    console.log(process.env.REACT_APP_FOO);

    Can be referenced in your index.html like so: <title>%REACT_APP_BAR%</title>

Configuring the supported browsers

    {
      "browserslist": {
        "production": [
          ">0.2%",
          "not dead",
          "not op_mini all"
        ],
        "development": [
          "last 1 chrome version",
          "last 1 firefox version",
          "last 1 safari version"
        ]
      }
    }

-   <span id="8a03">If you specify older browsers it will affect how your code get’s transpiled. Creating a production build</span>
-   <span id="fee3">Run `npm run build` to create a production build.</span>
-   <span id="bdaf">Bundles React in production mode and optimizes the build for the best performance.</span>

------------------------------------------------------------------------

### Notes

### Introduction to React

-   <span id="7224">Simply a nice library that turns data into DOM.</span>
-   <span id="a9de">`Tree Diffing` : Fast comparison and patching of data by comparing the current virtual DOM and new virtual DOM - updating only the pieces that change.</span>
-   <span id="1bbc">`It's just a tree with some fancy diffing`</span>

------------------------------------------------------------------------

### Create Element

From JavaScript To DOM

-   <span id="cae8">The `React.createElement` function has the following form:</span>

<!-- -->

    React.createElement(type, [props], [...children]);

-   <span id="1688">`Type` : Type of element to create, i.e. a string for an HTML element or a reference to a function or class that is a React component.</span>
-   <span id="3249">`Props` : Object that contains data to render the element.</span>
-   <span id="56ab">`Children` : Children of the elemet, as many as you want. Creating elements</span>
-   <span id="ee64">Our rendering goal:</span>

<!-- -->

    <ul>
      <li class="selected">
        <a href="/pets">Pets</a>
      </li>
      <li>
        <a href="/owners">Owners</a>
      </li>
    </ul>

-   <span id="eb8b">There are five tags to create:</span>
-   <span id="ea28">One `ul`</span>
-   <span id="a4ba">Two `li`</span>
-   <span id="de01">Two `a`</span>
-   <span id="90b5">There are certain attributes we want to appear in the DOM for these tags as well:</span>
-   <span id="dab5">Each `li` has a `class` (or `className` in React)</span>
-   <span id="e88e">Both `a` ele's have `href` attributes</span>
-   <span id="fd8c">Also keep in mind the parent child relationships happening between the tags.</span>
-   <span id="9893">`ul` is the parent of both `li`</span>
-   <span id="eafa">Each `li` has an `a` element as a child</span>
-   <span id="84cc">Each `a` has a `text content` child</span>

<figure><img src="https://cdn-images-1.medium.com/max/800/0*8ls0PmtREELbf5Wm" class="graf-image" /></figure>React.createElement(
      "ul",
      null,
      React.createElement(
        "li",
        { className: "selected" },
        React.createElement("a", { href: "/pets" }, "Pets")
      ),
      React.createElement(
        "li",
        null,
        React.createElement("a", { href: "/owners" }, "Owners")
      )
    );

Converting to virtual DOM

-   <span id="e7d4">After you set up your `React.createElement`, you use `React.render` to take the value returned from cE and a DOM node to insert into the conversion of the real DOM.</span>

<!-- -->

    // Put the element tree in a variable
    const navList = React.createElement(
      "ul",
      null,
      React.createElement(
        "li",
        { className: "selected" },
        React.createElement("a", { href: "/pets" }, "Pets")
      ),
      React.createElement(
        "li",
        null,
        React.createElement("a", { href: "/owners" }, "Owners")
      )
    );
    // Get a DOM node for React to render to
    const mainElement = document.querySelector("main");
    // Give React the element tree and the target
    ReactDOM.render(navList, mainElement);

-   <span id="2cbc">JS Code =&gt; Virtual DOM =&gt; Real Dom Updates</span>
-   <span id="25d5">If you call React.render a second or multiple times it just checks the existing Virtual DOM and it knows which smaller areas to change. Thinking in Components</span>
-   <span id="fe61">Components are pieces of reusable front-end pieces.</span>
-   <span id="bffa">Components should be Single Responsibility Principle compliant.</span>

------------------------------------------------------------------------

### Create Element

`React.createElement Demo`

-   <span id="a288">Can import non-local dependencies with `import 'package-link'`</span>

<!-- -->

    const App = () => React.createElement("h1", null, "Hello, Programmers!");
    const target = document.querySelector("main");
    const app = React.createElement(App, null);
    // Give React the element tree and the target
    ReactDOM.render(app, target);

-   <span id="0693">Remember when importing modules from other files you have to denote the file type in the import statement. HTML Original</span>

<!-- -->

    <section class="clue">
      <h1 class="clue__title">Clue$ 268530</h1>
      <div class="clue__question">
          2009: I dreamed a Dream
      </div>
      <div class="clue__category">
          <<unparsed>>
      </div>
      <div class="clue__amount">
          $800
      </div>
    </section>

React Version

    const Clue = () =>
      React.createElement(
        "section",
        { className: "clue" },
        React.createElement("h1", { className: "clue__title" }, "Title"),
        React.createElement("div", { className: "clue__question" }, "?"),
        React.createElement("div", { className: "clue__category" }, "Category"),
        React.createElement("div", { className: "clue__amount" }, "$800")
      );

-   <span id="f587">Because `class` is a reserved keyword in JS, in React we can use `className` to assign a class to an element.</span>
-   <span id="4d51">Remember the data that goes into createElement: element type, data to pass into the element, and then children.</span>
-   <span id="8199">`props` : Properties;</span>
-   <span id="6b53">To handle certain values that are initially undefined, we can use `defaultProps`.</span>

<!-- -->

    Clue.defaultProps = {
      category: {},
    };

-   <span id="4abe">You can change in the devTools Network tab the internet speed to check for values that may be undefined to hangle with defaultProps.</span>
-   <span id="79e3">If we fetch multiple pieces of data, we can render many things by using `map`.</span>
-   <span id="06f2">You need to assign a unique key to each of the clues.</span>
-   <span id="c12e">We need to keep track of them individually so that React can easily refer to a specific one if there is an issue. `clue => { key:clue.id, ...clue }`</span>

<!-- -->

    const App = (props) =>
      React.createElement(
        "h1",
        null,
        props.clues.map((clue) =>
          React.createElement(Clue, { key: clue.id, ...clue })
        )
      );
    export default App;

-   <span id="1dd5">Note: JSX is preferred over React.createElement;</span>

------------------------------------------------------------------------

### Notes from Hello Programmer Exercise

-   <span id="1fb8">When you import modules from websites they must have CORs activated.</span>
-   <span id="1ef6">These import statements, import `global variables`.</span>
-   <span id="6613">When we want to move our code into production we need to change the imports into the production minified versions.</span>

<!-- -->

    import "https://unpkg.com/react@16/umd/react.production.min.js";
    import "https://unpkg.com/react-dom@16.13.1/umd/react-dom.production.min.js";

-   <span id="0046">While we will never actually be creating full apps with just React.createElement =&gt; it is the enginer that is running under the hood!</span>

<!-- -->

    import "https://unpkg.com/react@16/umd/react.development.js";
    import "https://unpkg.com/react-dom@16/umd/react-dom.development.js";
    const Links = () =>
      React.createElement(
        "ul",
        { id: "nav-links" },
        React.createElement(
          "li",
          { className: "is-selected" },
          React.createElement("a", { href: "http://appacademy.io" }, "App Academy")
        ),
        React.createElement(
          "li",
          null,
          React.createElement("a", { href: "https://aaonline.io" }, "a/A Open")
        )
      );
    // Set up React Element: Type, Imported Data, Child (Child is Text in this Scenario)
    // HelloWorld is a function based component
    const HelloWorld = () => React.createElement("h1", null, "Hello, Programmers");
    const AllTogether = () =>
      React.createElement(
        "div",
        null,
        React.createElement(HelloWorld, null),
        React.createElement(Links, null)
      );
    // Target the Element to append new Ele
    const target = document.querySelector("main");
    // Assign your 'App' to your created Elements
    // We are creating an element from the HelloWorld function.
    const app = React.createElement(AllTogether, null);
    // Render from the Virtual Dom to the Actual Dom
    ReactDOM.render(app, target);

------------------------------------------------------------------------

### Introduction to JSX

-   <span id="a5ee">`JSX` : Javascript Extension, a new language created by React developers to have an easier way of interacting with the React API. How to use JSX</span>
-   <span id="24bf">We will use `babel` to convert version of modern JS into an older version of JS. React Create Element</span>

<!-- -->

    const ExampleComponent = (props) =>
      React.createElement(
        React.Fragment,
        null,
        React.createElement("h1", null, "Hello!"),
        React.createElement("img", { src: "https://via.placeholder.com/150" }),
        React.createElement("a", { href: props.searchUrl }, props.searchText)
      );

JSX Version

    const ExampleComponent = (props) => (
      <React.Fragment>
        <h1>Hello!</h1>
        <img src="https://via.placeholder.com/150" />
        <a href={props.searchUrl}>{props.searchText}</a>
      </React.Fragment>
    );

-   <span id="b00d">Keep in mind that self closing tags in React must have a `forward slash` to close it.</span>

<figure><img src="https://cdn-images-1.medium.com/max/800/0*NNxuFMF-sOL8Wvdl" class="graf-image" /></figure>-   <span id="346d">Properties and Data</span>

<!-- -->

    <img src="https://via.placeholder.com/150" />;
    // becomes..
    React.createElement("img", { src: "https://via.placeholder.com/150" });
    // if we want to pass in data vs just a string literal
    <a href={props.searchUrl}>{props.searchText}</a>;
    // so it becomes..
    React.createElement("a", { href: props.searchUrl }, props.searchText);
    // if you want the text search uppercase..
    <a href={props.searchUrl}>{props.searchText.toUpperCase()}</a>;

-   <span id="467c">Comments in JSX have the following syntax:</span>

<!-- -->

    <div>
      <h2>This is JSX</h2>
      {/* This is a comment in JSX */}
    </div>

-   <span id="8cb8">`Property Names`:</span>
-   <span id="837b">`checked` : Attribute of input components such as checkbox or radio, use it to set whether the component is checked or not.</span>
-   <span id="aec0">`className` : Used to specify a CSS class.</span>
-   <span id="2f92">`dangerouslySetInnerHTML` : React's equivalent of innerHTML because it is risky to cross-site scripting attacks.</span>
-   <span id="3eab">`htmlFor` : Because `for` is protected keyword, React elements use this instead.</span>
-   <span id="9194">`onChange` : Event fired whenever a form field is changed.</span>
-   <span id="014a">`style` : Accepts a JS object with camelCase properties rather than a CSS string.</span>
-   <span id="76d8">`value` : Supported by Input, Select, and TextArea components; use it to set the value of the component.</span>
-   <span id="22c2">Note: React uses camel-case!!! The JSX semicolon gotcha</span>

<!-- -->

    function App() {
      return (
        <div>
          <h1>Hello!</h1>
          <div>Welcome to JSX.</div>
        </div>
      );
    }

create Element equivalent

    is equivalent to
    function App() {
      return (
        React.createElement(
          'div',
          null,
          React.createElement('h1', null, 'Hello!'),
          React.createElement('div', null, 'Welcome to JSX.'),
        )
      );
    }

-   <span id="dbc1">We wrap what want to return in parenthesis so JS doesn’t auto add semi-colons after every line and run the code incorrectly.</span>
-   <span id="62c0">Just remember if you decided to use the return keyword in a function to ‘return some JSX’, then make sure you wrap the JSX in parenthesis.</span>

------------------------------------------------------------------------

`npx create-react-app my-app`

-   <span id="8ad9">Single line used to initiate a React application.</span>
-   <span id="3cb1">React has a great toolchain where you can see changes live as you’re editing your application.</span>
-   <span id="c1d0">React errors will be rendered directly onto the browser window.</span>
-   <span id="1365">A downside is that it installs a lot of bloat files.</span>
-   <span id="aaed">Examples of React create Element and JSX equivalent</span>

<!-- -->

    React.createElement(
      "a",
      {
        className: "active",
        href: "https://appacademy.io",
      },
      "App Academy"
    );
    // JSX Version
    <a className="active" href="https://appacademy.io">
      App Academy
    </a>;

    React.createElement(
      OwnerDetails,
      {
        owner: props.data.owner,
        number: props.index + 1,
      },
      props.name
    );
    // JSX Version
    <OwnerDetails owner={props.data.owner} number={props.index + 1}>
      {props.name}
    </OwnerDetails>;

More Complex JSX Example

    const BookPanel = (props) => {
      <section className="book" id={`book-${props.id}`}>
        <h1 className="book__title">{props.title}</h1>
        <img src={props.coverUrl} />
        <div className="book__desc">{props.description}</div>
      </section>;
    };

------------------------------------------------------------------------

### Notes

### Using Custom CRA Templates

Using a Custom Template `npx create-react-app my-app --template @appacademy/simple`

-   <span id="9607">Keep in mind that using `create-react-app` automatically initializes a git repository for you!</span>
-   <span id="f0fe">App Academy custom template for creating a react app.</span>
-   <span id="1b4e">If using the default react create project you can delete the following files:</span>
-   <span id="ef1c">favicon.ico</span>
-   <span id="627b">robots.txt</span>
-   <span id="3b34">logo192.png</span>
-   <span id="9b50">logo512.png</span>
-   <span id="8101">manifest.json</span>
-   <span id="77db">You can also simplify the `html` file into:</span>

<!-- -->

    <!DOCTYPE html>
    <html lang="en">
      <head>
        <meta charset="utf-8" />
        <title>React App</title>
      </head>
      <body>
        <div id="root"></div>
      </body>
    </html>

Simplifying the src folder

-   <span id="ac69">Remove: App.css App.test.js logo.svg serviceWorker.js setupTests.js</span>
-   <span id="064f">Update the Following Files:</span>

<!-- -->

    // ./src/App.js
    import React from "react";
    function App() {
      return <h1>Hello world!</h1>;
    }
    export default App;
    ``;

    // ./src/index.js
    import React from "react";
    import ReactDOM from "react-dom";
    import "./index.css";
    import App from "./App";
    ReactDOM.render(
      <React.StrictMode>
        <App />
      </React.StrictMode>,
      document.getElementById("root")
    );

------------------------------------------------------------------------

### React Class Components

Class Components

-   <span id="b5e6">You can write React components using ES2015 Classes: Function Component</span>

<!-- -->

    // ./src/Message.js
    import React from "react";
    const Message = (props) => {
      return <div>{props.text}</div>;
    };
    export default Message;

ES2015 Version

    // ./src/Message.js
    import React from "react";
    class Message extends React.Component {
      render() {
        return <div>{this.props.text}</div>;
      }
    }
    export default Message;

-   <span id="ae33">We can access props within a `class component` by using `this.props`</span>
-   <span id="0b60">Keep in mind Class Components are used just like function components.</span>

<!-- -->

    // ./src/index.js
    import React from "react";
    import ReactDOM from "react-dom";
    import Message from "./Message";
    ReactDOM.render(
      <React.StrictMode>
        <Message text="Hello world!" />
      </React.StrictMode>,
      document.getElementById("root")
    );

Setting and accessing props

    class Message extends React.Component {
      constructor(props) {
        super(props);
        // TODO Initialize state, etc.
      }
      render() {
        return <div>{this.props.text}</div>;
      }
    }

-   <span id="cd5a">If we define a constructor method in our Class Component, we have to define the `super` method with `props` passed through it.</span>
-   <span id="8bf7">Side Note: Before React used ES2015 Classes, it used `React.createclass` function, if you ever need to use this antiquated method make sure you install a module called `create-react-class` Stateful components</span>
-   <span id="4b12">One of the major reasons why you would choose to use a Class Component over a Function Component is to add and manage local or internal state to your component.</span>
-   <span id="8e82">Second of the major reasons is to be able to use a Class Component’s lifecycle methods. What is state?</span>
-   <span id="7fab">Props are data that are provided by the consumer or caller of the component.</span>
-   <span id="98f4">Not meant to be changed by a component.</span>
-   <span id="c6a9">State is data that is `internal` to the component.</span>
-   <span id="3e89">Intended to be updated or mutated. When to use state</span>
-   <span id="c03f">*Only Use State when it is absolutely necessary*</span>
-   <span id="204b">If the data never changes, or if it’s needed through an entire application use props instead.</span>
-   <span id="0b53">State is more often used when creating components that retrieve data from APIs or render forms.</span>
-   <span id="1b6b">The general rule of thumb: If a component doesn’t need to use state or lifecyle methods, it should be prioritized as a `function component`.</span>
-   <span id="d708">Functional:Stateless || Class:Stateful Initializing state</span>
-   <span id="e5d5">Use a class constructor method to initialize `this.state` object. // Application Entry Point</span>

<!-- -->

    // ./src/index.js
    import React from 'react'
    import ReactDOM from 'react-dom';
    import RandomQuote from './RandomQuote';
    ReactDOM.render(
      <React.StrictMode>
        <RandomQuote />
      </React.StrictMode>
      document.getElementById('root');
    )

// Class Component: RandomQuote

    import React from "react";
    class RandomQuote extends React.Component {
      constructor() {
        super();
        const quotes = [
          "May the Force be with you.",
          "There's no place like home.",
          "I'm the king of the world!",
          "My mama always said life was like a box of chocolates.",
          "I'll be back.",
        ];
        this.state = {
          quotes,
          currentQuoteIndex: this.getRandomInt(quotes.length);
        }
      }
      getRandomInt(max) {
        return Math.floor(Math.random() * Math.floor(max));
      }
      render() {
        return (
          <div>
            <h2>Random Quote</h2>
            <p>{this.state.quotes[this.state.currentQuoteIndex]}</p>
          </div>
        )
      }
    }
    export default RandomQuote;

Updating State

-   <span id="3fdc">Let’s say we want to update our state with a new quote.</span>
-   <span id="eddc">We can set up event listeners in React similarly to how we did them before.</span>
-   <span id="106c">&lt;button type=”button” onClick={this.changeQuote}&gt; Change Quote &lt;/button&gt;</span>
-   <span id="a77a">`onClick` is the event listener.</span>
-   <span id="f406">`{this.changeQuote}` is the event handler method.</span>
-   <span id="7dca">Our Class Component File should now look like this with the new additions:</span>

<!-- -->

    import React from "react";
    class RandomQuote extends React.Component {
      constructor() {
        super();
        const quotes = [
          "May the Force be with you.",
          "There's no place like home.",
          "I'm the king of the world!",
          "My mama always said life was like a box of chocolates.",
          "I'll be back.",
        ];
        this.state = {
          quotes,
          currentQuoteIndex: this.getRandomInt(quotes.length);
        }
      }
      changeQuote = () => {
        const newIndex = this.getRandomInt(this.state.quotes.length);
        // Setting the 'new state' of currentQuoteIndex state property
        // to newly generated random index #.
        this.setState({
          currentQuoteIndex: newIndex;
        })
      }
      getRandomInt(max) {
        return Math.floor(Math.random() * Math.floor(max));
      }
      render() {
        return (
          <div>
            <h2>Random Quote</h2>
            <p>{this.state.quotes[this.state.currentQuoteIndex]}</p>
            <button type="button" onClick={this.changeQuote}>
              Change Quote
            </button>
          </div>
        )
      }
    }
    export default RandomQuote;

Don’t modify state directly

-   <span id="ca27">It is important to `never` modify your state directly!</span>
-   <span id="780d">ALWAYS use `this.setState` method to update state.</span>
-   <span id="1581">This is because when you only use this.state to re-assign, no re-rendering will occur =&gt; leaving our component out of sync. Properly updating state from the previous state</span>
-   <span id="dc5a">In our current example, the way we have `changeQuote` set up leaves us with occasionally producing the same index twice in a row.</span>
-   <span id="0bff">One solution is to design a loop but keep in mind that state updates are handled asynchronously in React (your current value is not guaranteed to be the latest)</span>
-   <span id="39f9">A safe method is to pass an anonymous method to `this.setState` (instead of an object literal) Previous</span>

<!-- -->

    changeQuote = () => {
        const newIndex = this.getRandomInt(this.state.quotes.length);
        this.setState({
          currentQuoteIndex: newIndex;
        })
      }

Passing w/ Anon Method

    changeQuote = () => {
      this.setState((state, props) => {
        const { quotes, currentQuoteIndex } = state;
        let newIndex = -1;
        do {
          newIndex = this.getRandomInt(quote.length);
        } while (newIndex === currentQuoteIndex);
        return {
          currentQuoteIndex: newIndex,
        };
      });
    };

Providing default values for props

-   <span id="7e8c">In our current example, we pass in a static array of predefined quotes in our constructor.</span>
-   <span id="3e8f">The way it is set up right now leaves our list of quotes unchanged after initialization.</span>
-   <span id="add0">We can make quotes more dynamic by replacing our static array with a `props` argument passed into `super`.</span>
-   <span id="53d6">constructor(props) { super(props); }</span>
-   <span id="918a">We can now move our quotes array to our application entry point and pass it in as a prop. // Application Entry Point</span>

<!-- -->

    // ./src/index.js
    import React from 'react'
    import ReactDOM from 'react-dom';
    import RandomQuote from './RandomQuote';
    // Re-assign our array here and pass it in as a prop in Render.
    const quotes = [
          "May the Force be with you.",
          "There's no place like home.",
          "I'm the king of the world!",
          "My mama always said life was like a box of chocolates.",
          "I'll be back.",
          "This way I can define more quotes",
        ];
    ReactDOM.render(
      <React.StrictMode>
        <RandomQuote quotes={quotes}/>
      </React.StrictMode>
      document.getElementById('root');
    )

-   <span id="a0bb">One thing to note about this workaround is that the caller of the component *must* set the quotes prop or the component will throw an error =&gt; so use `defaultProps`!</span>

<!-- -->

    // At the bottom of RandomQuote.js...
    RandomQuote.defaultProps = {
      quotes: [
        "May the Force be with you.",
        "There's no place like home.",
        "I'm the king of the world!",
        "My mama always said life was like a box of chocolates.",
        "I'll be back.",
        "This way I can define more quotes",
      ],
    };

-   <span id="c575">A good safety net in case the consumer/caller doesn’t provide a value for the quotes array.</span>
-   <span id="3be6">We can even remove it from our index.js now and an error will not be thrown.</span>

------------------------------------------------------------------------

### Handling Events

-   <span id="a82e">To add an event listener to an element, just define a method to handle the event and associate that method with the element event you are listening for. Example</span>

<!-- -->

    import React from "react";
    class AlertButton extends React.Component {
      showAlert = () => {
        window.alert("Button Clicked!");
      };
      render() {
        return (
          <button type="button" onClick={this.showAlert}>
            Submit
          </button>
        );
      }
    }

-   <span id="a852">Note that when refering the handler method in onClick we’re not invoking showAlert simply just passing a reference. Preventing default behavior</span>
-   <span id="5cb0">HTML Elements in the browser often have a lot of default behavior.</span>
-   <span id="df4d">I.E. Clicking on an `<a>` element navigates so a resource denoted by `<href>` property.</span>
-   <span id="952c">Here is an example of where using `e.preventDefault()` could come in handy.</span>

<!-- -->

    import React from "react";
    class NoDefaultSubmitForm extends React.Component {
      submitForm = (e) => {
        e.preventDefault();
        window.alert("Handling form submission...");
      };
      render() {
        return (
        <form onSubmit={this.submitForm}>
          <button>Submit</button>
        </form>;
        )}
    }

-   <span id="b149">The button contained within the form will end up refreshing the page before `this.submitForm` method can be completed.</span>
-   <span id="a034">We can stick an `e.preventDefault()` into the actual method to get around this problem.</span>
-   <span id="004a">`e` : Parameter that references a `Synthetic Event` object type. Using `this` in event handlers</span>

<!-- -->

    // ./src/AlertButton.js
    import React from "react";
    class AlertButton extends React.Component {
      showAlert = () => {
        window.alert("Button clicked!");
        console.log(this);
      };
      render() {
        return (
          <button type="button" onClick={this.showAlert}>
            Click Me
          </button>
        );
      }
    }
    export default AlertButton;

-   <span id="3c8f">When we console log `this` we see the AlertButton object.</span>
-   <span id="42a0">If we were to write the showAlert method with a regular class method like:</span>

<!-- -->

    showAlert() {
      console.log(this);
    }

-   <span id="c081">We would get `undefined` =&gt; remember that fat arrow binds to the current context! Reviewing class methods and the `this` keyword</span>
-   <span id="e98e">Let’s refresh on binding.</span>

<!-- -->

    class Boyfriend {
      constructor() {
        this.name = "Momato Riruru";
      }
      displayName() {
        console.log(this.name);
      }
    }
    const Ming = new Boyfriend();
    Ming.displayName(); // => Momato Riruru
    const displayAgain = Ming.displayName;
    displayAgain(); // => Result in a Type Error: Cannot read property 'name' of undefined.

-   <span id="fb85">The first time we use our `displayMethod` call, it is called directly on the instance of the boyfriend class, which is why `Momato Riruru` was printed out.</span>
-   <span id="3a9b">The second time it was called, the ref of the method is stored as a variable and method is called on that variable instead of the instance; resulting in a type error (it has lost it’s context)</span>
-   <span id="0a2c">Remember we can use the `bind` method to rebind context!</span>
-   <span id="d6d9">We can refactor to get the second call working like this:</span>
-   <span id="7ead">const displayAgain = Ming.displayName.bind(Ming); displayAgain(); // =&gt; Now Momato Riruru will be printed out.</span>
-   <span id="a8b0">To continue using function declarations vs fat arrow we can assign context in a constructor within a class component.</span>

<!-- -->

    import React from "react";
    class AlertButton extends React.Component {
      constructor() {
        super();
        this.showAlert = this.showAlert.bind(this); // binding context
      }
      showAlert() {
        console.log(this);
      }
      render() {
        return (
          <button type="button" onClick={this.showAlert}>
            Submit
          </button>
        );
      }
    }
    export default AlertButton;

-   <span id="a4e6">`Experimental Syntax` : Syntax that has been proposed to add to ECMAScript but hasn't officially been added to the language specification yet.</span>
-   <span id="801d">It’s good to pick one approach and use it consistently, either:</span>

1.  <span id="2e3e">Class Properties & Arrow Functions</span>
2.  <span id="cc27">Bind Method & This Keyword The `SyntheticEvent` object</span>

-   <span id="f177">Synthetic Event Objects: Cross Browser wrappeds around the browser’s native event.</span>
-   <span id="418f">Includes the use of stopPropagation() and preventDefault();</span>
-   <span id="b94f">Attributes of the Synthetic Event Object:Attributesboolean bubblesboolean cancelableDOMEventTarget currentTargetboolean defaultPreventednumber eventPhaseboolean isTrustedDOMEvent nativeEventvoid preventDefault()boolean isDefaultPrevented()void stopPropagation()boolean isPropagationStopped()void persist()DOMEventTarget targetnumber timeStampstring type</span>
-   <span id="7484">`nativeEvent` : property defined in a synthetic event object that gives you access to the underlying native browser event (rarely used!)</span>

------------------------------------------------------------------------

### Forms in React

*Exercise being done in a separate file* Random Notes

-   <span id="45ec">`onChange` : detects when a value of an input element changes.</span>
-   <span id="9ca4">Assigning `onChange` to our input fields makes our component's state update in real time during user input.</span>
-   <span id="eb83">Dont forget to add `preventDefault` onto form submissions to deal with the default behavior of the browser refreshing the page!</span>
-   <span id="c413">`submittedOn: new Date(),` Can be added to a form, most likely will persist into a DB.</span>
-   <span id="b97f">Controlled Components</span>
-   <span id="ac48">We use the `onChange` event handlers on form fields to keep our component's state as the `"one source of truth"`</span>
-   <span id="4685">Adding an `onChange` event handler to every single input can massively bloat your code.</span>
-   <span id="448c">Try assiging it to it’s own method to apply everywhere.</span>
-   <span id="f229">`textarea` is handled differently in react: it takes in a value property to handle what the inner text will be.</span>

<!-- -->

    // ./src/ContactUs.js
    import React from "react";
    class ContactUs extends React.Component {
      constructor() {
        super();
        this.state = {
          name: "",
          email: "",
          phone: "",
          phoneType: "",
          comments: "",
          validationErrors: [],
        };
      }
      onChange = (e) => {
        const { name, value } = e.target;
        this.setState({ [name]: value });
      };
      // Vanilla JS Function for validating inputs
      validate(name, email) {
        const validationErrors = [];
        if (!name) {
          validationErrors.push("Please provide a Name");
        }
        if (!email) {
          validationErrors.push("Please provide an Email");
        }
        return validationErrors;
      }
      onSubmit = (e) => {
        // Prevent the default form behavior
        // so the page doesn't reload.
        e.preventDefault();
        // Retrieve the contact us information from state.
        const { name, email, phone, phoneType, comments } = this.sta