Design patterns are typical solutions to common problems in software design. Each pattern is like a blueprint that you can customize to solve a particular design problem in your code.

## Benefits of patterns
![[Pasted image 20230507150252.png]]
Patterns are a toolkit of solutions to common problems in software design.

## What does the pattern consist of?

Most patterns are described very formally so people can reproduce them in many contexts. Here are the sections that are usually present in a pattern description:

-   **Intent** of the pattern briefly describes both the problem and the solution.
-   **Motivation** further explains the problem and the solution the pattern makes possible.
-   **Structure** of classes shows each part of the pattern and how they are related.
-   **Code example** in one of the popular programming languages makes it easier to grasp the idea behind the pattern.

## Classification
![[Pasted image 20230507150334.png]]
Design patterns differ by their complexity, level of detail and scale of applicability. In addition, they can be categorized by their intent and divided into three groups.

`Note: The most basic and low-level patterns are often called idioms. They usually apply only to a single programming language.`

`Note: The most universal and high-level patterns are architectural patterns.`

All patterns can be categorized by their _intent_, or _purpose_

- **Creational patterns** provide object creation mechanisms that increase flexibility and reuse of existing code.
- **Structural patterns** explain how to assemble objects and classes into large structures, while keeping these structure flexible and efficient.
- **Behavioral patterns** take care of effective communication and the assignment of responsibilities between objects.

## Criticism of patterns
![[Pasted image 20230507150440.png]]
Are patterns as good as advertised? Is it always possible to use them? Can patterns sometimes be harmful?

### Kludges for a weak programming language 

Usually the need for patterns arises ==when people choose a programming language or a technology that lacks the necessary level of abstraction==. In this case, patterns become a kludge that gives the language much-needed super-abilities.

For example, the **Strategy** pattern can be implemented with a simple anonymous (lambda) function in most modern programming languages.

### Inefficient solutions

Patterns try to systematize approaches that are already widely used. This unification is viewed by many as a dogma, and they implement patterns "to the letter", without adapting them to the context of their project.

### Unjustified use

`If all you have is a hammer, everything looks like a nail.`