## Table of Contents
1. [JavaScript Fundamentals](#javascript-fundamentals)
2. [TypeScript](#typescript)
3. [Object-Oriented Programming (OOP)](#object-oriented-programming-oop)
4. [React.js](#reactjs)
5. [React Native](#react-native)
6. [Node.js](#nodejs)
7. [Express.js](#expressjs)
8. [MongoDB](#mongodb)
9. [SQL & PostgreSQL](#sql--postgresql)
10. [Docker](#docker)
11. [System Design & Architecture](#system-design--architecture)
12. [Performance & Optimization](#performance--optimization)
13. [Security](#security)
14. [Testing](#testing)
15. [DevOps & Deployment](#devops--deployment)
16. [Behavioral Questions](#behavioral-questions)

---

## JavaScript Fundamentals

### Basic Concepts (Questions 1-50)

**1. What is JavaScript and how does it differ from Java?**
JavaScript is a high-level, interpreted programming language primarily used for web development. Unlike Java, it's dynamically typed, prototype-based, and runs in browsers without compilation.

**2. What are the different data types in JavaScript?**
Primitive: number, string, boolean, undefined, null, symbol, bigint
Non-primitive: object (including arrays, functions, dates)

**3. What is the difference between `var`, `let`, and `const`?**
- `var`: function-scoped, hoisted, can be redeclared
- `let`: block-scoped, hoisted but not initialized, cannot be redeclared
- `const`: block-scoped, must be initialized, cannot be reassigned

**4. Explain hoisting in JavaScript.**
Hoisting is JavaScript's behavior of moving variable and function declarations to the top of their scope during compilation phase.

**5. What is the difference between `==` and `===`?**
- `==`: performs type coercion before comparison
- `===`: strict equality, no type coercion

**6. What is closure in JavaScript?**
A closure is a function that has access to variables in its outer (lexical) scope even after the outer function has returned.

**7. What is the `this` keyword in JavaScript?**
`this` refers to the object that the function is a property of or the context in which the function is called.

**8. What are arrow functions and how do they differ from regular functions?**
Arrow functions are a concise way to write functions. They don't have their own `this`, `arguments`, `super`, or `new.target`.

**9. What is event delegation?**
Event delegation is a technique where you attach an event listener to a parent element instead of individual child elements.

**10. What is the difference between `null` and `undefined`?**
- `undefined`: variable declared but not assigned a value
- `null`: intentional absence of value

**11. What are template literals?**
Template literals use backticks (`) and allow embedded expressions with ${}.

**12. What is destructuring assignment?**
Destructuring allows unpacking values from arrays or properties from objects into distinct variables.

**13. What are spread and rest operators?**
- Spread (...): expands elements
- Rest (...): collects elements into an array

**14. What is a Promise in JavaScript?**
A Promise represents the eventual completion or failure of an asynchronous operation.

**15. What is async/await?**
Async/await is syntactic sugar for working with Promises, making asynchronous code look synchronous.

**16. What is the event loop?**
The event loop is responsible for executing code, collecting and processing events, and executing queued sub-tasks.

**17. What are higher-order functions?**
Functions that take other functions as arguments or return functions.

**18. What is the difference between call, apply, and bind?**
- `call`: invokes function with specified `this` and arguments
- `apply`: like call but takes arguments as an array
- `bind`: returns a new function with specified `this`

**19. What are prototypes in JavaScript?**
Every object has a prototype property that allows adding properties and methods to all instances.

**20. What is prototype chain?**
The prototype chain is the mechanism by which objects inherit features from one another.

**21. What are generators?**
Generator functions can pause and resume execution, yielding values.

**22. What is the difference between synchronous and asynchronous code?**
Synchronous code blocks execution until completion; asynchronous code doesn't block.

**23. What are callbacks?**
Functions passed as arguments to other functions to be executed later.

**24. What is callback hell?**
Nested callbacks that become difficult to read and maintain.

**25. What are modules in JavaScript?**
Modules are reusable pieces of code that export functionality for use in other files.

**26. What is the difference between CommonJS and ES6 modules?**
- CommonJS: `require()`/`module.exports` (Node.js)
- ES6: `import`/`export` (modern JavaScript)

**27. What is JSON?**
JavaScript Object Notation - a lightweight data interchange format.

**28. What are Web APIs?**
Browser-provided APIs like DOM, fetch, localStorage, etc.

**29. What is the DOM?**
Document Object Model - programming interface for HTML documents.

**30. What are cookies?**
Small pieces of data stored in the browser for websites.

**31. What is localStorage vs sessionStorage?**
- localStorage: persists until explicitly cleared
- sessionStorage: cleared when tab closes

**32. What is CORS?**
Cross-Origin Resource Sharing - mechanism allowing restricted resources to be requested from another domain.

**33. What are regular expressions?**
Patterns used to match character combinations in strings.

**34. What is type coercion?**
Automatic conversion of values from one data type to another.

**35. What are falsy values in JavaScript?**
false, 0, -0, 0n, "", null, undefined, NaN

**36. What is the `arguments` object?**
Array-like object containing arguments passed to a function.

**37. What is the difference between for...in and for...of?**
- for...in: iterates over enumerable properties
- for...of: iterates over iterable objects

**38. What are symbols?**
Unique identifiers that can be used as object property keys.

**39. What is a Map vs Object?**
Map allows any type as key and maintains insertion order; Object keys are strings/symbols.

**40. What is a Set?**
Collection of unique values of any type.

**41. What is a WeakMap?**
Map where keys must be objects and are weakly referenced.

**42. What is a WeakSet?**
Set that holds weak references to objects.

**43. What are Proxies?**
Objects that define custom behavior for fundamental operations.

**44. What is Reflect?**
Built-in object providing methods for interceptable JavaScript operations.

**45. What are tagged template literals?**
Template literals prefixed with a function for custom processing.

**46. What is the ternary operator?**
Conditional operator: condition ? value1 : value2

**47. What is short-circuit evaluation?**
Logical operators that don't evaluate second operand if unnecessary.

**48. What is the comma operator?**
Evaluates operands left to right and returns the last one.

**49. What is strict mode?**
"use strict" enables stricter parsing and error handling.

**50. What are immediately invoked function expressions (IIFE)?**
Functions that run immediately after definition: (function(){})()

### Advanced JavaScript (Questions 51-100)

**51. What is the difference between microtasks and macrotasks?**
Microtasks (Promise callbacks) have higher priority than macrotasks (setTimeout).

**52. What is memoization?**
Optimization technique storing expensive function call results.

**53. What is throttling and debouncing?**
- Throttling: limits execution frequency
- Debouncing: delays execution until after wait period

**54. What are design patterns in JavaScript?**
Reusable solutions to common problems (Singleton, Observer, Factory, etc.)

**55. What is functional programming?**
Programming paradigm treating computation as evaluation of functions.

**56. What is currying?**
Technique of translating a function with multiple arguments into a sequence of functions.

**57. What is partial application?**
Process of fixing some arguments of a function, producing another function.

**58. What is composition?**
Combining simple functions to build complex ones.

**59. What are pure functions?**
Functions that always return the same output for the same input with no side effects.

**60. What is immutability?**
Objects whose state cannot be modified after creation.

**61. What is the Observer pattern?**
Behavioral pattern where object maintains list of dependents and notifies them of changes.

**62. What is the Module pattern?**
Pattern providing encapsulation and privacy.

**63. What is the Singleton pattern?**
Pattern ensuring a class has only one instance.

**64. What is the Factory pattern?**
Pattern creating objects without specifying exact class.

**65. What is event bubbling and capturing?**
- Bubbling: events propagate up the DOM tree
- Capturing: events propagate down the DOM tree

**66. What is the difference between target and currentTarget?**
- target: element that triggered the event
- currentTarget: element with the event listener

**67. What are custom events?**
User-defined events that can be dispatched and listened for.

**68. What is the Fetch API?**
Modern way to make HTTP requests in JavaScript.

**69. What are Service Workers?**
Scripts that run in background, enabling features like push notifications and offline functionality.

**70. What are Web Workers?**
Scripts that run in background threads, separate from main thread.

**71. What is IndexedDB?**
Low-level API for client-side storage of structured data.

**72. What is the History API?**
API for manipulating browser session history.

**73. What are Intersection Observers?**
API for observing changes in intersection of target element with ancestor or viewport.

**74. What are Mutation Observers?**
API for observing changes to DOM tree.

**75. What is the Geolocation API?**
API for accessing geographical position of device.

**76. What are Progressive Web Apps (PWAs)?**
Web applications that use modern web capabilities to deliver app-like experience.

**77. What is the Critical Rendering Path?**
Sequence of steps browser takes to render initial view of webpage.

**78. What is Virtual DOM?**
Programming concept where virtual representation of UI is kept in memory.

**79. What is tree shaking?**
Dead code elimination technique to remove unused code.

**80. What is code splitting?**
Technique of splitting code into smaller chunks loaded on demand.

**81. What are polyfills?**
Code that provides modern functionality on older browsers.

**82. What is transpilation?**
Process of converting code from one version to another (e.g., ES6 to ES5).

**83. What is bundling?**
Process of combining multiple files into fewer files.

**84. What is minification?**
Process of removing unnecessary characters from code.

**85. What is source mapping?**
Technique mapping minified code back to original source.

**86. What is the V8 engine?**
Google's JavaScript engine used in Chrome and Node.js.

**87. What is garbage collection?**
Automatic memory management process that frees up unused memory.

**88. What are memory leaks?**
Situations where application uses increasing amounts of memory over time.

**89. What is the call stack?**
Data structure tracking function calls in program.

**90. What is heap memory?**
Memory region where objects are allocated.

**91. What are closures used for?**
Data privacy, function factories, module pattern, callbacks.

**92. What is the difference between shallow and deep copy?**
- Shallow: copies only first level
- Deep: copies all levels recursively

**93. What are getters and setters?**
Special methods for accessing and modifying object properties.

**94. What is Object.create()?**
Method creating new object with specified prototype.

**95. What is Object.assign()?**
Method copying properties from source objects to target object.

**96. What are computed property names?**
Dynamic property names using square brackets notation.

**97. What is the spread syntax for objects?**
{...obj} creates shallow copy of object.

**98. What are optional chaining and nullish coalescing?**
- Optional chaining (?.) safely accesses nested properties
- Nullish coalescing (??) provides default for null/undefined

**99. What are BigInt and when would you use it?**
Primitive for integers larger than Number.MAX_SAFE_INTEGER.

**100. What is the difference between function declaration and expression?**
Declarations are hoisted completely; expressions are not.

---

## TypeScript

### Basic TypeScript (Questions 101-150)

**101. What is TypeScript?**
Strongly typed superset of JavaScript that compiles to plain JavaScript.

**102. What are the benefits of using TypeScript?**
Type safety, better IDE support, early error detection, improved refactoring.

**103. What are primitive types in TypeScript?**
boolean, number, string, null, undefined, symbol, bigint

**104. What is type annotation?**
Explicitly specifying the type of a variable, parameter, or return value.

**105. What is type inference?**
TypeScript's ability to automatically determine types based on context.

**106. What are interfaces in TypeScript?**
Contracts that define the structure of objects.

**107. What are type aliases?**
Custom names for types using the `type` keyword.

**108. What is the difference between interface and type?**
Interfaces are extendable and mergeable; types are more flexible with unions.

**109. What are union types?**
Types that can be one of several types: string | number

**110. What are intersection types?**
Types that combine multiple types: A & B

**111. What are optional properties?**
Properties marked with ? that may or may not exist.

**112. What are readonly properties?**
Properties that cannot be modified after initialization.

**113. What are generic types?**
Types that work with multiple types while preserving type information.

**114. What is the `any` type?**
Type that disables TypeScript's type checking.

**115. What is the `unknown` type?**
Top type that's safer than `any` - requires type checking before use.

**116. What is the `never` type?**
Type for values that never occur (functions that always throw).

**117. What is the `void` type?**
Type for functions that don't return a value.

**118. What are literal types?**
Types that represent exact values: "hello" | "world"

**119. What are mapped types?**
Types that create new types by transforming properties of existing types.

**120. What are conditional types?**
Types that depend on a condition: T extends U ? X : Y

**121. What are utility types?**
Built-in helper types like Partial, Required, Pick, Omit.

**122. What is the `keyof` operator?**
Operator that produces union of all property names of a type.

**123. What is the `typeof` operator in TypeScript?**
Operator that gets the type of a variable or property.

**124. What are index signatures?**
Way to describe types of possible values for properties not known ahead of time.

**125. What are function overloads?**
Multiple function signatures for the same function with different parameters.

**126. What are abstract classes?**
Classes that cannot be instantiated and may contain abstract methods.

**127. What are access modifiers?**
public, private, protected, readonly modifiers for class members.

**128. What are decorators?**
Special declarations that can be attached to classes, methods, properties.

**129. What are namespaces?**
Way to organize code and avoid naming collisions (modules preferred).

**130. What are modules in TypeScript?**
Files that contain top-level import or export declarations.

**131. What is ambient declaration?**
Declaration that tells TypeScript about code written elsewhere.

**132. What are declaration files (.d.ts)?**
Files containing only type information, no implementation.

**133. What is type assertion?**
Way to tell TypeScript the type of a value: `<Type>value` or `value as Type`

**134. What are template literal types?**
Types built from template literal strings.

**135. What is discriminated union?**
Union types with a common property for type narrowing.

**136. What is type narrowing?**
Process of refining types within conditional blocks.

**137. What are type guards?**
Runtime checks that guarantee type in some scope.

**138. What is the `in` operator?**
Operator for checking if property exists in object.

**139. What is the `instanceof` operator?**
Operator for checking object's prototype chain.

**140. What are user-defined type guards?**
Functions that return type predicates for type narrowing.

**141. What is strict mode in TypeScript?**
Compiler flag that enables several strict type checking options.

**142. What is `strictNullChecks`?**
Option that makes null and undefined not assignable to other types.

**143. What is `noImplicitAny`?**
Option that raises error for variables with implicit any type.

**144. What are triple-slash directives?**
Single-line comments containing XML tags for compiler directives.

**145. What is module resolution?**
Process TypeScript uses to figure out what an import refers to.

**146. What are path mapping?**
Compiler option to map module names to locations relative to baseUrl.

**147. What is the TypeScript compiler (tsc)?**
Command-line tool that compiles TypeScript to JavaScript.

**148. What is tsconfig.json?**
Configuration file for TypeScript compiler options.

**149. What are compiler options?**
Settings that control TypeScript compilation behavior.

**150. What is incremental compilation?**
Feature that speeds up builds by reusing previous compilation information.

---

## Object-Oriented Programming (OOP)

### OOP Fundamentals (Questions 151-200)

**151. What is Object-Oriented Programming?**
Programming paradigm based on objects containing data (attributes) and code (methods).

**152. What are the four pillars of OOP?**
Encapsulation, Inheritance, Polymorphism, Abstraction.

**153. What is encapsulation?**
Bundling data and methods that work on that data within one unit.

**154. What is inheritance?**
Mechanism where new class inherits properties and methods from existing class.

**155. What is polymorphism?**
Ability of different classes to be treated as instances of the same type.

**156. What is abstraction?**
Hiding complex implementation details while showing only essential features.

**157. What is a class?**
Blueprint or template for creating objects.

**158. What is an object?**
Instance of a class containing state and behavior.

**159. What is a constructor?**
Special method called when object is created.

**160. What is method overriding?**
Providing specific implementation of method already defined in parent class.

**161. What is method overloading?**
Having multiple methods with same name but different parameters.

**162. What is multiple inheritance?**
Class inheriting from multiple parent classes (not supported in JavaScript).

**163. What is composition?**
Design principle where class contains instances of other classes.

**164. What is aggregation?**
Weak form of composition where child can exist independently.

**165. What is association?**
Relationship between two separate classes established through objects.

**166. What is the difference between composition and inheritance?**
Composition: "has-a" relationship; Inheritance: "is-a" relationship.

**167. What is a static method?**
Method that belongs to class rather than instance.

**168. What is a static property?**
Property that belongs to class rather than instance.

**169. What is an instance method?**
Method that requires object instance to be called.

**170. What is an abstract method?**
Method declared without implementation in abstract class.

**171. What is the super keyword?**
Keyword used to access parent class members.

**172. What is the this keyword in OOP?**
Reference to current instance of class.

**173. What are access modifiers?**
Keywords controlling visibility of class members (public, private, protected).

**174. What is a getter method?**
Method that retrieves value of private property.

**175. What is a setter method?**
Method that sets value of private property.

**176. What is the Liskov Substitution Principle?**
Objects of superclass should be replaceable with objects of subclass.

**177. What is the Single Responsibility Principle?**
Class should have only one reason to change.

**178. What is the Open/Closed Principle?**
Classes should be open for extension but closed for modification.

**179. What is the Interface Segregation Principle?**
Clients shouldn't be forced to depend on interfaces they don't use.

**180. What is the Dependency Inversion Principle?**
High-level modules shouldn't depend on low-level modules.

**181. What is a design pattern?**
Reusable solution to commonly occurring problem in software design.

**182. What is the Singleton pattern?**
Pattern ensuring class has only one instance.

**183. What is the Factory pattern?**
Pattern creating objects without specifying exact class.

**184. What is the Observer pattern?**
Pattern where object maintains list of dependents.

**185. What is the Strategy pattern?**
Pattern defining family of algorithms and making them interchangeable.

**186. What is the Decorator pattern?**
Pattern adding new functionality to objects dynamically.

**187. What is the Adapter pattern?**
Pattern allowing incompatible interfaces to work together.

**188. What is the Template Method pattern?**
Pattern defining skeleton of algorithm in base class.

**189. What is the Command pattern?**
Pattern encapsulating request as object.

**190. What is coupling?**
Degree of interdependence between software modules.

**191. What is cohesion?**
Degree to which elements within module work together.

**192. What is tight coupling vs loose coupling?**
Tight: high dependency; Loose: low dependency between modules.

**193. What is the difference between aggregation and composition?**
Aggregation: weak ownership; Composition: strong ownership.

**194. What is the difference between abstract class and interface?**
Abstract class can have implementation; Interface only defines contract.

**195. What is a virtual method?**
Method that can be overridden in derived classes.

**196. What is a copy constructor?**
Constructor that creates object by copying another object.

**197. What is shallow copy vs deep copy?**
Shallow: copies references; Deep: copies actual values recursively.

**198. What is operator overloading?**
Ability to define custom behavior for operators (not in JavaScript).

**199. What is a friend function?**
Function that has access to private members (not in JavaScript).

**200. What is the difference between has-a and is-a relationship?**
Has-a: composition/aggregation; Is-a: inheritance relationship.

---

## React.js

### React Fundamentals (Questions 201-300)

**201. What is React?**
JavaScript library for building user interfaces, particularly SPAs.

**202. What is JSX?**
JavaScript XML - syntax extension allowing HTML-like code in JavaScript.

**203. What are components in React?**
Reusable pieces of UI that can be class-based or functional.

**204. What is the difference between functional and class components?**
Functional: simpler, use hooks; Class: use lifecycle methods, more verbose.

**205. What are props in React?**
Properties passed from parent to child components (read-only).

**206. What is state in React?**
Internal data of component that can change over time.

**207. What is the useState hook?**
Hook for adding state to functional components.

**208. What is the useEffect hook?**
Hook for handling side effects in functional components.

**209. What are lifecycle methods?**
Methods called at different stages of component's lifecycle.

**210. What is componentDidMount?**
Lifecycle method called after component is mounted to DOM.

**211. What is componentDidUpdate?**
Lifecycle method called after component re-renders.

**212. What is componentWillUnmount?**
Lifecycle method called before component is removed from DOM.

**213. What is the Virtual DOM?**
In-memory representation of real DOM for efficient updates.

**214. How does React reconciliation work?**
Process of comparing virtual DOM trees and updating only changed parts.

**215. What is the key prop?**
Special prop helping React identify changed, added, or removed items.

**216. What is conditional rendering?**
Rendering components or elements based on conditions.

**217. What are React fragments?**
Way to group multiple elements without adding extra DOM nodes.

**218. What is event handling in React?**
Handling user interactions using SyntheticEvent system.

**219. What are controlled components?**
Form elements whose value is controlled by React state.

**220. What are uncontrolled components?**
Form elements that maintain their own state internally.

**221. What is React Router?**
Library for handling routing in React applications.

**222. What are higher-order components (HOCs)?**
Functions that take component and return enhanced component.

**223. What are render props?**
Pattern sharing code between components using prop whose value is function.

**224. What is context in React?**
Way to pass data through component tree without prop drilling.

**225. What is the useContext hook?**
Hook for consuming context in functional components.

**226. What is useReducer hook?**
Hook for managing complex state logic using reducer pattern.

**227. What is useMemo hook?**
Hook for memoizing expensive calculations.

**228. What is useCallback hook?**
Hook for memoizing function references.

**229. What is useRef hook?**
Hook for accessing DOM elements directly or storing mutable values.

**230. What are custom hooks?**
Functions that use React hooks and can be shared between components.

**231. What is prop drilling?**
Passing props through multiple levels of components.

**232. What is React.memo?**
Higher-order component for preventing unnecessary re-renders.

**233. What is the difference between useMemo and useCallback?**
useMemo memoizes values; useCallback memoizes functions.

**234. What is lazy loading in React?**
Loading components only when they're needed using React.lazy.

**235. What is Suspense?**
Component for handling loading states of lazy-loaded components.

**236. What are error boundaries?**
Components that catch errors in component tree and display fallback UI.

**237. What is server-side rendering (SSR)?**
Rendering React components on server before sending to client.

**238. What is Next.js?**
React framework providing SSR, static site generation, and more.

**239. What is static site generation (SSG)?**
Pre-rendering pages at build time.

**240. What is incremental static regeneration (ISR)?**
Updating static content after build without full rebuild.

**241. What are React hooks rules?**
Only call hooks at top level and only from React functions.

**242. What is the dependency array in useEffect?**
Array specifying when effect should run based on value changes.

**243. What is cleanup in useEffect?**
Returning function from useEffect to clean up resources.

**244. What is strict mode in React?**
Development mode feature for identifying problems in application.

**245. What are portals in React?**
Way to render children into DOM node outside parent component's hierarchy.

**246. What is the difference between state and props?**
State is internal and mutable; props are external and immutable.

**247. What is lifting state up?**
Moving state to common ancestor component to share between siblings.

**248. What are synthetic events?**
React's wrapper around native events for cross-browser compatibility.

**249. What is event pooling?**
React's optimization where event objects are reused (removed in React 17).

**250. What is the difference between createElement and cloneElement?**
createElement creates new element; cloneElement clones existing element.

**251. What are React refs?**
Way to access DOM nodes or component instances directly.

**252. What is forwardRef?**
Function allowing components to expose ref to parent components.

**253. What is the useImperativeHandle hook?**
Hook for customizing instance value exposed by ref.

**254. What is the useLayoutEffect hook?**
Hook that runs synchronously after DOM mutations.

**255. What is the difference between useEffect and useLayoutEffect?**
useLayoutEffect runs synchronously; useEffect runs asynchronously.

**256. What is React DevTools?**
Browser extension for debugging React applications.

**257. What is profiling in React?**
Measuring performance of React applications.

**258. What are performance optimization techniques in React?**
Memoization, lazy loading, code splitting, virtualization.

**259. What is windowing/virtualization?**
Technique for rendering only visible items in large lists.

**260. What is React testing library?**
Testing utilities focused on testing components as users interact with them.

**261. What is Enzyme?**
JavaScript testing utility for React (less commonly used now).

**262. What is snapshot testing?**
Testing technique capturing component output and comparing changes.

**263. What are the different ways to style React components?**
CSS files, CSS modules, styled-components, inline styles, Tailwind.

**264. What is CSS-in-JS?**
Styling technique using JavaScript to style components.

**265. What is styled-components?**
Library for styling React components using tagged template literals.

**266. What are CSS modules?**
CSS files with locally scoped class names.

**267. What is the difference between React and ReactDOM?**
React: core library; ReactDOM: DOM-specific methods.

**268. What is concurrent mode?**
Experimental React feature for improving app responsiveness.

**269. What is time slicing?**
Breaking work into chunks to maintain smooth user interactions.

**270. What is Suspense for data fetching?**
Future React feature for handling async data fetching.

**271. What are the new features in React 18?**
Concurrent features, automatic batching, new hooks like useId.

**272. What is automatic batching?**
React 18 feature batching state updates automatically.

**273. What is the useId hook?**
Hook for generating unique IDs for accessibility attributes.

**274. What is the useDeferredValue hook?**
Hook for deferring updates to non-urgent parts of UI.

**275. What is the useTransition hook?**
Hook for marking state updates as non-urgent.

**276. What is React Server Components?**
Experimental feature for running components on server.

**277. What are the benefits of React Server Components?**
Reduced bundle size, better performance, direct server access.

**278. What is hydration?**
Process of attaching event listeners to server-rendered HTML.

**279. What are the differences between React and Vue?**
React: more flexible, JSX; Vue: template-based, more opinionated.

**280. What are the differences between React and Angular?**
React: library, more flexible; Angular: full framework, more structured.

**281. What is the React fiber architecture?**
New reconciliation algorithm enabling incremental rendering.

**282. What are the phases of React fiber?**
Render phase: building fiber tree; Commit phase: applying changes to DOM.

**283. What is the difference between controlled and uncontrolled forms?**
Controlled: React manages form state; Uncontrolled: DOM manages state.

**284. What is form validation in React?**
Process of validating user input using various techniques.

**285. What are React hooks for forms?**
useState for form state, custom hooks for form logic.

**286. What is React Hook Form?**
Library for performant, flexible forms with easy validation.

**287. What is Formik?**
Library for building forms with validation and error handling.

**288. What is the Context API vs Redux?**
Context: built-in, simpler; Redux: external, more powerful for complex state.

**289. What is React testing best practices?**
Test behavior not implementation, use React Testing Library, write tests users would understand.

**290. What is accessibility in React?**
Making React applications usable by people with disabilities.

**291. What are ARIA attributes?**
Accessibility attributes providing semantic information.

**292. What is semantic HTML in React?**
Using appropriate HTML elements for their intended purpose.

**293. What is focus management in React?**
Controlling where focus goes in response to user actions.

**294. What are React performance patterns?**
Memoization, lazy loading, code splitting, avoiding inline objects.

**295. What is bundle splitting?**
Dividing application code into smaller chunks for better loading.

**296. What is tree shaking in React?**
Removing unused code from final bundle.

**297. What are micro-frontends?**
Architectural pattern dividing frontend into smaller, independent pieces.

**298. What is the React ecosystem?**
Collection of tools, libraries, and frameworks around React.

**299. What are React alternatives?**
Vue.js, Angular, Svelte, Solid.js, Alpine.js.

**300. What is state management in React?**
Managing and organizing application state across components.

---

## React Native

### React Native Fundamentals (Questions)
# React Native Interview Questions

## React Native Fundamentals (Questions 301-350)

**301. What is React Native?**
Cross-platform mobile development framework using React to build native mobile apps.

**302. How does React Native work?**
Uses JavaScript bridge to communicate between JavaScript code and native platform APIs.

**303. What is the difference between React and React Native?**
React: web development; React Native: mobile development with native components.

**304. What are native components in React Native?**
Platform-specific UI components that render to actual native views.

**305. What is the JavaScript bridge?**
Communication layer between JavaScript thread and native threads.

**306. What are the main threads in React Native?**
JavaScript thread, Native/UI thread, Shadow thread (layout calculation).

**307. What is Metro bundler?**
JavaScript bundler for React Native that handles code transformation and bundling.

**308. What are the core components in React Native?**
View, Text, Image, ScrollView, TextInput, TouchableOpacity, FlatList.

**309. What is the View component?**
Fundamental building block similar to div in web development.

**310. What is the Text component?**
Component for displaying text, required for all text content.

**311. What is StyleSheet in React Native?**
API for creating and managing styles in a structured way.

**312. How do you handle styling in React Native?**
Using StyleSheet.create(), inline styles, or styled-components.

**313. What is Flexbox in React Native?**
Layout system for arranging components (similar to CSS Flexbox).

**314. What are the main Flexbox properties?**
flexDirection, justifyContent, alignItems, flex, flexWrap.

**315. What is the difference between px and dp in React Native?**
React Native uses density-independent pixels (dp) automatically, no px units.

**316. How do you handle different screen sizes?**
Using Dimensions API, responsive design patterns, and flexible layouts.

**317. What is the Dimensions API?**
API for getting device screen dimensions and orientation.

**318. What is Platform-specific code?**
Code that runs differently on iOS and Android platforms.

**319. How do you write platform-specific code?**
Using Platform.OS, .ios.js/.android.js files, or Platform.select().

**320. What is the Platform module?**
Module providing information about the platform the app is running on.

**321. What are TouchableOpacity and TouchableHighlight?**
Components for handling touch interactions with visual feedback.

**322. What is the difference between TouchableOpacity and TouchableWithoutFeedback?**
TouchableOpacity provides visual feedback; TouchableWithoutFeedback doesn't.

**323. What is FlatList?**
Performant component for rendering large lists of data.

**324. What is the difference between FlatList and ScrollView?**
FlatList: lazy rendering for large datasets; ScrollView: renders all items.

**325. What are the key props for FlatList?**
data, renderItem, keyExtractor, numColumns, horizontal.

**326. What is SectionList?**
Component for rendering sectioned lists with headers.

**327. What is VirtualizedList?**
Base component that FlatList and SectionList are built upon.

**328. How do you handle images in React Native?**
Using Image component with source prop (local or remote images).

**329. What is the difference between local and remote images?**
Local: require('./image.png'); Remote: {uri: 'https://...'}.

**330. What is ImageBackground component?**
Component for displaying content over a background image.

**331. What is TextInput component?**
Component for text input with various keyboard types and validation.

**332. How do you handle form validation in React Native?**
Using state management, validation libraries, or custom validation functions.

**333. What is KeyboardAvoidingView?**
Component that adjusts position when keyboard appears.

**334. How do you handle keyboard interactions?**
Using Keyboard API, KeyboardAvoidingView, and keyboard event listeners.

**335. What is Modal component?**
Component for displaying content over the current view.

**336. What are Alert and ActionSheet?**
Native dialog components for user interactions and choices.

**337. What is the ActivityIndicator component?**
Component for showing loading spinners.

**338. What is the Switch component?**
Toggle component similar to HTML checkbox but with native styling.

**339. What is the Picker component?**
Dropdown selection component (deprecated, use @react-native-picker/picker).

**340. What is the Slider component?**
Component for selecting values from a range (moved to community package).

**341. What is SafeAreaView?**
Component that renders content within safe area boundaries (iOS).

**342. What is StatusBar component?**
Component for controlling the status bar appearance.

**343. How do you handle navigation in React Native?**
Using React Navigation library for screen navigation and routing.

**344. What is React Navigation?**
Most popular navigation library for React Native applications.

**345. What are the types of navigators in React Navigation?**
Stack, Tab, Drawer, and Bottom Tab navigators.

**346. What is Stack Navigator?**
Navigation pattern where screens are stacked on top of each other.

**347. What is Tab Navigator?**
Navigation pattern with tabs at bottom or top of screen.

**348. What is Drawer Navigator?**
Navigation pattern with slide-out drawer menu.

**349. How do you pass parameters between screens?**
Using navigation.navigate('Screen', {params}) and route.params.

**350. What are navigation lifecycle events?**
focus, blur, beforeRemove events for handling screen transitions.

## React Native Advanced (Questions 351-400)

**351. What is React Native CLI vs Expo?**
CLI: full native development; Expo: managed workflow with limited native access.

**352. What is Expo?**
Platform providing tools and services for React Native development.

**353. What are the pros and cons of Expo?**
Pros: easy setup, OTA updates; Cons: limited native modules, larger bundle.

**354. What is ejecting from Expo?**
Process of converting Expo project to bare React Native project.

**355. What are native modules?**
Bridge between JavaScript and native platform code (iOS/Android).

**356. How do you create custom native modules?**
Writing platform-specific code and bridging it to JavaScript.

**357. What is the difference between native modules and native components?**
Modules: logic/functionality; Components: UI elements.

**358. What is linking in React Native?**
Process of connecting native dependencies to React Native project.

**359. What is autolinking?**
Automatic linking of native dependencies (React Native 0.60+).

**360. What is React Native New Architecture?**
New architecture with JSI, Fabric, and TurboModules for better performance.

**361. What is JSI (JavaScript Interface)?**
New way for JavaScript to communicate directly with native code.

**362. What is Fabric renderer?**
New UI layer for React Native providing better performance and consistency.

**363. What are TurboModules?**
New native modules system with lazy loading and better type safety.

**364. How do you handle state management in React Native?**
Using React Context, Redux, Zustand, or other state management libraries.

**365. What is AsyncStorage?**
Persistent storage system for React Native (moved to community package).

**366. What are the alternatives to AsyncStorage?**
react-native-mmkv, react-native-keychain, SQLite, Realm.

**367. What is react-native-mmkv?**
Fast, secure key-value storage for React Native.

**368. How do you handle offline data in React Native?**
Using local storage, SQLite databases, and offline-first strategies.

**369. What is SQLite in React Native?**
Embedded database for storing structured data locally.

**370. What is Realm database?**
Object database for mobile applications.

**371. How do you handle network requests in React Native?**
Using fetch API, Axios, or other HTTP client libraries.

**372. What is the Network module?**
Built-in module for checking network connectivity status.

**373. How do you handle push notifications?**
Using react-native-push-notification or @react-native-firebase/messaging.

**374. What is Firebase in React Native?**
Google's platform providing backend services like analytics, messaging, etc.

**375. How do you implement deep linking?**
Using React Navigation deep linking or react-native-deep-linking.

**376. What is universal linking (iOS) and app links (Android)?**
Native deep linking that opens app from web URLs.

**377. How do you handle permissions in React Native?**
Using react-native-permissions or platform-specific permission APIs.

**378. What is react-native-permissions?**
Library for managing device permissions across platforms.

**379. How do you access device features?**
Using community packages for camera, location, contacts, etc.

**380. What is react-native-camera?**
Library for camera functionality (deprecated, use react-native-vision-camera).

**381. How do you handle geolocation?**
Using @react-native-community/geolocation package.

**382. What is react-native-maps?**
Library for displaying maps in React Native applications.

**383. How do you implement biometric authentication?**
Using react-native-biometrics or react-native-touch-id.

**384. What is Flipper?**
Desktop debugging platform for React Native and native apps.

**385. How do you debug React Native apps?**
Using Chrome DevTools, Flipper, Reactotron, or native debugging tools.

**386. What is Reactotron?**
Desktop app for inspecting React Native apps.

**387. How do you handle crashes in React Native?**
Using crash reporting tools like Crashlytics or Sentry.

**388. What is over-the-air (OTA) updates?**
Updating JavaScript bundle without going through app stores.

**389. What is CodePush?**
Microsoft's service for OTA updates in React Native.

**390. How do you optimize React Native performance?**
Optimizing images, using FlatList, avoiding unnecessary re-renders.

**391. What is the RAM bundle?**
Bundling technique that loads modules on demand.

**392. What is Hermes engine?**
JavaScript engine optimized for React Native.

**393. What are the benefits of Hermes?**
Faster startup time, reduced memory usage, smaller bundle size.

**394. How do you handle animations in React Native?**
Using Animated API, react-native-reanimated, or Lottie animations.

**395. What is react-native-reanimated?**
Library for smooth, performant animations in React Native.

**396. What is Lottie in React Native?**
Library for rendering After Effects animations.

**397. How do you test React Native apps?**
Using Jest for unit tests, Detox for E2E tests, and testing-library.

**398. What is Detox?**
End-to-end testing and automation library for React Native.

**399. How do you deploy React Native apps?**
Building and submitting to App Store (iOS) and Google Play Store (Android).

**400. What are the common React Native deployment issues?**
Bundle size, platform differences, native dependency conflicts, store approval.

---

# Node.js Interview Questions

## Node.js Fundamentals (Questions 401-450)

**401. What is Node.js?**
JavaScript runtime built on Chrome's V8 engine for server-side development.

**402. What makes Node.js different from browser JavaScript?**
Server-side APIs, file system access, no DOM, global object instead of window.

**403. What is the V8 engine?**
Google's JavaScript engine that compiles JavaScript to native machine code.

**404. What is the event loop in Node.js?**
Mechanism that handles asynchronous operations using a single-threaded event loop.

**405. How does the event loop work?**
Phases: timers, pending callbacks, idle/prepare, poll, check, close callbacks.

**406. What is non-blocking I/O?**
Operations that don't halt execution while waiting for I/O operations to complete.

**407. What is the difference between synchronous and asynchronous operations?**
Sync: blocks execution; Async: continues execution while operation completes in background.

**408. What are callbacks in Node.js?**
Functions passed as arguments to be executed after async operations complete.

**409. What is callback hell?**
Nested callbacks creating difficult-to-read and maintain code structure.

**410. How do you avoid callback hell?**
Using Promises, async/await, modularization, and control flow libraries.

**411. What are Promises in Node.js?**
Objects representing eventual completion or failure of asynchronous operations.

**412. What is async/await in Node.js?**
Syntax for handling Promises in a synchronous-looking manner.

**413. What is the global object in Node.js?**
Global namespace object (similar to window in browsers).

**414. What is the process object?**
Global object providing information about current Node.js process.

**415. What are some important process object properties?**
process.env, process.argv, process.cwd(), process.exit(), process.pid.

**416. What is process.env?**
Object containing user environment variables.

**417. What is process.argv?**
Array containing command-line arguments passed to Node.js process.

**418. What are modules in Node.js?**
Reusable blocks of code that can be imported and exported.

**419. What is CommonJS?**
Module system used by Node.js using require() and module.exports.

**420. What is the difference between require() and import?**
require(): CommonJS, synchronous; import: ES6 modules, asynchronous.

**421. What is module.exports vs exports?**
module.exports: actual export object; exports: reference to module.exports.

**422. What is the __dirname and __filename?**
Global variables containing directory path and file path of current module.

**423. What is the Buffer class?**
Built-in class for handling binary data in Node.js.

**424. Why do we need Buffers?**
JavaScript strings are Unicode, but many operations require binary data.

**425. How do you create Buffers?**
Buffer.from(), Buffer.alloc(), Buffer.allocUnsafe().

**426. What are Streams in Node.js?**
Objects for handling streaming data (reading/writing data piece by piece).

**427. What are the types of Streams?**
Readable, Writable, Duplex, Transform streams.

**428. What is a Readable stream?**
Stream you can read data from (e.g., fs.createReadStream).

**429. What is a Writable stream?**
Stream you can write data to (e.g., fs.createWriteStream).

**430. What is pipe() method?**
Method for connecting readable stream to writable stream.

**431. What is the EventEmitter class?**
Core class that enables objects to emit and listen to events.

**432. How do you create and use EventEmitter?**
Extend EventEmitter class, use emit() to fire events, on() to listen.

**433. What is the fs module?**
File system module for interacting with file system.

**434. What are fs.readFile() vs fs.readFileSync()?**
readFile(): asynchronous; readFileSync(): synchronous (blocks execution).

**435. What is the path module?**
Utility module for working with file and directory paths.

**436. What are some important path methods?**
path.join(), path.resolve(), path.dirname(), path.basename(), path.extname().

**437. What is the os module?**
Module providing operating system-related utilities.

**438. What is the url module?**
Module for URL parsing and formatting.

**439. What is the querystring module?**
Module for parsing and formatting URL query strings.

**440. What is the crypto module?**
Module providing cryptographic functionality.

**441. What is the http module?**
Core module for creating HTTP servers and making HTTP requests.

**442. How do you create an HTTP server?**
Using http.createServer() and listening on a port.

**443. What is the difference between http and https modules?**
http: plain HTTP; https: secure HTTP with TLS/SSL encryption.

**444. What is the util module?**
Utility module providing helpful functions for debugging and formatting.

**445. What is util.promisify()?**
Function that converts callback-style functions to Promise-based.

**446. What is cluster module?**
Module for creating child processes sharing server ports.

**447. What is child_process module?**
Module for spawning child processes.

**448. What are the methods in child_process?**
spawn(), exec(), execFile(), fork().

**449. What is the difference between spawn() and exec()?**
spawn(): streams data; exec(): buffers output in memory.

**450. What is worker_threads module?**
Module for running JavaScript in parallel using worker threads.

## Node.js Advanced (Questions 451-490)

**451. What is npm?**
Node Package Manager for installing and managing JavaScript packages.

**452. What is package.json?**
File containing metadata about Node.js project and its dependencies.

**453. What are dependencies vs devDependencies?**
dependencies: runtime packages; devDependencies: development-only packages.

**454. What is package-lock.json?**
File locking exact versions of installed packages for consistent installs.

**455. What is the difference between npm install and npm ci?**
install: updates lock file; ci: installs from lock file exactly.

**456. What are npm scripts?**
Custom commands defined in package.json scripts section.

**457. What is npx?**
Tool for executing npm packages without installing them globally.

**458. What is yarn?**
Alternative package manager to npm with faster installs and better caching.

**459. What is semantic versioning (semver)?**
Versioning scheme using MAJOR.MINOR.PATCH format.

**460. What do ^, ~, and exact versions mean?**
^: compatible within major version; ~: compatible within minor version; exact: specific version.

**461. What is middleware in Node.js?**
Functions that execute during request-response cycle with access to req, res, next.

**462. What is error handling in Node.js?**
Using try-catch, error events, and error-first callbacks.

**463. What is error-first callback pattern?**
Convention where callback's first parameter is error object or null.

**464. How do you handle unhandled promise rejections?**
Using process.on('unhandledRejection') event listener.

**465. What is uncaughtException?**
Event fired when unhandled exception bubbles back to event loop.

**466. What is the difference between setImmediate and setTimeout?**
setImmediate: executes after I/O events; setTimeout: executes after minimum delay.

**467. What is process.nextTick()?**
Method to execute callback on next iteration of event loop.

**468. What is the order of execution for timers?**
process.nextTick() → Promise.resolve() → setImmediate() → setTimeout().

**469. What is memory management in Node.js?**
Automatic garbage collection with configurable heap size limits.

**470. What are memory leaks in Node.js?**
Unreleased memory references causing increasing memory usage.

**471. How do you debug memory leaks?**
Using heap dumps, profilers, and monitoring memory usage patterns.

**472. What is the --inspect flag?**
Flag enabling debugger interface for Node.js applications.

**473. What are Node.js debugging tools?**
Node Inspector, Chrome DevTools, VS Code debugger, console.log().

**474. What is performance monitoring in Node.js?**
Tracking metrics like CPU usage, memory consumption, and response times.

**475. What are popular Node.js monitoring tools?**
New Relic, AppDynamics, DataDog, PM2, Clinic.js.

**476. What is PM2?**
Production process manager for Node.js applications.

**477. What are PM2 features?**
Process management, load balancing, monitoring, log management, clustering.

**478. What is load balancing in Node.js?**
Distributing requests across multiple Node.js processes or servers.

**479. What is horizontal vs vertical scaling?**
Horizontal: adding more servers; Vertical: upgrading existing server hardware.

**480. What is caching in Node.js?**
Storing frequently accessed data in memory for faster retrieval.

**481. What are caching strategies?**
In-memory caching, Redis, Memcached, CDN caching.

**482. What is Redis?**
In-memory data store used for caching, sessions, and real-time applications.

**483. What is session management in Node.js?**
Storing user session data across HTTP requests.

**484. What are session storage options?**
Memory store, database store, Redis store, file store.

**485. What is CORS in Node.js?**
Cross-Origin Resource Sharing mechanism for handling cross-domain requests.

**486. How do you implement CORS?**
Using CORS middleware or manually setting appropriate headers.

**487. What is helmet.js?**
Security middleware for setting various HTTP headers.

**488. What are Node.js security best practices?**
Input validation, SQL injection prevention, secure headers, dependency updates.

**489. What is rate limiting?**
Controlling number of requests from clients to prevent abuse.

**490. What are popular Node.js frameworks?**
Express.js, Koa.js, Fastify, Nest.js, Hapi.js.

## MongoDB

### MongoDB Fundamentals (Questions 491-570)

**491. What is MongoDB?**
NoSQL document database storing data in flexible, JSON-like documents.

**492. What is a document in MongoDB?**
Record in MongoDB consisting of field-value pairs, similar to JSON objects.

**493. What is a collection in MongoDB?**
Group of documents, equivalent to table in relational databases.

**494. What is BSON?**
Binary representation of JSON documents that MongoDB uses internally.

**495. What is the difference between SQL and NoSQL?**
SQL: structured, relational; NoSQL: flexible schema, various data models.

**496. What are the advantages of MongoDB?**
Flexible schema, horizontal scaling, rich queries, high performance.

**497. What are the disadvantages of MongoDB?**
Memory usage, data consistency challenges, limited transactions (before 4.0).

**498. What is a database in MongoDB?**
Container for collections, similar to database in relational systems.

**499. What is the _id field?**
Primary key field automatically created for every document.

**500. What is ObjectId?**
12-byte identifier consisting of timestamp, machine id, process id, and counter.

**501. What are the basic CRUD operations in MongoDB?**
Create (insert), Read (find), Update (update), Delete (remove).

**502. What is the insertOne() method?**
Method for inserting single document into collection.

**503. What is the insertMany() method?**
Method for inserting multiple documents into collection.

**504. What is the find() method?**
Method for querying documents from collection.

**505. What is the findOne() method?**
Method for querying single document from collection.

**506. What are query selectors in MongoDB?**
Operators for specifying criteria in queries ($eq, $ne, $gt, $lt, etc.).

**507. What are logical operators in MongoDB?**
$and, $or, $not, $nor for combining query conditions.

**508. What are comparison operators in MongoDB?**
$eq, $ne, $gt, $gte, $lt, $lte, $in, $nin for comparing values.

**509. What are element operators in MongoDB?**
$exists, $type for checking field existence and data types.

**510. What are array operators in MongoDB?**
$all, $elemMatch, $size for querying arrays.

**511. What is the updateOne() method?**
Method for updating single document in collection.

**512. What is the updateMany() method?**
Method for updating multiple documents in collection.

**513. What are update operators in MongoDB?**
$set, $unset, $inc, $push, $pull, etc. for modifying documents.

**514. What is the replaceOne() method?**
Method for replacing entire document except _id.

**515. What is the deleteOne() method?**
Method for deleting single document from collection.

**516. What is the deleteMany() method?**
Method for deleting multiple documents from collection.

**517. What is projection in MongoDB?**
Selecting specific fields to include or exclude in query results.

**518. What is sorting in MongoDB?**
Ordering query results using sort() method.

**519. What is limiting in MongoDB?**
Restricting number of documents returned using limit() method.

**520. What is skipping in MongoDB?**
Skipping number of documents using skip() method for pagination.

**521. What are indexes in MongoDB?**
Data structures improving query performance by creating shortcuts.

**522. What is the createIndex() method?**
Method for creating indexes on collection fields.

**523. What are compound indexes?**
Indexes on multiple fields.

**524. What is a unique index?**
Index ensuring uniqueness of field values.

**525. What is a sparse index?**
Index that only includes documents with indexed field.

**526. What is a text index?**
Index supporting text search queries.

**527. What is the aggregation framework?**
Pipeline-based data processing and analysis tool.

**528. What are aggregation stages?**
Individual operations in aggregation pipeline ($match, $group, $sort, etc.).

**529. What is the $match stage?**
Aggregation stage for filtering documents.

**530. What is the $group stage?**
Aggregation stage for grouping documents by specified fields.

**531. What is the $project stage?**
Aggregation stage for selecting and transforming fields.

**532. What is the $sort stage?**
Aggregation stage for sorting documents.

**533. What is the $limit stage?**
Aggregation stage for limiting number of documents.

**534. What is the $skip stage?**
Aggregation stage for skipping number of documents.

**535. What is the $lookup stage?**
Aggregation stage for performing left outer joins.

**536. What is the $unwind stage?**
Aggregation stage for deconstructing array fields.

**537. What is MapReduce in MongoDB?**
Data processing paradigm for large datasets (deprecated in favor of aggregation).

**538. What is replication in MongoDB?**
Process of maintaining multiple copies of data across servers.

**539. What is a replica set?**
Group of MongoDB instances maintaining same dataset.

**540. What is the primary node?**
Main node accepting write operations in replica set.

**541. What are secondary nodes?**
Nodes that replicate primary's data and can serve read operations.

**542. What is an arbiter?**
Replica set member that participates in elections but doesn't hold data.

**543. What is automatic failover?**
Process where secondary becomes primary when primary fails.

**544. What is sharding in MongoDB?**
Horizontal scaling by distributing data across multiple servers.

**545. What is a shard?**
Individual server or replica set holding subset of sharded data.

**546. What is a config server?**
Server storing metadata about sharded cluster.

**547. What is mongos?**
Router that directs operations to appropriate shards.

**548. What is a shard key?**
Field determining how documents are distributed across shards.

**549. What are transactions in MongoDB?**
ACID operations spanning multiple documents (available from 4.0).

**550. What is the session in MongoDB transactions?**
Context in which transaction operations are executed.

**551. What is read concern?**
Level of isolation for read operations.

**552. What is write concern?**
Acknowledgment level for write operations.

**553. What are the read concern levels?**
local, available, majority, linearizable, snapshot.

**554. What are the write concern levels?**
Acknowledged, unacknowledged, journaled, replica acknowledged.

**555. What is the oplog?**
Capped collection recording all write operations for replication.

**556. What is journaling?**
Write-ahead logging for crash recovery.

**557. What is GridFS?**
Specification for storing large files in MongoDB.

**558. What is the mongo shell?**
Interactive JavaScript interface for MongoDB.

**559. What is MongoDB Compass?**
GUI for MongoDB database management and analysis.

**560. What is Mongoose?**
Object Data Modeling (ODM) library for MongoDB and Node.js.

**561. What are Mongoose schemas?**
Blueprints defining structure of documents.

**562. What are Mongoose models?**
Constructors compiled from schemas for creating documents.

**563. What is middleware in Mongoose?**
Functions executed during specific lifecycle events.

**564. What are Mongoose virtuals?**
Document properties not stored in database.

**565. What is population in Mongoose?**
Process of replacing document references with actual documents.

**566. What are Mongoose hooks?**
Pre and post middleware for document operations.

**567. What is validation in Mongoose?**
Ensuring document data meets specified criteria.

**568. What are Mongoose plugins?**
Reusable schema functionality.

**569. What is connection pooling in MongoDB?**
Managing multiple database connections for efficiency.

**570. What are MongoDB best practices?**
Proper indexing, schema design, query optimization, connection management.

---

## SQL & PostgreSQL

### SQL Fundamentals (Questions 571-650)

**571. What is SQL?**
Structured Query Language for managing relational databases.

**572. What are the types of SQL commands?**
DDL (Data Definition), DML (Data Manipulation), DCL (Data Control), TCL (Transaction Control).

**573. What is DDL?**
Data Definition Language: CREATE, ALTER, DROP, TRUNCATE.

**574. What is DML?**
Data Manipulation Language: SELECT, INSERT, UPDATE, DELETE.

**575. What is DCL?**
Data Control Language: GRANT, REVOKE for permissions.

**576. What is TCL?**
Transaction Control Language: COMMIT, ROLLBACK, SAVEPOINT.

**577. What is a database?**
Collection of organized data stored and accessed electronically.

**578. What is a table?**
Collection of related data organized in rows and columns.

**579. What is a row/record?**
Single entry in database table.

**580. What is a column/field?**
Vertical entity in table containing specific data type.

**581. What is a primary key?**
Column or combination uniquely identifying each row.

**582. What is a foreign key?**
Column referencing primary key in another table.

**583. What is a composite key?**
Primary key consisting of multiple columns.

**584. What is normalization?**
Process of organizing data to reduce redundancy.

**585. What are the normal forms?**
1NF, 2NF, 3NF, BCNF rules for database normalization.

**586. What is denormalization?**
Intentionally adding redundancy for performance.

**587. What is an index?**
Data structure improving query performance.

**588. What are the types of indexes?**
Clustered, non-clustered, unique, composite indexes.

**589. What is a clustered index?**
Index that physically reorders table data.

**590. What is a non-clustered index?**
Index that creates separate structure pointing to table rows.

**591. What is a view?**
Virtual table based on query result.

**592. What is a stored procedure?**
Precompiled collection of SQL statements.

**593. What is a function in SQL?**
Routine that returns single value.

**594. What is a trigger?**
Special procedure that executes automatically on database events.

**595. What are the types of joins?**
INNER, LEFT, RIGHT, FULL OUTER, CROSS joins.

**596. What is INNER JOIN?**
Returns rows with matching values in both tables.

**597. What is LEFT JOIN?**
Returns all rows from left table and matched rows from right.

**598. What is RIGHT JOIN?**
Returns all rows from right table and matched rows from left.

**599. What is FULL OUTER JOIN?**
Returns all rows when there's match in either table.

**600. What is CROSS JOIN?**
Returns Cartesian product of both tables.

**601. What is UNION?**
Combines result sets of two or more queries.

**602. What is the difference between UNION and UNION ALL?**
UNION removes duplicates; UNION ALL includes all rows.

**603. What is a subquery?**
Query nested inside another query.

**604. What are correlated subqueries?**
Subqueries that reference columns from outer query.

**605. What is EXISTS operator?**
Tests for existence of rows in subquery.

**606. What is GROUP BY?**
Groups rows sharing property for aggregate functions.

**607. What is HAVING?**
Filters groups based on aggregate conditions.

**608. What is the difference between WHERE and HAVING?**
WHERE filters rows; HAVING filters groups.

**609. What are aggregate functions?**
Functions performing calculations on set of values: COUNT, SUM, AVG, MIN, MAX.

**610. What are window functions?**
Functions performing calculations across set of related rows.

**611. What is RANK() function?**
Assigns rank to rows within partition.

**612. What is ROW_NUMBER() function?**
Assigns unique sequential number to rows.

**613. What is DENSE_RANK() function?**
Assigns rank without gaps in sequence.

**614. What is a transaction?**
Unit of work performed against database.

**615. What are ACID properties?**
Atomicity, Consistency, Isolation, Durability.

**616. What is Atomicity?**
Transaction is all-or-nothing.

**617. What is Consistency?**
Database remains in valid state after transaction.

**618. What is Isolation?**
Concurrent transactions don't interfere with each other.

**619. What is Durability?**
Committed changes persist even after system failure.

**620. What are isolation levels?**
READ UNCOMMITTED, READ COMMITTED, REPEATABLE READ, SERIALIZABLE.

**621. What is deadlock?**
Situation where two transactions wait for each other indefinitely.

**622. What is a cursor?**
Database object for traversing result set row by row.

**623. What is PostgreSQL?**
Open-source object-relational database system.

**624. What are PostgreSQL advantages?**
ACID compliance, extensibility, JSON support, full-text search.

**625. What are PostgreSQL data types?**
Integer, text, boolean, date, timestamp, JSON, arrays, custom types.

**626. What is JSONB in PostgreSQL?**
Binary JSON format with indexing and query capabilities.

**627. What are PostgreSQL indexes?**
B-tree, Hash, GiST, SP-GiST, GIN, BRIN indexes.

**628. What is a GIN index?**
Generalized Inverted Index for composite values like arrays.

**629. What is full-text search in PostgreSQL?**
Built-in text search functionality with ranking and highlighting.

**630. What are PostgreSQL extensions?**
Additional functionality like PostGIS, pg_trgm, uuid-ossp.

**631. What is VACUUM in PostgreSQL?**
Maintenance operation reclaiming storage and updating statistics.

**632. What is ANALYZE in PostgreSQL?**
Operation collecting statistics for query planner.

**633. What are Common Table Expressions (CTEs)?**
Named temporary result sets within query scope.

**634. What is a recursive CTE?**
CTE that references itself for hierarchical queries.

**635. What is EXPLAIN in PostgreSQL?**
Command showing query execution plan.

**636. What is EXPLAIN ANALYZE?**
EXPLAIN with actual execution statistics.

**637. What is connection pooling in PostgreSQL?**
Managing database connections efficiently using tools like PgBouncer.

**638. What is replication in PostgreSQL?**
Copying data from master to slave servers for availability.

**639. What are the types of PostgreSQL replication?**
Streaming replication, logical replication, synchronous/asynchronous.

**640. What is WAL in PostgreSQL?**
Write-Ahead Logging for crash recovery and replication.

**641. What is partitioning in PostgreSQL?**
Dividing large tables into smaller, manageable pieces.

**642. What are the types of partitioning?**
Range, list, hash partitioning.

**643. What is a materialized view?**
View that stores query results physically for performance.

**644. What is the difference between view and materialized view?**
View: virtual, always current; Materialized view: stored, needs refresh.

**645. What are PostgreSQL constraints?**
Rules enforcing data integrity: NOT NULL, UNIQUE, CHECK, FOREIGN KEY.

**646. What is a check constraint?**
Constraint ensuring column values meet specific condition.

**647. What are PostgreSQL performance tuning techniques?**
Indexing, query optimization, configuration tuning, connection pooling.

**648. What is pg_stat_statements?**
Extension tracking execution statistics of SQL statements.

**649. What are PostgreSQL backup methods?**
pg_dump, pg_basebackup, continuous archiving.

**650. What is point-in-time recovery?**
Restoring database to specific moment using WAL files.

---

## Docker

### Docker Fundamentals (Questions 651-750)

**651. What is Docker?**
Platform for developing, shipping, and running applications in containers.

**652. What is containerization?**
Packaging applications with dependencies into lightweight, portable containers.

**653. What is the difference between containers and virtual machines?**
Containers: share OS kernel, lightweight; VMs: separate OS, heavier.

**654. What is a Docker image?**
Read-only template used to create containers.

**655. What is a Docker container?**
Running instance of Docker image.

**656. What is Dockerfile?**
Text file containing instructions to build Docker image.

**657. What are common Dockerfile instructions?**
FROM, RUN, COPY, ADD, WORKDIR, EXPOSE, CMD, ENTRYPOINT.

**658. What is the FROM instruction?**
Specifies base image for building new image.

**659. What is the RUN instruction?**
Executes commands during image build process.

**660. What is the COPY instruction?**
Copies files from host to image.

**661. What is the ADD instruction?**
Similar to COPY but with additional features like URL download.

**662. What is the difference between COPY and ADD?**
COPY: simple file copying; ADD: additional features, less predictable.

**663. What is the WORKDIR instruction?**
Sets working directory for subsequent instructions.

**664. What is the EXPOSE instruction?**
Documents which ports container listens on.

**665. What is the CMD instruction?**
Provides default command when container starts.

**666. What is the ENTRYPOINT instruction?**
Configures container to run as executable.

**667. What is the difference between CMD and ENTRYPOINT?**
CMD: can be overridden; ENTRYPOINT: always executed.

**668. What is Docker Hub?**
Cloud-based registry for sharing Docker images.

**669. What is a Docker registry?**
Storage and distribution system for Docker images.

**670. What are Docker layers?**
Read-only layers that make up Docker image.

**671. What is layer caching?**
Optimization where unchanged layers are reused.

**672. What is docker build command?**
Command for building Docker images from Dockerfile.

**673. What is docker run command?**
Command for creating and starting containers.

**674. What is docker ps command?**
Command for listing running containers.

**675. What is docker images command?**
Command for listing available images.

**676. What is docker pull command?**
Command for downloading images from registry.

**677. What is docker push command?**
Command for uploading images to registry.

**678. What is docker exec command?**
Command for executing commands in running container.

**679. What are Docker volumes?**
Mechanism for persisting data generated by containers.

**680. What are the types of Docker volumes?**
Anonymous volumes, named volumes, bind mounts.

**681. What is the difference between volumes and bind mounts?**
Volumes: managed by Docker; Bind mounts: direct host filesystem access.

**682. What is Docker networking?**
System allowing containers to communicate with each other.

**683. What are Docker network types?**
Bridge, host, overlay, macvlan, none networks.

**684. What is bridge network?**
Default network type for containers on single host.

**685. What is host network?**
Network mode where container uses host's networking.

**686. What is overlay network?**
Network spanning multiple Docker hosts.

**687. What is Docker Compose?**
Tool for defining and running multi-container applications.

**688. What is docker-compose.yml?**
YAML file defining services, networks, and volumes.

**689. What are Docker Compose commands?**
docker-compose up, down, build, logs, ps, exec.

**690. What is docker-compose up?**
Command for creating and starting services.

**691. What is docker-compose down?**
Command for stopping and removing services.

**692. What is the difference between docker run and docker-compose up?**
docker run: single container; docker-compose up: multiple services.

**693. What are environment variables in Docker?**
Variables passing configuration to containers.

**694. What is .dockerignore?**
File specifying files/folders to exclude from build context.

**695. What is multi-stage build?**
Dockerfile technique using multiple FROM instructions.

**696. What are the benefits of multi-stage builds?**
Smaller final images, improved security, better caching.

**697. What is Docker health check?**
Feature for monitoring container health status.

**698. What is Docker restart policy?**
Configuration defining when container should restart.

**699. What are Docker restart policy options?**
no, always, unless-stopped, on-failure.

**700. What is Docker Swarm?**
Native clustering and orchestration solution.

**701. What is orchestration?**
Automated management of containerized applications.

**702. What are orchestration platforms?**
Docker Swarm, Kubernetes, Apache Mesos.

**703. What is the difference between Docker Swarm and Kubernetes?**
Swarm: simpler, Docker-native; Kubernetes: more features, complex.

**704. What are Docker secrets?**
Secure way to manage sensitive data in containers.

**705. What are Docker configs?**
Non-sensitive configuration data for services.

**706. What is container orchestration?**
Managing lifecycle of containers in large, dynamic environments.

**707. What are Docker security best practices?**
Use official images, scan for vulnerabilities, run as non-root user.

**708. What is Docker image scanning?**
Process of analyzing images for security vulnerabilities.

**709. What is the principle of least privilege in Docker?**
Running containers with minimal required permissions.

**710. What are Docker logging drivers?**
Mechanisms for collecting container logs.

**711. What are common logging drivers?**
json-file, syslog, journald, splunk, fluentd.

**712. What is Docker monitoring?**
Tracking container and application performance metrics.

**713. What are Docker monitoring tools?**
cAdvisor, Prometheus, Grafana, ELK stack.

**714. What is container resource management?**
Controlling CPU, memory, and other resources for containers.

**715. What are Docker resource constraints?**
--memory, --cpus, --cpu-shares flags for limiting resources.

**716. What is Docker performance optimization?**
Techniques for improving container and application performance.

**717. What are Docker anti-patterns?**
Common mistakes like storing data in containers, running multiple processes.

**718. What is immutable infrastructure?**
Infrastructure that is never modified after deployment.

**719. What is the difference between development and production Docker setup?**
Development: bind mounts, debug mode; Production: volumes, optimized images.

**720. What is Docker in production best practices?**
Use specific image tags, implement health checks, monitor resources.

**721. What is container-as-a-service (CaaS)?**
Cloud service providing container orchestration and management.

**722. What are popular container registries?**
Docker Hub, AWS ECR, Google Container Registry, Azure Container Registry.

**723. What is private registry?**
Self-hosted registry for storing proprietary images.

**724. What is image signing?**
Cryptographically signing images to verify authenticity.

**725. What is Docker Content Trust?**
Security feature ensuring image authenticity and integrity.

**726. What is alpine Linux in Docker?**
Minimal Linux distribution often used for smaller images.

**727. What are distroless images?**
Container images containing only application and runtime dependencies.

**728. What is scratch image?**
Empty base image for building minimal containers.

**729. What is Docker build context?**
Files and folders sent to Docker daemon during build.

**730. What are Docker build arguments?**
Variables available during build time.

**731. What is .env file in Docker Compose?**
File containing environment variables for compose services.

**732. What is Docker Compose override?**
Additional compose file for environment-specific configurations.

**733. What is Docker service?**
Definition of how containers should run in production.

**734. What is Docker stack?**
Collection of services that make up application in swarm mode.

# Express.js Interview Questions

## Express.js Fundamentals (Questions 751-800)

**751. What is Express.js?**
Fast, unopinionated web framework for Node.js applications.

**752. What are the main features of Express.js?**
Routing, middleware, template engines, static file serving, error handling.

**753. How do you install Express.js?**
npm install express

**754. How do you create a basic Express server?**
```javascript
const express = require('express');
const app = express();
app.listen(3000);
```

**755. What is the Express application object?**
Main interface representing Express application with methods for routing and configuration.

**756. What is routing in Express.js?**
Mechanism for defining how application responds to client requests for specific endpoints.

**757. What are HTTP methods supported by Express?**
GET, POST, PUT, DELETE, PATCH, HEAD, OPTIONS, ALL.

**758. How do you define routes in Express?**
Using app.get(), app.post(), app.put(), app.delete(), etc.

**759. What is app.all()?**
Method that matches all HTTP verbs for a route.

**760. What are route parameters?**
Dynamic segments in route paths accessible via req.params.

**761. How do you define route parameters?**
Using colon syntax: app.get('/users/:id', handler)

**762. What are query parameters?**
URL parameters accessible via req.query object.

**763. What is the difference between req.params and req.query?**
params: route parameters; query: URL query string parameters.

**764. What is middleware in Express.js?**
Functions with access to request, response objects and next function in request-response cycle.

**765. What are the types of middleware?**
Application-level, router-level, error-handling, built-in, third-party middleware.

**766. How do you create custom middleware?**
Function with (req, res, next) parameters calling next() to continue.

**767. What is the next() function?**
Function that passes control to next middleware in the stack.

**768. What is application-level middleware?**
Middleware bound to app object using app.use() or app.METHOD().

**769. What is router-level middleware?**
Middleware bound to express.Router() instance.

**770. What is the difference between app.use() and app.get()?**
app.use(): applies to all HTTP methods; app.get(): applies only to GET requests.

**771. What is the order of middleware execution?**
Middleware executes in the order it's defined (top to bottom).

**772. What are built-in middleware in Express?**
express.static(), express.json(), express.urlencoded().

**773. What is express.static()?**
Built-in middleware for serving static files.

**774. What is express.json()?**
Built-in middleware for parsing JSON request bodies.

**775. What is express.urlencoded()?**
Built-in middleware for parsing URL-encoded request bodies.

**776. What are popular third-party middleware?**
body-parser, cors, helmet, morgan, compression, cookie-parser.

**777. What is body-parser?**
Middleware for parsing request bodies (now built into Express).

**778. What is cors middleware?**
Middleware for handling Cross-Origin Resource Sharing.

**779. What is helmet middleware?**
Security middleware that sets various HTTP headers.

**780. What is morgan middleware?**
HTTP request logger middleware.

**781. What is compression middleware?**
Middleware for compressing response bodies.

**782. What is cookie-parser middleware?**
Middleware for parsing Cookie header and populating req.cookies.

**783. What is the request object (req)?**
Object representing HTTP request with properties like params, query, body.

**784. What are important req object properties?**
req.params, req.query, req.body, req.headers, req.method, req.url.

**785. What is the response object (res)?**
Object representing HTTP response with methods for sending responses.

**786. What are important res object methods?**
res.send(), res.json(), res.status(), res.redirect(), res.render().

**787. What is res.send()?**
Method for sending HTTP response with automatic content-type detection.

**788. What is res.json()?**
Method for sending JSON response with appropriate content-type.

**789. What is res.status()?**
Method for setting HTTP status code of response.

**790. What is res.redirect()?**
Method for redirecting request to different URL.

**791. What is template engine in Express?**
Engine for generating HTML markup with dynamic content.

**792. What are popular template engines?**
EJS, Handlebars, Pug (Jade), Mustache, Nunjucks.

**793. How do you set up a template engine?**
Using app.set('view engine', 'ejs') and app.set('views', './views').

**794. What is res.render()?**
Method for rendering template with data and sending HTML response.

**795. What is error handling in Express?**
Mechanism for catching and processing errors in middleware and routes.

**796. How do you create error-handling middleware?**
Function with (err, req, res, next) four parameters.

**797. What is the default error handler?**
Built-in error handler that Express uses when no custom handler is defined.

**798. How do you trigger error handling?**
By passing error to next() function: next(error).

**799. What is express.Router()?**
Modular mountable route handlers for creating modular routes.

**800. How do you use Router for modular routing?**
Create router instance, define routes, and mount with app.use().

## Express.js Advanced (Questions 801-850)

**801. What is Express Generator?**
Command-line tool for quickly creating Express application skeleton.

**802. How do you use Express Generator?**
npx express-generator myapp or npm install -g express-generator.

**803. What is the structure created by Express Generator?**
app.js, routes/, views/, public/, bin/www, package.json.

**804. What is app.js in Express Generator?**
Main application file containing Express app configuration.

**805. What is bin/www?**
Script that starts the HTTP server and handles server configuration.

**806. What are Express.js best practices for routing?**
Use Router for modular routes, organize by feature, use middleware for common logic.

**807. How do you handle file uploads in Express?**
Using multer middleware for multipart/form-data handling.

**808. What is multer?**
Middleware for handling multipart/form-data (file uploads).

**809. How do you implement authentication in Express?**
Using sessions, JWT tokens, passport.js, or custom authentication middleware.

**810. What is Passport.js?**
Authentication middleware for Node.js with various strategies.

**811. What are Passport strategies?**
Different authentication methods: local, OAuth, OpenID, etc.

**812. How do you implement session management?**
Using express-session middleware with session store.

**813. What is express-session?**
Middleware for session management in Express applications.

**814. What are session stores?**
Storage backends for session data: memory, Redis, MongoDB, etc.

**815. What is JWT (JSON Web Token)?**
Compact, URL-safe token format for secure information transmission.

**816. How do you implement JWT authentication?**
Generate token on login, verify token on protected routes.

**817. What is input validation in Express?**
Process of validating and sanitizing user input data.

**818. What are popular validation libraries?**
joi, express-validator, yup, ajv.

**819. What is express-validator?**
Middleware for validation and sanitization based on validator.js.

**820. How do you handle CORS in Express?**
Using cors middleware or manually setting headers.

**821. What is rate limiting in Express?**
Controlling number of requests from clients to prevent abuse.

**822. What is express-rate-limit?**
Middleware for basic rate limiting in Express applications.

**823. How do you implement logging in Express?**
Using morgan for HTTP logging, winston for application logging.

**824. What is winston?**
Versatile logging library for Node.js applications.

**825. What are winston transports?**
Different output destinations for logs: console, file, database.

**826. How do you handle environment variables?**
Using process.env and dotenv package for loading .env files.

**827. What is dotenv?**
Zero-dependency module for loading environment variables from .env file.

**828. What are Express.js security best practices?**
Use helmet, validate input, implement authentication, use HTTPS, update dependencies.

**829. How do you implement caching in Express?**
Using memory caching, Redis, or HTTP caching headers.

**830. What is cache-control header?**
HTTP header controlling caching behavior of responses.

**831. How do you implement WebSocket in Express?**
Using Socket.IO or ws library alongside Express server.

**832. What is Socket.IO?**
Library for real-time bidirectional event-based communication.

**833. How do you test Express applications?**
Using Jest, Mocha, Supertest for HTTP testing.

**834. What is Supertest?**
Library for testing HTTP servers in Node.js.

**835. How do you implement API versioning?**
Using route prefixes, headers, or subdomain-based versioning.

**836. What is REST API design in Express?**
Following RESTful principles for resource-based URL design.

**837. What are HTTP status codes for REST APIs?**
200 (OK), 201 (Created), 400 (Bad Request), 404 (Not Found), 500 (Server Error).

**838. How do you implement pagination in Express?**
Using query parameters (page, limit) and database offset/limit.

**839. What is API documentation for Express?**
Documenting endpoints using Swagger/OpenAPI, JSDoc, or Postman.

**840. What is Swagger/OpenAPI?**
Specification for describing REST APIs with interactive documentation.

**841. How do you handle database integration in Express?**
Using ORMs like Sequelize, Mongoose, or database drivers.

**842. What is connection pooling in Express?**
Managing database connections efficiently to improve performance.

**843. How do you implement graceful shutdown?**
Handling SIGTERM/SIGINT signals to close connections cleanly.

**844. What is clustering in Express?**
Running multiple instances of Express app to utilize multiple CPU cores.

**845. How do you deploy Express applications?**
Using PM2, Docker, cloud platforms (Heroku, AWS, Azure).

**846. What are Express.js performance optimization techniques?**
Caching, compression, connection pooling, code splitting, CDN usage.

**847. What is the difference between Express and Koa?**
Express: callback-based; Koa: async/await-based, smaller core.

**848. What is the difference between Express and Fastify?**
Express: mature ecosystem; Fastify: better performance, JSON schema validation.

**849. What is the difference between Express and NestJS?**
Express: minimal framework; NestJS: opinionated framework with decorators.

**850. What are alternatives to Express.js?**
Koa.js, Fastify, Hapi.js, Restify, NestJS.

# Docker Remaining Interview Questions

## Docker Advanced Topics (Questions 735-785)

**735. What is docker-compose build?**
Command for building images defined in docker-compose.yml file.

**736. What is docker-compose logs?**
Command for viewing logs from services defined in compose file.

**737. What is docker-compose ps?**
Command for listing containers created by docker-compose.

**738. What is docker-compose exec?**
Command for executing commands in running compose services.

**739. What is docker-compose scale?**
Command for scaling services to specified number of containers.

**740. What are Docker environment files?**
.env files containing environment variables for compose services.

**741. What is docker-compose override?**
Additional compose file (docker-compose.override.yml) for environment-specific configurations.

**742. What are Docker profiles in Compose?**
Feature for selectively enabling services based on profiles.

**743. What is Docker build context optimization?**
Minimizing files sent to Docker daemon using .dockerignore and multi-stage builds.

**744. What are Docker build arguments (ARG)?**
Variables available only during build time, defined with ARG instruction.

**745. What is the difference between ARG and ENV?**
ARG: build-time only; ENV: available at runtime in containers.

**746. What is Docker image layering?**
Each Dockerfile instruction creates a new layer in the image.

**747. What is layer caching in Docker?**
Reusing unchanged layers from previous builds to speed up build process.

**748. How do you optimize Docker image size?**
Use alpine images, multi-stage builds, combine RUN commands, remove unnecessary files.

**749. What is the scratch image?**
Empty base image containing no files or programs.

**750. What are distroless images?**
Images containing only application and runtime dependencies, no shell or package manager.

**751. What is Docker image vulnerability scanning?**
Analyzing images for known security vulnerabilities in packages.

**752. What are popular image scanning tools?**
Clair, Trivy, Snyk, Docker Security Scanning, Anchore.

**753. What is Docker Content Trust (DCT)?**
Feature providing image authenticity and integrity through digital signatures.

**754. What is image signing?**
Cryptographically signing Docker images to verify authenticity.

**755. What is the principle of least privilege in containers?**
Running containers with minimal required permissions and capabilities.

**756. How do you run containers as non-root user?**
Using USER instruction in Dockerfile or --user flag.

**757. What are Linux capabilities in Docker?**
Fine-grained privileges that can be added or dropped from containers.

**758. What is container escape?**
Security vulnerability allowing attackers to break out of container isolation.

**759. What are Docker secrets management best practices?**
Use Docker secrets, environment variables, external secret management systems.

**760. What is the Docker daemon socket?**
Unix socket (/var/run/docker.sock) for communicating with Docker daemon.

**761. What are the risks of mounting Docker socket?**
Provides root-level access to host system, potential security vulnerability.

**762. What is Docker-in-Docker (DinD)?**
Running Docker daemon inside Docker container.

**763. What are alternatives to Docker-in-Docker?**
Docker socket mounting, rootless Docker, Podman, Buildah.

**764. What is rootless Docker?**
Running Docker daemon and containers as non-root user.

**765. What is Podman?**
Daemonless container engine compatible with Docker commands.

**766. What is Buildah?**
Tool for building OCI and Docker container images.

**767. What is the Open Container Initiative (OCI)?**
Industry standards around container formats and runtimes.

**768. What is the difference between Docker and containerd?**
Docker: complete platform; containerd: container runtime.

**769. What is runc?**
Low-level container runtime implementing OCI specification.

**770. What is container orchestration?**
Automated management, scaling, and networking of containers.

**771. What is Docker Swarm mode?**
Native clustering and orchestration solution for Docker.

**772. What are Docker Swarm services?**
Declarative way to run and scale containers across swarm cluster.

**773. What is a Docker Swarm node?**
Instance of Docker Engine participating in swarm.

**774. What are manager and worker nodes?**
Manager: control plane, scheduling; Worker: run containers.

**775. What is Docker stack?**
Group of services deployed together using docker-compose.yml.

**776. What is service mesh?**
Infrastructure layer handling service-to-service communication.

**777. What are popular service mesh solutions?**
Istio, Linkerd, Consul Connect, AWS App Mesh.

**778. What is container monitoring?**
Tracking resource usage, performance metrics, and health of containers.

**779. What are container monitoring tools?**
Prometheus + Grafana, cAdvisor, Docker Stats, Datadog, New Relic.

**780. What is cAdvisor?**
Container Advisor - tool for monitoring container resource usage.

**781. What is Prometheus in container monitoring?**
Open-source monitoring system collecting and storing metrics.

**782. What is Grafana?**
Visualization and analytics platform often used with Prometheus.

**783. What is centralized logging for containers?**
Collecting logs from all containers in central location.

**784. What are popular logging solutions?**
ELK Stack (Elasticsearch, Logstash, Kibana), Fluentd, Splunk.

**785. What is the ELK Stack?**
Elasticsearch (search), Logstash (processing), Kibana (visualization).

## Docker in Production (Questions 786-830)

**786. What are Docker production deployment strategies?**
Blue-green deployment, rolling updates, canary deployments.

**787. What is blue-green deployment?**
Strategy switching traffic between two identical production environments.

**788. What is rolling update?**
Gradually replacing containers with new versions to avoid downtime.

**789. What is canary deployment?**
Releasing new version to small subset of users before full deployment.

**790. What are Docker health checks in production?**
Automated tests determining if container is healthy and ready to serve traffic.

**791. How do you implement zero-downtime deployment?**
Using load balancers, health checks, and gradual container replacement.

**792. What is container lifecycle management?**
Managing creation, running, stopping, and removal of containers.

**793. What are Docker restart policies?**
Configuration determining when containers should restart: no, always, unless-stopped, on-failure.

**794. What is resource management in production?**
Setting CPU and memory limits to prevent resource contention.

**795. What are Docker resource constraints?**
--memory, --cpus, --cpu-shares, --memory-swap flags.

**796. What is container auto-scaling?**
Automatically adjusting number of containers based on load.

**797. What are auto-scaling triggers?**
CPU usage, memory usage, request queue length, custom metrics.

**798. What is Docker in CI/CD pipelines?**
Using containers for consistent build, test, and deployment environments.

**799. What are benefits of Docker in CI/CD?**
Environment consistency, faster builds, isolated testing, easy rollbacks.

**800. What are popular CI/CD tools with Docker support?**
Jenkins, GitLab CI, GitHub Actions, Azure DevOps, CircleCI.

**801. What is infrastructure as code with Docker?**
Managing infrastructure using version-controlled configuration files.

**802. What are infrastructure as code tools?**
Terraform, CloudFormation, Ansible, Pulumi.

**803. What is container backup strategy?**
Backing up persistent data, configurations, and images.

**804. How do you backup Docker volumes?**
Creating volume backups using docker run with volume mounts.

**805. What is disaster recovery for containerized applications?**
Planning for system failures and data recovery procedures.

**806. What is container security scanning in production?**
Continuously scanning running containers for vulnerabilities.

**807. What are runtime security tools?**
Falco, Twistlock, Aqua Security, Sysdig Secure.

**808. What is network security for containers?**
Implementing firewalls, network policies, and encrypted communication.

**809. What are container compliance requirements?**
Meeting regulatory standards like PCI-DSS, HIPAA, SOC 2.

**810. What is container image governance?**
Policies and processes for managing container images in organization.

**811. What are image signing and scanning policies?**
Requirements for cryptographic signing and vulnerability scanning.

**812. What is container registry security?**
Securing access to and content of container registries.

**813. What are private registry considerations?**
Security, scalability, backup, access control, integration.

**814. What is container cost optimization?**
Strategies for reducing infrastructure costs of containerized applications.

**815. What are cost optimization techniques?**
Right-sizing containers, efficient resource allocation, reserved instances.

**816. What is multi-tenancy in containers?**
Running multiple applications or customers on shared infrastructure.

**817. What are multi-tenancy isolation strategies?**
Namespaces, resource quotas, network policies, separate clusters.

**818. What is container performance tuning?**
Optimizing container and application performance in production.

**819. What are performance tuning areas?**
Resource allocation, I/O optimization, network configuration, application tuning.

**820. What is observability in containerized systems?**
Comprehensive monitoring including metrics, logs, and traces.

**821. What are the three pillars of observability?**
Metrics (what), Logs (why), Traces (how).

**822. What is distributed tracing?**
Tracking requests across multiple containers and services.

**823. What are distributed tracing tools?**
Jaeger, Zipkin, AWS X-Ray, Google Cloud Trace.

**824. What is container troubleshooting?**
Diagnosing and resolving issues in containerized applications.

**825. What are common container issues?**
Resource limits, networking problems, storage issues, configuration errors.

**826. What are container debugging techniques?**
Log analysis, exec into containers, resource monitoring, health checks.

**827. What is Docker system pruning?**
Cleaning up unused containers, images, networks, and volumes.

**828. What are Docker system commands?**
docker system df, docker system prune, docker system info.

**829. What is container lifecycle automation?**
Automating container deployment, scaling, and maintenance tasks.

**830. What are the future trends in containerization?**
Serverless containers, WebAssembly, improved security, edge computing.

## Docker Ecosystem (Questions 831-850)

**831. What is Kubernetes?**
Container orchestration platform for automating deployment, scaling, and management of containerized applications.

**832. What is the difference between Docker Swarm and Kubernetes?**
Docker Swarm: simpler, Docker-native; Kubernetes: more features, complex, industry standard.

**833. What is kubectl?**
Command-line tool for interacting with Kubernetes clusters.

**834. What are Kubernetes pods?**
Smallest deployable units containing one or more containers.

**835. What is container runtime interface (CRI)?**
Standard for container runtimes to work with Kubernetes.

**836. What are popular container runtimes?**
Docker, containerd, CRI-O, runc.

**837. What is Helm?**
Package manager for Kubernetes applications.

**838. What are Helm charts?**
Packages of pre-configured Kubernetes resources.

**839. What is Istio?**
Service mesh providing traffic management, security, and observability.

**840. What is container as a service (CaaS)?**
Cloud service providing container orchestration without managing infrastructure.

**841. What are popular CaaS platforms?**
Amazon ECS, Google Cloud Run, Azure Container Instances.

**842. What is serverless containers?**
Running containers without managing underlying servers (AWS Fargate, Google Cloud Run).

**843. What is the difference between containers and serverless?**
Containers: more control, longer-running; Serverless: event-driven, auto-scaling, pay-per-use.

**844. What is WebAssembly (WASM) and containers?**
Emerging technology for running portable code in containers with near-native performance.

**845. What is edge computing with containers?**
Running containerized applications closer to end users for reduced latency.

**846. What are container security standards?**
CIS Docker Benchmark, NIST guidelines, OCI security specifications.

**847. What is the future of container technology?**
Improved security, WebAssembly integration, better developer experience, edge computing.

**848. What are container alternatives?**
Virtual machines, unikernels, WebAssembly, serverless functions.

**849. What is the container ecosystem landscape?**
Runtime (Docker, Podman), Orchestration (Kubernetes), Service Mesh (Istio), Monitoring (Prometheus).

**850. What are container best practices summary?**
Use official images, implement security scanning, optimize image size, monitor resources, automate deployments.

**1010. What is security culture?**
Organization-wide commitment to security awareness and practices.

---

## Testing

### Testing Fundamentals (Questions 1011-1100)

**1011. What is software testing?**
Process of evaluating software to ensure it meets requirements and functions correctly.

**1012. What are the types of testing?**
Unit testing, integration testing, system testing, acceptance testing.

**1013. What is unit testing?**
Testing individual components or modules in isolation.

**1014. What is integration testing?**
Testing how different modules work together.

**1015. What is system testing?**
Testing complete integrated system to verify it meets requirements.

**1016. What is acceptance testing?**
Testing to determine if system meets business requirements.

**1017. What is Test-Driven Development (TDD)?**
Development process where tests are written before code.

**1018. What are the TDD phases?**
Red (write failing test), Green (make test pass), Refactor.

**1019. What is Behavior-Driven Development (BDD)?**
Development approach focusing on behavior specification using natural language.

**1020. What is the difference between TDD and BDD?**
TDD: focuses on implementation; BDD: focuses on behavior and requirements.

**1021. What are JavaScript testing frameworks?**
Jest, Mocha, Jasmine, Vitest, QUnit.

**1022. What is Jest?**
Popular JavaScript testing framework with built-in mocking and coverage.

**1023. What are Jest features?**
Zero configuration, snapshot testing, mocking, code coverage.

**1024. What is describe() in Jest?**
Function grouping related tests together.

**1025. What is it() or test() in Jest?**
Function defining individual test cases.

**1026. What are Jest matchers?**
Functions checking if values meet certain conditions.

**1027. What are common Jest matchers?**
toBe, toEqual, toBeNull, toBeTruthy, toContain, toThrow.

**1028. What is beforeEach() in Jest?**
Function running before each test in describe block.

**1029. What is afterEach() in Jest?**
Function running after each test in describe block.

**1030. What is mocking in testing?**
Creating fake implementations of dependencies for isolated testing.

**1031. What is jest.mock()?**
Function for mocking modules in Jest.

**1032. What is jest.fn()?**
Creating mock functions in Jest.

**1033. What is spying in testing?**
Monitoring function calls without changing implementation.

**1034. What is stubbing?**
Replacing function implementation with predefined behavior.

**1035. What is snapshot testing?**
Comparing component output against saved snapshots.

**1036. What are the benefits of snapshot testing?**
Catching unexpected changes, easy regression testing.

**1037. What is code coverage?**
Measuring how much code is executed during tests.

**1038. What are coverage metrics?**
Line coverage, branch coverage, function coverage, statement coverage.

**1039. What is a good code coverage percentage?**
Generally 70-80%, but quality matters more than quantity.

**1040. What is React Testing Library?**
Testing utilities for React focusing on user behavior.

**1041. What are React Testing Library principles?**
Test behavior not implementation, query by accessibility attributes.

**1042. What is render() in React Testing Library?**
Function rendering React components for testing.

**1043. What are query methods in React Testing Library?**
getBy, findBy, queryBy with various selectors.

**1044. What is the difference between getBy and queryBy?**
getBy throws error if not found; queryBy returns null.

**1045. What is fireEvent in React Testing Library?**
Utility for triggering DOM events in tests.

**1046. What is userEvent?**
More realistic user interaction simulation than fireEvent.

**1047. What is async testing?**
Testing asynchronous operations like API calls.

**1048. What is waitFor() in React Testing Library?**
Waiting for asynchronous changes in tests.

**1049. What is MSW (Mock Service Worker)?**
Tool for mocking API requests in tests.

**1050. What is end-to-end testing?**
Testing complete user workflows from start to finish.

**1051. What are E2E testing tools?**
Cypress, Playwright, Selenium, Puppeteer.

**1052. What is Cypress?**
End-to-end testing framework running in browser.

**1053. What are Cypress advantages?**
Real-time reloading, time travel debugging, automatic waiting.

**1054. What is Playwright?**
Cross-browser end-to-end testing framework by Microsoft.

**1055. What is Selenium?**
Web automation framework supporting multiple browsers and languages.

**1056. What is visual regression testing?**
Comparing screenshots to detect visual changes.

**1057. What are visual testing tools?**
Percy, Chromatic, Applitools, BackstopJS.

**1058. What is accessibility testing?**
Ensuring applications work for users with disabilities.

**1059. What are accessibility testing tools?**
axe-core, React Axe, WAVE, Lighthouse accessibility audit.

**1060. What is performance testing?**
Evaluating application performance under various conditions.

**1061. What are performance testing tools?**
Lighthouse**617. What is Consistency?**
Database remains in valid state after transaction.

# Remaining Interview Question Sections

## System Design & Architecture (Questions 851-950)

**851. What is system design?**
Process of defining architecture, components, modules, interfaces, and data for a system.

**852. What are the key principles of system design?**
Scalability, reliability, availability, consistency, performance, security.

**853. What is scalability?**
System's ability to handle increased load by adding resources.

**854. What is horizontal vs vertical scaling?**
Horizontal: adding more machines; Vertical: upgrading existing machine.

**855. What is load balancing?**
Distributing incoming requests across multiple servers.

**856. What are types of load balancers?**
Layer 4 (transport), Layer 7 (application), DNS load balancing.

**857. What is caching?**
Storing frequently accessed data in fast storage for quick retrieval.

**858. What are caching strategies?**
Cache-aside, write-through, write-behind, refresh-ahead.

**859. What is CDN (Content Delivery Network)?**
Geographically distributed servers for delivering content efficiently.

**860. What is database sharding?**
Horizontally partitioning database across multiple machines.

**861. What is database replication?**
Creating copies of database on multiple servers for availability.

**862. What is CAP theorem?**
System can guarantee only two of: Consistency, Availability, Partition tolerance.

**863. What is eventual consistency?**
Consistency model where system becomes consistent over time.

**864. What is ACID vs BASE?**
ACID: strong consistency; BASE: eventual consistency, high availability.

**865. What is microservices architecture?**
Architectural pattern decomposing application into small, independent services.

**866. What is monolithic architecture?**
Traditional approach where application is built as single deployable unit.

**867. What are pros and cons of microservices?**
Pros: scalability, technology diversity; Cons: complexity, network latency.

**868. What is service discovery?**
Mechanism for services to find and communicate with each other.

**869. What is API gateway?**
Entry point managing requests between clients and microservices.

**870. What is message queue?**
System for asynchronous communication between services.

**871. What are popular message queue systems?**
RabbitMQ, Apache Kafka, Amazon SQS, Redis Pub/Sub.

**872. What is event-driven architecture?**
Architecture where services communicate through events.

**873. What is pub/sub pattern?**
Publishers send messages to topics; subscribers receive from topics.

**874. What is CQRS?**
Command Query Responsibility Segregation - separating read and write operations.

**875. What is event sourcing?**
Storing state changes as sequence of events rather than current state.

**876. What is circuit breaker pattern?**
Pattern preventing cascading failures by monitoring service health.

**877. What is bulkhead pattern?**
Isolating resources to prevent failures from affecting entire system.

**878. What is retry pattern?**
Automatically retrying failed operations with backoff strategies.

**879. What is rate limiting?**
Controlling number of requests to prevent system overload.

**880. What is back pressure?**
Mechanism to handle situations where consumer can't keep up with producer.

**881. What is database indexing strategy?**
Planning indexes to optimize query performance.

**882. What is connection pooling?**
Managing database connections efficiently to improve performance.

**883. What is lazy loading vs eager loading?**
Lazy: load data when needed; Eager: load data immediately.

**884. What is data partitioning?**
Dividing large datasets across multiple storage systems.

**885. What is consensus algorithms?**
Algorithms for achieving agreement in distributed systems (Raft, PBFT).

**886. What is distributed locking?**
Coordinating access to shared resources across multiple nodes.

**887. What is saga pattern?**
Managing distributed transactions across microservices.

**888. What is two-phase commit?**
Protocol for ensuring atomicity in distributed transactions.

**889. What is master-slave vs master-master replication?**
Master-slave: one write node; Master-master: multiple write nodes.

**890. What is read replica?**
Read-only copy of database for handling read queries.

**891. What is blue-green deployment?**
Deployment strategy using two identical production environments.

**892. What is canary deployment?**
Gradually rolling out changes to subset of users.

**893. What is A/B testing architecture?**
Infrastructure for testing different versions with user groups.

**894. What is monitoring and observability?**
Tracking system health through metrics, logs, and traces.

**895. What is distributed tracing?**
Tracking requests across multiple services in distributed system.

**896. What is log aggregation?**
Collecting logs from multiple sources into centralized system.

**897. What is service mesh?**
Infrastructure layer handling service-to-service communication.

**898. What is data lake vs data warehouse?**
Data lake: raw data storage; Data warehouse: structured analytical data.

**899. What is real-time vs batch processing?**
Real-time: immediate processing; Batch: processing data in chunks.

**900. What is stream processing?**
Processing continuous data streams in real-time.

**901. What is MapReduce?**
Programming model for processing large datasets across clusters.

**902. What is Apache Spark?**
Unified analytics engine for large-scale data processing.

**903. What is Apache Kafka?**
Distributed streaming platform for high-throughput data pipelines.

**904. What is REST API design principles?**
Resource-based URLs, HTTP methods, stateless, cacheable.

**905. What is GraphQL?**
Query language and runtime for APIs providing flexible data fetching.

**906. What is gRPC?**
High-performance RPC framework using HTTP/2 and Protocol Buffers.

**907. What is WebSocket?**
Protocol providing full-duplex communication over single TCP connection.

**908. What is content negotiation?**
Process of selecting best representation for response (JSON, XML).

**909. What is idempotency?**
Property where operations produce same result when applied multiple times.

**910. What is API versioning strategies?**
URL versioning, header versioning, content negotiation.

**911. What is authentication vs authorization?**
Authentication: verifying identity; Authorization: granting permissions.

**912. What is OAuth 2.0?**
Authorization framework for secure API access.

**913. What is JWT token-based authentication?**
Using JSON Web Tokens for stateless authentication.

**914. What is SSL/TLS?**
Cryptographic protocols for secure communication over networks.

**915. What is symmetric vs asymmetric encryption?**
Symmetric: same key; Asymmetric: public/private key pairs.

**916. What is hashing vs encryption?**
Hashing: one-way function; Encryption: reversible transformation.

**917. What is database normalization in system design?**
Organizing data to reduce redundancy and improve integrity.

**918. What is denormalization?**
Intentionally adding redundancy for performance optimization.

**919. What is OLTP vs OLAP?**
OLTP: transactional processing; OLAP: analytical processing.

**920. What is data modeling?**
Process of creating data structure for database systems.

**921. What is schema design for NoSQL?**
Designing data structure for document, key-value, or graph databases.

**922. What is time series data architecture?**
Systems optimized for time-stamped data storage and analysis.

**923. What is search architecture?**
Systems for full-text search and information retrieval.

**924. What is recommendation system architecture?**
Systems for providing personalized content recommendations.

**925. What is machine learning system design?**
Architecture for training, serving, and monitoring ML models.

**926. What is batch prediction vs real-time prediction?**
Batch: offline predictions; Real-time: online predictions on demand.

**927. What is feature store?**
Centralized repository for machine learning features.

**928. What is model serving?**
Deploying ML models to production for making predictions.

**929. What is A/B testing for ML models?**
Comparing performance of different models with live traffic.

**930. What is data pipeline architecture?**
Systems for extracting, transforming, and loading data (ETL/ELT).

**931. What is lambda architecture?**
Big data architecture combining batch and real-time processing.

**932. What is kappa architecture?**
Simplified architecture using only stream processing.

**933. What is disaster recovery?**
Planning and procedures for recovering from system failures.

**934. What is backup strategies?**
Methods for creating copies of data for recovery purposes.

**935. What is high availability design?**
Designing systems to minimize downtime and ensure reliability.

**936. What is fault tolerance?**
System's ability to continue operating despite component failures.

**937. What is graceful degradation?**
Maintaining partial functionality when system components fail.

**938. What is capacity planning?**
Determining resource requirements for expected system load.

**939. What is performance testing?**
Evaluating system performance under various load conditions.

**940. What is bottleneck analysis?**
Identifying limiting factors in system performance.

**941. What is cost optimization in system design?**
Balancing performance requirements with infrastructure costs.

**942. What is cloud-native architecture?**
Designing applications specifically for cloud environments.

**943. What is multi-cloud strategy?**
Using multiple cloud providers to avoid vendor lock-in.

**944. What is edge computing architecture?**
Processing data closer to source for reduced latency.

**945. What is serverless architecture?**
Using cloud functions for event-driven, auto-scaling applications.

**946. What is container orchestration?**
Managing containerized applications across clusters.

**947. What is infrastructure as code?**
Managing infrastructure through version-controlled configuration.

**948. What is GitOps?**
Using Git workflows for infrastructure and application deployment.

**949. What is chaos engineering?**
Practice of testing system resilience by introducing failures.

**950. What is system design interview approach?**
Understand requirements, estimate scale, design high-level, dive deep, address bottlenecks.

## Performance & Optimization (Questions 951-1010)

**951. What is web performance optimization?**
Techniques for improving website loading speed and user experience.

**952. What is the critical rendering path?**
Sequence of steps browser takes to render initial view of page.

**953. What are Core Web Vitals?**
Google's metrics for measuring user experience: LCP, FID, CLS.

**954. What is Largest Contentful Paint (LCP)?**
Metric measuring loading performance of largest content element.

**955. What is First Input Delay (FID)?**
Metric measuring interactivity delay from first user input.

**956. What is Cumulative Layout Shift (CLS)?**
Metric measuring visual stability of page elements.

**957. What is Time to First Byte (TTFB)?**
Time between request initiation and first byte received.

**958. What is First Contentful Paint (FCP)?**
Time when first content element appears on screen.

**959. What is Speed Index?**
Metric showing how quickly page content is visually populated.

**960. What is image optimization?**
Techniques for reducing image file sizes while maintaining quality.

**961. What are modern image formats?**
WebP, AVIF, JPEG XL offering better compression than traditional formats.

**962. What is lazy loading?**
Loading content only when it's needed or about to be viewed.

**963. What is code splitting?**
Dividing application code into smaller chunks loaded on demand.

**964. What is tree shaking?**
Eliminating unused code from final bundle.

**965. What is minification?**
Removing unnecessary characters from code to reduce file size.

**966. What is compression (gzip/brotli)?**
Reducing file sizes during transfer using compression algorithms.

**967. What is browser caching?**
Storing resources locally to avoid repeated downloads.

**968. What are cache headers?**
HTTP headers controlling how browsers cache resources.

**969. What is cache-control directive?**
HTTP header specifying caching policies for resources.

**970. What is service worker caching?**
Programmatic caching using service workers for offline functionality.

**971. What is CDN (Content Delivery Network)?**
Geographically distributed servers for faster content delivery.

**972. What is HTTP/2?**
Next version of HTTP protocol with multiplexing and server push.

**973. What is resource bundling?**
Combining multiple files into fewer HTTP requests.

**974. What is inline vs external resources?**
Inline: embedded in HTML; External: separate files.

**975. What is above-the-fold optimization?**
Prioritizing loading of content visible without scrolling.

**976. What is preloading?**
Loading critical resources before they're needed.

**977. What is prefetching?**
Loading resources that might be needed in future.

**978. What is DNS prefetching?**
Resolving domain names before they're needed.

**979. What is resource hints?**
Browser instructions for optimizing resource loading (preload, prefetch).

**980. What is JavaScript performance optimization?**
Techniques for improving JS execution speed and efficiency.

**981. What is event delegation?**
Attaching single event listener to parent instead of multiple children.

**982. What is debouncing and throttling?**
Controlling frequency of function execution for performance.

**983. What is memoization?**
Caching function results to avoid redundant calculations.

**984. What is virtual scrolling?**
Rendering only visible items in large lists for performance.

**985. What is web workers?**
Running JavaScript in background threads to avoid blocking main thread.

**986. What is CSS performance optimization?**
Techniques for improving CSS loading and rendering performance.

**987. What is CSS delivery optimization?**
Inlining critical CSS and loading non-critical CSS asynchronously.

**988. What is CSS selector performance?**
Writing efficient selectors to reduce rendering time.

**989. What is will-change property?**
CSS property hinting browser about expected changes for optimization.

**990. What is font loading optimization?**
Techniques for improving web font loading performance.

**991. What is font-display property?**
CSS property controlling font loading behavior and fallbacks.

**992. What is database query optimization?**
Techniques for improving database query performance.

**993. What is database indexing?**
Creating data structures to speed up query execution.

**994. What is query plan analysis?**
Examining how database executes queries for optimization opportunities.

**995. What is connection pooling?**
Reusing database connections to improve performance.

**996. What is server-side rendering (SSR) optimization?**
Improving performance of server-rendered applications.

**997. What is static site generation (SSG)?**
Pre-generating pages at build time for faster delivery.

**998. What is incremental static regeneration?**
Updating static pages after build without full rebuild.

**999. What is edge-side includes (ESI)?**
Caching strategy for dynamic content at CDN edge.

**1000. What is application monitoring?**
Tracking application performance and user experience metrics.

**1001. What is real user monitoring (RUM)?**
Collecting performance data from actual user interactions.

**1002. What is synthetic monitoring?**
Automated testing of application performance from various locations.

**1003. What is performance budgets?**
Setting limits on resource sizes and timing metrics.

**1004. What is lighthouse?**
Google's tool for auditing web page performance and best practices.

**1005. What is WebPageTest?**
Tool for testing website performance from multiple locations.

**1006. What is performance profiling?**
Analyzing application execution to identify performance bottlenecks.

**1007. What is memory leak detection?**
Identifying and fixing memory leaks that degrade performance.

**1008. What is garbage collection optimization?**
Tuning garbage collection for better application performance.

**1009. What is load testing?**
Testing application performance under expected and peak loads.

**1010. What is performance regression testing?**
Automatically detecting performance degradations in new releases.

## Security (Questions 1011-1050)

**1011. What is web application security?**
Protecting web applications from threats and vulnerabilities.

**1012. What are the OWASP Top 10?**
Most critical web application security risks identified by OWASP.

**1013. What is injection attack?**
Malicious code inserted into application queries or commands.

**1014. What is SQL injection?**
Inserting malicious SQL code into application queries.

**1015. What is XSS (Cross-Site Scripting)?**
Injecting malicious scripts into web pages viewed by other users.

**1016. What are types of XSS?**
Stored, reflected, and DOM-based XSS attacks.

**1017. What is CSRF (Cross-Site Request Forgery)?**
Tricking users into performing unwanted actions on trusted sites.

**1018. What is CORS (Cross-Origin Resource Sharing)?**
Mechanism allowing or restricting cross-origin HTTP requests.

**1019. What is Content Security Policy (CSP)?**
HTTP header preventing code injection attacks.

**1020. What is HTTPS?**
Secure HTTP using TLS/SSL encryption for data transmission.

**1021. What is SSL/TLS?**
Cryptographic protocols providing secure communication.

**1022. What is certificate pinning?**
Associating specific certificates with particular domains.

**1023. What is HSTS (HTTP Strict Transport Security)?**
Header forcing browsers to use HTTPS connections.

**1024. What is input validation?**
Verifying user input meets expected format and constraints.

**1025. What is output encoding?**
Transforming data to prevent interpretation as executable code.

**1026. What is authentication?**
Process of verifying user identity.

**1027. What is authorization?**
Process of determining user permissions and access rights.

**1028. What is multi-factor authentication (MFA)?**
Using multiple methods to verify user identity.

**1029. What is OAuth 2.0?**
Authorization framework for secure API access delegation.

**1030. What is JWT (JSON Web Token)?**
Compact token format for secure information transmission.

**1031. What is session management?**
Maintaining user state across multiple HTTP requests.

**1032. What is session hijacking?**
Unauthorized access to user session by stealing session tokens.

**1033. What is session fixation?**
Attack where attacker sets user's session ID to known value.

**1034. What is password security?**
Best practices for storing and managing user passwords.

**1035. What is password hashing?**
Converting passwords into irreversible hash values.

**1036. What is salt in password hashing?**
Random data added to passwords before hashing.

**1037. What is bcrypt?**
Secure password hashing function with configurable cost.

**1038. What is rate limiting?**
Controlling number of requests to prevent abuse.

**1039. What is DDoS (Distributed Denial of Service)?**
Attack overwhelming system with traffic from multiple sources.

**1040. What is bot protection?**
Detecting and blocking automated malicious traffic.

**1041. What is API security?**
Protecting APIs from unauthorized access and attacks.

**1042. What is API key management?**
Securely generating, distributing, and rotating API keys.

**1043. What is API versioning security?**
Maintaining security across different API versions.

**1044. What is data encryption?**
Converting data into unreadable format using cryptographic algorithms.

**1045. What is encryption at rest?**
Protecting stored data through encryption.

**1046. What is encryption in transit?**
Protecting data during transmission between systems.

**1047. What is key management?**
Securely handling cryptographic keys throughout their lifecycle.

**1048. What is vulnerability scanning?**
Automated testing for known security vulnerabilities.

**1049. What is penetration testing?**
Simulated cyber attacks to test security defenses.

**1050. What is security monitoring?**
Continuously watching for security threats and incidents.

## DevOps & Deployment (Questions 1051-1100)

**1051. What is DevOps?**
Cultural and technical practices combining development and operations teams.

**1052. What are DevOps principles?**
Collaboration, automation, continuous integration, continuous delivery, monitoring.

**1053. What is CI/CD?**
Continuous Integration and Continuous Delivery/Deployment practices.

**1054. What is Continuous Integration?**
Automatically building and testing code changes frequently.

**1055. What is Continuous Delivery?**
Automatically preparing code changes for release to production.

**1056. What is Continuous Deployment?**
Automatically deploying code changes to production after passing tests.

**1057. What are popular CI/CD tools?**
Jenkins, GitHub Actions, GitLab CI, CircleCI, Azure DevOps.

**1058. What is Jenkins?**
Open-source automation server for building CI/CD pipelines.

**1059. What is GitHub Actions?**
CI/CD platform integrated with GitHub repositories.

**1060. What is GitLab CI?**
Built-in CI/CD capabilities of GitLab platform.

**1061. What is version control?**
System for tracking changes in source code over time.

**1062. What is Git?**
Distributed version control system for tracking code changes.

**1063. What are Git branching strategies?**
GitFlow, GitHub Flow, feature branches, release branches.

**1064. What is Infrastructure as Code (IaC)?**
Managing infrastructure through version-controlled configuration files.

**1065. What are popular IaC tools?**
Terraform, CloudFormation, Ansible, Pulumi, Chef, Puppet.

**1066. What is Terraform?**
Tool for building, changing, and versioning infrastructure safely.

**1067. What is CloudFormation?**
AWS service for provisioning infrastructure using templates.

**1068. What is Ansible?**
Automation tool for configuration management and deployment.

**1069. What is containerization?**
Packaging applications with dependencies into portable containers.

**1070. What is container orchestration?**
Managing containerized applications across multiple hosts.

**1071. What is Kubernetes?**
Container orchestration platform for automating deployment and scaling.

**1072. What is Docker Swarm?**
Native Docker clustering and orchestration solution.

**1073. What is monitoring and logging?**
Tracking system health and collecting operational data.

**1074. What are monitoring tools?**
Prometheus, Grafana, Nagios, Zabbix, DataDog, New Relic.

**1075. What is log aggregation?**
Collecting logs from multiple sources into centralized system.

**1076. What is ELK Stack?**
Elasticsearch, Logstash, and Kibana for log management.

**1077. What is alerting?**
Notifying teams when systems exceed defined thresholds.

**1078. What is deployment strategies?**
Methods for releasing software changes to production.

**1079. What is blue-green deployment?**
Using two identical environments to enable zero-downtime deployment.

**1080. What is canary deployment?**
Gradually rolling out changes to small subset of users.

**1081. What is rolling deployment?**
Gradually replacing old version with new version across instances.

**1082. What is feature flags?**
Technique for toggling features on/off without code deployment.

**1083. What is configuration management?**
Managing system and application configurations across environments.

**1084. What is environment management?**
Maintaining consistent development, staging, and production environments.

**1085. What is backup and disaster recovery?**
Planning for data protection and system recovery procedures.

**1086. What is cloud platforms?**
Services providing computing resources over the internet.

**1087. What are major cloud providers?**
AWS, Microsoft Azure, Google Cloud Platform, IBM Cloud.

**1088. What is AWS?**
Amazon Web Services cloud computing platform.

**1089. What is Azure?**
Microsoft's cloud computing platform and services.

**1090. What is GCP?**
Google Cloud Platform for cloud computing services.

**1091. What is serverless computing?**
Running code without managing servers using cloud functions.

**1092. What is auto-scaling?**
Automatically adjusting resource capacity based on demand.

**1093. What is load balancing?**
Distributing incoming requests across multiple servers.

**1094. What is CDN (Content Delivery Network)?**
Network of servers for delivering content from locations closest to users.

**1095. What is security in DevOps (DevSecOps)?**
Integrating security practices throughout development and operations lifecycle.

**1096. What is compliance as code?**
Managing regulatory compliance through automated policies.

**1097. What is immutable infrastructure?**
Infrastructure that is never modified after deployment.

**1098. What is chaos engineering?**
Practice of testing system resilience by introducing controlled failures.

**1099. What is site reliability engineering (SRE)?**
Discipline applying software engineering to operations problems.

**1100. What is performance optimization in DevOps?**
Techniques for improving application and infrastructure performance.

## Behavioral Questions (Questions 1101-1200)

**1101. Tell me about yourself.**
Brief professional summary highlighting relevant experience and skills.

**1102. Why are you interested in this position?**
Express genuine interest in role, company, and growth opportunities.

**1103. What are your strengths?**
Highlight technical and soft skills relevant to the position.

**1104. What are your weaknesses?**
Share genuine weakness with steps you're taking to improve.

**1105. Describe a challenging project you worked on.**
Use STAR method: Situation, Task, Action, Result.

**1106. How do you handle tight deadlines?**
Discuss prioritization, communication, and time management strategies.

**1107. Describe a time you had to learn new technology quickly.**
Show adaptability and learning approach with specific example.

**1108. How do you handle disagreements with team members?**
Emphasize communication, compromise, and focus on project goals.

**1109. Tell me about a bug you found difficult to solve.**
Describe systematic debugging approach and problem-solving skills.

**1110. How do you stay updated with technology trends?**
Mention resources, communities, and continuous learning practices.

**1111. Describe your ideal work environment.**
Balance team collaboration with individual productivity needs.

**1112. How do you prioritize tasks?**
Discuss methods for managing multiple priorities and deadlines.

**1113. Tell me about a time you failed.**
Share learning experience and how you applied lessons learned.

**1114. How do you handle criticism?**
Show openness to feedback and growth mindset.

**1115. Describe your experience with code reviews.**
Emphasize collaborative improvement and knowledge sharing.

**1116. How do you approach testing your code?**
Discuss testing strategies and quality assurance practices.

**1117. Tell me about a time you mentored someone.**
Share experience helping others grow professionally.

**1118. How do you handle working with legacy code?**
Discuss approach to understanding, maintaining, and improving existing systems.

**1119. Describe your experience with agile methodologies.**
Share experience with Scrum, Kanban, or other agile practices.

**1120. How do you handle scope changes in projects?**
Discuss adaptability and communication with stakeholders.

**1121. Tell me about a time you had to make a technical decision.**
Show decision-making process and consideration of trade-offs.

**1122. How do you ensure code quality?**
Discuss practices like code reviews, testing, and documentation.

**1123. Describe your experience working remotely.**
Share strategies for communication and productivity in remote work.

**1124. How do you handle multiple competing priorities?**
Discuss time management and stakeholder communication strategies.

**1125. Tell me about a time you improved a process.**
Share example of identifying inefficiency and implementing improvement.

**1126. How do you approach learning new programming languages?**
Discuss learning strategies and transferable programming concepts.

**1127. Describe your experience with performance optimization.**
Share specific examples of identifying and resolving performance issues.

**1128. How do you handle production issues?**
Discuss incident response, debugging, and communication practices.

**1129. Tell me about a successful team project.**
Highlight collaboration, communication, and shared success.

**1130. How do you document your code?**
Discuss documentation practices and importance of maintainable code.

**1131. Describe your experience with databases.**
Share knowledge of database design, optimization, and management.

**1132. How do you approach security in your applications?**
Discuss security best practices and awareness of common vulnerabilities.

**1133. Tell me about a time you had to debug a complex issue.**
Share systematic approach to problem-solving and investigation.

**1134. How do you handle technical debt?**
Discuss balancing feature development with code quality improvement.

**1135. Describe your experience with deployment processes.**
Share knowledge of CI/CD, testing, and production deployment strategies.

**1136. How do you ensure your applications are scalable?**
Discuss architectural patterns and performance considerations.

**1137. Tell me about a time you worked with difficult stakeholders.**
Show communication skills and ability to manage expectations.

**1138. How do you approach API design?**
Discuss RESTful principles, documentation, and versioning strategies.

**1139. Describe your experience with monitoring and logging.**
Share knowledge of observability and operational practices.

**1140. How do you handle feature requests that seem technically unfeasible?**
Discuss communication, alternative solutions, and technical leadership.

**1141. Tell me about a time you had to refactor significant code.**
Share approach to improving code structure while maintaining functionality.

**1142. How do you evaluate and choose new technologies?**
Discuss criteria for technology selection and risk assessment.

**1143. Describe your experience with mobile development.**
Share knowledge of mobile platforms, constraints, and best practices.

**1144. How do you approach building maintainable software?**
Discuss clean code principles, architecture patterns, and documentation.

**1145. Tell me about a time you had to work with external APIs.**
Share experience with integration, error handling, and reliability.

**1146. How do you handle data migration projects?**
Discuss planning, testing, and risk mitigation strategies.

**1147. Describe your experience with cloud platforms.**
Share knowledge of cloud services, deployment, and cost optimization.

**1148. How do you approach accessibility in your applications?**
Discuss awareness of accessibility standards and inclusive design.

**1149. Tell me about a time you had to optimize database performance.**
Share specific examples of query optimization and indexing

# Missing Interview Questions - Completed Sections

## Completing Behavioral Questions (1149-1200)

1149. Tell me about a time you had to optimize database performance. Share specific examples of query optimization, indexing strategies, and performance monitoring techniques you used.

1150. How do you approach accessibility in your applications? Discuss WCAG guidelines, screen reader compatibility, keyboard navigation, and inclusive design principles.

1151. Describe your experience with internationalization (i18n). Share knowledge of multi-language support, locale handling, and cultural considerations in software design.

1152. How do you handle third-party integrations? Discuss API reliability, error handling, fallback strategies, and vendor relationship management.

1153. Tell me about a time you had to make architectural decisions. Share decision-making process, trade-offs considered, and long-term impact assessment.

1154. How do you approach technical documentation? Discuss documentation strategies, audience consideration, and maintaining up-to-date technical resources.

1155. Describe your experience with microservices architecture. Share knowledge of service decomposition, inter-service communication, and distributed system challenges.

1156. How do you handle backward compatibility? Discuss versioning strategies, migration planning, and maintaining existing functionality.

1157. Tell me about a time you identified a security vulnerability. Share discovery process, remediation steps, and prevention strategies implemented.

1158. How do you approach mobile-first development? Discuss responsive design, progressive enhancement, and mobile optimization strategies.

1159. Describe your experience with real-time applications. Share knowledge of WebSockets, server-sent events, and real-time data synchronization.

1160. How do you handle large-scale data processing? Discuss batch processing, stream processing, and data pipeline architecture.

1161. Tell me about a time you had to integrate with legacy systems. Share challenges faced, integration strategies, and modernization approaches.

1162. How do you approach caching strategies? Discuss different caching layers, cache invalidation, and performance optimization through caching.

1163. Describe your experience with automated testing. Share testing pyramid concepts, test-driven development, and continuous testing practices.

1164. How do you handle cross-browser compatibility? Discuss testing strategies, polyfills, and progressive enhancement approaches.

1165. Tell me about a time you had to scale an application. Share scaling strategies, performance bottleneck identification, and infrastructure considerations.

1166. How do you approach error handling and logging? Discuss error tracking, log aggregation, and debugging strategies in production environments.

1167. Describe your experience with containerization. Share Docker knowledge, container orchestration, and deployment strategies.

1168. How do you handle database schema changes? Discuss migration strategies, rollback procedures, and zero-downtime deployment considerations.

1169. Tell me about a time you had to work with distributed teams. Share communication strategies, collaboration tools, and timezone management approaches.

1170. How do you approach performance budgets? Discuss metric selection, monitoring strategies, and optimization prioritization.

1171. Describe your experience with GraphQL. Share schema design, query optimization, and comparison with REST APIs.

1172. How do you handle feature flagging? Discuss feature toggle strategies, gradual rollouts, and A/B testing implementation.

1173. Tell me about a time you had to debug a production issue under pressure. Share incident response process, communication strategies, and post-mortem practices.

1174. How do you approach technical interviewing? Discuss evaluation criteria, inclusive interviewing practices, and candidate assessment strategies.

1175. Describe your experience with observability. Share monitoring, logging, and tracing strategies for distributed systems.

1176. How do you handle technical leadership responsibilities? Discuss mentoring, architectural guidance, and team technical direction.

1177. Tell me about a time you had to evaluate competing technologies. Share evaluation criteria, proof-of-concept approaches, and decision-making processes.

1178. How do you approach progressive web app development? Discuss service workers, offline functionality, and native app-like experiences.

1179. Describe your experience with machine learning integration. Share model deployment, data pipeline management, and ML operations practices.

1180. How do you handle compliance requirements? Discuss GDPR, accessibility standards, and industry-specific regulations in software development.

1181. Tell me about a time you had to migrate a large dataset. Share migration strategies, data validation, and rollback procedures.

1182. How do you approach technical debt prioritization? Discuss assessment criteria, business impact evaluation, and refactoring strategies.

1183. Describe your experience with event-driven architecture. Share event sourcing, CQRS patterns, and asynchronous processing strategies.

1184. How do you handle vendor management? Discuss third-party service evaluation, contract negotiation, and vendor relationship maintenance.

1185. Tell me about a time you had to implement disaster recovery. Share backup strategies, recovery procedures, and business continuity planning.

1186. How do you approach API design and documentation? Discuss RESTful principles, OpenAPI specifications, and developer experience considerations.

1187. Describe your experience with edge computing. Share CDN usage, edge function deployment, and latency optimization strategies.

1188. How do you handle technical presentations? Discuss audience adaptation, technical communication, and stakeholder engagement strategies.

1189. Tell me about a time you had to optimize for mobile performance. Share mobile-specific optimization techniques and performance measurement strategies.

1190. How do you approach cross-functional collaboration? Discuss working with designers, product managers, and business stakeholders effectively.

1191. Describe your experience with blockchain or Web3 technologies. Share knowledge of distributed ledgers, smart contracts, and decentralized applications.

1192. How do you handle long-running processes? Discuss background job processing, queue management, and progress tracking strategies.

1193. Tell me about a time you had to build developer tools. Share internal tooling development, developer experience optimization, and tool adoption strategies.

1194. How do you approach technical writing? Discuss documentation strategies, technical blog writing, and knowledge sharing practices.

1195. Describe your experience with data visualization. Share charting libraries, dashboard development, and data presentation strategies.

1196. How do you handle technical interviews as a candidate? Share preparation strategies, problem-solving approaches, and communication techniques.

1197. Tell me about a time you had to work with tight security requirements. Share security implementation, compliance adherence, and secure development practices.

1198. How do you approach continuous learning? Discuss learning strategies, skill development planning, and staying current with technology trends.

1199. Describe your long-term career goals. Share professional development aspirations, skill advancement plans, and leadership interests.

1200. What questions do you have for me? Prepare thoughtful questions about the role, team, company culture, and growth opportunities.

## Additional Missing Sections

### React Native Performance & Optimization (Questions 401-420)

401. How do you optimize React Native app performance? Use FlatList for large lists, optimize images, implement lazy loading, minimize bridge communication.

402. What are React Native performance bottlenecks? JavaScript bridge communication, large lists rendering, image loading, memory leaks.

403. How do you implement lazy loading in React Native? Use React.lazy() with Suspense, lazy load screens and components, implement image lazy loading.

404. What is React Native app profiling? Using Flipper, React DevTools Profiler, and platform-specific profiling tools to identify performance issues.

405. How do you optimize React Native bundle size? Code splitting, unused code elimination, optimizing dependencies, using Hermes engine.

406. What is RAM bundle in React Native? Bundle format that loads JavaScript modules on-demand rather than at startup.

407. How do you handle memory management? Avoiding memory leaks, proper cleanup in useEffect, optimizing image caching, monitoring memory usage.

408. What is React Native New Architecture benefits? Better performance, type safety, easier native module development, reduced bridge communication.

409. How do you optimize React Native animations? Use native driver, avoid animating layout properties, use transform properties, implement 60fps animations.

410. What is InteractionManager in React Native? API for deferring work until after interactions are complete to maintain smooth animations.

411. How do you implement efficient navigation? Use React Navigation v6, lazy loading screens, proper navigation structure, avoiding deep nesting.

412. What are React Native rendering optimization techniques? Using React.memo, PureComponent, avoiding inline objects/functions, proper key props.

413. How do you optimize React Native startup time? Reducing bundle size, using Hermes engine, optimizing initialization code, lazy loading.

414. What is React Native Metro bundler optimization? Configuring Metro for faster builds, enabling caching, optimizing resolver configuration.

415. How do you handle React Native background tasks? Using background job libraries, implementing proper task scheduling, handling app state changes.

416. What is React Native Flipper? Desktop debugging platform providing network inspection, layout inspection, and performance profiling.

417. How do you optimize React Native for different devices? Responsive design, platform-specific code, device capability detection, performance scaling.

418. What are React Native testing performance considerations? Avoiding heavy computations in tests, mocking expensive operations, parallel test execution.

419. How do you implement efficient data fetching? Caching strategies, request deduplication, pagination, background sync, offline support.

420. What is React Native app size optimization? Removing unused assets, optimizing images, using vector icons, enabling ProGuard/R8 on Android.

### Node.js Security & Best Practices (Questions 491-520)

491. What are Node.js security vulnerabilities? Injection attacks, insecure dependencies, authentication issues, data exposure, DoS attacks.

492. How do you secure Node.js applications? Input validation, authentication, HTTPS usage, dependency scanning, security headers.

493. What is helmet.js and its features? Security middleware setting various HTTP headers: CSP, HSTS, X-Frame-Options, etc.

494. How do you handle authentication in Node.js? JWT tokens, session-based auth, OAuth integration, password hashing, MFA implementation.

495. What is bcrypt and why use it? Password hashing library using salt and configurable rounds for secure password storage.

496. How do you prevent SQL injection in Node.js? Parameterized queries, ORM usage, input validation, least privilege database access.

497. What are environment variable best practices? Using .env files, never committing secrets, validation, type conversion, default values.

498. How do you implement rate limiting? Express-rate-limit middleware, Redis-based limiting, distributed rate limiting, adaptive limits.

499. What is CSRF protection in Node.js? Using CSRF tokens, SameSite cookies, origin verification, double-submit cookies.

500. How do you secure API endpoints? Authentication, authorization, input validation, rate limiting, CORS configuration.

501. What are Node.js dependency security practices? Regular updates, vulnerability scanning (npm audit), lock files, minimal dependencies.

502. How do you implement logging securely? Avoiding sensitive data in logs, structured logging, log rotation, secure transmission.

503. What is input sanitization? Cleaning user input to prevent injection attacks, using libraries like validator.js, DOMPurify.

504. How do you handle file uploads securely? Size limits, type validation, secure storage, virus scanning, access control.

505. What are Node.js HTTPS best practices? TLS configuration, certificate management, HSTS headers, cipher suite selection.

506. How do you implement session security? Secure cookies, session timeout, regeneration, storage security, HTTPS-only.

507. What is least privilege principle? Granting minimal necessary permissions to users, processes, and services.

508. How do you secure Node.js in production? Process isolation, security updates, monitoring, access control, infrastructure security.

509. What are Node.js audit and compliance practices? Security assessments, penetration testing, compliance frameworks, documentation.

510. How do you handle secrets management? Environment variables, secret management services (HashiCorp Vault), encryption at rest.

511. What is OWASP security guidelines for Node.js? Following OWASP Top 10, security testing, secure coding practices, regular assessments.

512. How do you implement content security policy? CSP headers, nonce usage, strict policies, reporting violations, gradual enforcement.

513. What are Node.js error handling security implications? Avoiding information disclosure, proper error logging, user-friendly error messages.

514. How do you secure Node.js microservices? Service-to-service authentication, network security, API gateways, distributed tracing.

515. What is security monitoring in Node.js? Intrusion detection, log analysis, anomaly detection, automated alerting, incident response.

516. How do you handle data encryption? Encryption at rest and transit, key management, algorithm selection, compliance requirements.

517. What are Node.js container security practices? Minimal base images, non-root users, security scanning, runtime security, network policies.

518. How do you implement API versioning securely? Deprecation strategies, backward compatibility, access control, documentation updates.

519. What is security testing in Node.js? Static analysis, dependency scanning, penetration testing, security unit tests.

520. How do you handle Node.js security incidents? Incident response plan, forensics, communication, recovery procedures, post-incident analysis.

### Advanced System Design Patterns (Questions 951-1000)

951. What is the Saga pattern in distributed systems? Managing distributed transactions using compensating actions for failure handling.

952. What is event sourcing architecture? Storing state changes as events rather than current state, enabling audit trails and replay capability.

953. What is CQRS (Command Query Responsibility Segregation)? Separating read and write operations using different models for optimal performance.

954. What is the Bulkhead pattern? Isolating critical resources to prevent cascade failures, similar to ship compartments.

955. What is the Circuit Breaker pattern implementation? Monitoring service health and preventing calls to failing services with automatic recovery.

956. What is the Strangler Fig pattern? Gradually replacing legacy systems by incrementally routing traffic to new implementation.

957. What is the Adapter pattern in system design? Allowing incompatible interfaces to work together through translation layers.

958. What is the Ambassador pattern? Proxy pattern for handling cross-cutting concerns like logging, monitoring, and security.

959. What is the Sidecar pattern? Deploying additional functionality alongside main application in separate containers.

960. What is the Backend for Frontend (BFF) pattern? Creating specific backend services tailored for different frontend applications.

961. What is the API Gateway pattern? Central entry point managing cross-cutting concerns for microservices architecture.

962. What is the Database per Service pattern? Each microservice owning its data and database schema independently.

963. What is the Shared Database anti-pattern? Multiple services sharing database leading to tight coupling and scalability issues.

964. What is the Event-Driven Architecture pattern? Services communicating through events rather than direct API calls.

965. What is the Publish-Subscribe pattern? Decoupled communication where producers publish events consumed by multiple subscribers.

966. What is the Request-Reply pattern? Synchronous communication pattern with request correlation and response handling.

967. What is the Competing Consumers pattern? Multiple service instances processing messages from shared queue for scalability.

968. What is the Priority Queue pattern? Processing messages based on priority levels rather than arrival order.

969. What is the Message Router pattern? Routing messages to different destinations based on content or rules.

970. What is the Content-Based Router pattern? Directing messages to specific handlers based on message content analysis.

971. What is the Message Translator pattern? Converting message formats between different systems or services.

972. What is the Message Aggregator pattern? Combining related messages into single composite message.

973. What is the Message Splitter pattern? Breaking composite messages into individual messages for parallel processing.

974. What is the Dead Letter Queue pattern? Handling messages that cannot be processed successfully after multiple attempts.

975. What is the Idempotent Consumer pattern? Ensuring message processing produces same result regardless of delivery count.

976. What is the Transactional Outbox pattern? Ensuring reliable message publishing using database transactions.

977. What is the Change Data Capture pattern? Capturing and propagating database changes as events for system integration.

978. What is the Materialized View pattern? Pre-computing and storing query results for improved read performance.

979. What is the Read Replica pattern? Scaling read operations using synchronized copies of master database.

980. What is the Sharding pattern? Horizontally partitioning data across multiple databases for scalability.

981. What is the Federated Identity pattern? Centralizing identity management across multiple systems and organizations.

982. What is the Token Bucket pattern? Rate limiting algorithm allowing burst traffic within defined limits.

983. What is the Leaky Bucket pattern? Rate limiting with smooth, consistent output regardless of input bursts.

984. What is the Sliding Window pattern? Time-based rate limiting using moving time windows for request counting.

985. What is the Retry pattern with exponential backoff? Automatically retrying failed operations with increasing delays.

986. What is the Timeout pattern? Preventing resource exhaustion by limiting operation execution time.

987. What is the Cache-Aside pattern? Application managing cache population and invalidation explicitly.

988. What is the Write-Through cache pattern? Writing to cache and database simultaneously for consistency.

989. What is the Write-Behind cache pattern? Writing to cache immediately and database asynchronously.

990. What is the Refresh-Ahead cache pattern? Proactively refreshing cache before expiration to maintain performance.

991. What is the Multi-Level Cache pattern? Using multiple cache layers with different characteristics and lifetimes.

992. What is the Distributed Cache pattern? Sharing cache across multiple application instances or services.

993. What is the Blue-Green Deployment pattern? Maintaining two identical production environments for zero-downtime deployment.

994. What is the Canary Deployment pattern? Gradually rolling out changes to subset of users for risk mitigation.

995. What is the Rolling Deployment pattern? Sequentially updating instances while maintaining service availability.

996. What is the Feature Toggle pattern? Runtime configuration for enabling/disabling features without deployment.

997. What is the Database Migration pattern? Versioned schema changes with rollback capabilities and zero-downtime updates.

998. What is the Health Check pattern? Monitoring service health through dedicated endpoints for orchestration decisions.

999. What is the Service Discovery pattern? Dynamic location and registration of services in distributed systems.

1000. What is the Configuration Management pattern? Centralizing and versioning application configuration across environments.