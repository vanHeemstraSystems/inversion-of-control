# 100 - Introduction

**Inversion of Control (IoC)** is an abstract programming principle based on the [flow of control](https://en.wikipedia.org/wiki/Control_flow) (execution of statements/instructions) that should be fully managed by the specific implementation of the framework, which is external to your code.

Let’s consider the following comparison: in the traditional approach, your code executes methods from the library/framework, and the inversion of this approach means that your code is called by the library/framework. Of course, it is better to say a framework - rather than a library. You register parts of your code (methods, classes, modules, etc. …) in the IoC framework that resolves itself when it has to call your code.

This comparison is rather rough but good enough for the initial understanding and it gives direction for the further and deeper perception of this concept.

A **Dependency** is an object or any software programming unit that is used by the client program or software unit. For example, the dependency is a service that returns data that must be represented in the client (web component), and so on. Those kinds of objects are often used in different places of the project.

**Dependency Injection (DI)** is one of the implementations of IoC based on the composition of dependencies in a client (dependent unit).

See also [Dependency Injection](https://github.com/vanHeemstraSystems/dependency-injection).

**Dependency Inversion Principle (DIP)** is one of [SOLID](https://en.wikipedia.org/wiki/SOLID)’s principles, which satisfies the following:

- the upper levels modules do not depend on implementations of the lower levels ones. Modules should depend on abstractions;
- abstractions do not depend on the details, but the details depend on abstractions;

The **IoC-container** is the implementation of the described principles in the form of a framework, library or module that facilitates the writing of a code and takes care of dependency injection and class instantiation.

Let’s try to look into more details of these concepts including examples in JavaScript.
