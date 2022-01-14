# Summary

Congratulations! You've completed all the tutorials that equip you to become a Penrose user, developer, and domain expert! We've come a long way. Here's a quick rundown of some of what we learned:

* **Style**, **Substance**, and **Domain** files make up a Penrose program. They are called a **triple**.&#x20;
* We use `type TYPE_NAME` syntax to define the type of an object in our Domain.&#x20;
* We define the substances in our diagram with the `TYPE_NAME Substance` syntax in the Substance file.
* We define the style selectors using the syntax `forall TYPE_NAME x {}`.
* We use the keyword `predicate` to define relationships between objects, the keyword `ensure` to define constraints on the diagram, and the keyword `function` to declare a function.&#x20;
* When working with Style files, start by defining styles for base objects, make use of cascading styles, and override if needed with the keyword `override`.
* The visual meaning is defined in the style program, including all the concrete numbers.&#x20;
* The substance and domain files are infinitely flexible with no built-in functionality.
* Penrose implements constraints & objectives with energy functions in order to optimize diagrams.&#x20;

We hope you've had a fun time going through the tutorials and exercises and have enjoyed the opportunity to view diagramming differently!

For further explorations, here are some resources:

* More examples on complex diagrams: [LINK](https://github.com/penrose/penrose/wiki/Example-diagrams)
* How the Style compiler works: [LINK](https://github.com/penrose/penrose/wiki/How-the-Style-compiler-works)
* How to troubleshoot: [LINK](https://github.com/penrose/penrose/wiki/Troubleshooting)
* Check out the Penrose inspector for debugging (some features like mod and drag are experimental at the moment).

Have fun diagramming, and we will see you for future tutorials!
