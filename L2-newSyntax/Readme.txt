

ECMAScript-2015 / ES6
-----------------------


  New syntax
  ------------

    - let & const keywords with block scope
    - string interpolation
    - function with default params & rest param
    - destructuring
    - spread operator
    - obj-literal enhancements
    - symbol type
    - for-of loop
    - arrow-function
    - New-OO with class syntax





concurrency-model in javascript-lang
------------------------------------

  .js-lang

    ==> all IO operations ar 'non-blocking'
    ==> single-threaded lang , we can execute actions concurrenctly



    browser e.g chrome

         1. JavaScript runtime/engine    => based on ECMAScript spec

                a. single-call-stack    -> to execute contexts
                b. heap                 -> to hold objects

         2. Web APIs ( DOM , XHR , Timer API , etc..)   ==> w3c recommendation
         3. Event-Queue
         4. Event-Loop

 ----------------------------------------------------------------

  imp-note:

  ==> after event, event-handler(callaback) always executes async     


  also we can execute our function asyc using Async-APIs   

    -> Promise API ( ES6 )
    -> RxJS ( Reactive eXtensions for JavaScript)  

----------------------------------------------------------------s





