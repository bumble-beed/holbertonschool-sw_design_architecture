Design Patterns
Introduction and Context

Writing classes is only one part of object-oriented programming. A more difficult step is deciding how responsibilities should be distributed between objects so that a program remains understandable, maintainable, and easy to extend.

Several design problems appear repeatedly in software systems:

    How should objects be created without scattering construction logic across the codebase?
    How can one part of the system react to changes in another without becoming tightly coupled to it?
    How can behavior be extended without modifying existing code or creating an unmanageable number of subclasses?

These problems appear in real applications such as notification systems, APIs, payment platforms, user interfaces, and content management tools. Solving them well requires more than syntax. It requires good design decisions.

A design pattern is a reusable way of organizing code to solve a recurring design problem. A pattern is not a finished implementation to copy mechanically. Instead, it describes a structure of responsibilities and interactions that has proven useful in many systems.

A design pattern usually helps answer three questions:

    What design problem is being solved?
    Which roles do the participating classes or objects play?
    Why does this structure make the system easier to change?

In this project, you will work with three foundational patterns from the Gang of Four catalog. Each belongs to one major category:

    Creational patterns focus on how objects are created
    Behavioral patterns focus on how objects communicate
    Structural patterns focus on how objects are composed

The goal of this project is not to memorize patterns by name. The goal is to understand why a given structure solves a specific problem, and how that structure supports maintainable object-oriented design.

