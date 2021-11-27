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
        const { name, email, phone, phoneType, comments } = this.state;
        // Get Validation Errors - proceeding destructuring values from this.state.
        const validationErrors = this.validate(name, email);
        // If we have errors...
        if (validationErrors.length > 0) {
          this.setState({ validationErrors });
        } else {
          // Proceed normally
          // Create a new object for the contact us information.
          const contactUsInformation = {
            name,
            email,
            phone,
            phoneType,
            comments,
            submittedOn: new Date(),
          };
          console.log(contactUsInformation);
          // Reset the form state.
          this.setState({
            name: "",
            email: "",
            phone: "",
            phoneType: "",
            comments: "",
            validationErrors: [],
          });
        }
      };
      render() {
        const { name, email, phone, phoneType, comments, validationErrors } =
          this.state;
        return (
          <div>
            <h2>Contact Us</h2>
            {validationErrors.length > 0 && (
              <div>
                The following errors were found:
                <ul>
                  {validationErrors.map((error) => (
                    <li key={error}>{error}</li>
                  ))}
                </ul>
              </div>
            )}
            <form onSubmit={this.onSubmit}>
              <div>
                <label htmlFor="name">Name:</label>
                <input
                  id="name"
                  name="name"
                  type="text"
                  onChange={this.onChange}
                  value={name}
                />
              </div>
              <div>
                <label htmlFor="email">Email:</label>
                <input
                  id="email"
                  name="email"
                  type="text"
                  onChange={this.onChange}
                  value={email}
                />
              </div>
              <div>
                <label htmlFor="phone">Phone:</label>
                <input
                  id="phone"
                  name="phone"
                  type="text"
                  onChange={this.onChange}
                  value={phone}
                />
                <select name="phoneType" onChange={this.onChange} value={phoneType}>
                  <option value="">Select a phone type...</option>
                  {this.props.phoneTypes.map((phoneType) => (
                    <option key={phoneType}>{phoneType}</option>
                  ))}
                </select>
              </div>
              <div>
                <label htmlFor="comments">Comments:</label>
                <textarea
                  id="comments"
                  name="comments"
                  onChange={this.onChange}
                  value={comments}
                />
              </div>
              <div>
                <button>Submit</button>
              </div>
            </form>
          </div>
        );
      }
    }
    ContactUs.defaultProps = {
      phoneTypes: ["Home", "Work", "Mobile"],
    };
    export default ContactUs;

-   <span id="a2da">We can use validation libraries like `validate` to make our validation functions more complex.</span>

<!-- -->

    import isEmail from "validator/es/lib/isEmail";
      validate(name, email) {
        const validationErrors = [];
        if (!name) {
          validationErrors.push("Please provide a Name");
        }
        if (!email) {
          validationErrors.push("Please provide an Email");
        } else if (!isEmail(email)) {
          validationErrors.push("Please provide a valid Email");
        }
        return validationErrors;
      }

Note About Client-side vs server-side validation

-   <span id="5808">Server-side validation is not optional.</span>
-   <span id="3bb8">Tech-savvy users can manipulate client-side validations.</span>
-   <span id="311f">Sometimes the ‘best approach’ is to skip implementing validations on the client-side and rely completely on the server-side validation.</span>

------------------------------------------------------------------------

### Component Lifecycle

<figure><img src="https://cdn-images-1.medium.com/max/800/0*c24XQBvqBBg0Eztz" class="graf-image" /></figure>-   <span id="e1d9">Component Lifecycle is simply a way of describing the key moments in the lifetime of a component.</span>

1.  <span id="8e64">Loading (Mounting)</span>
2.  <span id="7e94">Updating</span>
3.  <span id="2cd3">Unloading (Unmounting) The lifecycle of a React component</span>

-   <span id="7740">Each `Class Component` has several `lifecycle methods` that you can add to run code at specific times.</span>
-   <span id="e7d0">`componentDidMount` : Method called after your component has been added to the component tree.</span>
-   <span id="6d92">`componentDidUpdate` : Method called after your component has been updated.</span>
-   <span id="9ee2">`componentWillUnmount` : Method called just before your component is removed from the component tree.</span>
-   <span id="7bd8">`Mounting`</span>

1.  <span id="6f9e">`constructor` method is called</span>
2.  <span id="e9c7">`render` method is called</span>
3.  <span id="eef3">React updates the `DOM`</span>
4.  <span id="19bb">`componentDidMount` is called</span>

-   <span id="85f1">`Updating`</span>
-   <span id="94f5">When component receives new `props`</span>

1.  <span id="e635">`render` method is called</span>
2.  <span id="70f9">React updates the `DOM`</span>
3.  <span id="9507">`componentDidUpdate` is called</span>

-   <span id="b00a">When `setState` is called</span>

1.  <span id="6864">`render` method is called</span>
2.  <span id="e13b">React updates the `DOM`</span>
3.  <span id="c459">`componentDidUpdate` is called</span>

-   <span id="bfdd">`Unmounting`</span>
-   <span id="10c1">The moment before a class component is removed from the component tree:</span>
-   <span id="c214">`componentDidMount` will be called. Avoiding the legacy lifecycle methods</span>
-   <span id="d438">Occasionally you will encounter some deprecated lifecycle methods:</span>
-   <span id="1f6b">UNSAFE\_componentWillMount</span>
-   <span id="48ac">UNSAFE\_componentWillReceiveProps</span>
-   <span id="df27">UNSAFE\_componentWillUpdate</span>
-   <span id="af07">Just know they will be removed soon from React’s API, peace. Using the class component lifecycle methods *Exercise done in sep. directory*</span>
-   <span id="344c">Assorted Notes:</span>
-   <span id="d6b1">Common Use for `componentDidMount` lifecycle method is for fetching data from an API.</span>

------------------------------------------------------------------------

—

### Notes

### React Context

-   <span id="e968">You can use `React Context` to pass data through a component tree without having to manually thread props.</span>
-   <span id="89d9">Convenient way to share & update `global data`. Creating a Context</span>

<!-- -->

    // PupContext.js
    import { createContext } from "react";
    const PupContext = createContext();
    export default PupContext;

-   <span id="a8bf">We use `React.createContext` to create context.</span>
-   <span id="98b9">Keep in mind if you invoke this method with aruguments, those arguments will be set as default context. Adding a Provider to the App component</span>
-   <span id="a919">In order to pass context over to child components we need to wrap them in a provider component.</span>
-   <span id="9afc">The provider component takes in a value property that points to the information that needs to be passed to the children.</span>

<!-- -->

    <MyContext.Provider value={/* some value */}>
      <ChildComponent />
    </MyContext.Provider>

Setting up a Consumer

    <MyContext.Consumer>
      {(value) => <Component value={value} />}
    </MyContext.Consumer>

-   <span id="2693">Keep in mind that `Context.Consumer` expects a function as a child.</span>
-   <span id="19fc">The function has a value prop passed in from `Context.Provider`</span>

------------------------------------------------------------------------

### Notes

### Redux Explained

-   <span id="eab4">JS Framework for managing the frontend state of a web application.</span>
-   <span id="3c8b">Gives us ability to store information in an organized manner in a web app and quickly retrieve that information from anywhere in the app.</span>
-   <span id="695d">`Redux`</span>
-   <span id="00d5">Client Side Data Management</span>
-   <span id="dd41">Controls “Frontend State”</span>
-   <span id="d828">NOT Your Database</span>
-   <span id="855a">NOT Component State</span>
-   <span id="4c1a">Just used for managing Data</span>

<figure><img src="https://cdn-images-1.medium.com/max/800/0*N7KFfhOZZ7UrY8s4" class="graf-image" /></figure>-   <span id="04c0">Visual of how an app without React manages it’s data.</span>
-   <span id="bae2">A lot of prop threading happening.</span>
-   <span id="989f">Data stored in a sep. location — `global data`. The Anatomy of Redux</span>
-   <span id="cd66">`Store`</span>
-   <span id="9453">Holds the Frontend State</span>
-   <span id="cea4">Provides an API for the Frontend State</span>
-   <span id="c653">`Action`</span>
-   <span id="7fb4">POJOs</span>
-   <span id="69a1">Outline Changes to Frontend State</span>
-   <span id="1a0a">`Reducers`</span>
-   <span id="a372">Functions</span>
-   <span id="8bb8">Make Changes to Frontend State Where did Redux come from?</span>
-   <span id="6d0b">There are three central philosophies of Redux:</span>

1.  <span id="12ac">`A Single Source of Truth` : state is stored in a POJO</span>
2.  <span id="d178">`State is Read Only` : State is immutable, modified by dispatching actions.</span>
3.  <span id="51c5">`Changes are Made with Pure Functions` : Reducers that receive the actions and return updated state are pure functions of the old state and action. When is it appropriate to use Redux?</span>

-   <span id="117f">When doing a project with simpler global state requirements, it may be better to choose React’s Context API over Redux.</span>
-   <span id="5d3d">Redux offers more flexibility and support for middleware along with richer developer tools. Vocabulary</span>
-   <span id="1ceb">`State`</span>
-   <span id="49e7">*Redux is a State Manager*</span>
-   <span id="5018">State is all the information stored by that program at a particular point in time.</span>
-   <span id="8fdb">Redux’s main job is to store the state and make it directly available to your entire app.</span>
-   <span id="8bbd">`Store`</span>
-   <span id="f027">*Redux stores state in a single store*.</span>
-   <span id="c97e">Redux store is a single JS object with a couple of methods (not a class!)</span>
-   <span id="199d">Methods include: `getState`, `dispatch(action)`, and `subscribe(listener)`</span>
-   <span id="8bcf">`Actions`</span>
-   <span id="2049">*Redux store is updated by dispatching actions*</span>
-   <span id="cbac">Action is just a POJO that includes a mandatory `type` property.</span>
-   <span id="f2d5">Contain info to update the store.</span>
-   <span id="1bd9">We dispatch actions in response to User actions or AJAX requests.</span>
-   <span id="1b78">`Pure Functions`</span>
-   <span id="c436">*Redux Reducers are Pure Functions*</span>
-   <span id="e204">Functions are pure when their behavior depends only on it’s arguments as has no side effects.</span>
-   <span id="450b">Simply takes in an argument and outputs a value.</span>
-   <span id="e146">`Reducer`</span>
-   <span id="9721">*Redux handles actions using reducers*</span>
-   <span id="c312">A function that is called each time an action is dispatched.</span>
-   <span id="84d8">Takes in an `action` and `current state`</span>
-   <span id="90a3">Required to be pure functions so their behavior is predictable.</span>
-   <span id="5c36">`Middleware`</span>
-   <span id="6b22">*Customize response to dispatch actions by using Middleware*</span>
-   <span id="9287">Middleware is an optional component of Redus that allows custom responses to dispatched actions.</span>
-   <span id="f953">Most common use is to dispatch async requests to a server.</span>
-   <span id="773e">`Time Traveling Dev Tools`</span>
-   <span id="d703">*Redux can time travel wow*</span>
-   <span id="7187">Time travel refers to Redux’s ability to revert to a previous state because reducers are all pure functions.</span>
-   <span id="ada3">`Thunks`</span>
-   <span id="ee0f">*Convenient format for taking async actions in Redux*</span>
-   <span id="586e">General concept in CS referring to a function who’s primary purpose is to call another function.</span>
-   <span id="6f45">Most commonly used to make async API requests.</span>

------------------------------------------------------------------------

### Flux and Redux

What is Flux?

-   <span id="06d1">Front-end application architecutre.</span>
-   <span id="8311">A pattern in which to structure an application.</span>
-   <span id="05e6">Unidirectional Data Flow — offers more predictability.</span>
-   <span id="751c">`Actions` : Begins the data flow of data, simple object that contains a type; type indicates the type of change to be performed.</span>
-   <span id="e8e7">`Dispatcher` : Mechanism for distributing actions to the store.</span>
-   <span id="af4f">`Store` : The entire state of the application, responsible for updating the state of your app.</span>
-   <span id="d7ff">`View` : Unit of code that's responsible for rendering the user interface. Used to re-render the application when actions and changes occur.</span>

<figure><img src="https://cdn-images-1.medium.com/max/800/0*ywV6dO4a4QcGJxK5" class="graf-image" /></figure>-   <span id="af94">Redux</span>

<figure><img src="https://cdn-images-1.medium.com/max/800/0*Nd73GjTY1PVQtjtQ" class="graf-image" /></figure>-   <span id="dc16">Library that facilitates the implementation of Flux.</span>
-   <span id="623a">Redux Three Principles</span>
-   <span id="2ac6">`Single Source of Truth`</span>
-   <span id="a2b9">`State is Read-Only`</span>
-   <span id="897b">`Only Pure Functions Change State`</span>

------------------------------------------------------------------------

### Store

-   <span id="cd1e">Simply an object that holds the application state wrapped in an API.</span>
-   <span id="f57c">`Three methods`:</span>
-   <span id="354c">`getState()` : Returns the store's current state.</span>
-   <span id="537c">`dispatch(action)` : Passes an action into the store's reducer to tell it what info to update.</span>
-   <span id="4539">`subscribe(callback)` : Registers a callback to be triggered whenever the store updates. Updating the Store</span>

<!-- -->

    store.dispatch(action);
    // Add Orange Action
    const addOrange = {
      type: "ADD_FRUIT",
      fruit: "orange",
    };
    // Reducer for Orange Action
    const fruitReducer = (state = [], action) => {
      switch (action.type) {
        case "ADD_FRUIT":
          return [...state, action.fruit];
        default:
          return state;
      }
    };
    // Run the Dispatch
    console.log(store.getState()); // []
    store.dispatch(addOrange);
    console.log(store.getState()); // [ 'orange' ]

Subscribing to the store

-   <span id="1a02">Whenever a store process a dispatch(), it triggers all its subscribers.</span>
-   <span id="e667">`Subscribers` : callbacks that can be added to the store via subscribe().</span>

<!-- -->

    const display = () => {
      console.log(store.getState());
    };
    const unsubscribeDisplay = store.subscribe(display);
    store.dispatch(addOrange); // [ 'orange', 'orange' ]
    // display will no longer be invoked after store.dispatch()
    unsubscribeDisplay();
    store.dispatch(addOrange); // no output

Reviewing a simple example

    // app.js
    const { createStore } = require("redux");
    // Define the store's reducer.
    const fruitReducer = (state = [], action) => {
      switch (action.type) {
        case "ADD_FRUIT":
          return [...state, action.fruit];
        default:
          return state;
      }
    };
    // Create the store.
    const store = createStore(fruitReducer);
    // Define an 'ADD_FRUIT' action for adding an orange to the store.
    const addOrange = {
      type: "ADD_FRUIT",
      fruit: "orange",
    };
    // Log to the console the store's state before and after
    // dispatching the 'ADD_FRUIT' action.
    console.log(store.getState()); // []
    store.dispatch(addOrange);
    console.log(store.getState()); // [ 'orange' ]
    // Define and register a callback to listen for store updates
    // and console log the store's state.
    const display = () => {
      console.log(store.getState());
    };
    const unsubscribeDisplay = store.subscribe(display);
    // Dispatch the 'ADD_FRUIT' action. This time the `display` callback
    // will be called by the store when its state is updated.
    store.dispatch(addOrange); // [ 'orange', 'orange' ]
    // Unsubscribe the `display` callback to stop listening for store updates.
    unsubscribeDisplay();
    // Dispatch the 'ADD_FRUIT' action one more time
    // to confirm that the `display` method won't be called
    // when the store state is updated.
    store.dispatch(addOrange); // no output

### Reducers

-   <span id="98f3">Reducer function receives the current `state` and `action`, updates the state appropriately based on the `action.type` and returns the following state.</span>
-   <span id="4cee">You can bundles different action types and ensuing logic by using a switch/case statement.</span>

<!-- -->

    const fruitReducer = (state = [], action) => {
      switch (action.type) {
        case "ADD_FRUIT":
          return [...state, action.fruit];
        case "ADD_FRUITS":
          return [...state, ...action.fruits];
        case "SELL_FRUIT":
          const index = state.indexOf(action.fruit);
          if (index !== -1) {
            // remove first instance of action.fruit
            return [...state.slice(0, index), ...state.slice(index + 1)];
          }
          return state; // if action.fruit is not in state, return previous state
        case "SELL_OUT":
          return [];
        default:
          return state;
      }
    };

Reviewing how Array\#slice works

    const fruits = ["apple", "apple", "orange", "banana", "watermelon"];
    // The index of the 'orange' element is 2.
    const index = fruits.indexOf("orange");
    // `...fruits.slice(0, index)` returns the array ['apple', 'apple']
    // `...fruits.slice(index + 1)` returns the array ['banana', 'watermelon']
    // The spread syntax combines the two array slices into the array
    // ['apple', 'apple', 'banana', 'watermelon']
    const newFruits = [...fruits.slice(0, index), ...fruits.slice(index + 1)];

-   <span id="f322">Approach that can be used to remove an element without mutating the original array. Avoiding state mutations</span>
-   <span id="f862">Your reducer must always return a new object if the state changes. GOOD</span>

<!-- -->

    const goodReducer = (state = { count: 0 }, action) => {
      switch (action.type) {
        case "INCREMENT_COUNTER":
          const nextState = Object.assign({}, state);
          nextState.count++;
          return nextState;
        default:
          return state;
      }
    };

BAD

    const badReducer = (state = { count: 0 }, action) => {
      switch (action.type) {
        case "INCREMENT_COUNTER":
          state.count++;
          return state;
        default:
          return state;
      }
    };

------------------------------------------------------------------------

### Actions

-   <span id="64b4">Actions are the only way to trigger changes to the store’s state. Using action creators</span>

<!-- -->

    const addOrange = {
      type: "ADD_FRUIT",
      fruit: "orange",
    };
    store.dispatch(addOrange);
    console.log(store.getState()); // [ 'orange' ]

-   <span id="c39d">fruit is the `payload key` and orange is the `state data`</span>
-   <span id="43e2">`Action Creators` : Functions created from extrapolating the creation of an action object.</span>

<!-- -->

    const addFruit = (fruit) => ({
      type: "ADD_FRUIT",
      fruit,
    });

-   <span id="11fd">Use parenthesis for implicit return value.</span>
-   <span id="eea8">We can now add whatever fruit we’d like.</span>

<!-- -->

    store.dispatch(addFruit("apple"));
    store.dispatch(addFruit("strawberry"));
    store.dispatch(addFruit("lychee"));
    console.log(store.getState()); // [ 'orange', 'apple', 'strawberry', 'lychee' ]

Preventing typos in action type string literals

    const ADD_FRUIT = "ADD_FRUIT";
    const ADD_FRUITS = "ADD_FRUITS";
    const SELL_FRUIT = "SELL_FRUIT";
    const SELL_OUT = "SELL_OUT";
    const addFruit = (fruit) => ({
      type: ADD_FRUIT,
      fruit,
    });
    const addFruits = (fruits) => ({
      type: ADD_FRUITS,
      fruits,
    });
    const sellFruit = (fruit) => ({
      type: SELL_FRUIT,
      fruit,
    });
    const sellOut = () => ({
      type: SELL_OUT,
    });

-   <span id="ae86">Using constant variables helps reduce simple typos in a reducer’s case clauses.</span>

------------------------------------------------------------------------

### Debugging Arrow Functions

-   <span id="43c6">It is important to learn how to use debugger statements with arrow functions to effectively debug Redux cycle. Understanding the limitations of implicit return values</span>

<!-- -->

    const addFruit = (fruit) => {
      return {
        type: "ADD_FRUIT",
        fruit,
      };
    };
    const addFruit = (fruit) => {
      debugger;
      return {
        type: "ADD_FRUIT",
        fruit,
      };
    };

-   <span id="2806">You must use explicit return statement arrow function to use a debugger.</span>

------------------------------------------------------------------------

### React Router Introduction

Now that you know how to render components in a React app, how do you handle rendering different components for different website pages? React Router is the answer!

Think of how you have created server-side routes in Express. Take the following URL and server-side route. Notice how the `/users/:userId` path corresponds with the `http://localhost:3000/users/2` URL to render a specific HTML page.

    // http://localhost:3000/users/2
    app.get('/users/:userId', (req, res) => {
      res.render('userProfile.pug');
    });

In the default React setup, you lose the ability to create routes in the same manner as in Express. This is what React Router aims to solve!

<a href="https://github.com/ReactTraining/react-router" class="markup--anchor markup--p-anchor">React Router</a> is a frontend routing library that allows you to control which components to display using the browser location. A user can also copy and paste a URL and email it to a friend or link to it from their own website.

When you finish this article, you should be able to use the following from the `react-router-dom` library:

-   <span id="e5d3">`<BrowserRouter>` to provide your application access to the `react-router-dom` library; and</span>
-   <span id="e1cd">`<Route>` to connect specific URL paths to specific components you want rendered; and</span>
-   <span id="bf15">`<Switch>` to wrap several `Route` elements, rendering only one even if several match the current URL; and</span>
-   <span id="0318">React Router’s `match` prop to access route path parameters.</span>

### Getting started with routing

Since you are writing single page apps, you don’t want to refresh the page each time you change the browser location. Instead, you want to update the browser location and your app’s response using JavaScript. This is known as client-side routing. You are using React, so you will use React Router to do this.

Create a simple react project template:

    npx create-react-app my-app --template @appacademy/simple

Then install React Router:

    npm install --save react-router-dom@^5.1.2

Now import `BrowserRouter` from `react-router-dom` in your entry file:

    import { BrowserRouter } from 'react-router-dom`;

### BrowserRouter

`BrowserRouter` is the primary component of the router that wraps your route hierarchy. It creates a React context that passes routing information down to all its descendent components. For example, if you want to give `<App>` and all its children components access to React Router, you would wrap `<App>` like so:

    // ./src/index.js
    import React from 'react';
    import ReactDOM from 'react-dom';
    import { BrowserRouter } from 'react-router-dom';
    import App from './App';

    const Root = () => {
      return (
        <BrowserRouter>
          <App />
        </BrowserRouter>
      );
    };

    ReactDOM.render(
      <React.StrictMode>
        <Root />
      </React.StrictMode>,
      document.getElementById('root'),
    );

Now you can route the rendering of certain components to certain URLs (i.e `https://www.website.com/profile`<a href="https://www.website.com/profile%29." class="markup--anchor markup--p-anchor">).</a>

### HashRouter

Alternatively, you could import and use `HashRouter` from `react-router-dom`. Links for applications that use `<HashRouter>` would look like `https://www.website.com/#/profile` (with an `#` between the domain and path).

You’ll focus on using the `<BrowserRouter>`.

### Creating frontend routes

React Router helps your React application render specific components based on the URL. The React Router component you’ll use most often is `<Route>`.

The `<Route>` component is used to wrap another component, causing that component to only be rendered if a certain URL is matched. The behavior of the `<Route>` component is controlled by the following props: `path`, `component`, `exact`, and `render` (optional).

Create a simple `Users` component that returns `<h1>This is the users index!</h1>`. Now let's refactor your `index.js` file so that you can create your routes within the component:

    // ./src/index.js
    import React from 'react';
    import ReactDOM from 'react-dom';
    import { BrowserRouter, Route } from 'react-router-dom';
    import App from './App';
    import Users from './Users';

    const Root = () => {
      return (
        <BrowserRouter>
          <div>
            {/* TODO: Routes */}
          </div>
        </BrowserRouter>
      );
    };

    ReactDOM.render(
      <React.StrictMode>
        <Root />
      </React.StrictMode>,
      document.getElementById('root'),
    );

Note that `BrowserRouter` can only have a single child component, so the snippet above wraps all routes within parent a `<div>` element. Now let's create some routes!

### component

Begin with the `component` prop. This prop takes a reference to the component to be rendered. Let's render your `App` component:

    const Root = () => {
      return (
        <BrowserRouter>
          <div>
            <Route component={App} />
          </div>
        </BrowserRouter>
      );
    };

Now you’ll need to connect a path to the component!

### path

The wrapped component will only be rendered when the path is matched. The path matches the URL when it matches some initial portion of the URL. For example, a path of `/` would match both of the following URLs: `/` and `/users`. (Because `/users` begins with a `/` it matches the path `/`)

    <Route path='/' component={App} />
    <Route path='/users' component={Users} />

Take a moment to navigate to `http://localhost:3000/users` to see how both the `App` component and `Users` component are rendering.

### exact

If this `exact` flag is set, the path will only match when it exactly matches the URL. Then browsing to the `/users` path would no longer match `/` and only the `Users` component will be rendered (instead of both the `App` component and `Users` component).

    <Route exact path='/' component={App} />
    <Route path='/users' component={Users} />

### render

This is an optional prop that takes in a function to be called. The function will be called when the path matches. The function’s return value is rendered. You could also define a functional component inside the `component` prop, but this results in extra, unnecessary work for React. The `render` prop is preferred for inline rendering of simple functional components.

The difference between using `component` and `render` is that `component` returns new JSX to be re-mounted every time the route renders, while `render` simply returns to JSX what will be mounted once and re-rendered. For any given route, you should only use either the `component` prop, or the `render` prop. If both are supplied, only the `component` prop will be used.

    // This inline rendering will work, but is unnecessarily slow.
    <Route path="/hello" component={() => <h1>Hello!</h1>} />

    // This is the preferred way for inline rendering.
    <Route path="/hello" render={() => <h1>Hello!</h1>} />

It can be helpful to use `render` instead of `component` in your `<Route>` when you need to pass props into the rendered component. For example, imagine that you needed to pass the `users` object as a prop to your `Users` component. Then you could pass in props from `Root` to `Users` by returning the `Users` component like so:

    // `users` to be passed as a prop:
    const users = {
      1: { name: 'Andrew' },
      2: { name: 'Raymond' }
    };

    <Route path="/users" render={() => <Users users={users} />} />

