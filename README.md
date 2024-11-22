# Developer Education

## Motivation

I get asked a lot by junior developer friends and colleagues:

- how did you learn to write good tests?
- how do know how to structure the application?
- where did you learn to apply that pattern?
- how do you manage your time?
- which books on IT are worth reading?
- what skills are needed to become a true professional?
- etc.

I was teaching development to friends and colleagues for a while already, telling the same things over and over again and answering the same questions over and over for years. And every time I get to know new beginners or aspiring professionals in new teams the questions get raised again. The answers I give are battle proven and are rarely taught at schools, boot camps and universities. 

This repository is an attempt to collect my **opinionated** wisdom which I gained in about one and a half decades in the industry. It is a living document and I will present it in a structured way. I will provide a path to mastery in form of a study guide. You will have to walk the path yourself but you don't have to walk it alone. Support is always a call or message away. Also connect among each other.

Read on.

## Table of Contents

- [Development Fundamentals](#development-fundamentals)
  - [Refactoring](#refactoring)
  - [Test Driven Development](#test-driven-development)
  - [SOLID Principles](#solid-principles)
- [Architecture](#architecture)
  - [Basic](#basics)


## Development Fundamentals

You get instant value by focusing on the three skills listed below. They will teach you architecture/design basic which make code easier to change.

1. Refactoring.
1. Test Driven Development.
1. SOLID Principles.

### Refactoring

**Book:** Refactoring Second Edition, Martin Fowler, [O'Reilley link.](https://learning.oreilly.com/library/view/refactoring-improving-the/9780134757681/)
- Read and practice the first chapter. Code the example yourself, [Tests and Kata Setup](https://martinfowler.com/articles/2024-refactoring-code-samples.html).
- Study the code smells and how to resolve them.
- Pick a class or module from your current project and apply what you learned in a feature branch.
- Create a PR and get it merged.
- Read at least till the Refactorings Catalog. Continue if you like and have time. Otherwise move on to second topic.

### Test Driven Development

**Book 1:** Test Driven Development by Example, Kent Beck, [O'Reilley link.](https://learning.oreilly.com/library/view/test-driven-development/0321146530/)

- Read it entirely, its short.
- Practice the example in the first chapter in your language. He uses Java.
- Understand the workflow: red, green, refactor.

**Book 2:** Clean Craftsmanship by Robert Martin, [O'Reilley link.](https://learning.oreilly.com/library/view/clean-craftsmanship-disciplines/9780136915805/), [the videos on O'Reilley.](https://learning.oreilly.com/course/clean-craftsmanship-disciplines/9780137676385/)
- Watch the videos and read the chapters about TDD und practice all the examples in your language. He uses Java.
- Memorize the rules. Practice the small steps.
- Its hard, I know. Keep on practicing. The reward is big. It will change your code for ever.

### SOLID Principles

The resources here are spread over many books and courses. I will link here a selection which I think is best.

**Book 1:** Agile Principles, Patterns, and Practices in C# by Micah Martin and Robert C. Martin, [O'Reilley link.](https://learning.oreilly.com/library/view/agile-principles-patterns/0131857258/pt02.xhtml)

- Understand all of the principles.
- I recommend to code each one of them.
- You should recognize some from the Refactoring book and the first chapter.
- Look in your project for code where you can apply them so that you try them in the real world.

**Book 2:** Clean Architecture by Robert C. Martin, [O'Reilley link.](https://learning.oreilly.com/library/view/clean-architecture-a/9780134494272/part3.xhtml)

- The book is not for beginners so I recommend only to study the SOLID section linked above.
- It took me reading it twice with two years apart to get all the stuff there.

**Course:** Clean Code Fundamentals by Robert C. Martin, [O'Reilley link.](https://learning.oreilly.com/course/clean-code-fundamentals/9780134661742/)

- The SOLID section is worth watching.
- The entire course is 53h and very comprehensive. Watch it at some point. For now SOLID is enough.

## Architecture

### Basics

**Article:** [Modularizing React Application with Established UI Patterns](https://martinfowler.com/articles/modularizing-react-apps.html)

- Great introduction into how to structure a frontend. He uses React and TypeScript but its universal.
- Understand the code. I recommend coding all of his examples.

**Book:** React Anti-Patterns by Juntao Quo, [O'Reilley link.](https://learning.oreilly.com/library/view/react-anti-patterns/9781805123972/)

- Expands on the article above.
- He introduces more concepts and goes over basics in TDD and refactoring of React apps.
