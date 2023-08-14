# 300 - Building Our Application

**Inversion of Control**

This principle takes place in every modern UI framework. As an example, let’s consider the classical approach to implementing a router (Vue Router, Angular Router, React Router, etc.). We should specify a map (preferably an array of maps) where the key is an URL path, and the value is a Javascript class. In general, we actually set the configuration for the router, and the framework itself listens to the ```hashchange``` event and creates instances of the corresponding classes that render the desired page.

Similarly, with the component approach in the above-mentioned frameworks (Vue, Angular, React), the creation of Javascript classes (that describes the components), is concerned with the framework, while the LifeCycle hooks on the component are invoked by the framework.

The considered frameworks specify a skeleton where the client code is written, the execution of which is related to the framework.

The above examples follow the IoC principle. In the context of our topic, it is important to emphasize that we have the ability to configure and implement certain classes or functions that will be called not by our code, but by the frameworks.

== WE ARE HERE ==