As a reminder, `BrowserRouter` can only have a single child component. That's why you have wrapped all your routes within parent a `<div>` element.

    const Root = () => {
      const users = {
        1: { name: 'Andrew' },
        2: { name: 'Raymond' }
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

With this `Root` component, you will always render the `<h1>Hi, I'm Root!</h1>`, regardless of the path. Because of the first `<Route>`, you will only render the `App` component if the path exactly matches `/`. Because of the second `<Route>`, you will only render the `Users` component if the path matches `/users`.

### Route path params

A component’s props can also hold information about a URL’s parameters. The router will match route segments starting at `:` up to the next `/`, `?`, or `#`. Those matched values are then passed to components via their props. Such segments are *wildcard* values that make up your route parameters.

For example, take the route below:

    <Route path="/users/:userId"
           render={(props) => <Profile users={users} {...props} />} />

The router would break down the full `/users/:userId/photos` path to two parts: `/users`, `:userId`.

The `Profile` component's props would have access to the `:userId` part of the `http://localhost:3000/users/:userId/photos` URL through the `props` with router parameter information. You would access the the `match` prop's parameters (`props.match.params`). If you are using the `render` prop of the `Route` component, make sure to spread the props back into the component if you want it to know about the "match" parameters.

    // Route's `render` prop allows you to pass the `users`
    // prop and spread the router `props`.
    render={(props) => <Profile users={users} {...props} />}

The `params` object would then have a property of `userId` which would hold the value of the `:userId` *wildcard* value. Let's render the `userId` parameter in a user profile component. Take a moment to create a `Profile.js` file with the following code:

    // ./src/Profile.js
    import React from "react";

    const Profile = (props) => (
      <div>
        The user's id is {props.match.params.userId}.
      </div>
    );

    export default Profile;

Notice how it uses the `match` prop to access the `:userId` parameter from the URL. You can use this wildcard to make and AJAX call to fetch the user information from the database and render the return data in the `Profile` component. Recall that your `Profile` component was rendered at the path `/users/:userId`. Thus you can use your `userId` parameters from `match.params` to fetch a specific user:

    // ./src/Profile.js
    import React from "react";

    const Profile = ({ users, match: { params } }) => {

      // In a real-world scenario, you'd make a call to an API to fetch the user,
      // instead of passing down and keying into a `users` prop.
      const user = users[params.userId];

      return (
        <div>
          The user's id is {params.userId} and the user's name is {user.name}.
        </div>
      );
    };

    export default Profile;

### Match

Now that you’ve seen your React Router’s `match` prop in action, let's go over more about <a href="https://reacttraining.com/react-router/web/api/Route/route-props" class="markup--anchor markup--p-anchor">route props</a>! React Router passes information to the components as route props, accessible to all components with access to the React Router. The three props it makes available are `location`, `match` and `history`. You've learned about `props.match.params`, but now let's review the other properties of the `match` prop!

This is an object that contains important information about how the current URL matches the route path. Here are some of the more useful keys on the `match` object:

-   <span id="1d2c">`isExact`: a boolean that tells you whether or not the URL exactly matches the path</span>
-   <span id="b558">`url`: the current URL</span>
-   <span id="ab28">`path`: the route path it matched against (without wildcards filled in)</span>
-   <span id="be5b">`params`: the matches for the individual wildcard segments, nested under their names</span>

When you use React Router, the browser `location` and `history` are a part of the state of your app. You can store information about which component should be displayed, which user profile you are currently viewing, or any other piece of state, in the browser location. You can then access that information from anywhere your Router props are passed to in your app.

Now that you’ve learned about parameters and route props, let’s revisit your `Root` component to add an `exact` flag to your `/users` route so that it does not render with your `/users/:userId` route. Your component should look something like this:

    const Root = () => {
      const users = {
        1: { name: 'Andrew' },
        2: { name: 'Raymond' }
      };

      return (
        <BrowserRouter>
          <h1>Hi, I'm Root!</h1>
          <div>
            <Route exact path="/" component={App} />
            <Route path="/hello" render={() => <h1>Hello!</h1>} />

            {/* Render the `Users` page if no ID is included. */}
            <Route exact path="/users" render={() => <Users users={users} />} />

            {/* Otherwise, render the profile page for that userId. */}
            <Route path="/users/:userId" component={(props) => <Profile users={users} {...props} />} />
          </div>
        </BrowserRouter>
      );
    };

### What you learned

In this article, you learned how to:

-   <span id="92fc">Use components from the React Router library; and</span>
-   <span id="19b5">Create routes to render specific components; and</span>
-   <span id="fc9d">Manage the order of rendered routes; and</span>
-   <span id="3281">Use the `exact` flag to ensure that a specific path renders a specific component; and</span>
-   <span id="3949">Use the React Router `match` prop to access Router params.</span>

------------------------------------------------------------------------

### React Router Navigation

Now that you know how to create front-end routes with React Router, you’ll need to implement a way for your users to navigate the routes! This is what using React Router’s `Link`, `NavLink`, `Redirect`, and `history` prop can help you do.

In this article, you’ll be working off of the demo project you built in the React Router Intro reading. When you finish this article, you should be able to use the following components from the `react-router-dom` library:

-   <span id="76bc">`<Link>` or `<NavLink>` to create links with absolute paths to routes in your application (like "/users/1"); and,</span>
-   <span id="cdc2">`<Redirect>` to redirect a user to another path (i.e. a login page when the user is not logged in); and</span>
-   <span id="d8a7">React Router’s `history` prop to update a browser's URL programmatically.</span>

### Adding links for navigation

React Router’s `<Link>` is one way to simplify navigation around your app. It issues an on-click navigation event to a route defined in your app's router. Using `<Link>` renders an anchor tag with a correctly set `href` attribute.

### Link

To use it, update your imports from the `react-router-dom` package to include `Link`:

    import { BrowserRouter, Route, Link } from 'react-router-dom';

Note that `<Link>` can take two props: `to` and `onClick`.

The `to` prop is a route location description that points to an absolute path, (i.e. `/users`). Add the following `Link` components in your `index.js` file above your routes:

    <Link to="/">App</Link>
    <Link to="/users">Users</Link>
    <Link to="/users/1">Andrew's Profile</Link>

The `onClick` prop is just like any other JSX click handler. You can write a function that takes in an `event` and handles it. Add the following `Link` before your routes and the following click handler function within your `Root` component:

    // Link with onClick prop
    <Link to="/" onClick={handleClick}>App with click handler</Link>

    // Click handler function
    const handleClick = () => {
      console.log('Thanks for clicking!')
    };

Now, test your routes and links! If you inspect the page, you’ll see that your links are now rendered as `<a>` elements. Notice that clicking the `App with click handler` link logs a message in your console while directing your browser to render the `App` component.

### NavLink

The `<NavLink>` works just like a `<Link>`, but with a little extra functionality. It has the ability to add extra styling when the path it links to matches the current path. This makes it an ideal choice for a navigation bar, hence the name. This styling can be controlled by three extra props: `activeClassName`, `activeStyle`, and `exact`. To begin using `NavLink`, update your imports from the `react-router-dom` package:

    import { BrowserRouter, Route, NavLink } from 'react-router-dom';

The `activeClassName` prop of the `NavLink` component allows you to set a CSS class name for styling the `NavLink` when its route is active. By default, the `activeClassName` is already set to `active`. This means that you simply need to add an `.active` class to your CSS file to add active styling to your link. A `NavLink` will be active if its `to` prop path matches the current URL.

Let’s change your “Users”, “Hello”, and “Andrew’s Profile” links to be different colors and have a larger font size when active.

    <NavLink to="/">App</NavLink>
    <NavLink activeClassName="red" to="/users">Users</NavLink>
    <NavLink activeClassName="blue" to="/hello">Hello</NavLink>
    <NavLink activeClassName="green" to="/users/1">Andrew's Profile</NavLink>
    <NavLink to="/" onClick={handleClick}>App with click handler</NavLink>

For example, this is what the rendered HTML `<a>` tag would look like when when the browser is navigated to the `/` path or the `/users` path:

    <!-- Navigated to the / path (the activeClassName
         prop is set to active by default) -->
    <a href="/" class="active">App</a>

    <!-- NOT navigated to the `/` path -->
    <a href="/">App</a>

    <!-- Navigated to the /users path (the activeClassName
         prop is manually set to red) -->
    <a href="/users" class="red">Users</a>

    <!-- NOT navigated to the `/users` path -->
    <a href="/users">Users</a>

Import `NavLink` into your `index.js` file and take a moment to update all your `Link` elements to `NavLink` elements. Set an `activeClassName` prop to an `active` class. Add the following `.active` class to your `index.css` file:

    .active {
      font-weight: bold;
    }

    .red {
      color: red;
      font-size: 30px;
    }

    .blue {
      color: blue;
      font-size: 30px;
    }

    .green {
      color: green;
      font-size: 30px;
    }

Test your styled links! Notice how the `App` and `App with click handler` links are always bolded. This is because all of your links include the `/` path, meaning that the link to `/` will be active when browsing to `/users` and `/users/1` because of how `users` and `users/1` are both prefaced by a `/`.

The `activeStyle` prop is a style object that will be applied inline to the `NavLink` when its `to` prop matches the current URL. Add the following `activeStyle` to your `App` link and comment out the `.active` class in your CSS file.

    <NavLink to="/" activeStyle={{ fontWeight: "bold" }}>App</NavLink>

The following html is rendered when at the `/` path:

    <a href="/" style="font-weight:bold;" class="active">App</a>

Notice how your `App with click handler` is not bolded anymore. This is because the default `active` class being applied does not have any CSS stylings set to the class. Uncomment your `.active` class in your CSS file to bring back bolding to this NavLink.

The `exact` prop is a boolean that defaults to `false`. If set to `true`, then the `activeStyle` and `activeClassName` props will only be applied when the current URL exactly matches the `to` prop. Update your `App` and `App with click handler` links with an `exact` prop set. Just like in your routes, you can use the `exact` flag instead of `exact={true}`.

    <NavLink to="/" exact={true} activeStyle={{ fontWeight: "bold" }}>App</NavLink>
    <NavLink to="/" exact onClick={handleClick}>App with click handler</NavLink>

Now your `App` and `App with click handler` links will only be bolded when you have navigated precisely to the `/` path.

### Switching between routes

You came across styling issues when the `/users` and `/users/1` paths matched the `/` path. Routing can have this issue as well. This is why you need to control the switching between routes.

React Router’s `<Switch>` component allows you to only render one `<Route>` even if several match the current URL. You can nest as many `Route`s as you wish between the opening and closing `Switch` tags, but only the first one that matches the current URL will be rendered.

This is particularly useful if you want a default component that will only render if none of our other routes match. View the example below. Without the Switch, `DefaultComponent` would always render. Since there isn't set a path in the `DefaultComponent` route, it will simply use the default path of `/`. Now the `DefaultComponent` will only render when neither of the preceding routes match.

    <Switch>
      <Route path="some/url" component={SomeComponent} />
      <Route path="some/other/url" component={OtherComponent} />
      <Route component={DefaultComponent} />
    </Switch>

Import `Switch` from `react-router-dom` and add `<Switch>` tags around your routes to take care of ordering and switching between your routes! Begin by adding the following route to the bottom of your routes to render that a `404: Page not found` message:

    <Route render={() => <h1>404: Page not found</h1>} />

This is what your `Root` component should look like at this point:

    const Root = () => {
      const users = [
        { name: 'andrew' },
        { name: 'raymond' }
      ];

      const handleClick = () => {
        console.log('Thanks for clicking!')
      };

      return (
        <BrowserRouter>
          <h1>Hi, I'm Root!</h1>

          <div>
            <NavLink to="/" exact={true} activeStyle={{ fontWeight: "bold" }}>App</NavLink>
            <NavLink activeClassName="red" to="/users">Users</NavLink>
            <NavLink activeClassName="blue" to="/hello">Hello</NavLink>
            <NavLink activeClassName="green" to="/users/1">Andrew's Profile</NavLink>
            <NavLink to="/" exact onClick={handleClick}>App with click handler</NavLink>

            <Switch>
              <Route path="/users/:userId" component={(props) => <Profile users={users} {...props} />} />
              <Route exact path="/users" render={() => <Users users={users} />} />
              <Route path="/hello" render={() => <h1>Hello!</h1>} />
              <Route exact path="/" component={App} />
              <Route render={() => <h1>404: Page not found</h1>} />
            </Switch>
          </div>
        </BrowserRouter>
      );
    };

Now you have control over the precedence of rendered components! Try navigating to `http://localhost:3000/asdf` or any other route you have not defined. The `<h1>404: Page not found</h1>` JSX of the last `<Route>` will be rendered whenever the browser attempts to visit an undefined route.

### Redirecting users

But what if you want to redirect users to a login page when they aren’t logged in? The `<Redirect>` component from React Router helps you redirect users!

The component takes only one prop: `to`. When it renders, it replaces the current URL with the value of its `to` prop. Typically you conditionally render `<Redirect>` to redirect the user away from some page you don't want them to visit. The example below checks whether there is a defined `currentUser` prop. If so, the `<Route>` will render the `Home` component. Otherwise, it will redirect the user to the `/login` path.

    <Route
      exact path="/"
      render={() => (this.props.currentUser ? <Home /> : <Redirect to="/login" />)}
    />

Note: you will learn how to use a more flexible auth pattern — don’t directly imitate this example.

### History

You know how to redirect users with a `<Redirect>` component, but what if you need to redirect users programmatically? You've learned about the React Router's `match` prop, but now let's go over another one of the <a href="https://reacttraining.com/react-router/web/api/Route/route-props" class="markup--anchor markup--p-anchor">route props</a>: `history`!

    // Pushing a new URL (and adding to the end of history stack):
    const handleClick = () => this.props.history.push('/some/url');

    // Replacing the current URL (won't be tracked in history stack):
    const redirect = () => this.props.history.replace('/some/other/url');

This prop lets you update the URL programmatically. For example, suppose you want to push a new URL when the user clicks a button. It has two useful methods:

-   <span id="31f3">`push` - This adds a new URL to the end of the history stack. That means that clicking the back button will take the browser to the previous URL. Note that pushing the same URL multiple times in a row will have no effect; the URL will still only show up on the stack once. In development mode, pushing the same URL twice in a row will generate a console warning. This warning is disabled in production mode.</span>
-   <span id="90c1">`replace` - This replaces the current URL on the history stack, so the back button won't take you to it. For example:</span>

### What you learned

In this article, you learned how to:

-   <span id="169b">Create navigation links for your route paths; and</span>
-   <span id="d108">Redirect users through using the `<Redirect>` component; and</span>
-   <span id="d090">Update a browser’s URL programmatically by using React Router’s `history` prop.</span>

------------------------------------------------------------------------

### React Router Nested Routes

Now you know how to create front-end routes and add navigation with React Router. When initializing Express projects, you declare static routes. Static routes are routes that are declared when an application is initialized. When using React Router in your application’s initialization, you can declare dynamic routes. React Router introduces dynamic routing, where your routes are created as your application is rendering. This allows you to create nested routes within components!

In this article, let’s dive into <a href="https://reacttraining.com/react-router/core/guides/philosophy/nested-routes" class="markup--anchor markup--p-anchor">nested routes</a>! When you finish the article, you should:

-   <span id="38ee">Describe what nested routes are; and</span>
-   <span id="0559">Be able to use React Router to create and navigate nested routes; and</span>
-   <span id="ce4a">Know how to use the React Router `match` prop to generate links and routes.</span>

### Why nested routes?

Let’s begin with why you might need nested routes. As you remember, you are using React to create a single-page application. This means that you’ll be organizing your application into different components and sub-components.

For example, imagine creating a simple front-end application with three main pages: a home welcome page (path of `/`), a users index page (path of `/users`), and user profile pages (path of `/users/:userId`). Now imagine if every user had links to separate `posts` and `photos` pages.

You can create those routes and links within the user profile component, instead of creating the routes and links where the main routes are defined.

### What are nested routes?

Now let’s dive into a user profile component to understand what are nested routes! Imagine you have a route in your application’s entry file to each user’s profile like so:

    <Route path="/users/:userId" component={Profile} />

This means that upon navigating to `http://localhost:3000/users/1`, you would render the following `Profile` component and the `userId` parameter within `props.match.params` would have the value of `"1"`.

    const Profile = (props) => {
      // Custom call to database to fetch a user by a user ID.
      const user = fetchUser(props.match.params.userId);
      const { name, id } = user;

      return (
        <div>
          <h1>Welcome to the profile of {name}!</h1>

          {/* Links to a specific user's posts and photos */}
          <Link to={`/users/${id}/posts`}>{name}'s Posts</Link>
          <Link to={`/users/${id}/photos`}>{name}'s Photos</Link>

          {/* Routes to a specific user's posts and photos */}
          <Route path='/users/:userId/posts' component={UserPosts} />
          <Route path='/users/:userId/photos' component={UserPhotos} />
        </div>
      );
    };

Since this route is not created until the `Profile` component is rendered, you are dynamically creating your nested `/users/:userId/posts` and `/users/:userId/photos` routes. Remember that your `match` prop also has other helpful properties. You can use `match.url` instead of `/users/${id}` in your profile links. You can also use `match.path` instead of `/users/:userId` in your profile routes. Remember that you can destructure `url`, `path`, and `params` from your `match` prop!

    // Destructure `match` prop
    const Profile = ({ match: { url, path, params }) => {

      // Custom call to database to fetch a user by a user ID.
      const user = fetchUser(params.userId);
      const { name, id } = user;

      return (
        <div>
          <h1>Welcome to the profile of {name}!</h1>

          {/* Replaced `/users/${id}` URL with `props.match.url` */}
          <Link to={`${url}/posts`}>{name}'s Posts</Link>
          <Link to={`${url}/photos`}>{name}'s Photos</Link>

          {/* Replaced `/users/:userId` path with `props.match.path` */}
          <Route path={`${path}/posts`} component={UserPosts} />
          <Route path={`${path}/photos`} component={UserPhotos} />
        </div>}
      );
    };

In tomorrow’s project, you’ll build a rainbow of routes as well as define nested routes. In the future, you may choose to implement nested routes to keep your application’s routes organized within related components.

### What you learned

In this article, you learned:

-   <span id="2378">What nested routes are; and</span>
-   <span id="e072">About creating and navigating nested routes with React Router; and</span>
-   <span id="c8b8">How to use the React Router props to generate nested links and routes.</span>

------------------------------------------------------------------------

### React Builds

A “build” is the process of converting code into something that can actually execute or run on the target platform. A “front-end build” is a process of preparing a front-end or client-side application for the browser.

With React applications, that means (at a minimum) converting JSX to something that browsers can actually understand. When using Create React App, the build process is automatically configured to do that and a lot more.

When you finish this article, you should be able to:

-   <span id="2448">Describe what front-end builds are and why they’re needed;</span>
-   <span id="efab">Describe at a high level what happens in a Create React App when you run `npm start`; and</span>
-   <span id="502f">Prepare to deploy a React application into a production environment.</span>

### Understanding front-end builds

The need for front-end builds predates React. Over the years, developers have found it helpful to extend the lowest common denominator version of JavaScript and CSS that they could use.

Sometimes developers extend JavaScript and CSS with something like <a href="https://www.typescriptlang.org/" class="markup--anchor markup--p-anchor">TypeScript</a> or <a href="https://sass-lang.com/" class="markup--anchor markup--p-anchor">Sass</a>. Using these non-standard languages and syntaxes require you to use a build process to convert your code into standard JavaScript and CSS that can actually run in the browser.

Browser-based applications also require a fair amount of optimization to deliver the best, or at least acceptable, experience to end users. Front-end build processes could be configured to lint code, run unit tests, optimize images, minify and bundle code, and more — all automatically at the press of a button (i.e. running a command at the terminal).

### JavaScript versions and the growth of front-end builds

Developers are generally an impatient lot. When new features are added to JavaScript, we don’t like to wait for browsers to widely support those features before we start to use them in our code. And we *really* don’t like when we have to support older, legacy versions of browsers.

In recent years, JavaScript has been updated on a yearly basis and browser vendors do a decent job of updating their browsers to support the new features as they’re added to the language. Years ago though, there was an infamous delay between versions 5 and 6 of JavaScript. It took *years* before ES6 (or ES2015 as it eventually was renamed to) to officially be completed and even longer before browsers supported all of its features.

In the period of time before ES2015 was broadly supported by browsers, developers used front-end builds to convert or *transpile* ES2015 features and syntax to an older version of the language that was more broadly supported by browsers (typically ES5). The transpilation from ES2015/ES6 down to ES5 was one of the major drivers for developers to add front-end builds to their client-side projects.

### Reviewing common terminology

When learning about front-end or React builds, you’ll encounter a lot of terminology that you may or may not be familiar with. Here’s some of the terminology that you’ll likely encounter:

Linting is process of using a tool to analyze your code to catch common programming errors, bugs, stylistic inconsistencies, and suspicious coding patterns. <a href="https://eslint.org/" class="markup--anchor markup--p-anchor">ESLint</a> is a popular JavaScript linting tool.

Transpilation is the process of converting source code, like JavaScript, from one version to another version. Usually this means converting newer versions of JavaScript, <a href="https://www.ecma-international.org/ecma-262/10.0/index.html" class="markup--anchor markup--p-anchor">ES2019</a> or <a href="https://tc39.es/ecma262/" class="markup--anchor markup--p-anchor">ES2021</a>, to a version that’s more widely supported by browsers, like <a href="http://www.ecma-international.org/ecma-262/6.0/" class="markup--anchor markup--p-anchor">ES2015</a>, or even <a href="https://www.ecma-international.org/ecma-262/5.1/" class="markup--anchor markup--p-anchor">ES5</a> or <a href="https://www.ecma-international.org/publications/files/ECMA-ST-ARCH/ECMA-262,%203rd%20edition,%20December%201999.pdf" class="markup--anchor markup--p-anchor">ES3</a> (if you need to support the browser that your parents or grandparents use).

Minification is the process of removing all unnecessary characters in your code (e.g. white space characters, new line characters, comments) to produce an overall smaller file. Minification tools will often also rename identifers in your code (i.e. parameter and variable names) in the quest for smaller and smaller file sizes. Source maps can also be generated to allow debugging tools to cross reference between minified code and the original source code.

Bundling is the process of combining multiple code files into a single file. Creating a bundle (or a handful of bundles) reduces the number of requests that a client needs to make to the server.

Tree shaking is the process of removing unused (or dead) code from your application before it’s bundled. Tree shaking external dependencies can sometimes have a dramatic positive impact on overall bundled file sizes.

### Configuration or code?

Front-end build tools have come and gone over the years; sometimes very quickly, which helped bring about the phenomenon known as <a href="https://sdtimes.com/softwaredev/is-the-javascript-fatigue-real/" class="markup--anchor markup--p-anchor">JavaScript fatigue</a>.

Configuration based tools allow you to create your build tasks by declaring (usually using JSON, XML, or YAML) what you want to be done, without explicitly writing every step in the process. In contrast, coding or scripting based tools allow you to, well, write code to create your build tasks. Configuration based tools *can* sometimes feel simpler to use while giving up some control (at least initially) while coding based tools *can* feel more familiar and predictable (since you’re describing tasks procedurally). Every generalization is false though (including this one), so there are plenty of exceptions.

<a href="https://gruntjs.com/" class="markup--anchor markup--p-anchor">Grunt</a> is a JSON configuration based task runner that can be used to orchestrate the various tasks that make up your front-end build. Grunt was very quickly supplanted by <a href="https://gulpjs.com/" class="markup--anchor markup--p-anchor">Gulp</a>, which allowed developers to write JavaScript to define front-end build tasks. After Gulp, the front-end tooling landscape became a bit more muddled. Some developers preferred the simplicity of using <a href="https://docs.npmjs.com/misc/scripts" class="markup--anchor markup--p-anchor">npm scripts</a> to define build tasks while others preferred the power of configuration based bundlers like <a href="https://webpack.js.org/" class="markup--anchor markup--p-anchor">webpack</a>.

### Babel and webpack (yes, that’s intentionally a lowercase ‘w’)

As front-end or client-side applications grew in complexity, developers found themselves wanting to leverage more advanced JavaScript features and newer syntax like classes, arrow functions, destructuring, async/await, etc. Using a code transpiler, like <a href="https://babeljs.io/" class="markup--anchor markup--p-anchor">Babel</a>, allows you to use all of the latest and greatest features and syntax without worrying about what browsers support what.

Module loaders and bundlers, like <a href="https://webpack.js.org/" class="markup--anchor markup--p-anchor">webpack</a>, also allowed developers to use JavaScript modules without requiring users to use a browser that natively supports ES modules. Also, module bundling (along with minification and tree-shaking) helps to reduce the bandwidth that’s required to deliver the assets for your application to the client.

\[Create React App\]\[cra\] uses webpack (along with Babel) under the covers to build your React applications. Even if you’re not using Create React App, webpack and Babel are still very popular choices for building React applications.

### Pulling back the covers (a bit) on the Create React App build process

Running an application created by Create React App using `npm start` can feel magical. Some stuff happens in the terminal and your application opens into your default browser. Even better, when you make changes to your application, your changes will (usually) automatically appear in the browser!

### The Create React App build process

At a high level, here’s what happens when you run `npm start`:

-   <span id="2808">Environment variables are loaded (more about this in a bit);</span>
-   <span id="f272">The list of browsers to support are checked (more about this too in a bit);</span>
-   <span id="71b2">The configured HTTP port is checked to ensure that it’s available;</span>
-   <span id="f826">The application compiler is configured and created;</span>
-   <span id="c605">`webpack-dev-server` is started;</span>
-   <span id="a696">`webpack-dev-server` compiles your application;</span>
-   <span id="c66e">The `index.html` file is loaded into the browser; and</span>
-   <span id="6add">A file watcher is started to watch your files, waiting for changes.</span>

### Ejecting

Create React App provides a script that you can run to “eject” your application from the Create React App tooling. When you eject your application, all of the hidden stuff is exposed so that you can review and customize it.

> *The need to customize Create React App rarely happens. Also, don’t eject an actual project as it’s a one-way trip! Once a Create React App project has been ejected, there’s no going back (though you could always undo the ejection process by reverting to an earlier commit if you’re using source control).*

To eject your application from Create React App, run the command `npm run eject`. You'll be prompted if you want to continue; type "y" to continue with the ejection process. Once the ejection process has completed, you can review the files that were previously hidden from you.

In the `package.json` file, you'll see the following npm scripts:

    {
      "scripts": {
        "start": "node scripts/start.js",
        "build": "node scripts/build.js",
        "test": "node scripts/test.js"
      }
    }

You can open the `./scripts/start.js` file to see the code that's executed when you run `npm start`.

If you’re curious about the webpack configuration, you can open and review the `./config/webpack.config.js`.

### Preparing to deploy a React application for production

Before you deploy your application to production, you’ll want to make sure that you’ve replaced static values in your code with environment variables and considered what browsers you need to support.

### Defining environment variables

Create React App supports defining environment variables in an `.env` file. To define an environment variable, add an `.env` file to your project and define one or more variables that start with the prefix `REACT_APP_`:

    REACT_APP_FOO: some value
    REACT_APP_BAR: another value

Environment variables can be used in code like this:

    console.log(process.env.REACT_APP_FOO);

You can also reference environment variables in your `index.html` like this:

    <title>%REACT_APP_BAR%</title>

> *Important: Environment variables are embedded into your HTML, CSS, and JavaScript bundles during the build process. Because of this, it’s* very important *to not store any secrets, like API keys, in your environment variables as anyone can view your bundled code in the browser by inspecting your files.*

### Configuring the supported browsers

In your project’s `package.json` file, you can see the list of targeted browsers:

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

Adjusting these targets affect how your code will be transpiled. Specifying older browser versions will result in your code being transpiled to older versions of JavaScript in order to be compatible with the specified browser versions. The `production` list specifies the browsers to target when creating a production build and the `development` list specifics the browsers to target when running the application using `npm start`.

The <a href="https://browserl.ist/" class="markup--anchor markup--p-anchor">browserl.ist</a> website can be used to see the browsers supported by your configured `browserslist`.

### Creating a production build

To create a production build, run the command `npm run build`. The production build process bundles React in production mode and optimizes the build for the best performance. When the command completes, you'll find your production ready files in the `build` folder.

Now your application is ready to be deployed!

> *For more information about how to deploy a Create React App project into production, see* <a href="https://facebook.github.io/create-react-app/docs/deployment" class="markup--anchor markup--blockquote-anchor"><em>this page</em></a> *in the official documentation.*

### What you learned

In this article, you learned how to:

-   <span id="1ff3">Describe what front-end builds are and why they’re needed;</span>
-   <span id="1fc3">Describe at a high level what happens in a Create React App when you run `npm start`; and</span>
-   <span id="6adc">Prepare to deploy a React application into a production environment.</span>

------------------------------------------------------------------------

### React Router Documentation

Now that you’ve had an introduction to React Router, feel free to explore the official documentation to learn more! As you become a full-fledged software engineer, remember that documentation is your friend. You can take a brief overview for now, as the documentation might include a lot of information at first. The more you learn about React, the more you should revisit the official documentation and learn!

### Setting up React Router

-   <span id="bfa4"><a href="https://reacttraining.com/react-router/web/guides/quick-start" class="markup--anchor markup--li-anchor">React Router Quick Start</a></span>
-   <span id="b0cb"><a href="https://reacttraining.com/react-router/web/api/HashRouter" class="markup--anchor markup--li-anchor">HashRouter</a></span>
-   <span id="f48b"><a href="https://reacttraining.com/react-router/web/api/BrowserRouter" class="markup--anchor markup--li-anchor">BrowserRouter</a></span>

### Routes and Links

-   <span id="72bd"><a href="https://reacttraining.com/react-router/web/api/Route" class="markup--anchor markup--li-anchor">Route</a></span>
-   <span id="e256"><a href="https://reacttraining.com/react-router/web/api/Link" class="markup--anchor markup--li-anchor">Link</a></span>
-   <span id="1d9d"><a href="https://reacttraining.com/react-router/web/api/NavLink" class="markup--anchor markup--li-anchor">NavLink</a></span>

### Switch and Redirect

-   <span id="5240"><a href="https://reacttraining.com/react-router/web/api/Switch" class="markup--anchor markup--li-anchor">Switch</a></span>
-   <span id="b405"><a href="https://reacttraining.com/react-router/web/api/Redirect" class="markup--anchor markup--li-anchor">Redirect</a></span>

### React Router Params (ownProps)

-   <span id="e0d6"><a href="https://reacttraining.com/react-router/web/api/history" class="markup--anchor markup--li-anchor">props.history</a></span>
-   <span id="5f4a"><a href="https://reacttraining.com/react-router/web/api/location" class="markup--anchor markup--li-anchor">props.location</a></span>
-   <span id="bd15"><a href="https://reacttraining.com/react-router/web/api/match" class="markup--anchor markup--li-anchor">props.match</a></span>

------------------------------------------------------------------------

### Rainbow Routes Project

Today you’re going to get our first experience using React Router. The goal is to create a basic app that displays the colors of the rainbow. This rainbow, however, has something special about it — some of the colors are nested within others.

### Phase 0: Setup

Begin by creating a new React project:

    npx create-react-app rainbow-routes --template @appacademy/simple

Now you’ll remove all the contents of your `src` and all the contents from your `public` directory to build the application architecture from scratch! After you have deleted all your files within the directories, create a new `index.html` file in your `public` folder. Use the `html:5` emmet shortcut to generate an HTML template. Title your page "Rainbow Routes" and create a `div` with an `id` of `root` in your DOM's `<body>` element. Create an `index.css` file in your `src` directory with the following code. Now let's create your entry file!

    h4 {
      color: darkblue;
      cursor: pointer;
    }

    h4:hover {
      text-decoration: underline;
    }

    #rainbow {
      position: absolute;
      top: 0;
      left: 300px;
    }

    h3 {
      position: absolute;
      top: 1px;
    }

    .red {
      background-color: red;
      width: 100px;
      height: 100px;
    }

    .orange {
      background-color: orange;
      width: 100px;
      height: 50px;
    }

    .yellow {
      background-color: yellow;
      width: 100px;
      height: 50px;
    }

    .green {
      background-color: green;
      width: 100px;
      height: 100px;
    }

    .blue {
      background-color: blue;
      width: 100px;
      height: 100px;
    }

    .indigo {
      background-color: mediumslateblue;
      width: 100px;
      height: 50px;
    }

    .violet {
      background-color: darkviolet;
      width: 100px;
      height: 100px;
    }

    a {
      display: block;
      margin-bottom: 10px;
    }

Create an `index.js` entry file in the `src` directory. At the top of the file, make sure to import `React` from the `react` package and `ReactDOM` from the `react-dom` package. Make sure to also import your the `index.css` file you just created! This will take care of styling your *rainbow routes*.

Now you can use the `ReactDOM.render()` method to render a `<Root />` component instead of the DOM element with an `id` of `root`. Lastly, wrap your render function with a `DOMContentLoaded` event listener, like so:

    document.addEventListener('DOMContentLoaded', () => {
      ReactDOM.render(
        <Root />,
        document.getElementById('root'),
      );
    });

Let’s create your `Root` component right in your entry file! Your `Root` component will take care of applying your `BrowserRouter` to the application. Applying the `BrowserRouter` to your `Root` component allows all the child components rendering within `<BrowserRouter>` tags to use and access the `Route`, `Link`, and `NavLink` components within the `react-router-dom` package.

    const Root = () => (
      // TODO: Apply BrowserRouter
      // TODO: Render rainbow
    );

Install the `react-router-dom` package:

    npm install react-router-dom@^5.0.0

Now import `BrowserRouter` from the `react-router-dom` package, like so:

    import { BrowserRouter } from 'react-router-dom';

You’re going to be rendering a lot of components, so let’s keep your `src` directory organized by creating a `components` directory within. Within your new `./src/components` directory, create a `Rainbow.js` file for your `Rainbow` component with the following code:

    // ./src/components/Rainbow.js
    import React from 'react';
    import { Route, Link, NavLink } from 'react-router-dom';

    const Rainbow = () => (
      <div>
        <h1>Rainbow Router!</h1>
        {/* Your links should go here */}

        <div id="rainbow">
          {/* Your routes should go here */}
        </div>
      </div>
    );

    export default Rainbow;

Your `Rainbow` component will act as the home page or default path (`/`) of your application. Import the `Rainbow` component into your entry file and have your `Root` component render `<Rainbow />` wrapped within `<BrowserRouter>` tags, like so:

    const Root = () => (
      <BrowserRouter>
        <Rainbow />
      </BrowserRouter>
    );

Within your `Rainbow` component, you'll be rendering `<NavLink>` and `<Route>` components to add different navigation paths to different components. Let's create all the components you will render!

Create files for the following components in your `./src/components` directory:

-   <span id="1c8e">`Red`</span>
-   <span id="a8dd">`Blue`</span>
-   <span id="6ca3">`Green`</span>
-   <span id="8e44">`Indigo`</span>
-   <span id="f8f2">`Orange`</span>
-   <span id="0f47">`Violet`</span>
-   <span id="8a89">`Yellow`</span>

Your `Red` and `Blue` components will look something like this:

    import React from 'react';
    import { Route, Link, NavLink } from 'react-router-dom';

    const Color = () => (
      <div>
        <h2 className="color">Color</h2>
        {/* Links here */}

        {/* Routes here */}
      </div>
    );

    export default Color;

Your `Green`, `Indigo`, `Orange`, `Violet`, and `Yellow` components will look something like this:

    import React from 'react';

    const Color = () => (
      <div>
        <h3 className="color">Color</h3>
      </div>
    );

    export default Color;

Now start your server and verify you can see the “Rainbow Router!” header from your `Rainbow` component. Currently there is no functionality. Let's fix that!

### Phase 1: Routes

As a reminder, wrapping the `Rainbow` component in `<BrowserRouter>` tags makes the router available to all descendent React Router components. Now open the `Rainbow.js` file. You're going to render some of your color components from here. Ultimately you want your routes to look like this.

URLComponents`/Rainbow/redRainbow -> Red/red/orangeRainbow -> Red -> Orange/red/yellowRainbow -> Red -> Yellow/greenRainbow -> Green/blueRainbow -> Blue/blue/indigoRainbow -> Blue -> Indigo/violetRainbow -> Violet`

This means that the `Red`, `Green`, `Blue`, and `Violet` components need to render in the `Rainbow` component, but only when you are at the corresponding URL. You'll do this with `Route` components. Begin by importing the `Red`, `Green`, `Blue`, and `Violet` components into your `Rainbow.js` file. Then add the necessary `Route` components inside the `div` with `id="rainbow"` in the `Rainbow` component. For example to render the `Red` component with the `/red` path, you would use the following `Route` component:

    <Route path="/red" component={Red} />

Test that your code works! Manually type in each URL you just created, and you should see the color component pop up. Remember, these are React Routes, so the paths you created will come after the `/`. For example, your default rainbow route will look like `http://localhost:3000/` while your red route will look like `http://localhost:3000/red`<a href="http://localhost:3000/red." class="markup--anchor markup--p-anchor">.</a>

You want to nest the `Orange` and `Yellow` components inside the `Red` component, and the `Indigo` component inside the `Blue` component. Remember to import your components to use them in a `Route` tag. You'll have to go add the corresponding `Route` tags to the `Red.js` and `Blue.js` files. Make sure to use the correct nested paths, such as `"/red/orange"` for the orange `Route`.

### Phase 2: Links

Manually navigating to our newly created routes is tiresome, so let’s add functionality to take care of this process for us. React Router provides the `Link` and `NavLink` components for this purpose.

Add `Link`s to the paths `/red`, `/green`, `/blue`, and `/violet` in the `Rainbow` component. For example, your red link should look like

    <Link to="/red">Red</NavLink>

When you are at `blue` you want to be able to get to `/blue/indigo`, and then back to `/blue`. Add the corresponding `Link`s to the `Blue` component like this:

    <Link to='/blue' >Blue only</Link>
    <Link to='/blue/indigo' >Add indigo</Link>

Similarly, add `Link`s to `/red`, `/red/orange` and `/red/yellow` to the `Red` component. Test all your links. Navigation is so much easier now!

### Phase 3: NavLinks

It would be nice if our links gave us some indication of which route you were at. Fortunately, React Router has a special component for that very purpose: `NavLink`. NavLinks get an extra CSS class when their `to` prop matches the current URL. By default this class is called `active`.

Go ahead and switch all your `Link`s to `NavLink`s. If you open the app you won't see any change yet. That's because you haven't added any special styling to the `active` class. Go ahead and open the `index.css` file. Create an `.active` class and add the line `font-weight: 700`. Now your active links will be bold. Isn't that nice!

The only problem is that now the `Blue only` link is active even when the path is `/blue/indigo`. That doesn't make a lot of sense. Let's add the `exact` flag to that link so it will only be active when its `to` exactly matches the current path. Now it should look like:

    <NavLink exact to="/blue">
      Blue only
    </NavLink>

Do the same for the `Red only` link. Everything should be working now.

### Phase 4 — Changing NavLink’s Active Class

You’ve already set up `NavLink` to bold the link text using the `.active` class in `src/index.css`. But what if you wanted this class to be something else? For instance, what if you want your main color links (Red, Green, Blue, Violet) to be styled differently when active than your sub-route links (Red Only, Add Orange, Add Yellow, etc.).

You can set the class that React Router sets to an active `NavLink` by adding the `activeClassName` prop.

For instance, when we are at a route matching the below `NavLink`'s `to` prop, the component will have a class of `.parent-active` applied:

    <NavLink to="/blue" activeClassName="parent-active" >
      Blue
    </NavLink>

This allows much more flexibility to style an active `NavLink`!

Using the example above, add an `activeClassName` prop to each of your `NavLink`s in `src/components/Rainbow.js`. Now, add some CSS styling for that class in your `src/index.css` to distinguish your main and your sub-route links.

Compare your work to the solution and make sure the behavior is the same. Time to celebrate! ✨ 🌈 ✨

You can also learn more about using the React Router at <a href="https://reacttraining.com/react-router/web/guides/quick-start" class="markup--anchor markup--p-anchor">reacttraining.com</a>!

------------------------------------------------------------------------

### Exploring React Builds Project

In this project, you’ll use Create React App to create a simple React application. You’ll experiment with some of the features that Create React App provides and deploy a production build of your application to a standalone Express application.

### Phase 0: Setup

Begin by using the <a href="https://github.com/facebook/create-react-app" class="markup--anchor markup--p-anchor">create-react-app</a> package to create a React application:

    npx create-react-app exploring-react-builds --template @appacademy/simple

> *Remember that using the* `create-react-app` *command initializes your project as a Git repository. If you use the* `ls -a` *to view the hidden files in your project, you'll see the *`.git` *file.*

Update the `App` component:

-   <span id="9186">Wrap the `<h1>` element with a `<div>` element; and</span>
-   <span id="5e97">Change the `<h1>` element content to something like "Exploring React Builds".</span>

<!-- -->

    // ./src/App.js

    import React from 'react';

    function App() {
      return (
        <div>
          <h1>Exploring React Builds</h1>
        </div>
      );
    }

    export default App;

### Phase 1: Using CSS modules

You’ve already seen an example of using the `import` keyword to import a stylesheet into a module so that it'll be included in your application build. That's the technique being used to include the global `index.css` stylesheet:

    // ./src/index.js

    import React from 'react';
    import ReactDOM from 'react-dom';
    import './index.css';
    import App from './App';

    ReactDOM.render(
      <React.StrictMode>
        <App />
      </React.StrictMode>,
      document.getElementById('root')
    );

You can also leverage <a href="https://github.com/css-modules/css-modules" class="markup--anchor markup--p-anchor">CSS modules</a> in your Create React App projects. CSS Modules scope stylesheet class names so that they are unique to a specific React component. This allows you to create class names without having to worry if they might collide with class names used in another component.

Add a new `css-modules` folder to the `src` folder. Within that folder, add the following files:

-   <span id="2912">`HeadingA.js`</span>
-   <span id="3aa3">`HeadingA.module.css`</span>
-   <span id="2ea3">`HeadingB.js`</span>
-   <span id="ca2b">`HeadingB.module.css`</span>

Then update the contents of each file to the following:

    // ./src/css-modules/HeadingA.js

    import React from 'react';
    import styles from './HeadingA.module.css';

    function HeadingA() {
      return (
        <h1 className={styles.heading}>Heading A</h1>
      );
    }

    export default HeadingA;

    /* ./src/css-modules/HeadingA.module.css */

    .heading {
      color: green;
    }

    // ./src/css-modules/HeadingB.js

    import React from 'react';
    import styles from './HeadingB.module.css';

    function HeadingB() {
      return (
        <h1 className={styles.heading}>Heading B</h1>
      );
    }

    export default HeadingB;

    /* ./src/css-modules/HeadingB.module.css */

    .heading {
      color: red;
    }

Notice how the `.heading` CSS class name is being used within each component to set the color of the `<h1>` element. For the `HeadingA` component, the color is `green`, and for the `HeadingB` component, the color is `red`. Using the file naming convention `[name].module.css` let's Create React App know that we want these stylesheets to be processed as CSS Modules. Using CSS Modules allows the `.heading` class name to be reused across components without any issue.

To see this feature in action, update your `App` component to render both of your new components:

    import React from 'react';
    import HeadingA from './css-modules/HeadingA';
    import HeadingB from './css-modules/HeadingB';

    function App() {
      return (
        <div>
          <h1>Exploring React Builds</h1>
          <HeadingA />
          <HeadingB />
        </div>
      );
    }

    export default App;

Then run your application (`npm start`) to see "Heading A" and "Heading B" displayed respectively in green and red. If you use the browser's developer tools to inspect "Heading A", you'll see that the `.heading` class name has been modified so that it's unique to the `HeadingA` component:

CSS Modules is an example of how a front-end build process can be used to modify code to enable a feature that’s not natively supported by browsers.

### Phase 2: Using an image in a component

Create React App configures webpack with support for loading images (as well as CSS, fonts, and other file types). What this means, for you as the developer, is that you can add an image file to your project, import it directly into a module, and render it in a React component.

Download any image of off the Web or <a href="https://appacademy-open-assets.s3-us-west-1.amazonaws.com/Modular-Curriculum/content/react-redux/topics/react-builds/assets/react-builds-cat.png" class="markup--anchor markup--p-anchor">click here</a> to download the below image.

<figure><img src="https://cdn-images-1.medium.com/max/800/0*233dNJ6vfgAmEVCD" class="graf-image" /></figure>Then within the `src` folder add a new folder named `image`. Within that folder add a new component file named `Image.js`. Also add your downloaded image file to the `image` folder (so it's a sibling to the `Image.js` file).

Update the contents of the `Image.js` file to this:

    // ./src/image/Image.js

    import React from 'react';
    import cat from './react-builds-cat.png';

    console.log(cat); // /static/media/react-builds-cat.45f7f4d2.png

    function Image() {
      // Import result is the URL of your image.
      return <img src={cat} alt="images/images/Cat" />;
    }

    export default Image;

You can import an image into a component using the `import` keyword. This tells webpack to include the image in the build. Notice that when you import an image into a module, you'll get a path to the image's location within the build. You can use this path to set the `src` attribute on an `<img>` element.

> *Be sure to update the image* `import` *statement to the correct file name if you're using your own image!*

Now update the `App` component to import and render the `Image` component:

    // ./src/App.js

    import React from 'react';
    import HeadingA from './css-modules/HeadingA';
    import HeadingB from './css-modules/HeadingB';
    import Image from './image/Image';

    function App() {
      return (
        <div>
          <h1>Exploring React Builds</h1>
          <HeadingA />
          <HeadingB />
          <Image />
        </div>
      );
    }

    export default App;

If you run your application (`npm start`) you'll see your image displayed on the page! You can also open your browser's developer tools and view the "Sources" for the current page. If you can expand the `localhost:3000` &gt; `static` &gt; `media` node on the left, you can see the image file that webpack copied to your build.

### Images in stylesheets

You can also reference images in your CSS files too. Add a CSS file named `Image.css` to the `./src/image` folder and update its contents to this:

    /* ./src/image/Image.css */

    .cat {
      background-image: url(./react-builds-cat.png);
      width: 400px;
      height: 400px;
    }

Then update the `Image` component to this:

    // ./src/image/Image.js

    import React from 'react';
    import './Image.css';
    import cat from './react-builds-cat.png';

    console.log(cat); // /static/media/react-builds-cat.45f7f4d2.png

    function Image() {
      return (
        <div>
          {/* Import result is the URL of your image. */}
          <img src={cat} alt="Cat" />
          <div className='cat'></div>
        </div>
      );
    }

    export default Image;

Now you’ll see the image displayed twice on the page!

### Phase 3: Updating the supported browsers (and its affect on code transpilation)

Earlier you learned about the `browerslist` setting in the `package.json` file and now adjusting these targets affect how your code will be transpiled:

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

The `production` list specifies the browsers to target when creating a production build and the `development` list specifics the browsers to target when running the application using `npm start`. Currently, you're targeting relatively recent versions of the major browsers when creating a development build. Targeting older browser versions results in your code being transpiled to an older version of JavaScript.

To experiment with this configuration option, let’s add a class component to the project. Add a new folder named `class-component` to the `src` folder. Within that folder, add a file named `ClassComponent.js` containing the following code:

    // ./src/class-component/ClassComponent.js

    import React from 'react';

    class ClassComponent extends React.Component {
      render() {
        return (
          <h1>Class Component</h1>
        );
      }
    }

    export default ClassComponent;

Don’t forget to update your `App` component to render the new component:

    // ./src/App.js

    import React from 'react';
    import HeadingA from './css-modules/HeadingA';
    import HeadingB from './css-modules/HeadingB';
    import Image from './image/Image';
    import ClassComponent from './class-component/ClassComponent';

    function App() {
      return (
        <div>
          <h1>Exploring React Builds</h1>
          <HeadingA />
          <HeadingB />
          <Image />
          <ClassComponent />
        </div>
      );
    }

    export default App;

Now run your application using `npm start`. Open your browser's developer tools and view the "Sources" for the current page. Expand the `localhost:3000` &gt; `static` &gt; `js` node on the left and select the `main.chunk.js` file. Press `CMD+F` on macOS or `CTRL+F` on Windows to search the file for "Class Component". Here's what the transpiled code looks like for the `ClassComponent` class:

    class ClassComponent extends react__WEBPACK_IMPORTED_MODULE_0___default.a.Component {
      render() {
        return /*#__PURE__*/react__WEBPACK_IMPORTED_MODULE_0___default.a.createElement("h1", {
          __self: this,
          __source: {
            fileName: _jsxFileName,
            lineNumber: 7,
            columnNumber: 7
          }
        }, "Class Component");
      }
    }

> *Have you wondered yet why you need to use the developer tools to view the bundles generated by Create React App? Remember that when you run* `npm start`*, Create React App builds your application using* `webpack-dev-server`*. To keep things as performant as possible, the bundles generated by* `webpack-dev-server` *are stored in memory instead of writing them to the file system.*

The JSX in the component’s `render` method has been converted to JavaScript but the `ClassComponent` ES2015 class is left alone. This makes sense though as JSX isn't natively supported by any browser while ES2015 classes have been natively supported by browsers for awhile now.

But what if you need to target a version of a browser that doesn’t support ES2015 classes? You can use the <a href="https://caniuse.com/#feat=es6-class" class="markup--anchor markup--p-anchor">“Can I use…”</a> website to see when browsers started supporting ES2105 (or ES6) classes. Starting with version 49, Chrome natively supported classes. But imagine that you need to support Chrome going back to version 30, a version of Chrome that doesn’t support classes.

Change the `browserslist.development` property in the `package.json` file to this:

    {
      "browserslist": {
        "production": [
          ">0.2%",
          "not dead",
          "not op_mini all"
        ],
        "development": [
          "chrome >= 30",
          "last 1 firefox version",
          "last 1 safari version"
        ]
      }
    }

The query `chrome >= 30` specifies that you want to target Chrome version 30 or newer.

> *The* <a href="https://browserl.ist/" class="markup--anchor markup--blockquote-anchor"><em>browserl.ist</em></a> *website can be used to see the browsers supported by your configured* `browserslist`*.*

Stop your application if it’s currently running. Delete the `./node_modules/.cache` folder and run `npm start` again. Then view the `main.chunk.js` bundle again in the developer tools:

<figure><img src="https://cdn-images-1.medium.com/max/800/0*TKBUkpbL5aSm5PTQ" class="graf-image" /></figure>Now your ES2015 class component is being converted to a constructor function! Here’s the transpiled code for reference:

    var ClassComponent = /*#__PURE__*/function (_React$Component) {
      Object(_Users_jameschurchill_Documents_GitHub_Modular_Curriculum_content_react_redux_topics_react_builds_projects_exploring_react_builds_solution_node_modules_babel_preset_react_app_node_modules_babel_runtime_helpers_esm_inherits__WEBPACK_IMPORTED_MODULE_2__["default"])(ClassComponent, _React$Component);

      var _super = Object(_Users_jameschurchill_Documents_GitHub_Modular_Curriculum_content_react_redux_topics_react_builds_projects_exploring_react_builds_solution_node_modules_babel_preset_react_app_node_modules_babel_runtime_helpers_esm_createSuper__WEBPACK_IMPORTED_MODULE_3__["default"])(ClassComponent);

      function ClassComponent() {
        Object(_Users_jameschurchill_Documents_GitHub_Modular_Curriculum_content_react_redux_topics_react_builds_projects_exploring_react_builds_solution_node_modules_babel_preset_react_app_node_modules_babel_runtime_helpers_esm_classCallCheck__WEBPACK_IMPORTED_MODULE_0__["default"])(this, ClassComponent);

        return _super.apply(this, arguments);
      }

      Object(_Users_jameschurchill_Documents_GitHub_Modular_Curriculum_content_react_redux_topics_react_builds_projects_exploring_react_builds_solution_node_modules_babel_preset_react_app_node_modules_babel_runtime_helpers_esm_createClass__WEBPACK_IMPORTED_MODULE_1__["default"])(ClassComponent, [{
        key: "render",
        value: function render() {
          return /*#__PURE__*/react__WEBPACK_IMPORTED_MODULE_4___default.a.createElement("h1", {
            __self: this,
            __source: {
              fileName: _jsxFileName,
              lineNumber: 7,
              columnNumber: 7
            }
          }, "Class Component");
        }
      }]);

      return ClassComponent;
    }(react__WEBPACK_IMPORTED_MODULE_4___default.a.Component);

Luckily it’s very rare that you’ll need to read the code in your generated bundles. webpack, by default, is configured to generate sourcemaps. Sourcemaps are a mapping of the code in a generated file, like a bundle file, to the original source code. This gives you access to your original source code in the browser’s developer tools:

You can even set a breakpoint in your source within the developer tools to stop execution on a specific line of code!

### Phase 4: Adding environment variables

Earlier you learned that Create React App supports defining environment variables in an `.env` file. This gives you a convenient way to avoid hard coding values that vary across environments.

Let’s experiment with this feature so that you can see how the Create React App build process embeds environment variables into your HTML, CSS, and JavaScript bundles.

Add an `.env` file to the root of your Create React App project. Define an environment variable named `REACT_APP_TITLE`:

    REACT_APP_TITLE=Exploring React Builds

Remember that environment variables need to be prefixed with `REACT_APP_` for Create React App to process them. After defining your environment variable, you can refer to it within JSX using an expression and `process.env`:

    // ./src/App.js

    import React from 'react';
    import HeadingA from './css-modules/HeadingA';
    import HeadingB from './css-modules/HeadingB';
    import Image from './image/Image';
    import ClassComponent from './class-component/ClassComponent';

    function App() {
      return (
        <div>
          <h1>{process.env.REACT_APP_TITLE}</h1>
          <HeadingA />
          <HeadingB />
          <Image />
          <ClassComponent />
        </div>
      );
    }

    export default App;

Environment variables can also be referred to in regular JavaScript code:

    console.log(process.env.REACT_APP_TITLE);

You can also reference environment variables in your `./public/index.html` file like this:

    <!DOCTYPE html>
    <html lang="en">
      <head>
        <meta charset="utf-8" />
        <title>%REACT_APP_TITLE%</title>
      </head>
      <body>
        <div id="root"></div>
      </body>
    </html>

Run your application again using `npm start`. Open your browser's developer tools and view the "Sources" for the current page. Expand the `localhost:3000` node on the left and select `(index)`. Notice that the text `%REACT_APP_TITLE%` within the `<title>` element has been converted to the text literal `Exploring React Builds`:

If you expand the `localhost:3000` &gt; `static` &gt; `js` node on the left and select the `main.chunk.js` file, you can see how the `App` component's JSX has been converted to JavaScript:

Here’s a closer look at the relevant `React.createElement` method call:

    /*#__PURE__*/react__WEBPACK_IMPORTED_MODULE_0___default.a.createElement("h1", {
        __self: this,
        __source: {
          fileName: _jsxFileName,
          lineNumber: 10,
          columnNumber: 7
        }
      }, "Exploring React Builds")

Again, notice how the environment variable has been replaced with a text literal. This has important security implications for you to consider. Because environment variables are embedded into your HTML, CSS, and JavaScript bundles during the build process, it’s *very important* to not store any secrets, like API keys, in your environment variables. Remember, anyone can view your bundled code in the browser by inspecting your files!

### Phase 5: Deploying a production build

In the last phase of this project, let’s add routing to the React application, create a production build, and deploy the build to an Express application!

### Adding routing

To add React Router to the application, start by installing the `react-router-dom` npm package:

    npm install react-router-dom@^5.0.0

Then update the `App` component to this code:

    // ./src/App.js

    import React from 'react';
    import {
      BrowserRouter,
      Switch,
      Route,
      Link
    } from 'react-router-dom';
    import HeadingA from './css-modules/HeadingA';
    import HeadingB from './css-modules/HeadingB';
    import Image from './image/Image';
    import ClassComponent from './class-component/ClassComponent';

    function App() {
      return (
        <BrowserRouter>
          <div>
            <h1>{process.env.REACT_APP_TITLE}</h1>
            <nav>
              <ul>
                <li>
                  <Link to="/">Home</Link>
                </li>
                <li>
                  <Link to="/image">Image</Link>
                </li>
                <li>
                  <Link to="/class-component">Class Component</Link>
                </li>
              </ul>
            </nav>
            <Switch>
              <Route path="/image">
                <Image />
              </Route>
              <Route path="/class-component">
                <ClassComponent />
              </Route>
              <Route path="/">
                <HeadingA />
                <HeadingB />
              </Route>
            </Switch>
          </div>
        </BrowserRouter>
      );
    }

    export default App;

Be sure to run and test your application to ensure that the defined routes work as expected:

-   <span id="151a">`/` - Should display the `HeadingA` and `HeadingB` components;</span>
-   <span id="1e2b">`/image` - Should display the `Image` component; and</span>
-   <span id="7f3a">`/class-component` - Should display the `ClassComponent` component.</span>

### Creating a production build

To create a production build, run the command `npm run build` from the root of your project. The output in the terminal should look something like this:

    > solution@0.1.0 build [absolute path to your project]
    > react-scripts build

    Creating an optimized production build...
    Compiled successfully.

    File sizes after gzip:

      47.83 KB  build/static/js/2.722c16c4.chunk.js
      773 B     build/static/js/runtime-main.b7d1e5ee.js
      745 B     build/static/js/main.12299197.chunk.js
      197 B     build/static/css/main.e9a0d1f8.chunk.css

    The project was built assuming it is hosted at /.
    You can control this with the homepage field in your package.json.

    The build folder is ready to be deployed.
    You may serve it with a static server:

      npm install -g serve
      serve -s build

    Find out more about deployment here:

      bit.ly/CRA-deploy

Ignore the comments about using `serve` to deploy your application (i.e. `npm install -g serve` and `serve -s build`). In the next step, you'll create a simple Express application to server your React application.

### Serving a React application using Express

Create a new folder for your Express application outside of the Create React App project folder.

> *For example, from the root of your project, use* `cd ..` *to go up a level and then create a new folder named* `express-server` *by running the command* `mkdir express-server`*. This makes the* `express-server` *folder a sibling to your Create React App project folder.*

Browse into the `express-server` folder and initialize it to use npm (i.e. `npm init -y`). Then install Express by running the command `npm install express@^4.0.0`.

App a file named `app.js` with the following contents:

    // ./app.js

    const express = require('express');
    const path = require('path');

    const app = express();

    app.use(express.static(path.join(__dirname, 'public')));

    app.get('*', function(req, res) {
      res.sendFile(path.join(__dirname, 'public', 'index.html'));
    });

    const port = 9000;

    app.listen(port, () => console.log(`Listening on port ${port}...`));

This simple Express application will:

-   <span id="31ba">Attempt to match incoming requests to static files located in the `public` folder; and</span>
-   <span id="16e6">If a matching static file isn’t found, then the `./public/index.html` file will be served for all other requests.</span>

Now add a folder named `public` to the root of your Express project. Copy the files from the `build` folder in your Create React App project to the `public` folder in the Express application project. Then run your application using the command `node app.js`.

Open a browser and browse to the URL `http://localhost:9000/`. You should see your React application served from your Express application! Be sure to click the navigation links to verify that all of your configured routes work as expected.

Also, because you configured Express to serve the `./public/index.html` file for any request that doesn't match a static file, you can "deep link" to any of your React application's routes:

-   <span id="58e7"><a href="http://localhost:9000/image" class="markup--anchor markup--li-anchor">http://localhost:9000/image</a></span>
-   <span id="3fa9"><a href="http://localhost:9000/class-component" class="markup--anchor markup--li-anchor">http://localhost:9000/class-component</a></span>

*More content at* <a href="http://plainenglish.io/" class="markup--anchor markup--p-anchor"><strong><em>plainenglish.io</em></strong></a>

By <a href="https://medium.com/@bryanguner" class="p-author h-card">Bryan Guner</a> on [July 15, 2021](https://medium.com/p/1965dcde8d4f).

<a href="https://medium.com/@bryanguner/react-in-depth-1965dcde8d4f" class="p-canonical">Canonical link</a>

Exported from [Medium](https://medium.com) on August 31, 2021.

A Quick Guide to Big-O Notation, Memoization, Tabulation, and Sorting Algorithms by Example
===========================================================================================

Curating Complexity: A Guide to Big-O Notation

------------------------------------------------------------------------

### A Quick Guide to Big-O Notation, Memoization, Tabulation, and Sorting Algorithms by Example

<figure><img src="https://cdn-images-1.medium.com/max/800/0*yjlSk3T9c2_14in1.png" class="graf-image" /></figure>***Curating Complexity: A Guide to Big-O Notation***

<a href="https://replit.com/@bgoonz/Medium-article-comp-complex" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://replit.com/@bgoonz/Medium-article-comp-complex"><strong>Medium-article-comp-complex</strong><br />
<em>A Node.js repl by bgoonz</em>replit.com</a><a href="https://replit.com/@bgoonz/Medium-article-comp-complex" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

-   <span id="b70f">Why is looking at runtime not a reliable method of calculating time complexity?</span>
-   <span id="2b21">Not all computers are made equal( some may be stronger and therefore boost our runtime speed )</span>
-   <span id="1e1a">How many background processes ran concurrently with our program that was being tested?</span>
-   <span id="1cad">We also need to ask if our code remains performant if we increase the size of the input.</span>
-   <span id="3cb7">The real question we need to answering is: `How does our performance scale?`.</span>

### big ‘O’ notation

-   <span id="9b21">Big O Notation is a tool for describing the efficiency of algorithms with respect to the size of the input arguments.</span>
-   <span id="c0e6">Since we use mathematical functions in Big-O, there are a few big picture ideas that we’ll want to keep in mind:</span>
-   <span id="2e86">The function should be defined by the size of the input.</span>
-   <span id="07b0">`Smaller` Big O is better (lower time complexity)</span>
-   <span id="f1b0">Big O is used to describe the worst case scenario.</span>
-   <span id="e11f">Big O is simplified to show only its most dominant mathematical term.</span>

### Simplifying Math Terms

-   <span id="64a4">We can use the following rules to simplify the our Big O functions:</span>
-   <span id="a2c2">`Simplify Products` : If the function is a product of many terms, we drop the terms that don't depend on n.</span>
-   <span id="b058">`Simplify Sums` : If the function is a sum of many terms, we drop the non-dominant terms.</span>
-   <span id="eb32">`n` : size of the input</span>
-   <span id="c042">`T(f)` : unsimplified math function</span>
-   <span id="7b41">`O(f)` : simplified math function.</span>

`Putting it all together`

<figure><img src="https://cdn-images-1.medium.com/max/800/1*TT8uuv1x3nmGUw5rvtoZ8A.png" class="graf-image" /></figure>-   <span id="d18b">First we apply the product rule to drop all constants.</span>
-   <span id="4335">Then we apply the sum rule to select the single most dominant term.</span>

------------------------------------------------------------------------

### Complexity Classes

Common Complexity Classes

#### There are 7 major classes in Time Complexity

<figure><img src="https://cdn-images-1.medium.com/max/800/1*6zKhmJoHkvDbrd8jfUDf3A.png" class="graf-image" /></figure>#### `O(1) Constant`

> **The algorithm takes roughly the same number of steps for any input size.**

#### `O(log(n)) Logarithmic`

> **In most cases our hidden base of Logarithmic time is 2, log complexity algorithm’s will typically display ‘halving’ the size of the input (like binary search!)**

#### `O(n) Linear`

> **Linear algorithm’s will access each item of the input “once”.**

### `O(nlog(n)) Log Linear Time`

> **Combination of linear and logarithmic behavior, we will see features from both classes.**

> Algorithm’s that are log-linear will use **both recursion AND iteration.**

### `O(nc) Polynomial`

> **C is a fixed constant.**

### `O(c^n) Exponential`

> **C is now the number of recursive calls made in each stack frame.**

> **Algorithm’s with exponential time are VERY SLOW.**

------------------------------------------------------------------------

### Memoization

-   <span id="b3b0">Memoization : a design pattern used to reduce the overall number of calculations that can occur in algorithms that use recursive strategies to solve.</span>
-   <span id="2583">MZ stores the results of the sub-problems in some other data structure, so that we can avoid duplicate calculations and only ‘solve’ each problem once.</span>
-   <span id="65c9">Two features that comprise memoization:</span>

1.  <span id="b2d2">FUNCTION MUST BE RECURSIVE.</span>
2.  <span id="91a3">Our additional Data Structure is usually an object (we refer to it as our memo… or sometimes cache!)</span>

<figure><img src="https://cdn-images-1.medium.com/max/800/1*4U79jBMjU2wKE_tyYcD_3A.png" class="graf-image" /></figure><figure><img src="https://cdn-images-1.medium.com/max/800/1*Qh42KZgcCxmVt6WrTasCVw.png" class="graf-image" /></figure>### Memoizing Factorial

Our memo object is *mapping* out our arguments of factorial to it’s return value.

-   <span id="854a">Keep in mind we didn’t improve the speed of our algorithm.</span>

### Memoizing Fibonacci

<figure><img src="https://cdn-images-1.medium.com/max/800/0*2XaPj7UGKZYFjYhb" class="graf-image" /></figure>-   <span id="5be6">Our time complexity for Fibonacci goes from O(2^n) to O(n) after applying memoization.</span>

### The Memoization Formula

> *Rules:*

1.  <span id="b3f0">*Write the unoptimized brute force recursion (make sure it works);*</span>
2.  <span id="b36e">*Add memo object as an additional argument .*</span>
3.  <span id="f81f">*Add a base case condition that returns the stored value if the function’s argument is in the memo.*</span>
4.  <span id="1b0f">*Before returning the result of the recursive case, store it in the memo as a value and make the function’s argument it’s key.*</span>

#### Things to remember

1.  <span id="bc4a">*When solving DP problems with Memoization, it is helpful to draw out the visual tree first.*</span>
2.  <span id="7bb1">*When you notice duplicate sub-tree’s that means we can memoize.*</span>

------------------------------------------------------------------------

### Tabulation

#### Tabulation Strategy

> Use When:

-   <span id="f5b0">**The function is iterative and not recursive.**</span>
-   <span id="015c">*The accompanying DS is usually an array.*</span>

#### Steps for tabulation

-   <span id="8918">*Create a table array based off the size of the input.*</span>
-   <span id="b4e7">*Initialize some values in the table to ‘answer’ the trivially small subproblem.*</span>
-   <span id="072e">*Iterate through the array and fill in the remaining entries.*</span>
-   <span id="192e">*Your final answer is usually the last entry in the table.*</span>

------------------------------------------------------------------------

### Memo and Tab Demo with Fibonacci

> *Normal Recursive Fibonacci*

    function fibonacci(n) {
      if (n <= 2) return 1;
      return fibonacci(n - 1) + fibonacci(n - 2);
    }

> *Memoization Fibonacci 1*

> *Memoization Fibonacci 2*

> *Tabulated Fibonacci*

### Example of Linear Search

-   <span id="84b2">*Worst Case Scenario: The term does not even exist in the array.*</span>
-   <span id="30dc">*Meaning: If it doesn’t exist then our for loop would run until the end therefore making our time complexity O(n).*</span>

------------------------------------------------------------------------

### Sorting Algorithms

### Bubble Sort

`Time Complexity`: Quadratic O(n^2)

-   <span id="ce1e">The inner for-loop contributes to O(n), however in a worst case scenario the while loop will need to run n times before bringing all n elements to their final resting spot.</span>

`Space Complexity`: O(1)

-   <span id="664f">Bubble Sort will always use the same amount of memory regardless of n.</span>

<figure><img src="https://cdn-images-1.medium.com/max/800/0*Ck9aeGY-d5tbz7dT" class="graf-image" /></figure>-   <span id="4115">The first major sorting algorithm one learns in introductory programming courses.</span>
-   <span id="ecd4">Gives an intro on how to convert unsorted data into sorted data.</span>

> It’s almost never used in production code because:

-   <span id="3cb1">*It’s not efficient*</span>
-   <span id="4eac">*It’s not commonly used*</span>
-   <span id="d730">*There is stigma attached to it*</span>
-   <span id="8da7">`Bubbling Up`* : Term that infers that an item is in motion, moving in some direction, and has some final resting destination.*</span>
-   <span id="8447">*Bubble sort, sorts an array of integers by bubbling the largest integer to the top.*</span>

<!-- -->

-   <span id="dcd2">*Worst Case & Best Case are always the same because it makes nested loops.*</span>
-   <span id="9a6a">*Double for loops are polynomial time complexity or more specifically in this case Quadratic (Big O) of: O(n²)*</span>

### Selection Sort

`Time Complexity`: Quadratic O(n^2)

-   <span id="646d">Our outer loop will contribute O(n) while the inner loop will contribute O(n / 2) on average. Because our loops are nested we will get O(n²);</span>

`Space Complexity`: O(1)

-   <span id="45ae">Selection Sort will always use the same amount of memory regardless of n.</span>

<figure><img src="https://cdn-images-1.medium.com/max/800/0*AByxtBjFrPVVYmyu" class="graf-image" /></figure>-   <span id="c618">Selection sort organizes the smallest elements to the start of the array.</span>

<figure><img src="https://cdn-images-1.medium.com/max/800/0*GeYNxlRcbt2cf0rY" class="graf-image" /></figure>Summary of how Selection Sort should work:

1.  <span id="2277">*Set MIN to location 0*</span>
2.  <span id="c76c">*Search the minimum element in the list.*</span>
3.  <span id="79d3">*Swap with value at location Min*</span>
4.  <span id="4ede">*Increment Min to point to next element.*</span>
5.  <span id="a649">*Repeat until list is sorted.*</span>

### Insertion Sort

`Time Complexity`: Quadratic O(n^2)

-   <span id="95ea">Our outer loop will contribute O(n) while the inner loop will contribute O(n / 2) on average. Because our loops are nested we will get O(n²);</span>

`Space Complexity`: O(n)

-   <span id="f6fa">Because we are creating a subArray for each element in the original input, our Space Comlexity becomes linear.</span>

<figure><img src="https://cdn-images-1.medium.com/max/800/0*gbNU6wrszGPrfAZG" class="graf-image" /></figure>### Merge Sort

`Time Complexity`: Log Linear O(nlog(n))

-   <span id="44b2">Since our array gets split in half every single time we contribute O(log(n)). The while loop contained in our helper merge function contributes O(n) therefore our time complexity is O(nlog(n)); `Space Complexity`: O(n)</span>
-   <span id="9a83">We are linear O(n) time because we are creating subArrays.</span>

<figure><img src="https://cdn-images-1.medium.com/max/800/0*GeU8YwwCoK8GiSTD" class="graf-image" /></figure><figure><img src="https://cdn-images-1.medium.com/max/800/0*IxqGb72XDVDeeiMl" class="graf-image" /></figure>### Example of Merge Sort

<figure><img src="https://cdn-images-1.medium.com/max/800/0*HMCR--9niDt5zY6M" class="graf-image" /></figure>-   <span id="48b4">**Merge sort is O(nlog(n)) time.**</span>
-   <span id="c598">*We need a function for merging and a function for sorting.*</span>

> Steps:

1.  <span id="213f">*If there is only one element in the list, it is already sorted; return the array.*</span>
2.  <span id="6214">*Otherwise, divide the list recursively into two halves until it can no longer be divided.*</span>
3.  <span id="3cc8">*Merge the smallest lists into new list in a sorted order.*</span>

### Quick Sort

`Time Complexity`: Quadratic O(n^2)

-   <span id="8e34">Even though the average time complexity O(nLog(n)), the worst case scenario is always quadratic.</span>

`Space Complexity`: O(n)

-   <span id="626b">Our space complexity is linear O(n) because of the partition arrays we create.</span>
-   <span id="7e3a">QS is another Divide and Conquer strategy.</span>
-   <span id="233d">Some key ideas to keep in mind:</span>
-   <span id="1173">It is easy to sort elements of an array relative to a particular target value.</span>
-   <span id="8634">An array of 0 or 1 elements is already trivially sorted.</span>

<figure><img src="https://cdn-images-1.medium.com/max/800/0*WLl_HpdBGXYx284T" class="graf-image" /></figure><figure><img src="https://cdn-images-1.medium.com/max/800/0*-LyHJXGPTYsWLDZf" class="graf-image" /></figure>### Binary Search

`Time Complexity`: Log Time O(log(n))

`Space Complexity`: O(1)

<figure><img src="https://cdn-images-1.medium.com/max/800/0*-naVYGTXzE2Yoali" class="graf-image" /></figure>*Recursive Solution*

> *Min Max Solution*

-   <span id="6fb1">*Must be conducted on a sorted array.*</span>
-   <span id="383b">*Binary search is logarithmic time, not exponential b/c n is cut down by two, not growing.*</span>
-   <span id="c940">*Binary Search is part of Divide and Conquer.*</span>

### Insertion Sort

-   <span id="26b7">**Works by building a larger and larger sorted region at the left-most end of the array.**</span>

> Steps:

1.  <span id="8c1f">*If it is the first element, and it is already sorted; return 1.*</span>
2.  <span id="1451">*Pick next element.*</span>
3.  <span id="0f8b">*Compare with all elements in the sorted sub list*</span>
4.  <span id="4d78">*Shift all the elements in the sorted sub list that is greater than the value to be sorted.*</span>
5.  <span id="9131">*Insert the value*</span>
6.  <span id="6c8a">*Repeat until list is sorted.*</span>

### If you found this guide helpful feel free to checkout my GitHub/gists where I host similar content:

<a href="https://gist.github.com/bgoonz" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://gist.github.com/bgoonz"><strong>bgoonz’s gists</strong><br />
<em>Instantly share code, notes, and snippets. Web Developer, Electrical Engineer JavaScript | CSS | Bootstrap | Python |…</em>gist.github.com</a><a href="https://gist.github.com/bgoonz" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://github.com/bgoonz" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://github.com/bgoonz"><strong>bgoonz — Overview</strong><br />
<em>Web Developer, Electrical Engineer JavaScript | CSS | Bootstrap | Python | React | Node.js | Express | Sequelize…</em>github.com</a><a href="https://github.com/bgoonz" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

### Or Checkout my personal Resource Site:

<a href="https://bgoonz-blog.netlify.app/" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bgoonz-blog.netlify.app/"><strong>Web-Dev-Hub</strong><br />
<em>Memoization, Tabulation, and Sorting Algorithms by Example Why is looking at runtime not a reliable method of…</em>bgoonz-blog.netlify.app</a><a href="https://bgoonz-blog.netlify.app/" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<figure><img src="https://cdn-images-1.medium.com/max/800/1*VCmj_H9AHs41oC9Yx1hZFQ.png" class="graf-image" /></figure>### Discover More:

<a href="https://bgoonz-blog.netlify.app/" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bgoonz-blog.netlify.app/"><strong>Web-Dev-Hub</strong><br />
<em>Memoization, Tabulation, and Sorting Algorithms by Example Why is looking at runtime not a reliable method of…</em>bgoonz-blog.netlify.app</a><a href="https://bgoonz-blog.netlify.app/" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

By <a href="https://medium.com/@bryanguner" class="p-author h-card">Bryan Guner</a> on [February 27, 2021](https://medium.com/p/803ff193c522).

<a href="https://medium.com/@bryanguner/a-quick-guide-to-big-o-notation-memoization-tabulation-and-sorting-algorithms-by-example-803ff193c522" class="p-canonical">Canonical link</a>

Exported from [Medium](https://medium.com) on August 31, 2021.

A Very Quick Guide To Calculating Big O Computational Complexity
================================================================

Big O: big picture, broad strokes, not details

------------------------------------------------------------------------

### A Very Quick Guide To Calculating Big O Computational Complexity

**Big O**: big picture, broad strokes, not details

For a more complete guide… checkout :

<a href="https://medium.com/star-gazers/a-quick-guide-to-big-o-notation-memoization-tabulation-and-sorting-algorithms-by-example-803ff193c522" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/star-gazers/a-quick-guide-to-big-o-notation-memoization-tabulation-and-sorting-algorithms-by-example-803ff193c522"><strong>A Quick Guide to Big-O Notation, Memoization, Tabulation, and Sorting Algorithms by Example</strong><br />
<em>Curating Complexity: A Guide to Big-O Notation</em>medium.com</a><a href="https://medium.com/star-gazers/a-quick-guide-to-big-o-notation-memoization-tabulation-and-sorting-algorithms-by-example-803ff193c522" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<figure><img src="https://cdn-images-1.medium.com/max/800/0*lte81mEvgEPYXodB.png" class="graf-image" /></figure>-   <span id="28b6">way we analyze how efficient algorithms are without getting too mired in details</span>
-   <span id="4141">can model how much time any function will take given `n` inputs</span>
-   <span id="9479">interested in order of magnitude of number of the exact figure</span>
-   <span id="8fe1">O absorbs all fluff and n = biggest term</span>
-   <span id="a9c8">Big O of `3x^2 +x + 1` = `O(n^2)`</span>

### Time Complexity

no loops or exit & return = O(1)

0 nested loops = `O(n)`  
1 nested loops = `O(n^2)`  
2 nested loops = `O(n^3)`  
3 nested loops = `O(n^4)`

**recursive**: as you add more terms, increase in time as you add input diminishes  
**recursion**: when you define something in terms of itself, a function that calls itself

-   <span id="f455">used because of ability to maintain state at diffferent levels of recursion</span>
-   <span id="f168">inherently carries large footprint</span>
-   <span id="5510">every time function called, you add call to stack</span>

**iterative**: use loops instead of recursion (preferred)  
- favor readability over performance

`O(n log(n))` & `O(log(n))`: dividing/halving

-   <span id="4f7e">if code employs recursion/divide-and-conquer strategy</span>
-   <span id="d1cc">what power do i need to power my base to get n</span>

### Time Definitions

-   <span id="9aad">**constant**: does not scale with input, will take same amount of time</span>
-   <span id="3a19">for any input size n, constant time performs same number of operations every time</span>
-   <span id="bf51">**logarithmic**: increases number of operations it performs as logarithmic function of input size n</span>
-   <span id="93d5">function log n grows very slowly, so as n gets longer, number of operations the algorithm needs to perform doesn’t increase very much</span>
-   <span id="a2cf">halving</span>
-   <span id="46c0">**linear**: increases number of operations it performs as linear function of input size n</span>
-   <span id="5f16">number of additional operations needed to perform grows in direct proportion to increase in input size n</span>
-   <span id="ab93">**log-linear**: increases number of operations it performs as log-linear function of input size n</span>
-   <span id="0459">looking over every element and doing work on each one</span>
-   <span id="bd8a">**quadratic**: increases number of operations it performs as quadratic function of input size n</span>
-   <span id="dc41">**exponential**: increases number of operations it performs as exponential function of input size n</span>
-   <span id="71fc">number of nested loops increases as function of n</span>
-   <span id="8253">**polynomial**: as size of input increases, runtime/space used will grow at a faster rate</span>
-   <span id="8827">**factorial**: as size of input increases, runtime/space used will grow astronomically even with relatively small inputs</span>
-   <span id="040c">**rate of growth**: how fast a function grows with input size</span>

<figure><img src="https://cdn-images-1.medium.com/max/800/1*5t2u8n1uKhioIzZIXX2zbg.png" class="graf-image" /></figure>### Space Complexity

-   <span id="403b">How does the space usage scale/change as input gets very large?</span>
-   <span id="5f20">What auxiliary space does your algorithm use or is it in place (constant)?</span>
-   <span id="b207">Runtime stack space counts as part of space complexity unless told otherwise.</span>

### Sorting Algorithms

<figure><img src="https://cdn-images-1.medium.com/max/800/1*HhXmG2cNdg8y4ZCCQGTyuQ.png" class="graf-image" /></figure><figure><img src="https://cdn-images-1.medium.com/max/800/1*ULeXxVCDkF73GwhsxyM_2g.png" class="graf-image" /></figure>### Data Structures

<figure><img src="https://cdn-images-1.medium.com/max/1200/1*hkZWlUgFyOSaLD5Uskv0tQ.png" class="graf-image" /></figure>

<figure><img src="https://cdn-images-1.medium.com/max/2560/1*COjzunj0-FsMJ0d7v7Z-6g.png" class="graf-image" /></figure>

For similar content check out my GitHub:

<a href="https://github.com/bgoonz" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://github.com/bgoonz"><strong>bgoonz - Overview</strong><br />
<em>Web Developer, Electrical Engineer https://bryanguner.medium.com/ https://portfolio42.netlify.app/…</em>github.com</a><a href="https://github.com/bgoonz" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

By <a href="https://medium.com/@bryanguner" class="p-author h-card">Bryan Guner</a> on [May 19, 2021](https://medium.com/p/eb1557e85fa3).

<a href="https://medium.com/@bryanguner/a-very-quick-guide-to-calculating-big-o-computational-complexity-eb1557e85fa3" class="p-canonical">Canonical link</a>

Exported from [Medium](https://medium.com) on August 31, 2021.

A list of all of my articles to link to future posts
====================================================

You should probably skip this one… seriously it’s just for internal use!

------------------------------------------------------------------------

### All Of My Medium Stories

<figure><img src="https://cdn-images-1.medium.com/max/800/1*yZ41P3YdMYMiyFPAPrzyGw.gif" class="graf-image" /></figure>

------------------------------------------------------------------------

### This is another backup of all of them!

<a href="https://golden-lobe-519.notion.site/Medium-7b5b9bd642344d60afe3f03fe6431952" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://golden-lobe-519.notion.site/Medium-7b5b9bd642344d60afe3f03fe6431952"><strong>All OF MEDIUM ARTICLES</strong><br />
<em>2021-02-27_A-Quick-Guide-to-Big-O-Notation--Memoization--Tabulation--and-Sorting-Algorithms-by-Example-803ff193c522…</em>golden-lobe-519.notion.site</a><a href="https://golden-lobe-519.notion.site/Medium-7b5b9bd642344d60afe3f03fe6431952" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

------------------------------------------------------------------------

<a href="https://medium.com/webdevhub/notes-i-wish-i-had-when-i-started-learning-python-16ce4244be12" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/webdevhub/notes-i-wish-i-had-when-i-started-learning-python-16ce4244be12"><strong>Notes I Wish I Had When I Started Learning Python</strong><br />
<em>Plus resources for learning data structures and algorithms in python at the bottom of this article!</em>medium.com</a><a href="https://medium.com/webdevhub/notes-i-wish-i-had-when-i-started-learning-python-16ce4244be12" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://bryanguner.medium.com/awesome-list-of-github-repositories-f1c433e32b17" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/awesome-list-of-github-repositories-f1c433e32b17"><strong>Awesome List Of Github Repositories</strong><br />
<em>Platforms</em>bryanguner.medium.com</a><a href="https://bryanguner.medium.com/awesome-list-of-github-repositories-f1c433e32b17" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://bryanguner.medium.com/my-personal-arsenal-of-convenience-scripts-3c7869fdae53" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/my-personal-arsenal-of-convenience-scripts-3c7869fdae53"><strong>My Personal Arsenal Of Convenience Scripts</strong><br />
<em>At the bottom the following commands are listed as a markdown file and embed in this article as a github gist.</em>bryanguner.medium.com</a><a href="https://bryanguner.medium.com/my-personal-arsenal-of-convenience-scripts-3c7869fdae53" class="js-mixtapeImage mixtapeImage mixtapeImage--empty u-ignoreBlock"></a>

<a href="https://bryanguner.medium.com/adding-css-to-your-html-3a17ba25ba82" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/adding-css-to-your-html-3a17ba25ba82"><strong>Adding CSS To Your HTML</strong><br />
<em>For beginners … very picture heavy since CSS is such a visual discipline!</em>bryanguner.medium.com</a><a href="https://bryanguner.medium.com/adding-css-to-your-html-3a17ba25ba82" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://bryanguner.medium.com/most-common-javascript-errors-311ea1356a3d" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/most-common-javascript-errors-311ea1356a3d"><strong>Most Common Javascript Errors</strong><br />
<em>Written in quiz format</em>bryanguner.medium.com</a><a href="https://bryanguner.medium.com/most-common-javascript-errors-311ea1356a3d" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://bryanguner.medium.com/super-simple-intro-to-react-5c78e4207b7f" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/super-simple-intro-to-react-5c78e4207b7f"><strong>Super Simple Intro To React</strong><br />
<em>This is a basic introduction for those who feel overwhelmed by the vast microcosm that is the React ecosystem!</em>bryanguner.medium.com</a><a href="https://bryanguner.medium.com/super-simple-intro-to-react-5c78e4207b7f" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://medium.com/codex/react-state-d8e0fc340714" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/codex/react-state-d8e0fc340714"><strong>React State</strong><br />
<em>Demystified</em>medium.com</a><a href="https://medium.com/codex/react-state-d8e0fc340714" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://bryanguner.medium.com/awesome-web-development-youtube-video-archive-792a25839143" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/awesome-web-development-youtube-video-archive-792a25839143"><strong>Awesome Web Development Youtube Video Archive</strong><br />
<em>This is going to be a running list of youtube videos and channels that I discover as I learn web development. It will…</em>bryanguner.medium.com</a><a href="https://bryanguner.medium.com/awesome-web-development-youtube-video-archive-792a25839143" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://levelup.gitconnected.com/beginner-python-problems-solutions-dd631e9c3a9f" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://levelup.gitconnected.com/beginner-python-problems-solutions-dd631e9c3a9f"><strong>Python Problems &amp; Solutions For Beginners</strong><br />
<em>Introduction to python taught through example problems. Solutions are included in embedded repl.it at the bottom of…</em>levelup.gitconnected.com</a><a href="https://levelup.gitconnected.com/beginner-python-problems-solutions-dd631e9c3a9f" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://medium.com/codex/fundamental-concepts-in-javascript-8e093a665b04" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/codex/fundamental-concepts-in-javascript-8e093a665b04"><strong>Fundamental Concepts In Javascript</strong><br />
<em>This is the stuff that comes up on interviews…</em>medium.com</a><a href="https://medium.com/codex/fundamental-concepts-in-javascript-8e093a665b04" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://bryanguner.medium.com/bash-proficiency-in-under-15-minutes-3ec9d4e2e65" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/bash-proficiency-in-under-15-minutes-3ec9d4e2e65"><strong>Bash Proficiency In Under 15 Minutes</strong><br />
<em>Cheat sheet and in-depth explanations located below main article contents… The UNIX shell program interprets user…</em>bryanguner.medium.com</a><a href="https://bryanguner.medium.com/bash-proficiency-in-under-15-minutes-3ec9d4e2e65" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://medium.com/analytics-vidhya/mini-review-of-sql-for-postgresql-w-node-express-f34676f3802b" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/analytics-vidhya/mini-review-of-sql-for-postgresql-w-node-express-f34676f3802b"><strong>Mini Review Of SQL For PostgreSQL W Node &amp; Express</strong><br />
<em>What is a Query?</em>medium.com</a><a href="https://medium.com/analytics-vidhya/mini-review-of-sql-for-postgresql-w-node-express-f34676f3802b" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://bryanguner.medium.com/all-the-things-you-can-embed-in-a-medium-article-b03a85c65d86" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/all-the-things-you-can-embed-in-a-medium-article-b03a85c65d86"><strong>All The Things You Can Embed In A Medium Article</strong><br />
<em>I have this innate desire to make everything available all in one place and it’s usually an unnecessary waste of time……</em>bryanguner.medium.com</a><a href="https://bryanguner.medium.com/all-the-things-you-can-embed-in-a-medium-article-b03a85c65d86" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://bryanguner.medium.com/front-end-behavioral-interview-bf5c079f7461" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/front-end-behavioral-interview-bf5c079f7461"><strong>Front End Behavioral Interview</strong><br />
<em>Web Developer Job Interview Questions</em>bryanguner.medium.com</a><a href="https://bryanguner.medium.com/front-end-behavioral-interview-bf5c079f7461" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://medium.com/codex/prerequisites-to-writing-express-apis-75e3267b284a" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/codex/prerequisites-to-writing-express-apis-75e3267b284a"><strong>The ExpressJS Way To Write APIs</strong><br />
<em>This article will cover the basics of express from the perspective of a beginner without concerning its self with the…</em>medium.com</a><a href="https://medium.com/codex/prerequisites-to-writing-express-apis-75e3267b284a" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://medium.com/analytics-vidhya/heroku-deploy-guides-cheatsheet-compilation-b2897b69ce02" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/analytics-vidhya/heroku-deploy-guides-cheatsheet-compilation-b2897b69ce02"><strong>Heroku Deploy Guides &amp; Cheatsheet Compilation</strong><br />
<em>Heroku lets you deploy, run and manage applications written in Ruby, Node.js, Java, Python, Clojure, Scala, Go and PHP…</em>medium.com</a><a href="https://medium.com/analytics-vidhya/heroku-deploy-guides-cheatsheet-compilation-b2897b69ce02" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://javascript.plainenglish.io/react-in-depth-1965dcde8d4f" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://javascript.plainenglish.io/react-in-depth-1965dcde8d4f"><strong>A Comprehensive Deep Dive into React</strong><br />
<em>An in-depth look into the world of React.</em>javascript.plainenglish.io</a><a href="https://javascript.plainenglish.io/react-in-depth-1965dcde8d4f" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://bryanguner.medium.com/take-a-look-at-the-big-picture-b69e0999a380" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/take-a-look-at-the-big-picture-b69e0999a380"><strong>Web Development Resource List #4</strong><br />
<em>Update:</em>bryanguner.medium.com</a><a href="https://bryanguner.medium.com/take-a-look-at-the-big-picture-b69e0999a380" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://bryanguner.medium.com/bash-d3077114aea7" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/bash-d3077114aea7"><strong>BASH CHEAT SHEET</strong><br />
<em>My Bash Cheatsheet Index:</em>bryanguner.medium.com</a><a href="https://bryanguner.medium.com/bash-d3077114aea7" class="js-mixtapeImage mixtapeImage mixtapeImage--empty u-ignoreBlock"></a>

<a href="https://bryanguner.medium.com/heroku-cheat-sheet-6107ce6ba52b" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/heroku-cheat-sheet-6107ce6ba52b"><strong>Heroku Cheat Sheet</strong><br />
<em>a cheatsheet for using heroku-cli</em>bryanguner.medium.com</a><a href="https://bryanguner.medium.com/heroku-cheat-sheet-6107ce6ba52b" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://bryanguner.medium.com/prerequisites-to-writing-express-apis-75e3267b284a" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/prerequisites-to-writing-express-apis-75e3267b284a"><strong>The ExpressJS Way To Write APIs</strong><br />
<em>This article will cover the basics of express from the perspective of a beginner without concerning it’s self with the…</em>bryanguner.medium.com</a><a href="https://bryanguner.medium.com/prerequisites-to-writing-express-apis-75e3267b284a" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://bryanguner.medium.com/heroku-deploy-guides-cheatsheet-compilation-b2897b69ce02" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/heroku-deploy-guides-cheatsheet-compilation-b2897b69ce02"><strong>Heroku Deploy Guides &amp; Cheatsheet Compilation</strong><br />
<em>Heroku lets you deploy, run and manage applications written in Ruby, Node.js, Java, Python, Clojure, Scala, Go and PHP…</em>bryanguner.medium.com</a><a href="https://bryanguner.medium.com/heroku-deploy-guides-cheatsheet-compilation-b2897b69ce02" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://javascript.plainenglish.io/react-in-depth-1965dcde8d4f" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://javascript.plainenglish.io/react-in-depth-1965dcde8d4f"><strong>A Comprehensive Deep Dive into React</strong><br />
<em>An in-depth look into the world of React.</em>javascript.plainenglish.io</a><a href="https://javascript.plainenglish.io/react-in-depth-1965dcde8d4f" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://bryanguner.medium.com/take-a-look-at-the-big-picture-b69e0999a380" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/take-a-look-at-the-big-picture-b69e0999a380"><strong>Web Development Resource List #4</strong><br />
<em>Update:</em>bryanguner.medium.com</a><a href="https://bryanguner.medium.com/take-a-look-at-the-big-picture-b69e0999a380" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://bryanguner.medium.com/bash-d3077114aea7" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/bash-d3077114aea7"><strong>BASH CHEAT SHEET</strong><br />
<em>My Bash Cheatsheet Index:</em>bryanguner.medium.com</a><a href="https://bryanguner.medium.com/bash-d3077114aea7" class="js-mixtapeImage mixtapeImage mixtapeImage--empty u-ignoreBlock"></a>

<a href="https://bryanguner.medium.com/heroku-cheat-sheet-6107ce6ba52b" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/heroku-cheat-sheet-6107ce6ba52b"><strong>Heroku Cheat Sheet</strong><br />
<em>a cheatsheet for using heroku-cli</em>bryanguner.medium.com</a><a href="https://bryanguner.medium.com/heroku-cheat-sheet-6107ce6ba52b" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://bryanguner.medium.com/web-developers-technical-glossary-2066beae5e96" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/web-developers-technical-glossary-2066beae5e96"><strong>Web Developer’s Technical Glossary</strong><br />
<em>This will be a running list as I make updates!</em>bryanguner.medium.com</a><a href="https://bryanguner.medium.com/web-developers-technical-glossary-2066beae5e96" class="js-mixtapeImage mixtapeImage mixtapeImage--empty u-ignoreBlock"></a>

<a href="https://medium.com/codex/postgresql-in-43-commands-or-less-19fba3e37110" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/codex/postgresql-in-43-commands-or-less-19fba3e37110"><strong>PostgreSQL In 43 Commands Or Less</strong><br />
<em>In database jargon, PostgreSQL uses a client/server model. A PostgreSQL session consists of the following cooperating…</em>medium.com</a><a href="https://medium.com/codex/postgresql-in-43-commands-or-less-19fba3e37110" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://medium.com/geekculture/why-jamstack-rocks-666114722f35" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/geekculture/why-jamstack-rocks-666114722f35"><strong>Why Jamstack Rocks🤘😎🤙</strong><br />
<em>JAMstack websites don’t use the microservices architecture, but they go for the micro frontends architecture. Each…</em>medium.com</a><a href="https://medium.com/geekculture/why-jamstack-rocks-666114722f35" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://bryanguner.medium.com/what-are-bash-aliases-and-why-should-you-be-using-them-30a6cfafdfeb" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/what-are-bash-aliases-and-why-should-you-be-using-them-30a6cfafdfeb"><strong>What Are Bash Aliases And Why Should You Be Using Them!</strong><br />
<em>A Bash alias is a method of supplementing or overriding Bash commands with new ones. Bash aliases make it easy for…</em>bryanguner.medium.com</a><a href="https://bryanguner.medium.com/what-are-bash-aliases-and-why-should-you-be-using-them-30a6cfafdfeb" class="js-mixtapeImage mixtapeImage mixtapeImage--empty u-ignoreBlock"></a>

<a href="https://medium.com/geekculture/life-saving-bash-scripts-part-2-b40c8ee22682" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/geekculture/life-saving-bash-scripts-part-2-b40c8ee22682"><strong>Life Saving Bash Scripts Part 2</strong><br />
<em>I am not saying they’re in any way special compared with other bash scripts… but when I consider that you can never…</em>medium.com</a><a href="https://medium.com/geekculture/life-saving-bash-scripts-part-2-b40c8ee22682" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://medium.com/analytics-vidhya/job-boards-and-the-hunt-8cbfefefbb33" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/analytics-vidhya/job-boards-and-the-hunt-8cbfefefbb33"><strong>Job Boards and The Hunt</strong><br />
<em>I can’t imagine the kind of masochism it would take to enjoy the act of posting and daily maintenance on a job…</em>medium.com</a><a href="https://medium.com/analytics-vidhya/job-boards-and-the-hunt-8cbfefefbb33" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://bryanguner.medium.com/absolutely-everything-you-could-need-to-know-about-how-javascript-works-633549469528" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/absolutely-everything-you-could-need-to-know-about-how-javascript-works-633549469528"><strong>Absolutely Everything You Could Need To Know About How JavaScript Works.</strong><br />
<em>Seriously… this list is utterly exhaustive it covers more core concepts than I can hold the names of in working memory…</em>bryanguner.medium.com</a><a href="https://bryanguner.medium.com/absolutely-everything-you-could-need-to-know-about-how-javascript-works-633549469528" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://bryanguner.medium.com/react-tutorial-from-basics-647ba595e607" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/react-tutorial-from-basics-647ba595e607"><strong>Basic React Tutorial</strong><br />
<em>Random Things to Remember</em>bryanguner.medium.com</a><a href="https://bryanguner.medium.com/react-tutorial-from-basics-647ba595e607" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://bryanguner.medium.com/fundamental-concepts-in-react-that-will-probably-come-up-on-an-interview-5495b6421287" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/fundamental-concepts-in-react-that-will-probably-come-up-on-an-interview-5495b6421287"><strong>Fundamental Concepts In React That Will Probably Come Up On An Interview</strong><br />
<em>Incomplete Article</em>bryanguner.medium.com</a><a href="https://bryanguner.medium.com/fundamental-concepts-in-react-that-will-probably-come-up-on-an-interview-5495b6421287" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://medium.com/geekculture/the-penultimate-web-developers-cheat-sheet-a02a423139a4" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/geekculture/the-penultimate-web-developers-cheat-sheet-a02a423139a4"><strong>The Penultimate Web Developer’s Cheat Sheet</strong><br />
<em>I am literally just going to combine a fair number of my Cheat Sheets in no particular order.</em>medium.com</a><a href="https://medium.com/geekculture/the-penultimate-web-developers-cheat-sheet-a02a423139a4" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://medium.com/geekculture/bash-commands-that-save-time-920fb6ab9d0a" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/geekculture/bash-commands-that-save-time-920fb6ab9d0a"><strong>Bash Commands That Save Me Time and Frustration</strong><br />
<em>Here’s a list of bash commands that stand between me and insanity.</em>medium.com</a><a href="https://medium.com/geekculture/bash-commands-that-save-time-920fb6ab9d0a" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://bryanguner.medium.com/quick-web-developers-website-checklist-a-list-of-tools-for-improvement-9a52e11c8ee1" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/quick-web-developers-website-checklist-a-list-of-tools-for-improvement-9a52e11c8ee1"><strong>Quick Web Developers Website Checklist &amp; A List Of Tools For Improvement</strong><br />
<em>A set of questions you should use before handing off your application to the client.</em>bryanguner.medium.com</a><a href="https://bryanguner.medium.com/quick-web-developers-website-checklist-a-list-of-tools-for-improvement-9a52e11c8ee1" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://javascript.plainenglish.io/react-md-cbaafb31765d" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://javascript.plainenglish.io/react-md-cbaafb31765d"><strong>10 Essential React Interview Questions For Aspiring Frontend Developers</strong><br />
<em>Comprehensive React Cheatsheet included at the bottom of this article!</em>javascript.plainenglish.io</a><a href="https://javascript.plainenglish.io/react-md-cbaafb31765d" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://levelup.gitconnected.com/long-list-of-invaluable-nodejs-resources-6a793ae1ce6" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://levelup.gitconnected.com/long-list-of-invaluable-nodejs-resources-6a793ae1ce6"><strong>Long List Of Invaluable NodeJS Resources</strong><br />
<em>Disclaimer: I know that I did not create this list all on my own… I can’t recall or track down the original list if you…</em>levelup.gitconnected.com</a><a href="https://levelup.gitconnected.com/long-list-of-invaluable-nodejs-resources-6a793ae1ce6" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://bryanguner.medium.com/open-ended-frontend-interview-questions-you-should-answer-before-your-next-interview-7c9722712521" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/open-ended-frontend-interview-questions-you-should-answer-before-your-next-interview-7c9722712521"><strong>Open Ended Frontend Interview Questions You Should Answer Before Your Next Interview</strong><br />
<em>Explain event delegation.</em>bryanguner.medium.com</a><a href="https://bryanguner.medium.com/open-ended-frontend-interview-questions-you-should-answer-before-your-next-interview-7c9722712521" class="js-mixtapeImage mixtapeImage mixtapeImage--empty u-ignoreBlock"></a>

<a href="https://bryanguner.medium.com/data-structures-under-the-hood-660256c2e4e3" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/data-structures-under-the-hood-660256c2e4e3"><strong>Data Structures… Under The Hood</strong><br />
<em>Data Structures Reference</em>bryanguner.medium.com</a><a href="https://bryanguner.medium.com/data-structures-under-the-hood-660256c2e4e3" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://medium.com/geekculture/web-development-interview-resource-list-88fce9876261" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/geekculture/web-development-interview-resource-list-88fce9876261"><strong>Web Development Interview Resource List</strong><br />
<em>Most good programmers do programming not because they expect to get paid or get adulation by the public, but because it…</em>medium.com</a><a href="https://medium.com/geekculture/web-development-interview-resource-list-88fce9876261" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://medium.com/geekculture/beginners-guide-to-python-e5a59b5bb64d" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/geekculture/beginners-guide-to-python-e5a59b5bb64d"><strong>Beginners Guide To Python</strong><br />
<em>My favorite language for maintainability is Python. It has simple, clean syntax, object encapsulation, good library…</em>medium.com</a><a href="https://medium.com/geekculture/beginners-guide-to-python-e5a59b5bb64d" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://bryanguner.medium.com/data-structures-algorithms-resource-list-part-1-8bad647a8ad8" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/data-structures-algorithms-resource-list-part-1-8bad647a8ad8"><strong>Data Structures &amp; Algorithms Resource List Part 1</strong><br />
<em>Guess the author of the following quotes:</em>bryanguner.medium.com</a><a href="https://bryanguner.medium.com/data-structures-algorithms-resource-list-part-1-8bad647a8ad8" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://javascript.plainenglish.io/memoization-86685d811182" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://javascript.plainenglish.io/memoization-86685d811182"><strong>What is Memoization?</strong><br />
<em>And why this programming paradigm shouldn’t make you cringe.</em>javascript.plainenglish.io</a><a href="https://javascript.plainenglish.io/memoization-86685d811182" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://bryanguner.medium.com/css-interview-prep-quiz-6e3e4de7ca53" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/css-interview-prep-quiz-6e3e4de7ca53"><strong>CSS Interview Prep Quiz</strong><br />
<em>Plus Css Cheat Sheet (82 questions total)</em>bryanguner.medium.com</a><a href="https://bryanguner.medium.com/css-interview-prep-quiz-6e3e4de7ca53" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://medium.com/geekculture/verbal-technical-interview-questions-about-graph-data-structures-fc6b1afbd8be" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/geekculture/verbal-technical-interview-questions-about-graph-data-structures-fc6b1afbd8be"><strong>Graph Data Structure Interview Questions At A Glance</strong><br />
<em>Because they’re just about the most important data structure there is.</em>medium.com</a><a href="https://medium.com/geekculture/verbal-technical-interview-questions-about-graph-data-structures-fc6b1afbd8be" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://medium.com/geekculture/object-methods-4066ed24b214" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/geekculture/object-methods-4066ed24b214"><strong>Object Methods</strong><br />
<em>Iterating Through Objects</em>medium.com</a><a href="https://medium.com/geekculture/object-methods-4066ed24b214" class="js-mixtapeImage mixtapeImage mixtapeImage--empty u-ignoreBlock"></a>

<a href="https://levelup.gitconnected.com/github-repositories-that-will-teach-you-how-to-code-for-free-ad0ecf59d89e" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://levelup.gitconnected.com/github-repositories-that-will-teach-you-how-to-code-for-free-ad0ecf59d89e"><strong>Github Repositories That Will Teach You How To Code For Free!</strong><br />
<em>30-seconds/30-seconds-of-code</em>levelup.gitconnected.com</a><a href="https://levelup.gitconnected.com/github-repositories-that-will-teach-you-how-to-code-for-free-ad0ecf59d89e" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://bryanguner.medium.com/resources-by-programming-language-399d9f9ef520" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/resources-by-programming-language-399d9f9ef520"><strong>Resources By Programming Language</strong><br />
<em>Here’s a list of programming resources sorted by programming language.</em>bryanguner.medium.com</a><a href="https://bryanguner.medium.com/resources-by-programming-language-399d9f9ef520" class="js-mixtapeImage mixtapeImage mixtapeImage--empty u-ignoreBlock"></a>

<a href="https://medium.com/codex/scope-closures-context-in-javascript-f126f1523104" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/codex/scope-closures-context-in-javascript-f126f1523104"><strong>Breaking Down Scope, Context, And Closure In JavaScript In Simple Terms.</strong><br />
<em>“JavaScript’s global scope is like a public toilet. You can’t avoid going in there, but try to limit your contact with…</em>medium.com</a><a href="https://medium.com/codex/scope-closures-context-in-javascript-f126f1523104" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://medium.com/codex/these-are-a-few-of-my-favorite-things-82e8b6e61879" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/codex/these-are-a-few-of-my-favorite-things-82e8b6e61879"><strong>These Are A Few Of My Favorite Things</strong><br />
<em>A web development student’s declassified school survival guide.</em>medium.com</a><a href="https://medium.com/codex/these-are-a-few-of-my-favorite-things-82e8b6e61879" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://medium.com/codex/objects-in-javascript-b212486dade6" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/codex/objects-in-javascript-b212486dade6"><strong>Objects In JavaScript</strong><br />
<em>The object is a data structure that stores other data, similar to how an array stores elements.</em>medium.com</a><a href="https://medium.com/codex/objects-in-javascript-b212486dade6" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://bryanguner.medium.com/fundamental-javascript-concepts-you-should-understand-81c4d839b827" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/fundamental-javascript-concepts-you-should-understand-81c4d839b827"><strong>Fundamental Javascript Concepts You Should Understand</strong><br />
<em>Plain Old JS Object Lesson Concepts</em>bryanguner.medium.com</a><a href="https://bryanguner.medium.com/fundamental-javascript-concepts-you-should-understand-81c4d839b827" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://bryanguner.medium.com/mutability-and-reference-vs-privative-types-in-javascript-5294422db4b0" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/mutability-and-reference-vs-privative-types-in-javascript-5294422db4b0"><strong>Mutability And Reference VS Privative Types in JavaScript</strong><br />
<em>Mutability &amp;&amp; Primitive &amp;&amp; Reference Examples</em>bryanguner.medium.com</a><a href="https://bryanguner.medium.com/mutability-and-reference-vs-privative-types-in-javascript-5294422db4b0" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://javascript.plainenglish.io/array-callback-methods-implemented-with-for-loops-d08875df6777" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://javascript.plainenglish.io/array-callback-methods-implemented-with-for-loops-d08875df6777"><strong>Array Callback Methods Implemented With For Loops</strong><br />
<em>How to implement array callback methods in JavaScript</em>javascript.plainenglish.io</a><a href="https://javascript.plainenglish.io/array-callback-methods-implemented-with-for-loops-d08875df6777" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://bryanguner.medium.com/introductory-react-part-2-cda01615a186" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/introductory-react-part-2-cda01615a186"><strong>Beginner’s Guide To React Part 2</strong><br />
<em>As I learn to build web applications in React I will blog about it in this series in an attempt to capture the…</em>bryanguner.medium.com</a><a href="https://bryanguner.medium.com/introductory-react-part-2-cda01615a186" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://bryanguner.medium.com/a-very-quick-guide-to-calculating-big-o-computational-complexity-eb1557e85fa3" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/a-very-quick-guide-to-calculating-big-o-computational-complexity-eb1557e85fa3"><strong>A Very Quick Guide To Calculating Big O Computational Complexity</strong><br />
<em>Big O: big picture, broad strokes, not details</em>bryanguner.medium.com</a><a href="https://bryanguner.medium.com/a-very-quick-guide-to-calculating-big-o-computational-complexity-eb1557e85fa3" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://javascript.plainenglish.io/introduction-to-react-for-complete-beginners-8021738aa1ad" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://javascript.plainenglish.io/introduction-to-react-for-complete-beginners-8021738aa1ad"><strong>Introduction to React for Complete Beginners</strong><br />
<em>All of the code examples below will be included a second time at the bottom of this article as an embedded gist.</em>javascript.plainenglish.io</a><a href="https://javascript.plainenglish.io/introduction-to-react-for-complete-beginners-8021738aa1ad" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://javascript.plainenglish.io/scheduling-settimeout-and-setinterval-fcb2f40d16f7" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://javascript.plainenglish.io/scheduling-settimeout-and-setinterval-fcb2f40d16f7"><strong>Scheduling: setTimeout and setInterval</strong><br />
<em>We may decide to execute a function not right now, but at a later time. That’s called “scheduling a call”.</em>javascript.plainenglish.io</a><a href="https://javascript.plainenglish.io/scheduling-settimeout-and-setinterval-fcb2f40d16f7" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://bryanguner.medium.com/css-animations-d196a20099a5" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/css-animations-d196a20099a5"><strong>LocalStorage VS SessionStorage</strong><br />
<em>Web storage objects localStorage and sessionStorage allow to save key/value pairs in the browser.</em>bryanguner.medium.com</a><a href="https://bryanguner.medium.com/css-animations-d196a20099a5" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://levelup.gitconnected.com/these-are-the-bash-shell-commands-that-stand-between-me-and-insanity-984865ba5d1b" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://levelup.gitconnected.com/these-are-the-bash-shell-commands-that-stand-between-me-and-insanity-984865ba5d1b"><strong>These Are The Bash Shell Commands That Stand Between Me And Insanity</strong><br />
<em>I will not profess to be a bash shell wizard… but I have managed to scour some pretty helpful little scripts from Stack…</em>levelup.gitconnected.com</a><a href="https://levelup.gitconnected.com/these-are-the-bash-shell-commands-that-stand-between-me-and-insanity-984865ba5d1b" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://bryanguner.medium.com/how-to-implement-native-es6-data-structures-using-arrays-objects-ce953b9f6a07" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/how-to-implement-native-es6-data-structures-using-arrays-objects-ce953b9f6a07"><strong>How To Implement Native(ES6) Data Structures Using Arrays &amp; Objects</strong><br />
<em>Smart data structures and dumb code works better than the other way around -“Eric S. Raymond”</em>bryanguner.medium.com</a><a href="https://bryanguner.medium.com/how-to-implement-native-es6-data-structures-using-arrays-objects-ce953b9f6a07" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://medium.com/codex/objects-in-javascript-cc578a781e1d" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/codex/objects-in-javascript-cc578a781e1d"><strong>Objects in Javascript</strong><br />
<em>Codepen with examples for you to practice with below!</em>medium.com</a><a href="https://medium.com/codex/objects-in-javascript-cc578a781e1d" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://javascript.plainenglish.io/absolute-beginners-guide-to-javascript-part-1-e222d166b6e1" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://javascript.plainenglish.io/absolute-beginners-guide-to-javascript-part-1-e222d166b6e1"><strong>The Beginner’s Guide To JavaScript</strong><br />
<em>Part 1</em>javascript.plainenglish.io</a><a href="https://javascript.plainenglish.io/absolute-beginners-guide-to-javascript-part-1-e222d166b6e1" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://medium.com/star-gazers/web-developer-resource-list-part-4-fd686892b9eb" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/star-gazers/web-developer-resource-list-part-4-fd686892b9eb"><strong>Web Developer Resource List Part 4</strong><br />
<em>A all encompassing list of tools and resources for web developers</em>medium.com</a><a href="https://medium.com/star-gazers/web-developer-resource-list-part-4-fd686892b9eb" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://medium.com/codex/vscode-extensions-specifically-for-javascript-development-ea91305cbd4a" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/codex/vscode-extensions-specifically-for-javascript-development-ea91305cbd4a"><strong>VSCode Extensions Specifically for JavaScript Development</strong><br />
<em>VSCode Extensions that are indispensable in JavaScript development</em>medium.com</a><a href="https://medium.com/codex/vscode-extensions-specifically-for-javascript-development-ea91305cbd4a" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://bryanguner.medium.com/a-list-of-all-of-my-articles-to-link-to-future-posts-1f6f88ebdf5b" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/a-list-of-all-of-my-articles-to-link-to-future-posts-1f6f88ebdf5b"><strong>A list of all of my articles to link to future posts</strong><br />
<em>You should probably skip this one… seriously it’s just for internal use!</em>bryanguner.medium.com</a><a href="https://bryanguner.medium.com/a-list-of-all-of-my-articles-to-link-to-future-posts-1f6f88ebdf5b" class="js-mixtapeImage mixtapeImage mixtapeImage--empty u-ignoreBlock"></a>

<a href="https://javascript.plainenglish.io/lists-stacks-and-queues-in-javascript-88466fae0fbb" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://javascript.plainenglish.io/lists-stacks-and-queues-in-javascript-88466fae0fbb"><strong>Fundamental Data Structures in JavaScript</strong><br />
<em>A simple to follow guide to Lists Stacks and Queues, with animated gifs, diagrams, and code examples!</em>javascript.plainenglish.io</a><a href="https://javascript.plainenglish.io/lists-stacks-and-queues-in-javascript-88466fae0fbb" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://bryanguner.medium.com/web-development-resources-part-3-f862ceb2b82a" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/web-development-resources-part-3-f862ceb2b82a"><strong>Web Development Resources Part 3</strong><br />
<em>I’m the psychological equivalent of a physical hoarder only instead of empty soda cans and dead racoons it’s lists of…</em>bryanguner.medium.com</a><a href="https://bryanguner.medium.com/web-development-resources-part-3-f862ceb2b82a" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://medium.com/codex/web-development-interview-part-3-826ae81a9107" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/codex/web-development-interview-part-3-826ae81a9107"><strong>Web Development Interview Part 3💻</strong><br />
<em>This installment is going to be the least technically demanding thus far however these questions are a more realistic…</em>medium.com</a><a href="https://medium.com/codex/web-development-interview-part-3-826ae81a9107" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://bryanguner.medium.com/the-best-cloud-based-code-playgrounds-of-2021-part-1-cdae9448db24" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/the-best-cloud-based-code-playgrounds-of-2021-part-1-cdae9448db24"><strong>The Best Cloud-Based Code Playgrounds of 2021 (Part 1)</strong><br />
<em>A plethora of front-end code playgrounds have appeared over the years. They offer a convenient way to experiment with…</em>bryanguner.medium.com</a><a href="https://bryanguner.medium.com/the-best-cloud-based-code-playgrounds-of-2021-part-1-cdae9448db24" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://medium.com/codex/front-end-interview-questions-part-2-86ddc0e91443" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/codex/front-end-interview-questions-part-2-86ddc0e91443"><strong>Front End Interview Questions Part 2</strong><br />
<em>These will focus more on vocabulary and concepts than the application driven approach in my last post!</em>medium.com</a><a href="https://medium.com/codex/front-end-interview-questions-part-2-86ddc0e91443" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://medium.com/star-gazers/web-developer-resource-list-part-2-9c5cb56ab263" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/star-gazers/web-developer-resource-list-part-2-9c5cb56ab263"><strong>Web Developer Resource List Part 2</strong><br />
<em>Because I compile these things compulsively anyway…</em>medium.com</a><a href="https://medium.com/star-gazers/web-developer-resource-list-part-2-9c5cb56ab263" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://levelup.gitconnected.com/http-basics-8f02a96a834a" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://levelup.gitconnected.com/http-basics-8f02a96a834a"><strong>HTTP Basics</strong><br />
<em>“If you want to build a ship, don’t drum up the men and women to gather wood, divide the work, and give orders…</em>levelup.gitconnected.com</a><a href="https://levelup.gitconnected.com/http-basics-8f02a96a834a" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://javascript.plainenglish.io/javascript-frameworks-libraries-35931e187a35" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://javascript.plainenglish.io/javascript-frameworks-libraries-35931e187a35"><strong>JavaScript Frameworks &amp; Libraries</strong><br />
<em>My Awesome JavaScript List Part 2</em>javascript.plainenglish.io</a><a href="https://javascript.plainenglish.io/javascript-frameworks-libraries-35931e187a35" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://javascript.plainenglish.io/my-take-on-awesome-javascript-243255451e74" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://javascript.plainenglish.io/my-take-on-awesome-javascript-243255451e74"><strong>My ‘awesome’ list of JavaScript resources</strong><br />
<em>Everyone’s seen the ‘Awesome’ lists on GitHub… and they are indeed awesome… so today I am going to attempt to curate my…</em>javascript.plainenglish.io</a><a href="https://javascript.plainenglish.io/my-take-on-awesome-javascript-243255451e74" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://levelup.gitconnected.com/everything-you-need-to-get-started-with-vscode-extensions-resources-b9f4c8d91931" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://levelup.gitconnected.com/everything-you-need-to-get-started-with-vscode-extensions-resources-b9f4c8d91931"><strong>Everything You Need to Get Started With VSCode + Extensions &amp; Resources</strong><br />
<em>Commands:</em>levelup.gitconnected.com</a><a href="https://levelup.gitconnected.com/everything-you-need-to-get-started-with-vscode-extensions-resources-b9f4c8d91931" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://levelup.gitconnected.com/my-favorite-vscode-themes-9bab65af3f0f" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://levelup.gitconnected.com/my-favorite-vscode-themes-9bab65af3f0f"><strong>My Favorite VSCode <em>Themes</em></strong><br />
Themeslevelup.gitconnected.com</a><a href="https://levelup.gitconnected.com/my-favorite-vscode-themes-9bab65af3f0f" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://levelup.gitconnected.com/object-oriented-programming-in-javascript-d45007d06333" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://levelup.gitconnected.com/object-oriented-programming-in-javascript-d45007d06333"><strong>Object Oriented Programming in JavaScript</strong><br />
<em>Object-Oriented Programming</em>levelup.gitconnected.com</a><a href="https://levelup.gitconnected.com/object-oriented-programming-in-javascript-d45007d06333" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://medium.com/codex/javascript-rotate-array-problemwalkthrough-31deb19ebba1" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/codex/javascript-rotate-array-problemwalkthrough-31deb19ebba1"><strong>JavaScript Rotate (Array) ProblemWalkthrough</strong><br />
<em>Explanation for Rotate Right</em>medium.com</a><a href="https://medium.com/codex/javascript-rotate-array-problemwalkthrough-31deb19ebba1" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://levelup.gitconnected.com/super-simple-intro-to-html-651d695f9bc" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://levelup.gitconnected.com/super-simple-intro-to-html-651d695f9bc"><strong>Super Simple Intro To HTML</strong><br />
<em>What is HTML, CSS &amp; JS and why do we need all three?</em>levelup.gitconnected.com</a><a href="https://levelup.gitconnected.com/super-simple-intro-to-html-651d695f9bc" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://medium.com/codex/everything-you-need-to-know-about-relational-databases-sql-postgresql-and-sequelize-to-build-8acb68284a98" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/codex/everything-you-need-to-know-about-relational-databases-sql-postgresql-and-sequelize-to-build-8acb68284a98"><strong>Everything You Need To Know About Relational Databases, SQL, PostgreSQL and Sequelize To Build…</strong><br />
<em>For Front end developers who like myself struggle with making the jump to fullstack.</em>medium.com</a><a href="https://medium.com/codex/everything-you-need-to-know-about-relational-databases-sql-postgresql-and-sequelize-to-build-8acb68284a98" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://levelup.gitconnected.com/understanding-git-a-beginners-guide-containing-cheat-sheets-resources-b50c9c01a107" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://levelup.gitconnected.com/understanding-git-a-beginners-guide-containing-cheat-sheets-resources-b50c9c01a107"><strong>Understanding Git (A Beginners Guide Containing Cheat Sheets &amp; Resources)</strong><br />
<em>Basic Git Work Flow.</em>levelup.gitconnected.com</a><a href="https://levelup.gitconnected.com/understanding-git-a-beginners-guide-containing-cheat-sheets-resources-b50c9c01a107" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://javascript.plainenglish.io/complete-javascript-reference-guide-64306cd6b0db" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://javascript.plainenglish.io/complete-javascript-reference-guide-64306cd6b0db"><strong>The Complete JavaScript Reference Guide</strong><br />
<em>You will want to bookmark this</em>javascript.plainenglish.io</a><a href="https://javascript.plainenglish.io/complete-javascript-reference-guide-64306cd6b0db" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://medium.com/geekculture/modules-in-javascript-a55333e35978" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/geekculture/modules-in-javascript-a55333e35978"><strong>Modules in Javascript</strong><br />
<em>Differences between Node.js and browsers</em>medium.com</a><a href="https://medium.com/geekculture/modules-in-javascript-a55333e35978" class="js-mixtapeImage mixtapeImage mixtapeImage--empty u-ignoreBlock"></a>

<a href="https://levelup.gitconnected.com/an-introduction-to-markdown-bonus-markdown-templates-included-3497ce56de3" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://levelup.gitconnected.com/an-introduction-to-markdown-bonus-markdown-templates-included-3497ce56de3"><strong>An Introduction to Markdown (Bonus Markdown Templates Included)</strong><br />
<em>Basic Syntax Guide</em>levelup.gitconnected.com</a><a href="https://levelup.gitconnected.com/an-introduction-to-markdown-bonus-markdown-templates-included-3497ce56de3" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://levelup.gitconnected.com/web-dev-resources-ec1975773d7d" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://levelup.gitconnected.com/web-dev-resources-ec1975773d7d"><strong>Web Dev Resources</strong><br />
<em>Web Development</em>levelup.gitconnected.com</a><a href="https://levelup.gitconnected.com/web-dev-resources-ec1975773d7d" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://medium.com/codex/regular-expressions-4d8fb3eb146b" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/codex/regular-expressions-4d8fb3eb146b"><strong>Regular Expressions</strong><br />
<em>description:</em>medium.com</a><a href="https://medium.com/codex/regular-expressions-4d8fb3eb146b" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://medium.com/geekculture/writing-files-using-python-d46b4851366f" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/geekculture/writing-files-using-python-d46b4851366f"><strong>Writing Files Using Python</strong><br />
<em>Basics of Writing Files in Python<br />
The common methods to operate with files are open() to open a file,</em>medium.com</a><a href="https://medium.com/geekculture/writing-files-using-python-d46b4851366f" class="js-mixtapeImage mixtapeImage mixtapeImage--empty u-ignoreBlock"></a>

<a href="https://bryanguner.medium.com/a-collection-of-my-most-useful-gist-entries-f4314f3ba3ab" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/a-collection-of-my-most-useful-gist-entries-f4314f3ba3ab"><strong>A Collection of my most useful Gist Entries</strong><br />
<em>This list is in no particular order!</em>bryanguner.medium.com</a><a href="https://bryanguner.medium.com/a-collection-of-my-most-useful-gist-entries-f4314f3ba3ab" class="js-mixtapeImage mixtapeImage mixtapeImage--empty u-ignoreBlock"></a>

<a href="https://javascript.plainenglish.io/learn-css-so-that-your-site-doesnt-look-like-garbage-938871b4521a" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://javascript.plainenglish.io/learn-css-so-that-your-site-doesnt-look-like-garbage-938871b4521a"><strong>Learn CSS So That Your Site Doesn’t Look Like Garbage</strong><br />
<em>CSS Selectors</em>javascript.plainenglish.io</a><a href="https://javascript.plainenglish.io/learn-css-so-that-your-site-doesnt-look-like-garbage-938871b4521a" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://bryanguner.medium.com/postgresql-setup-for-windows-wsl-ubuntu-801672ab7089" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/postgresql-setup-for-windows-wsl-ubuntu-801672ab7089"><strong>PostgreSQL Setup For Windows &amp; WSL/Ubuntu</strong><br />
<em>If you follow this guide to a tee… you will install PostgreSQL itself on your Windows installation. Then, you will…</em>bryanguner.medium.com</a><a href="https://bryanguner.medium.com/postgresql-setup-for-windows-wsl-ubuntu-801672ab7089" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://bryanguner.medium.com/emmet-cheat-sheet-24758e628d37" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/emmet-cheat-sheet-24758e628d37"><strong>Emmet Cheat Sheet</strong><br />
<em>EMMET</em>bryanguner.medium.com</a><a href="https://bryanguner.medium.com/emmet-cheat-sheet-24758e628d37" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://bryanguner.medium.com/git-tricks-57e8d0292285" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/git-tricks-57e8d0292285"><strong>Git-Tricks</strong><br />
<em>Refs</em>bryanguner.medium.com</a><a href="https://bryanguner.medium.com/git-tricks-57e8d0292285" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://levelup.gitconnected.com/python-study-guide-for-a-native-javascript-developer-5cfdf3d2bdfb" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://levelup.gitconnected.com/python-study-guide-for-a-native-javascript-developer-5cfdf3d2bdfb"><strong>Python Study Guide for a JavaScript Programmer</strong><br />
<em>A guide to commands in Python from what you know in JavaScript</em>levelup.gitconnected.com</a><a href="https://levelup.gitconnected.com/python-study-guide-for-a-native-javascript-developer-5cfdf3d2bdfb" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://bryanguner.medium.com/fetch-quick-sheet-8872650742b4" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/fetch-quick-sheet-8872650742b4"><strong><em>Fetch</em> Quick Sheet</strong><br />
Fetchbryanguner.medium.com</a><a href="https://bryanguner.medium.com/fetch-quick-sheet-8872650742b4" class="js-mixtapeImage mixtapeImage mixtapeImage--empty u-ignoreBlock"></a>

<a href="https://bryanguner.medium.com/express-quick-sheet-8f93762c59ca" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/express-quick-sheet-8f93762c59ca"><strong>Express Quick Sheet</strong><br />
<em>Settings</em>bryanguner.medium.com</a><a href="https://bryanguner.medium.com/express-quick-sheet-8f93762c59ca" class="js-mixtapeImage mixtapeImage mixtapeImage--empty u-ignoreBlock"></a>

<a href="https://medium.com/codex/fundamental-data-structures-in-javascript-8f9f709c15b4" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/codex/fundamental-data-structures-in-javascript-8f9f709c15b4"><strong>Fundamental Data Structures In JavaScript</strong><br />
<em>Data structures in JavaScript</em>medium.com</a><a href="https://medium.com/codex/fundamental-data-structures-in-javascript-8f9f709c15b4" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://bryanguner.medium.com/deploy-react-app-to-heroku-using-postgres-express-70b7ea807986" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/deploy-react-app-to-heroku-using-postgres-express-70b7ea807986"><strong>Deploy React App To Heroku Using Postgres &amp; Express</strong><br />
<em>Heroku is an web application that makes deploying applications easy for a beginner.</em>bryanguner.medium.com</a><a href="https://bryanguner.medium.com/deploy-react-app-to-heroku-using-postgres-express-70b7ea807986" class="js-mixtapeImage mixtapeImage mixtapeImage--empty u-ignoreBlock"></a>

<a href="https://medium.com/codex/postgresql-cheat-sheet-718b813d3e31" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/codex/postgresql-cheat-sheet-718b813d3e31"><strong>Postgresql Cheat Sheet</strong><br />
<em>PostgreSQL commands</em>medium.com</a><a href="https://medium.com/codex/postgresql-cheat-sheet-718b813d3e31" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://medium.com/star-gazers/a-quick-guide-to-big-o-notation-memoization-tabulation-and-sorting-algorithms-by-example-803ff193c522" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/star-gazers/a-quick-guide-to-big-o-notation-memoization-tabulation-and-sorting-algorithms-by-example-803ff193c522"><strong>A Quick Guide to Big-O Notation, Memoization, Tabulation, and Sorting Algorithms by Example</strong><br />
<em>Curating Complexity: A Guide to Big-O Notation</em>medium.com</a><a href="https://medium.com/star-gazers/a-quick-guide-to-big-o-notation-memoization-tabulation-and-sorting-algorithms-by-example-803ff193c522" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://levelup.gitconnected.com/basic-web-development-environment-setup-9f36c3f15afe" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://levelup.gitconnected.com/basic-web-development-environment-setup-9f36c3f15afe"><strong>Basic Web Development Environment Setup</strong><br />
<em>Windows Subsystem for Linux (WSL) and Ubuntu</em>levelup.gitconnected.com</a><a href="https://levelup.gitconnected.com/basic-web-development-environment-setup-9f36c3f15afe" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

By <a href="https://medium.com/@bryanguner" class="p-author h-card">Bryan Guner</a> on [March 22, 2021](https://medium.com/p/1f6f88ebdf5b).

<a href="https://medium.com/@bryanguner/a-list-of-all-of-my-articles-to-link-to-future-posts-1f6f88ebdf5b" class="p-canonical">Canonical link</a>

Exported from [Medium](https://medium.com) on August 31, 2021.

Absolutely Everything You Could Need To Know About How JavaScript Works.
========================================================================

Seriously… this list is utterly exhaustive it covers more core concepts than I can hold the names of in working memory on a very good day.

------------------------------------------------------------------------

### Absolutely Everything You Could Need To Know About How JavaScript Works.

#### Seriously… this list is utterly exhaustive it covers more core concepts than I can hold the names of in working memory on a very good day.

#### But first a little bit of mildly shameful self promotion:

> (self promotion ends after the line denoted by a bunch of pictures of my dog🐕 )

> (Followed by a brief introduction to JavaScript for beginners)

> (Finally the main content / resources / imbedded YouTube links)

<figure><img src="https://cdn-images-1.medium.com/max/800/0*huxNcspoDvOfqxvn.gif" class="graf-image" /></figure>### My Blog:

### Discover More:

<a href="https://bgoonz-blog.netlify.app/" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bgoonz-blog.netlify.app/"><strong>Web-Dev-Hub</strong><br />
<em>Memoization, Tabulation, and Sorting Algorithms by Example Why is looking at runtime not a reliable method of…</em>bgoonz-blog.netlify.app</a><a href="https://bgoonz-blog.netlify.app/" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<figure><img src="https://cdn-images-1.medium.com/max/600/1*_J5NcnQmHmPDBvZodMmyaA.png" class="graf-image" /></figure>***This is a work in progress and may be broken or hosted elsewhere at some time in the future.***

Related posts:

<a href="https://dev.to/bgoonz/js-modules-4c4d" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://dev.to/bgoonz/js-modules-4c4d"><strong>JS Modules</strong><br />
<em>A module is a reusable piece of code that encapsulates implementation details and exposes a public API so it can be…</em>dev.to</a><a href="https://dev.to/bgoonz/js-modules-4c4d" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://dev.to/bgoonz/closures-in-javascript-1moc" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://dev.to/bgoonz/closures-in-javascript-1moc"><strong>Closures In JavaScript</strong><br />
<em>Answer A closure is a function defined inside another function and has access to its lexical scope even when it is…</em>dev.to</a><a href="https://dev.to/bgoonz/closures-in-javascript-1moc" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://bryanguner.medium.com/a-list-of-all-of-my-articles-to-link-to-future-posts-1f6f88ebdf5b" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bryanguner.medium.com/a-list-of-all-of-my-articles-to-link-to-future-posts-1f6f88ebdf5b"><strong>A list of all of my articles to link to future posts</strong><br />
bryanguner.medium.com</a><a href="https://bryanguner.medium.com/a-list-of-all-of-my-articles-to-link-to-future-posts-1f6f88ebdf5b" class="js-mixtapeImage mixtapeImage mixtapeImage--empty u-ignoreBlock"></a>

<a href="https://javascript.plainenglish.io/complete-javascript-reference-guide-64306cd6b0db" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://javascript.plainenglish.io/complete-javascript-reference-guide-64306cd6b0db"><strong>The Complete JavaScript Reference Guide</strong><br />
<em>You will want to bookmark this</em>javascript.plainenglish.io</a><a href="https://javascript.plainenglish.io/complete-javascript-reference-guide-64306cd6b0db" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<figure><img src="https://cdn-images-1.medium.com/max/2560/1*2FC8D_rbP4cT3jukydhtkg.png" class="graf-image" /></figure>

### The Beginner’s Guide To JavaScript

> This is a quick intro for complete beginners … skip below for more advanced content and resources! (below the next photo montage of my dog)

### Skip The Following **↓** To Get To Main Content!!

<figure><img src="https://cdn-images-1.medium.com/max/600/1*HCYn5Uz_jZ6uRjgp_NA5Yw.png" class="graf-image" /></figure>**If you wanna skip this section you’ll find the main content about 10% of the way down the page… it will look like this:**

<figure><img src="https://cdn-images-1.medium.com/max/600/0*iHxLNzz1MOZACC5u.png" class="graf-image" /></figure>### The Number Data Type

The **number** data type in JS is used to represent any numerical  
values, including integers and decimal numbers. **Basic Arithmetic Operators** are the symbols that perform particular operations.

-   <span id="205d">**+** (addition)</span>
-   <span id="1df4">**-** (subtraction)</span>
-   <span id="f17b">**asterisk** (multiplication)</span>
-   <span id="ed52">**/** (division)</span>
-   <span id="d3a6">**%** (modulo)</span>

JS evaluates more complex expressions using the general math order of  
operations aka PEMDAS.

-   <span id="4923">**PEMDAS** : Parentheses, Exponents, Multiplication, Division, Modulo, Addition, Subtraction.</span>
-   <span id="e245">*To force a specific order of operation, use the group operator ( ) around a part of the expression.*</span>

**Modulo** : Very useful operation to check divisibility of numbers,  
check for even & odd, whether a number is prime, and much more!  
*(Discrete Math concept, circular problems can be solved with modulo)*

-   <span id="9608">Whenever you have a smaller number % a larger number, the answer will just be the initial small number.</span>
-   <span id="3b00">`console.log(7 % 10); // => 7;`</span>

### The String Data Type

The **string** data type is a primitive data type that used to represent  
textual data.

-   <span id="792d">can be wrapped by either **single** or **double** quotation marks, *best to choose one and stick with it for consistency*.</span>
-   <span id="4f91">If your string contains quotation marks inside, can layer single or double quotation marks to allow it to work.</span>

<!-- -->

    "That's a great string"; (valid)
    'Shakespeare wrote, "To be or not to be"'; (valid)
    'That's a bad string'; (invalid)

-   <span id="a54b">Alt. way to add other quotes within strings is to use template literals.</span>

### `This is a template literal`

`${function} // use ${} to invoke functions within.`

> **.length** : property that can be appended to data to return the length.

> empty strings have a length of zero.

> **indices** : indexes of data that begin at 0, can call upon index by using the bracket notation \[ \].

    console.log("bootcamp"[0]); // => "b"
    console.log("bootcamp"[10]); // => "undefined"
    console.log("boots"[1 * 2]); // => "o"
    console.log("boots"["boot".length - 1]); // => "t"

-   <span id="bcc3">we can pass expressions through the brackets as well since JS always evaluates expressions first.</span>
-   <span id="f60b">The index of the last character of a string is always one less than it’s length.</span>
-   <span id="5329">**indexOf()** : method used to find the first index of a given character within a string.</span>
-   <span id="6813">`console.log("bagel".indexOf("b")); // => 0 console.log("bagel".indexOf("z")); // => -1`</span>
-   <span id="262e">**if the character inside the indexOf() search does not exist in the string, the output will be -1.**</span>
-   <span id="0646">the indexOf() search will return the first instanced index of the the char in the string.</span>
-   <span id="15e0">**concatenate** : word to describe joining strings together into a single string.</span>

### The Boolean Data Type

The **Boolean** data type is the simplest data type since there are only  
two values: **true** and **false**.

-   <span id="62d6">**Logical Operators** (Boolean Operators) are used to establish logic in our code.</span>
-   <span id="bae2">**!** (not) : reverses a Boolean value.</span>

`console.log(!true); // => false console.log(!!false); // => false`

-   <span id="71d9">**&&** (and) **Truth Table**</span>

<figure><img src="https://cdn-images-1.medium.com/max/800/0*Y4qzqSB0C-9AmtXf.png" class="graf-image" /></figure>-   <span id="c706">**Logical Order of Operations** : JS will evaluate !, then &&, then ||.</span>
-   <span id="1e21">**De Morgan’s Law** : Common mistake in Boolean logic is incorrectly distributing ! across parentheses.</span>
-   <span id="2e3e">`!(A || B) === !A && !B; !(A && B) === !A || !B;`</span>
-   <span id="350f">In summary, to correctly distribute ! across parentheses we must also flip the operation within.</span>

### Comparison Operators

All comparison operators will result in a Boolean output.

**The relative comparators**

-   <span id="0d1c">**&gt;** (greater than)</span>
-   <span id="77dd">**&lt;** (less than)</span>
-   <span id="2041">**&gt;=** (greater than or equal to)</span>
-   <span id="55fd">**&lt;=** (less than or equal to)</span>
-   <span id="1b7c">**===** (equal to)</span>
-   <span id="09a6">**!==** (not equal to)</span>

> Fun Fact: “a” &lt; “b” is considered valid JS Code because string  
> comparisons are compared lexicographically (meaning dictionary order),  
> so “a” is less than “b” because it appears earlier!

> If there is ever a standstill comparison of two string  
> lexicographically (i.e. app vs apple) the comparison will deem the  
> shorter string lesser.

**Difference between == and ===**

-   <span id="3fec">**===** : Strict Equality, will only return true if the two comparisons are entirely the same.</span>
-   <span id="224d">**==** : Loose Equality, will return true even if the values are of a different type, due to coercion. (Avoid using this)</span>

### Variables

Variables are used to store information to be referenced and manipulated  
in a program.

-   <span id="e084">We initialize a variable by using the **let** keyword and a **=** single equals sign (assignment operator).</span>
-   <span id="92ec">`let bootcamp = "Lambda"; console.log(bootcamp); // "Lambda"`</span>
-   <span id="f5af">JS variable names can contain any alphanumeric characters,  
    underscores, or dollar signs (cannot being with a number).</span>
-   <span id="5288">If you do not declare a value for a variable, undefined is  
    automatically set.</span>
-   <span id="5f49">`let bootcamp; console.log(bootcamp); // undefined`</span>
-   <span id="ea4b">We can change the value of a previously declared variable (let, not  
    const) by re-assigning it another value.</span>
-   <span id="ef75">**let** is the updated version of **var**; there are some  
    differences in terms of hoisting and global/block scope — will be  
    covered later in the course (common interview question!)</span>

**Assignment Shorthand**

    let num = 0;num += 10; // same as num = num + 10num -= 2; // same as num = num - 2num /= 4; // same as num = num / 4num *= 7; // same as num = num * 7

-   <span id="7ff5">In general, any nonsensical arithmetic will result in **NaN** ; usually operations that include undefined.</span>
-   <span id="2798">**declaration** : process of simply introducing a variable name.</span>
-   <span id="ad51">**initialization** : process of both declaring and assigning a variable on the same line.</span>

### Functions

A function is a procedure of code that will run when called. Functions  
are used so that we do not have to rewrite code to do the same thing  
over and over. (Think of them as ‘subprograms’)

-   <span id="01bb">**Function Declaration** : Process when we first initially write our function.</span>
-   <span id="963b">Includes three things:</span>
-   <span id="32df">Name of the function.</span>
-   <span id="7930">A list of *parameters* ()</span>
-   <span id="145e">The code to execute {}</span>
-   <span id="37c0">**Function Calls** : We can call upon our function whenever and wherever\* we want. (\*wherever is only after the initial declaration)</span>
-   <span id="f3cc">JS evaluates code top down, left to right.</span>
-   <span id="cf9c">When we execute a declared function later on in our program we refer to this as **invoking** our function.</span>
-   <span id="4374">Every function in JS returns undefined unless otherwise specified.</span>
-   <span id="3bb7">When we hit a **return** statement in a function we immediately exit the function and return to where we called the function.</span>
-   <span id="0ce8">When naming functions in JS always use camelCase and name it something appropriate. &gt; Great code reads like English and almost explains itself. Think: Elegant, readable, and maintainable!</span>

### Parameters and Arguments

-   <span id="38d3">**Parameters** : Comma separated variables specified as part of a function’s declaration.</span>
-   <span id="ecef">**Arguments** : Values passed to the function when it is invoked.</span>
-   <span id="a836">*If the number of arguments passed during a function invocation is different than the number of parameters listed, it will still work.*</span>
-   <span id="a53a">However, is there are not enough arguments provided for parameters our function will likely yield **Nan**.</span>

------------------------------------------------------------------------

<figure><img src="https://cdn-images-1.medium.com/max/2560/1*2FC8D_rbP4cT3jukydhtkg.png" class="graf-image" /></figure>

> END OF INTRO FOR BEGINNERS (MAIN ARTICLE BELOW)

### ↓↓**Absolutely Everything You Could Need To Know About JavaScript**↓↓

<figure><img src="https://cdn-images-1.medium.com/max/800/0*fOaTsnCJCYc3wD4x" class="graf-image" /></figure><a href="https://github.com/leonardomso/33-js-concepts#20-pure-functions-side-effects-and-state-mutation" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://github.com/leonardomso/33-js-concepts#20-pure-functions-side-effects-and-state-mutation"><strong>leonardomso/33-js-concepts</strong><br />
<em>This repository was created with the intention of helping developers master their concepts in JavaScript. It is not a…</em>github.com</a><a href="https://github.com/leonardomso/33-js-concepts#20-pure-functions-side-effects-and-state-mutation" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://developer.mozilla.org/en-US/docs/Glossary/Call_stack" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://developer.mozilla.org/en-US/docs/Glossary/Call_stack"><strong>Call stack - MDN Web Docs Glossary: Definitions of Web-related terms | MDN</strong><br />
<em>A call stack is a mechanism for an interpreter (like the JavaScript interpreter in a web browser) to keep track of its…</em>developer.mozilla.org</a><a href="https://developer.mozilla.org/en-US/docs/Glossary/Call_stack" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://medium.com/@gaurav.pandvia/understanding-javascript-function-executions-tasks-event-loop-call-stack-more-part-1-5683dea1f5ec" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/@gaurav.pandvia/understanding-javascript-function-executions-tasks-event-loop-call-stack-more-part-1-5683dea1f5ec"><strong>Understanding Javascript Function Executions — Call Stack, Event Loop , Tasks &amp; more</strong><br />
<em>Web developers or Front end engineers, as that’s what we like to be called, nowadays do everything right from acting as…</em>medium.com</a><a href="https://medium.com/@gaurav.pandvia/understanding-javascript-function-executions-tasks-event-loop-call-stack-more-part-1-5683dea1f5ec" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://medium.freecodecamp.org/understanding-the-javascript-call-stack-861e41ae61d4" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.freecodecamp.org/understanding-the-javascript-call-stack-861e41ae61d4"><strong>Understanding the JavaScript call stack</strong><br />
<em>The JavaScript engine (which is found in a hosting environment like the browser), is a single-threaded interpreter…</em>medium.freecodecamp.org</a><a href="https://medium.freecodecamp.org/understanding-the-javascript-call-stack-861e41ae61d4" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://web.archive.org/web/20180701233338/https://www.valentinog.com/blog/js-execution-context-call-stack/" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://web.archive.org/web/20180701233338/https://www.valentinog.com/blog/js-execution-context-call-stack/"><strong>Javascript: What Is The Execution Context? What Is The Call Stack?</strong><br />
<em>What is the Execution Context in Javascript? I bet you don't know the answer. What are the most basic components of a…</em>web.archive.org</a><a href="https://web.archive.org/web/20180701233338/https://www.valentinog.com/blog/js-execution-context-call-stack/" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<figure><img src="https://cdn-images-1.medium.com/max/800/1*b31hiO4ynbDLRrXWEFF4aQ.png" class="graf-image" /></figure><a href="https://blog.bitsrc.io/understanding-execution-context-and-execution-stack-in-javascript-1c9ea8642dd0" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://blog.bitsrc.io/understanding-execution-context-and-execution-stack-in-javascript-1c9ea8642dd0"><strong>Understanding Execution Context and Execution Stack in Javascript</strong><br />
<em>Understanding execution context and stack to become a better Javascript developer.</em>blog.bitsrc.io</a><a href="https://blog.bitsrc.io/understanding-execution-context-and-execution-stack-in-javascript-1c9ea8642dd0" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://blog.sessionstack.com/how-does-javascript-actually-work-part-1-b0bacc073cf" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://blog.sessionstack.com/how-does-javascript-actually-work-part-1-b0bacc073cf"><strong>How JavaScript works: an overview of the engine, the runtime, and the call stack</strong><br />
<em>As JavaScript is getting more and more popular, teams are leveraging its support on many levels in their stack …</em>blog.sessionstack.com</a><a href="https://blog.sessionstack.com/how-does-javascript-actually-work-part-1-b0bacc073cf" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://medium.com/codex/scope-closures-context-in-javascript-f126f1523104" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/codex/scope-closures-context-in-javascript-f126f1523104"><strong>Breaking Down Scope, Context, And Closure In JavaScript In Simple Terms.</strong><br />
<em>“JavaScript’s global scope is like a public toilet. You can’t avoid going in there, but try to limit your contact with…</em>medium.com</a><a href="https://medium.com/codex/scope-closures-context-in-javascript-f126f1523104" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://tylermcginnis.com/ultimate-guide-to-execution-contexts-hoisting-scopes-and-closures-in-javascript/" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://tylermcginnis.com/ultimate-guide-to-execution-contexts-hoisting-scopes-and-closures-in-javascript/"><strong>The Ultimate Guide to Hoisting, Scopes, and Closures in JavaScript - ui.dev</strong><br />
<em>It may seem surprising, but in my opinion the most important and fundamental concept to understanding the JavaScript…</em>tylermcginnis.com</a><a href="https://tylermcginnis.com/ultimate-guide-to-execution-contexts-hoisting-scopes-and-closures-in-javascript/" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://dev.to/bipinrajbhar/how-javascript-works-under-the-hood-an-overview-of-javascript-engine-heap-and-call-stack-1j5o" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://dev.to/bipinrajbhar/how-javascript-works-under-the-hood-an-overview-of-javascript-engine-heap-and-call-stack-1j5o"><strong>How JavaScript Works: An Overview of JavaScript Engine, Heap, and Call Stack</strong><br />
<em>Hello everyone 👋, I hope you are doing great. So, today you are going to learn An Overview of JavaScript Engine, Heap…</em>dev.to</a><a href="https://dev.to/bipinrajbhar/how-javascript-works-under-the-hood-an-overview-of-javascript-engine-heap-and-call-stack-1j5o" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://medium.com/codex/fundamental-data-structures-in-javascript-8f9f709c15b4" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/codex/fundamental-data-structures-in-javascript-8f9f709c15b4"><strong>Fundamental Data Structures In JavaScript</strong><br />
<em>Data structures in JavaScript</em>medium.com</a><a href="https://medium.com/codex/fundamental-data-structures-in-javascript-8f9f709c15b4" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

Here’s a live code editor where you can mess with any of the examples…

<span class="graf-dropCap">H</span>ere’s a live code editor where you can mess with any of the examples…

#### Coding practice

-   <span id="824c"><a href="https://leetcode.com/" class="markup--anchor markup--li-anchor">LeetCode</a></span>
-   <span id="a528"><a href="https://www.interviewbit.com/" class="markup--anchor markup--li-anchor">InterviewBit</a></span>
-   <span id="fa41"><a href="https://codility.com/" class="markup--anchor markup--li-anchor">Codility</a></span>
-   <span id="6c61"><a href="https://www.hackerrank.com/" class="markup--anchor markup--li-anchor">HackerRank</a></span>
-   <span id="dff6"><a href="https://projecteuler.net/" class="markup--anchor markup--li-anchor">Project Euler</a></span>
-   <span id="b2dd"><a href="https://spoj.com/" class="markup--anchor markup--li-anchor">Spoj</a></span>
-   <span id="c8e8"><a href="https://code.google.com/codejam/contests.html" class="markup--anchor markup--li-anchor">Google Code Jam practice problems</a></span>
-   <span id="e8bb"><a href="https://www.hackerearth.com/" class="markup--anchor markup--li-anchor">HackerEarth</a></span>
-   <span id="e803"><a href="https://www.topcoder.com/" class="markup--anchor markup--li-anchor">Top Coder</a></span>
-   <span id="294e"><a href="https://www.codechef.com/" class="markup--anchor markup--li-anchor">CodeChef</a></span>
-   <span id="9c05"><a href="https://www.codewars.com/" class="markup--anchor markup--li-anchor">Codewars</a></span>
-   <span id="356e"><a href="https://codesignal.com/" class="markup--anchor markup--li-anchor">CodeSignal</a></span>
-   <span id="2d20"><a href="http://codekata.com/" class="markup--anchor markup--li-anchor">CodeKata</a></span>
-   <span id="d3bf"><a href="https://www.firecode.io/" class="markup--anchor markup--li-anchor">Firecode</a></span>

### Dependent on data

> *Something that data structure and algorithms have in common when talking about time complexity is that they are both dealing with data. When you deal with data you become dependent on them and as a result the time complexity is also dependent of the data that you received. To solve this problem we talk about 3 different time complexity.*

-   <span id="bc8d">**The best-case complexity: when the data looks the best**</span>
-   <span id="8b06">**The worst-case complexity: when the data looks the worst**</span>
-   <span id="881c">**The average-case complexity: when the data looks average**</span>

### Big O notation

The complexity is usually expressed with the Big O notation. The wikipedia page about this subject is pretty complex but you can find here a good summary of the different complexity for the most famous data structures and sorting algorithms.

### The Array data structure

<figure><img src="https://cdn-images-1.medium.com/max/800/0*Qk3UYgeqXamRrFLR.gif" class="graf-image" /></figure>### Definition

An Array data structure, or simply an Array, is a data structure consisting of a collection of elements (values or variables), each identified by at least one array index or key. The simplest type of data structure is a linear array, also called one-dimensional array. From Wikipedia

Arrays are among the oldest and most important data structures and are used by every program. They are also used to implement many other data structures.

<a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Data_structures#Primitive_values" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Data_structures#Primitive_values"><strong>JavaScript data types and data structures - JavaScript | MDN</strong><br />
<em>Programming languages all have built-in data structures, but these often differ from one language to another. This…</em>developer.mozilla.org</a><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Data_structures#Primitive_values" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="http://2ality.com/2012/04/number-encoding.html" class="markup--anchor markup--mixtapeEmbed-anchor" title="http://2ality.com/2012/04/number-encoding.html"><strong>How numbers are encoded in JavaScript</strong><br />
<em>Edit description</em>2ality.com</a><a href="http://2ality.com/2012/04/number-encoding.html" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://medium.com/angular-in-depth/javascripts-number-type-8d59199db1b6" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/angular-in-depth/javascripts-number-type-8d59199db1b6"><strong>Here is what you need to know about JavaScript’s Number type</strong><br />
<em>Why 0.1+0.2 IS NOT equal to 0.3 and 9007199254740992 IS equal to 9007199254740993</em>medium.com</a><a href="https://medium.com/angular-in-depth/javascripts-number-type-8d59199db1b6" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://blog.chewxy.com/2014/02/24/what-every-javascript-developer-should-know-about-floating-point-numbers/" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://blog.chewxy.com/2014/02/24/what-every-javascript-developer-should-know-about-floating-point-numbers/"><strong>What Every JavaScript Developer Should Know About Floating Point Numbers</strong><br />
<em>After I gave my talk on JavaScript (really, I was there trying to shamelessly plug my book - Underhanded JavaScript and…</em>blog.chewxy.com</a><a href="https://blog.chewxy.com/2014/02/24/what-every-javascript-developer-should-know-about-floating-point-numbers/" class="js-mixtapeImage mixtapeImage mixtapeImage--empty u-ignoreBlock"></a>

<a href="https://javascriptweblog.wordpress.com/2010/09/27/the-secret-life-of-javascript-primitives/" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://javascriptweblog.wordpress.com/2010/09/27/the-secret-life-of-javascript-primitives/"><strong>The Secret Life of JavaScript Primitives</strong><br />
<em>You may not know it but, in JavaScript, whenever you interact with string, number or boolean primitives you enter a…</em>javascriptweblog.wordpress.com</a><a href="https://javascriptweblog.wordpress.com/2010/09/27/the-secret-life-of-javascript-primitives/" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

### <a href="https://javascript.info/primitives-methods#a-primitive-as-an-object" class="markup--anchor markup--h3-anchor">A primitive as an object</a>

Here’s the paradox faced by the creator of JavaScript:

-   <span id="95d1">There are many things one would want to do with a primitive like a string or a number. It would be great to access them using methods.</span>
-   <span id="10fe">Primitives must be as fast and lightweight as possible.</span>

The solution looks a little bit awkward, but here it is:

1.  <span id="4506">Primitives are still primitive. A single value, as desired.</span>
2.  <span id="7880">The language allows access to methods and properties of strings, numbers, booleans and symbols.</span>
3.  <span id="be72">In order for that to work, a special “object wrapper” that provides the extra functionality is created, and then is destroyed.</span>

The “object wrappers” are different for each primitive type and are called: `String`, `Number`, `Boolean` and `Symbol`. Thus, they provide different sets of methods.

For instance, there exists a string method <a href="https://developer.mozilla.org/en/docs/Web/JavaScript/Reference/Global_Objects/String/toUpperCase" class="markup--anchor markup--p-anchor">str.toUpperCase()</a> that returns a capitalized `str`.

Here’s how it works:

    let str = "Hello";

    alert( str.toUpperCase() ); // HELLO

Simple, right? Here’s what actually happens in `str.toUpperCase()`:

1.  <span id="5a30">The string `str` is a primitive. So in the moment of accessing its property, a special object is created that knows the value of the string, and has useful methods, like `toUpperCase()`.</span>
2.  <span id="7659">That method runs and returns a new string (shown by `alert`).</span>
3.  <span id="8c3f">The special object is destroyed, leaving the primitive `str` alone.</span>

So primitives can provide methods, but they still remain lightweight.

The JavaScript engine highly optimizes this process. It may even skip the creation of the extra object at all. But it must still adhere to the specification and behave as if it creates one.

<a href="https://flow.org/en/docs/types/primitives/" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://flow.org/en/docs/types/primitives/"><strong>Primitive Types | Flow</strong><br />
<em>JavaScript has a number of different primitive types ( MDN): The primitive types appear in the language as either…</em>flow.org</a><a href="https://flow.org/en/docs/types/primitives/" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://dev.to/d4nyll/not-everything-in-javascript-is-an-object" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://dev.to/d4nyll/not-everything-in-javascript-is-an-object"><strong>(Not) Everything in JavaScript is an Object</strong><br />
<em>This was originally published on The Brewing Press For those who just wants the answers, feel free to jump to the…</em>dev.to</a><a href="https://dev.to/d4nyll/not-everything-in-javascript-is-an-object" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://medium.com/codex/objects-in-javascript-b212486dade6" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/codex/objects-in-javascript-b212486dade6"><strong>Objects In JavaScript</strong><br />
<em>The object is a data structure that stores other data, similar to how an array stores elements.</em>medium.com</a><a href="https://medium.com/codex/objects-in-javascript-b212486dade6" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://blog.bitsrc.io/diving-deeper-in-javascripts-objects-318b1e13dc12" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://blog.bitsrc.io/diving-deeper-in-javascripts-objects-318b1e13dc12"><strong>Diving Deeper in JavaScripts Objects</strong><br />
<em>A Closer Look at JavaScript Object Descriptors</em>blog.bitsrc.io</a><a href="https://blog.bitsrc.io/diving-deeper-in-javascripts-objects-318b1e13dc12" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://medium.com/@bolajiayodeji/the-differences-between-object-freeze-vs-const-in-javascript-4eacea534d7c" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/@bolajiayodeji/the-differences-between-object-freeze-vs-const-in-javascript-4eacea534d7c"><strong>The differences between Object.freeze() vs Const in JavaScript</strong><br />
<em>ES6 has brought several new features and methods into JavaScript since its release. These features have better improved…</em>medium.com</a><a href="https://medium.com/@bolajiayodeji/the-differences-between-object-freeze-vs-const-in-javascript-4eacea534d7c" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://codeburst.io/explaining-value-vs-reference-in-javascript-647a975e12a0" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://codeburst.io/explaining-value-vs-reference-in-javascript-647a975e12a0"><strong>Explaining Value vs. Reference in Javascript</strong><br />
<em>A simple look at computer memory explains what’s happening</em>codeburst.io</a><a href="https://codeburst.io/explaining-value-vs-reference-in-javascript-647a975e12a0" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

### DOES IT MUTATE:

<a href="https://doesitmutate.xyz/" class="markup--anchor markup--p-anchor">LINK….</a>

### <a href="https://doesitmutate.xyz/concat" class="markup--anchor markup--h3-anchor">.concat</a>

no mutation

### Description

The concat() method is used to merge two or more arrays. This method does not change the existing arrays, but instead returns a new array.

    Array.prototype.concat ( [ item1 [ , item2 [ , … ] ] ] )

<a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/concat" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/concat"><strong>Array.prototype.concat() - JavaScript | MDN</strong><br />
<em>The concat() method is used to merge two or more arrays. This method does not change the existing arrays, but instead…</em>developer.mozilla.org</a><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/concat" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

### Example

    var array1 = ['a', 'b', 'c'];
    var array2 = ['d', 'e', 'f'];

    console.log(array1.concat(array2));
    // expected output: Array ["a", "b", "c", "d", "e", "f"]

#### <a href="https://doesitmutate.xyz/copywithin" class="markup--anchor markup--h4-anchor">.copyWithin()</a>

**mutates**

### Description

The copyWithin() method shallow copies part of an array to another location in the same array and returns it, without modifying its size.

    arr.copyWithin(target)
    arr.copyWithin(target, start)
    arr.copyWithin(target, start, end)

<a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/copyWithin" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/copyWithin"><strong>Array.prototype.copyWithin() - JavaScript | MDN</strong><br />
<em>The copyWithin() method shallow copies part of an array to another location in the same array and returns it without…</em>developer.mozilla.org</a><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/copyWithin" class="js-mixtapeImage mixtapeImage mixtapeImage--empty u-ignoreBlock"></a>

### Example

    var array1 = ['a', 'b', 'c', 'd', 'e'];

    // copy to index 0 the element at index 3
    console.log(array1.copyWithin(0, 3, 4));
    // expected output: Array ["d", "b", "c", "d", "e"]

    // copy to index 1 all elements from index 3 to the end
    console.log(array1.copyWithin(1, 3));
    // expected output: Array ["d", "d", "e", "d", "e"]

### <a href="https://doesitmutate.xyz/entries" class="markup--anchor markup--h3-anchor">.entries()</a>

#### no mutation

### Description

The entries() method returns a new Array Iterator object that contains the key/value pairs for each index in the array.

    a.entries()

<a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/entries" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/entries"><strong>Array.prototype.entries() - JavaScript | MDN</strong><br />
<em>The entries() method returns a new Array Iterator object that contains the key/value pairs for each index in the array.</em>developer.mozilla.org</a><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/entries" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

### Example

    var array1 = ['a', 'b', 'c'];

    var iterator1 = array1.entries();

    console.log(iterator1.next().value);
    // expected output: Array [0, "a"]

    console.log(iterator1.next().value);
    // expected output: Array [1, "b"]

### <a href="https://doesitmutate.xyz/every" class="markup--anchor markup--h3-anchor">.every</a>

#### no mutation

### Description

The every() method tests whether all elements in the array pass the test implemented by the provided function.

    Array.prototype.every ( callbackfn [ , thisArg ] )

<a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/every" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/every"><strong>Array.prototype.every() - JavaScript | MDN</strong><br />
<em>The every() method tests whether all elements in the array pass the test implemented by the provided function. It…</em>developer.mozilla.org</a><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/every" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

### Example

    function isBelowThreshold(currentValue) {
      return currentValue < 40;
    }

    var array1 = [1, 30, 39, 29, 10, 13];

    console.log(array1.every(isBelowThreshold));
    // expected output: true

### <a href="https://doesitmutate.xyz/fill" class="markup--anchor markup--h3-anchor">.fill()</a>

#### mutates

### Description

The fill() method fills all the elements of an array from a start index to an end index with a static value.

    arr.fill(value)
    arr.fill(value, start)
    arr.fill(value, start, end)

<a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/fill" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/fill"><strong>Array.prototype.fill() - JavaScript | MDN</strong><br />
<em>The fill() method changes all elements in an array to a static value, from a start index (default 0) to an end index…</em>developer.mozilla.org</a><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/fill" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

### Example :

    var array1 = [1, 2, 3, 4];

    // fill with 0 from position 2 until position 4
    console.log(array1.fill(0, 2, 4));
    // expected output: [1, 2, 0, 0]

    // fill with 5 from position 1
    console.log(array1.fill(5, 1));
    // expected output: [1, 5, 5, 5]

    console.log(array1.fill(6));
    // expected output: [6, 6, 6, 6]

### <a href="https://doesitmutate.xyz/filter" class="markup--anchor markup--h3-anchor">.filter</a>

#### no mutation

### Description

The filter() method creates a new array with all elements that pass the test implemented by the provided function.

    Array.prototype.filter ( callbackfn [ , thisArg ] )

<a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/filter" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/filter"><strong>Array.prototype.filter() - JavaScript | MDN</strong><br />
<em>The method creates a new array with all elements that pass the test implemented by the provided function. Function is a…</em>developer.mozilla.org</a><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/filter" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

### Example

    var words = ['spray', 'limit', 'elite', 'exuberant', 'destruction', 'present'];

    const result = words.filter(word => word.length > 6);

    console.log(result);
    // expected output: Array ["exuberant", "destruction", "present"]

### <a href="https://doesitmutate.xyz/find" class="markup--anchor markup--h3-anchor">.find()</a>

no mutation

### Description

The find() method returns a value of the first element in the array that satisfies the provided testing function. Otherwise undefined is returned.

    arr.find(callback[, thisArg])

<a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/find" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/find"><strong>Array.prototype.find() - JavaScript | MDN</strong><br />
<em>The find() method returns the value of the first element in the provided array that satisfies the provided testing…</em>developer.mozilla.org</a><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/find" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

### Example

    var array1 = [5, 12, 8, 130, 44];

    var found = array1.find(function(element) {
      return element > 10;
    });

    console.log(found);
    // expected output: 12

<a href="https://medium.com/@_benaston/lesson-1b-javascript-fundamentals-380f601ba851" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/@_benaston/lesson-1b-javascript-fundamentals-380f601ba851"><strong>Value types, reference types and scope in JavaScript</strong><br />
<em>There are only two things fundamental to JavaScript: objects and functions.</em>medium.com</a><a href="https://medium.com/@_benaston/lesson-1b-javascript-fundamentals-380f601ba851" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://medium.com/dailyjs/back-to-roots-javascript-value-vs-reference-8fb69d587a18" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/dailyjs/back-to-roots-javascript-value-vs-reference-8fb69d587a18"><strong>Back to roots: JavaScript Value vs Reference</strong><br />
<em>Let’s look at the concept of Value vs Reference. Every JavaScript developer should know this topic as it’s often the…</em>medium.com</a><a href="https://medium.com/dailyjs/back-to-roots-javascript-value-vs-reference-8fb69d587a18" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://hackernoon.com/grasp-by-value-and-by-reference-in-javascript-7ed75efa1293" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://hackernoon.com/grasp-by-value-and-by-reference-in-javascript-7ed75efa1293"><strong>Grasp “By Value” and “By Reference” in JavaScript</strong><br />
<em>And learn why it’s crucial to know the difference</em>hackernoon.com</a><a href="https://hackernoon.com/grasp-by-value-and-by-reference-in-javascript-7ed75efa1293" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://hackernoon.com/javascript-reference-and-copy-variables-b0103074fdf0" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://hackernoon.com/javascript-reference-and-copy-variables-b0103074fdf0"><strong>JavaScript Reference and Copy Variables | Hacker Noon</strong><br />
<em>Each programming language has its own peculiarities (and JavaScript has a lot), and today I'm going to talk about…</em>hackernoon.com</a><a href="https://hackernoon.com/javascript-reference-and-copy-variables-b0103074fdf0" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="http://www.javascripttutorial.net/javascript-primitive-vs-reference-values/" class="markup--anchor markup--mixtapeEmbed-anchor" title="http://www.javascripttutorial.net/javascript-primitive-vs-reference-values/"><strong>JavaScript Primitive vs. Reference Values</strong><br />
<em>Summary: in this tutorial, you will learn the differences between primitive and reference values. In JavaScript, a…</em>www.javascripttutorial.net</a><a href="http://www.javascripttutorial.net/javascript-primitive-vs-reference-values/" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://stackoverflow.com/questions/6605640/javascript-by-reference-vs-by-value" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://stackoverflow.com/questions/6605640/javascript-by-reference-vs-by-value"><strong>JavaScript by reference vs. by value</strong><br />
<em>I'm looking for some good comprehensive reading material on when JavaScript passes something by value and when by…</em>stackoverflow.com</a><a href="https://stackoverflow.com/questions/6605640/javascript-by-reference-vs-by-value" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://dev.to/mostlyfocusedmike/javascript-interview-prep-primitive-vs-reference-types-3o4f" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://dev.to/mostlyfocusedmike/javascript-interview-prep-primitive-vs-reference-types-3o4f"><strong>JavaScript Interview Prep: Primitive vs. Reference Types</strong><br />
<em>original article In a JavaScript interview, they might ask if you understand the difference between primitive and…</em>dev.to</a><a href="https://dev.to/mostlyfocusedmike/javascript-interview-prep-primitive-vs-reference-types-3o4f" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://dev.to/promhize/what-you-need-to-know-about-javascripts-implicit-coercion-e23" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://dev.to/promhize/what-you-need-to-know-about-javascripts-implicit-coercion-e23"><strong>What you need to know about Javascript's Implicit Coercion</strong><br />
<em>Javascript's implicit coercion simply refers to Javascript attempting to coerce an unexpected value type to the…</em>dev.to</a><a href="https://dev.to/promhize/what-you-need-to-know-about-javascripts-implicit-coercion-e23" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://medium.freecodecamp.org/js-type-coercion-explained-27ba3d9a2839" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.freecodecamp.org/js-type-coercion-explained-27ba3d9a2839"><strong>JavaScript type coercion explained</strong><br />
<em>Know your engines</em>medium.freecodecamp.org</a><a href="https://medium.freecodecamp.org/js-type-coercion-explained-27ba3d9a2839" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://hackernoon.com/javascript-coercion-explained-545c895213d3" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://hackernoon.com/javascript-coercion-explained-545c895213d3"><strong>Javascript Coercion Explained</strong><br />
<em>Along with some practical examples</em>hackernoon.com</a><a href="https://hackernoon.com/javascript-coercion-explained-545c895213d3" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://stackoverflow.com/questions/19915688/what-exactly-is-type-coercion-in-javascript" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://stackoverflow.com/questions/19915688/what-exactly-is-type-coercion-in-javascript"><strong>What exactly is Type Coercion in Javascript?</strong><br />
<em>Let's start with a short intro to type systems which I think will help you understand the general idea of type…</em>stackoverflow.com</a><a href="https://stackoverflow.com/questions/19915688/what-exactly-is-type-coercion-in-javascript" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://thedevs.network/blog/type-coercion-in-javascript-and-why-everyone-gets-it-wrong" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://thedevs.network/blog/type-coercion-in-javascript-and-why-everyone-gets-it-wrong"><strong>https://thedevs.network/</strong><br />
<em>Weak dynamic typing is arguably one of those things everybody likes to pick at about JavaScript. For an elegant dynamic…</em>thedevs.network</a><a href="https://thedevs.network/blog/type-coercion-in-javascript-and-why-everyone-gets-it-wrong" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://github.com/getify/You-Dont-Know-JS/tree/1st-ed" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://github.com/getify/You-Dont-Know-JS/tree/1st-ed"><strong>getify/You-Dont-Know-JS</strong><br />
<em>A book series on JavaScript. @YDKJS on twitter. Contribute to getify/You-Dont-Know-JS development by creating an…</em>github.com</a><a href="https://github.com/getify/You-Dont-Know-JS/tree/1st-ed" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://codeburst.io/javascript-double-equals-vs-triple-equals-61d4ce5a121a" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://codeburst.io/javascript-double-equals-vs-triple-equals-61d4ce5a121a"><strong>JavaScript — Double Equals vs. Triple Equals</strong><br />
<em>Learn equality in JavaScript in 3 minutes</em>codeburst.io</a><a href="https://codeburst.io/javascript-double-equals-vs-triple-equals-61d4ce5a121a" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://bytearcher.com/articles/equality-comparison-operator-javascript/" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://bytearcher.com/articles/equality-comparison-operator-javascript/"><strong>Should I use === or == equality comparison operator in JavaScript?</strong><br />
<em>You know there are two different equality comparison operators in JavaScript: the === and == operators, or the triple…</em>bytearcher.com</a><a href="https://bytearcher.com/articles/equality-comparison-operator-javascript/" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://www.codementor.io/javascript/tutorial/double-equals-and-coercion-in-javascript" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://www.codementor.io/javascript/tutorial/double-equals-and-coercion-in-javascript"><strong>== vs === JavaScript: Double Equals and Coercion | Codementor</strong><br />
<em>The == (double equals or loose equality) operator is an interesting operator. Many avoid it because they don't know how…</em>www.codementor.io</a><a href="https://www.codementor.io/javascript/tutorial/double-equals-and-coercion-in-javascript" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://www.impressivewebs.com/why-use-triple-equals-javascipt/" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://www.impressivewebs.com/why-use-triple-equals-javascipt/"><strong>Why Use the Triple-Equals Operator in JavaScript? - Impressive Webs</strong><br />
<em>"Determining whether two variables are equivalent is one of the most important operations in programming." That's…</em>www.impressivewebs.com</a><a href="https://www.impressivewebs.com/why-use-triple-equals-javascipt/" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://www.oreilly.com/learning/what-is-the-difference-between-and-in-javascript" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://www.oreilly.com/learning/what-is-the-difference-between-and-in-javascript"><strong>What is the difference between == and === in JavaScript?</strong><br />
<em>On the surface == and === appear to be functionally the same, so why bother typing an extra character? In this video…</em>www.oreilly.com</a><a href="https://www.oreilly.com/learning/what-is-the-difference-between-and-in-javascript" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://stackoverflow.com/questions/3787901/why-javascripts-typeof-always-return-object" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://stackoverflow.com/questions/3787901/why-javascripts-typeof-always-return-object"><strong>Why javascript's typeof always return "object"?</strong><br />
<em>To add in with the others, typeof returns both objects and primitives. There are 5 primitive types in javascript…</em>stackoverflow.com</a><a href="https://stackoverflow.com/questions/3787901/why-javascripts-typeof-always-return-object" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="http://tobyho.com/2011/01/28/checking-types-in-javascript/" class="markup--anchor markup--mixtapeEmbed-anchor" title="http://tobyho.com/2011/01/28/checking-types-in-javascript/"><strong>Checking Types in Javascript</strong><br />
<em>Have you ever wondered: what is the correct way to check if a Javascript variable is an Array? Do a Google search and…</em>tobyho.com</a><a href="http://tobyho.com/2011/01/28/checking-types-in-javascript/" class="js-mixtapeImage mixtapeImage mixtapeImage--empty u-ignoreBlock"></a>

<a href="https://webbjocke.com/javascript-check-data-types/" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://webbjocke.com/javascript-check-data-types/"><strong>How to better check data types in javascript - Webbjocke</strong><br />
<em>To check what data type something has in javascript is not always the easiest. The language itself provides an operator…</em>webbjocke.com</a><a href="https://webbjocke.com/javascript-check-data-types/" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://tomeraberba.ch/html/post/checking-for-the-absence-of-a-value-in-javascript.html" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://tomeraberba.ch/html/post/checking-for-the-absence-of-a-value-in-javascript.html"><strong>Tomer Aberbach | Checking for the Absence of a Value in JavaScript</strong><br />
<em>When I first started learning JavaScript I was confused by the seemingly endless ways developers check for the absence…</em>tomeraberba.ch</a><a href="https://tomeraberba.ch/html/post/checking-for-the-absence-of-a-value-in-javascript.html" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://github.com/getify/You-Dont-Know-JS/tree/2nd-ed/scope-closures" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://github.com/getify/You-Dont-Know-JS/tree/2nd-ed/scope-closures"><strong>getify/You-Dont-Know-JS</strong><br />
<em>A book series on JavaScript. @YDKJS on twitter. Contribute to getify/You-Dont-Know-JS development by creating an…</em>github.com</a><a href="https://github.com/getify/You-Dont-Know-JS/tree/2nd-ed/scope-closures" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://codeburst.io/javascript-functions-understanding-the-basics-207dbf42ed99" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://codeburst.io/javascript-functions-understanding-the-basics-207dbf42ed99"><strong>JavaScript Functions — Understanding The Basics</strong><br />
<em>Explore Functions in JavaScript — declaration, expressions, invocation, and more.</em>codeburst.io</a><a href="https://codeburst.io/javascript-functions-understanding-the-basics-207dbf42ed99" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="http://www.deadcoderising.com/2017-04-11-es6-var-let-and-const-the-battle-between-function-scope-and-block-scope/" class="markup--anchor markup--mixtapeEmbed-anchor" title="http://www.deadcoderising.com/2017-04-11-es6-var-let-and-const-the-battle-between-function-scope-and-block-scope/"><strong>ES6: var, let and const - The battle between function scope and block scope</strong><br />
<em>In the pre-ES6 era, there was only one way of declaring variables in JavaScript - being the usage of var. var has…</em>www.deadcoderising.com</a><a href="http://www.deadcoderising.com/2017-04-11-es6-var-let-and-const-the-battle-between-function-scope-and-block-scope/" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="http://adripofjavascript.com/blog/drips/emulating-block-scope-in-javascript.html" class="markup--anchor markup--mixtapeEmbed-anchor" title="http://adripofjavascript.com/blog/drips/emulating-block-scope-in-javascript.html"><strong>Emulating Block Scope in JavaScript</strong><br />
<em>While there are many issues that trip up developers coming from other languages, variable scoping may be number one…</em>adripofjavascript.com</a><a href="http://adripofjavascript.com/blog/drips/emulating-block-scope-in-javascript.html" class="js-mixtapeImage mixtapeImage mixtapeImage--empty u-ignoreBlock"></a>

<a href="https://josephcardillo.medium.com/the-difference-between-function-and-block-scope-in-javascript-4296b2322abe" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://josephcardillo.medium.com/the-difference-between-function-and-block-scope-in-javascript-4296b2322abe"><strong>The Difference Between Function and Block Scope in JavaScript</strong><br />
<em>Back to the basics with the var, let and const variables</em>josephcardillo.medium.com</a><a href="https://josephcardillo.medium.com/the-difference-between-function-and-block-scope-in-javascript-4296b2322abe" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://edgecoders.com/function-scopes-and-block-scopes-in-javascript-25bbd7f293d7" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://edgecoders.com/function-scopes-and-block-scopes-in-javascript-25bbd7f293d7"><strong>Function scopes and block scopes in JavaScript</strong><br />
<em>Is the following line a valid line of JavaScript code?</em>edgecoders.com</a><a href="https://edgecoders.com/function-scopes-and-block-scopes-in-javascript-25bbd7f293d7" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="http://ryanmorr.com/understanding-scope-and-context-in-javascript/" class="markup--anchor markup--mixtapeEmbed-anchor" title="http://ryanmorr.com/understanding-scope-and-context-in-javascript/"><strong>Understanding Scope and Context in JavaScript</strong><br />
<em>Understanding Scope and Context in JavaScript August 16, 2013 JavaScript JavaScript's implementation of scope and…</em>ryanmorr.com</a><a href="http://ryanmorr.com/understanding-scope-and-context-in-javascript/" class="js-mixtapeImage mixtapeImage mixtapeImage--empty u-ignoreBlock"></a>

<a href="https://css-tricks.com/javascript-scope-closures/" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://css-tricks.com/javascript-scope-closures/"><strong>JavaScript Scope and Closures</strong><br />
<em>Scopes and closures are important in JavaScript. But, they were confusing for me when I first started. Here's an…</em>css-tricks.com</a><a href="https://css-tricks.com/javascript-scope-closures/" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://developer.telerik.com/topics/web-development/understanding-scope-in-javascript/" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://developer.telerik.com/topics/web-development/understanding-scope-in-javascript/"><strong>Understanding Scope in JavaScript - Telerik Blogs</strong><br />
<em>Scope is an important, yet ambiguous concept in JavaScript. Used correctly, it allows you to leverage good design…</em>developer.telerik.com</a><a href="https://developer.telerik.com/topics/web-development/understanding-scope-in-javascript/" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="http://speakingjs.com/es5/ch16.html" class="markup--anchor markup--mixtapeEmbed-anchor" title="http://speakingjs.com/es5/ch16.html"><strong>Chapter 16. Variables: Scopes, Environments, and Closures</strong><br />
<em>Chapter 16. Variables: Scopes, Environments, and Closures This chapter first explains how to use variables and then…</em>speakingjs.com</a><a href="http://speakingjs.com/es5/ch16.html" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://scotch.io/tutorials/understanding-scope-in-javascript" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://scotch.io/tutorials/understanding-scope-in-javascript"><strong>Understanding Scope in JavaScript</strong><br />
<em>JavaScript has a feature called Scope. Though the concept of scope is not that easy to understand for many new…</em>scotch.io</a><a href="https://scotch.io/tutorials/understanding-scope-in-javascript" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://medium.freecodecamp.org/when-to-use-a-function-declarations-vs-a-function-expression-70f15152a0a0" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.freecodecamp.org/when-to-use-a-function-declarations-vs-a-function-expression-70f15152a0a0"><strong>When to use a function declaration vs. a function expression</strong><br />
<em>The differences between them and when to use one or the other.</em>medium.freecodecamp.org</a><a href="https://medium.freecodecamp.org/when-to-use-a-function-declarations-vs-a-function-expression-70f15152a0a0" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://dev.to/alexandrafren/a-javascript-fundamentals-cheat-sheet-scope-context-and-this-28ai" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://dev.to/alexandrafren/a-javascript-fundamentals-cheat-sheet-scope-context-and-this-28ai"><strong>A JavaScript Fundamentals Cheat Sheet: Scope, Context, and "this"</strong><br />
<em>Scope Scope refers to where a variable can be accessed within a program. Some variables can be accessed from anywhere…</em>dev.to</a><a href="https://dev.to/alexandrafren/a-javascript-fundamentals-cheat-sheet-scope-context-and-this-28ai" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://www.sitepoint.com/function-expressions-vs-declarations/" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://www.sitepoint.com/function-expressions-vs-declarations/"><strong>Quick Tip: Function Expressions vs Function Declarations - SitePoint</strong><br />
<em>This article was peer reviewed by Jeff Mott. Thanks to all of SitePoint's peer reviewers for making SitePoint content…</em>www.sitepoint.com</a><a href="https://www.sitepoint.com/function-expressions-vs-declarations/" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://medium.com/@raviroshan.talk/javascript-function-declaration-vs-expression-f5873b8c7b38" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/@raviroshan.talk/javascript-function-declaration-vs-expression-f5873b8c7b38"><strong>JavaScript Function — Declaration vs Expression</strong><br />
<em>Functions are considered as First Class citizen in JavaScript and it is really important to be clear with the concept…</em>medium.com</a><a href="https://medium.com/@raviroshan.talk/javascript-function-declaration-vs-expression-f5873b8c7b38" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://medium.com/@mandeep1012/function-declarations-vs-function-expressions-b43646042052" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/@mandeep1012/function-declarations-vs-function-expressions-b43646042052"><strong>Function Declarations vs. Function Expressions</strong><br />
<em>What is Function Statement/Declarations in JavaScript?</em>medium.com</a><a href="https://medium.com/@mandeep1012/function-declarations-vs-function-expressions-b43646042052" class="js-mixtapeImage mixtapeImage mixtapeImage--empty u-ignoreBlock"></a>

<a href="https://javascriptweblog.wordpress.com/2010/07/06/function-declarations-vs-function-expressions/" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://javascriptweblog.wordpress.com/2010/07/06/function-declarations-vs-function-expressions/"><strong>Function Declarations vs. Function Expressions</strong><br />
<em>Lets start with a short quiz. What is alerted in each case?: Question 1: Question 2: Question 3: Question 4: If you…</em>javascriptweblog.wordpress.com</a><a href="https://javascriptweblog.wordpress.com/2010/07/06/function-declarations-vs-function-expressions/" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://vvkchandra.medium.com/essential-javascript-mastering-immediately-invoked-function-expressions-67791338ddc6" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://vvkchandra.medium.com/essential-javascript-mastering-immediately-invoked-function-expressions-67791338ddc6"><strong>Essential JavaScript: Mastering Immediately-invoked Function Expressions</strong><br />
<em>Understanding functions inside out and then learning how to exploit them to write modern, clean JavaScript code is a…</em>vvkchandra.medium.com</a><a href="https://vvkchandra.medium.com/essential-javascript-mastering-immediately-invoked-function-expressions-67791338ddc6" class="js-mixtapeImage mixtapeImage mixtapeImage--empty u-ignoreBlock"></a>

<a href="https://hashnode.com/post/do-es6-modules-make-the-case-of-iifes-obsolete-civ96wet80scqgc538un20es0" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://hashnode.com/post/do-es6-modules-make-the-case-of-iifes-obsolete-civ96wet80scqgc538un20es0"><strong>Do ES6 Modules make the case of IIFEs obsolete? - Hashnode</strong><br />
<em>IIFE was one of the most used patterns in the ES5 standard, as functions were the only way to declare a scoped block of…</em>hashnode.com</a><a href="https://hashnode.com/post/do-es6-modules-make-the-case-of-iifes-obsolete-civ96wet80scqgc538un20es0" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://www.jvandemo.com/a-10-minute-primer-to-javascript-modules-module-formats-module-loaders-and-module-bundlers/" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://www.jvandemo.com/a-10-minute-primer-to-javascript-modules-module-formats-module-loaders-and-module-bundlers/"><strong>A 10 minute primer to JavaScript modules, module formats, module loaders and module bundlers</strong><br />
<em>Modern JavaScript development can be overwhelming. When working on a project, you may wonder why all the modern…</em>www.jvandemo.com</a><a href="https://www.jvandemo.com/a-10-minute-primer-to-javascript-modules-module-formats-module-loaders-and-module-bundlers/" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="http://exploringjs.com/es6/ch_modules.html" class="markup--anchor markup--mixtapeEmbed-anchor" title="http://exploringjs.com/es6/ch_modules.html"><strong>16. Modules</strong><br />
<em>Edit description</em>exploringjs.com</a><a href="http://exploringjs.com/es6/ch_modules.html" class="js-mixtapeImage mixtapeImage mixtapeImage--empty u-ignoreBlock"></a>

<a href="https://hacks.mozilla.org/2018/03/es-modules-a-cartoon-deep-dive/" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://hacks.mozilla.org/2018/03/es-modules-a-cartoon-deep-dive/"><strong>ES modules: A cartoon deep-dive - Mozilla Hacks - the Web developer blog</strong><br />
<em>ES modules bring an official, standardized module system to JavaScript. With the release of Firefox 60 in May, all…</em>hacks.mozilla.org</a><a href="https://hacks.mozilla.org/2018/03/es-modules-a-cartoon-deep-dive/" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://www.sitepoint.com/understanding-es6-modules/" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://www.sitepoint.com/understanding-es6-modules/"><strong>Understanding ES6 Modules - SitePoint</strong><br />
<em>Almost every language has a concept of modules - a way to include functionality declared in one file within another…</em>www.sitepoint.com</a><a href="https://www.sitepoint.com/understanding-es6-modules/" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://blog.cloud66.com/an-overview-of-es6-modules-in-javascript/" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://blog.cloud66.com/an-overview-of-es6-modules-in-javascript/"><strong>An overview of ES6 Modules in JavaScript</strong><br />
<em>Introduction Until recently if you wanted to take full advantage of modules in JavaScript you needed to make use of…</em>blog.cloud66.com</a><a href="https://blog.cloud66.com/an-overview-of-es6-modules-in-javascript/" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://ponyfoo.com/articles/es6-modules-in-depth" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://ponyfoo.com/articles/es6-modules-in-depth"><strong>ES6 Modules in Depth</strong><br />
<em>Welcome back to ES6 - "Oh, good. It's not another article about Unicode" - in Depth series. If you've never been around…</em>ponyfoo.com</a><a href="https://ponyfoo.com/articles/es6-modules-in-depth" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://medium.com/dailyjs/es6-modules-node-js-and-the-michael-jackson-solution-828dc244b8b" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/dailyjs/es6-modules-node-js-and-the-michael-jackson-solution-828dc244b8b"><strong>ES6 modules, Node.js and the Michael Jackson Solution</strong><br />
<em>JavaScript’s never had a standard way to import and export functionality from a source file to another. Well, it has…</em>medium.com</a><a href="https://medium.com/dailyjs/es6-modules-node-js-and-the-michael-jackson-solution-828dc244b8b" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://medium.freecodecamp.org/javascript-modules-a-beginner-s-guide-783f7d7a5fcc" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.freecodecamp.org/javascript-modules-a-beginner-s-guide-783f7d7a5fcc"><strong>JavaScript Modules: A Beginner’s Guide</strong><br />
<em>If you’re a newcomer to JavaScript, jargon like “module bundlers vs. module loaders,” “Webpack vs. Browserify” and “AMD…</em>medium.freecodecamp.org</a><a href="https://medium.freecodecamp.org/javascript-modules-a-beginner-s-guide-783f7d7a5fcc" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://developers.google.com/web/fundamentals/primers/modules" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://developers.google.com/web/fundamentals/primers/modules"><strong>JavaScript modules</strong><br />
<em>This article explains how to use JavaScript modules, how to deploy them responsibly, and how the Chrome team is working…</em>developers.google.com</a><a href="https://developers.google.com/web/fundamentals/primers/modules" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://dev.to/bhagatparwinder/iife-immediately-invoked-function-expressions-49c5" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://dev.to/bhagatparwinder/iife-immediately-invoked-function-expressions-49c5"><strong>IIFE: Immediately Invoked Function Expressions</strong><br />
<em>IIFE is a function that is declared and invoked at the same time. You create them by using anonymous functions and…</em>dev.to</a><a href="https://dev.to/bhagatparwinder/iife-immediately-invoked-function-expressions-49c5" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://medium.com/front-end-weekly/javascript-event-loop-explained-4cd26af121d4" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://medium.com/front-end-weekly/javascript-event-loop-explained-4cd26af121d4"><strong>JavaScript Event Loop Explained</strong><br />
<em>“How is JavaScript asynchronous and single-threaded ?” The short answer is that JavaScript language is single-threaded…</em>medium.com</a><a href="https://medium.com/front-end-weekly/javascript-event-loop-explained-4cd26af121d4" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://blog.carbonfive.com/2013/10/27/the-javascript-event-loop-explained/" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://blog.carbonfive.com/2013/10/27/the-javascript-event-loop-explained/"><strong>The JavaScript Event Loop: Explained</strong><br />
<em>With JavaScript approaching near-ubiquity as the scripting language of the web browser, it benefits you to have a basic…</em>blog.carbonfive.com</a><a href="https://blog.carbonfive.com/2013/10/27/the-javascript-event-loop-explained/" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://hackernoon.com/understanding-js-the-event-loop-959beae3ac40" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://hackernoon.com/understanding-js-the-event-loop-959beae3ac40"><strong>Understanding JS: The Event Loop</strong><br />
<em>Due to the amazing quantity of libraries, tools and all kinds of things that make your development easier, a lot of…</em>hackernoon.com</a><a href="https://hackernoon.com/understanding-js-the-event-loop-959beae3ac40" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://www.zeolearn.com/magazine/understanding-the-javascript-event-loop" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://www.zeolearn.com/magazine/understanding-the-javascript-event-loop"><strong>Understanding the JavaScript event loop</strong><br />
<em>If you are someone who has heard about the terms event loop, callback queue, concurrency model and call stack but…</em>www.zeolearn.com</a><a href="https://www.zeolearn.com/magazine/understanding-the-javascript-event-loop" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://code.likeagirl.io/what-the-heck-is-event-loop-1e414fccef49" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://code.likeagirl.io/what-the-heck-is-event-loop-1e414fccef49"><strong>Event loop in javascript</strong><br />
<em>If you love javascript you’ve need to learn this. One of the deeper aspects of JavaScript is it’s Event Loop. Its…</em>code.likeagirl.io</a><a href="https://code.likeagirl.io/what-the-heck-is-event-loop-1e414fccef49" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://flaviocopes.com/javascript-event-loop/" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://flaviocopes.com/javascript-event-loop/"><strong>The JavaScript Event Loop</strong><br />
<em>The Event Loop is one of the most important aspects to understand about JavaScript. I've programmed for years with…</em>flaviocopes.com</a><a href="https://flaviocopes.com/javascript-event-loop/" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://blog.sessionstack.com/how-javascript-works-event-loop-and-the-rise-of-async-programming-5-ways-to-better-coding-with-2f077c4438b5" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://blog.sessionstack.com/how-javascript-works-event-loop-and-the-rise-of-async-programming-5-ways-to-better-coding-with-2f077c4438b5"><strong>How JavaScript works: Event loop and the rise of Async programming + 5 ways to better coding with…</strong><br />
<em>Welcome to post # 4 of the series dedicated to exploring JavaScript and its building components. In the process of…</em>blog.sessionstack.com</a><a href="https://blog.sessionstack.com/how-javascript-works-event-loop-and-the-rise-of-async-programming-5-ways-to-better-coding-with-2f077c4438b5" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://jakearchibald.com/2015/tasks-microtasks-queues-and-schedules/" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://jakearchibald.com/2015/tasks-microtasks-queues-and-schedules/"><strong>Tasks, microtasks, queues and schedules</strong><br />
<em>Edit description</em>jakearchibald.com</a><a href="https://jakearchibald.com/2015/tasks-microtasks-queues-and-schedules/" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://dev.to/presto412/visualising-the-javascript-event-loop-with-a-pizza-restaurant-analogy-47a8" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://dev.to/presto412/visualising-the-javascript-event-loop-with-a-pizza-restaurant-analogy-47a8"><strong>Visualising the JavaScript Event Loop with a Pizza Restaurant analogy</strong><br />
<em>Consider a pizza restaurant. There are two types of orders that we currently have from a single customer - one is an…</em>dev.to</a><a href="https://dev.to/presto412/visualising-the-javascript-event-loop-with-a-pizza-restaurant-analogy-47a8" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://dev.to/lydiahallie/javascript-visualized-event-loop-3dif" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://dev.to/lydiahallie/javascript-visualized-event-loop-3dif"><strong>✨♻️ JavaScript Visualized: Event Loop</strong><br />
<em>Oh boi the event loop. It's one of those things that every JavaScript developer has to deal with in one way or another…</em>dev.to</a><a href="https://dev.to/lydiahallie/javascript-visualized-event-loop-3dif" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://javascript.info/settimeout-setinterval" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://javascript.info/settimeout-setinterval"><strong>Scheduling: setTimeout and setInterval</strong><br />
<em>Edit description</em>javascript.info</a><a href="https://javascript.info/settimeout-setinterval" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://dev.to/akanksha_9560/why-not-to-use-setinterval--2na9" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://dev.to/akanksha_9560/why-not-to-use-setinterval--2na9"><strong>Why not to use setInterval</strong><br />
<em>Recently, I came across a requirement where I had to call a function repeatedly after specific time interval, like…</em>dev.to</a><a href="https://dev.to/akanksha_9560/why-not-to-use-setinterval--2na9" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://develoger.com/settimeout-vs-setinterval-cff85142555b" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://develoger.com/settimeout-vs-setinterval-cff85142555b"><strong>setTimeout VS setInterval</strong><br />
<em>Intro</em>develoger.com</a><a href="https://develoger.com/settimeout-vs-setinterval-cff85142555b" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://css-tricks.com/using-requestanimationframe/" class="markup--anchor markup--mixtapeEmbed-anchor" title="https://css-tricks.com/using-requestanimationframe/"><strong>Using requestAnimationFrame</strong><br />
<em>There used to be just one way to do a timed loop in JavaScript: setInterval(). If you needed to repeat something pretty…</em>css-tricks.com</a><a href="https://css-tricks.com/using-requestanimationframe/" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="http://www.javascriptkit.com/javatutors/requestanimationframe.shtml" class="markup--anchor markup--mixtapeEmbed-anchor" title="http://www.javascriptkit.com/javatutors/requestanimationframe.shtml"><strong>Understanding JavaScript's requestAnimationFrame() method for smooth animations</strong><br />
<em>Updated: Nov 1st, 2017 The modern web of today is filled with sights to behold on every page, where menus slide in and…</em>www.javascriptkit.com</a><a href="http://www.javascriptkit.com/javatutors/requestanimationframe.shtml" class="js-mixtapeImage mixtapeImage u-ignoreBlock"></a>

<a href="https://www.amitmerchant.com/Handling-Time-Intervals-In-Javascript/" class="marku