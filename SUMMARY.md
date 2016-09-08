# Summary

* [Introduction](README.md)
* [Book One: Up & Going](up & going/README.md)
   * [Foreword](up & going/foreword.md)
   * [Preface](preface.md)
   * [Chapter 1: Into Programming](up & going/ch1.md)
       * Code
       * Try It Yourself
       * Operators
       * Values & Types
       * Code Comments
       * Variables
       * Blocks
       * Conditionals
       * Loops
       * Functions
       * Practice
   * [Chapter 2: Into JavaScript](up & going/ch2.md)
       * Values & Types
       * Variables
       * Conditionals
       * Strict Mode
       * Functions As Values
       * `this` Keyword
       * Prototypes
       * Old & New
       * Non-JavaScript
   * [Chapter 3: Into YDKJS](up & going/ch3.md)
       * Scope & Closures
       * this & Object Prototypes
       * Types & Grammar
       * Async & Performance
       * ES6 & Beyond
   * [Appendix A: Acknowledgments](up & going/apA.md)
* [Book Two: Scope & Closures](scope & closures/README.md)
   * [Foreword](scope & closures/foreword.md)
   * [Chapter 1: What is Scope?](scope & closures/ch1.md)
       * Compiler Theory
       * Understanding Scope
       * Nested Scope
       * Errors
   * [Chapter 2: Lexical Scope](scope & closures/ch2.md)
       * Lex-time
       * Cheating Lexical
   * [Chapter 3: Function vs. Block Scope](scope & closures/ch3.md)
       * Scope From Functions
       * Hiding In Plain Scope
       * Functions As Scopes
       * Blocks As Scopes
   * [Chapter 4: Hoisting](scope & closures/ch4.md)
       * Chicken Or The Egg?
       * The Compiler Strikes Again
       * Functions First
   * [Chapter 5: Scope Closures](scope & closures/ch5.md)
       * Enlightenment
       * Nitty Gritty
       * Now I Can See
       * Loops + Closure
       * Modules
   * [Appendix A: Dynamic Scope](scope & closures/apA.md)
   * [Appendix B: Polyfilling Block Scope](scope & closures/apB.md)
   * [Appendix C: Lexical-this](scope & closures/apC.md)
   * [Appendix D: Acknowledgments](scope & closures/apD.md)
* [Book Three: this & Object Prototypes](this & object prototypes/README.md)
   * [Foreword](this & object prototypes/foreword.md)
   * Chapter 1: `this` Or That?
       * Why `this`?
       * Confusions
       * What's `this`?
   * Chapter 2: `this` All Makes Sense Now!
       * Call-site
       * Nothing But Rules
       * Everything In Order
       * Binding Exceptions
       * Lexical `this`
   * Chapter 3: Objects
       * Syntax
       * Type
       * Contents
       * Iteration
   * Chapter 4: Mixing (Up) "Class" Objects
       * Class Theory
       * Class Mechanics
       * Class Inheritance
       * Mixins
   * Chapter 5: Prototypes
       * `[[Prototype]]`
       * "Class"
       * "(Prototypal) Inheritance"
       * Object Links
   * Chapter 6: Behavior Delegation
       * Towards Delegation-Oriented Design
       * Classes vs. Objects
       * Simpler Design
       * Nicer Syntax
       * Introspection
   * Appendix A: ES6 `class`
   * Appendix B: Acknowledgments
* [Book Four: Types & Grammar](types & grammar/README.md)
   * Foreword
   * Preface
   * Chapter 1: Types
       * A Type By Any Other Name...
       * Built-in Types
       * Values as Types
   * Chapter 2: Values
       * Arrays
       * Strings
       * Numbers
       * Special Values
       * Value vs Reference
   * Chapter 3: Natives
       * Internal `[[Class]]`
       * Boxing Wrappers
       * Unboxing
       * Natives as Constructors
   * Chapter 4: Coercion
       * Converting Values
       * Abstract Value Operations
       * Explicit Coercion
       * Implicit Coercion
       * Loose Equals vs Strict Equals
       * Abstract Relational Comparison
   * Chapter 5: Grammar
       * Statements & Expressions
       * Operator Precedence
       * Automatic Semicolons
       * Errors
       * Function Arguments
       * `try..finally`
       * `switch`
   * Appendix A: Mixed Environment JavaScript
   * Appendix B: Acknowledgments
* [Book Five: Aysnc & Performance](async & performance/README.md)
   * Foreword
   * Preface
   * Chapter 1: Asynchrony: Now & Later
       * A Program In Chunks
       * Event Loop
       * Parallel Threading
       * Concurrency
       * Jobs
       * Statement Ordering
   * Chapter 2: Callbacks
       * Continuations
       * Sequential Brain
       * Trust Issues
       * Trying To Save Callbacks
   * Chapter 3: Promises
       * What is a Promise?
       * Thenable Duck-Typing
       * Promise Trust
       * Chain Flow
       * Error Handling
       * Promise Patterns
       * Promise API Recap
       * Promise Limitations
   * Chapter 4: Generators
       * Breaking Run-to-completion
       * Generator'ing Values
       * Iterating Generators Asynchronously
       * Generators + Promises
       * Generator Delegation
       * Generator Concurrency
       * Thunks
       * Pre-ES6 Generators
   * Chapter 5: Program Performance
       * Web Workers
       * SIMD
       * asm.js
   * Chapter 6: Benchmarking & Tuning
       * Benchmarking
       * Context Is King
       * jsPerf.com
       * Writing Good Tests
       * Microperformance
       * Tail Call Optimization (TCO)
   * Appendix A: *asynquence* Library
   * Appendix B: Advanced Async Patterns
   * Appendix C: Acknowledgments
* [Book Six: ES6 & Beyond](es6 & beyond/README.md)
   * Foreword
   * Preface
   * Chapter 1: ES? Now & Future
       * Versioning
       * Transpiling
   * Chapter 2: Syntax
       * Block-Scoped Declarations
       * Spread / Rest
       * Default Parameter Values
       * Destructuring
       * Object Literal Extensions
       * Template Literals
       * Arrow Functions
       * `for..of` Loops
       * Regular Expression Extensions
       * Number Literal Extensions
       * Unicode
       * Symbols
   * Chapter 3: Organization
       * Iterators
       * Generators
       * Modules
       * Classes
   * Chapter 4: Async Flow Control
       * Promises
       * Generators + Promises
   * Chapter 5: Collections
       * TypedArrays
       * Maps
       * WeakMaps
       * Sets
       * WeakSets
   * Chapter 6: API Additions
       * `Array`
       * `Object`
       * `Math`
       * `Number`
       * `String`
   * Chapter 7: Meta Programming
       * Function Names
       * Meta Properties
       * Well Known Symbols
       * Proxies
       * `Reflect` API
       * Feature Testing
       * Tail Call Optimization (TCO)
   * Chapter 8: Beyond ES6
       * `async function`s
       * `Object.observe(..)`
       * Exponentiation Operator
       * Object Properties and `...`
       * `Array#includes(..)`
           * SIMD
   * Appendix A: Acknowledgments

