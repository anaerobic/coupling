# Coupling: References & Further Reading

[← Back to Main Guide](README.md)

---

## Books

| Book                                                                                                           | Author                                                     | Focus                                                                                                                        |
| -------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------- |
| [**Balancing Coupling in Software Design**](https://amzn.to/4irApMt)                                           | Vlad Khononov                                              | The primary source for the three-dimensional coupling model (Integration Strength, Distance, Volatility). Essential reading. |
| [**Learning Domain-Driven Design**](https://amzn.to/4iMKeo2)                                                   | Vlad Khononov                                              | Domain-Driven Design with practical focus on bounded contexts, subdomains, and integration patterns.                         |
| [**Agile Software Development: Principles, Patterns, and Practices**](https://www.amazon.com/dp/0135974445)    | Robert C. Martin                                           | Where the Instability-Abstractness metrics originate. Chapter on package coupling metrics.                                   |
| [**Clean Architecture**](https://www.amazon.com/dp/0134494164)                                                 | Robert C. Martin                                           | Dependency Rule, component coupling principles (SAP, SDP, ADP).                                                              |
| [**Software Architecture: The Hard Parts**](https://www.amazon.com/dp/1492086894)                              | Neal Ford, Mark Richards, Pramod Sadalage, Zhamak Dehghani | Practical strategies for decomposition, data coupling in distributed systems.                                                |
| [**Building Microservices** (2nd ed.)](https://www.amazon.com/dp/1492034029)                                   | Sam Newman                                                 | Integration patterns, service decomposition, avoiding distributed monoliths.                                                 |
| [**Thinking in Systems: A Primer**](https://amzn.to/4kZcSEu)                                                   | Donella Meadows                                            | Systems thinking foundations — understanding how component interactions create emergent behavior.                            |
| [**Domain-Driven Design: Tackling Complexity in the Heart of Software**](https://www.amazon.com/dp/0321125215) | Eric Evans                                                 | The original DDD book — bounded contexts, ubiquitous language, subdomains.                                                   |
| [**A Philosophy of Software Design**](https://www.amazon.com/dp/173210221X)                                    | John Ousterhout                                            | Deep modules, information hiding, complexity management.                                                                     |

---

## Key Articles & Blog Posts

### Coupling Dimensions & Balance

- **[Dimensions of Coupling](https://coupling.dev/posts/dimensions-of-coupling/)** — Vlad Khononov's overview of Integration Strength, Distance, and Volatility
  - [Integration Strength](https://coupling.dev/posts/dimensions-of-coupling/integration-strength/)
  - [Distance](https://coupling.dev/posts/dimensions-of-coupling/distance/)
  - [Volatility](https://coupling.dev/posts/dimensions-of-coupling/volatility/)
- **[Core Concepts](https://coupling.dev/posts/core-concepts/)** — Complexity, Modularity, Coupling, Balance
  - [Complexity](https://coupling.dev/posts/core-concepts/complexity/)
  - [Modularity](https://coupling.dev/posts/core-concepts/modularity/)
  - [Coupling](https://coupling.dev/posts/core-concepts/coupling/)
  - [Balance](https://coupling.dev/posts/core-concepts/balance/)

### Metrics & Refactoring

- **[How to Use Module Coupling and Instability Metrics to Guide Refactoring](https://codinghelmet.com/articles/how-to-use-module-coupling-and-instability-metrics-to-guide-refactoring)** — Zoran Horvat. The clearest walkthrough of Ce, Ca, Instability metrics with before/after refactoring.
- **[How to Measure Module Coupling and Instability Using NDepend](https://codinghelmet.com/articles/how-to-measure-module-coupling-and-instability-using-ndepend)** — Zoran Horvat. Practical tooling guide for .NET.

### Critical Perspectives

- **[The Instability-Abstractness-Relationship — An Alternative View](https://odrotbohm.de/2024/09/the-instability-abstractness-relationsship-an-alternative-view/)** — Oliver Drotbohm. Critical analysis of why the abstractness metric can be misleading and how abstractness ≠ abstraction.

### Related Topics on coupling.dev

- [Module Coupling](https://coupling.dev/posts/related-topics/module-coupling/)
- [Connascence](https://coupling.dev/posts/related-topics/connascence/)
- [Semantic Coupling](https://coupling.dev/posts/related-topics/semantic-coupling/)
- [Temporal Coupling](https://coupling.dev/posts/related-topics/temporal-coupling/)
- [Lifecycle Coupling](https://coupling.dev/posts/related-topics/lifecycle-coupling/)
- [Runtime Coupling](https://coupling.dev/posts/related-topics/runtime-coupling/)
- [Afferent/Efferent Coupling](https://coupling.dev/posts/related-topics/afferent-and-efferent-coupling/)
- [Domain-Driven Design](https://coupling.dev/posts/related-topics/domain-driven-design/)
- [Cynefin](https://coupling.dev/posts/related-topics/cynefin/)

### Wikipedia

- [Coupling (computer programming)](<https://en.wikipedia.org/wiki/Coupling_(computer_programming)>)
- [Software package metrics](https://en.wikipedia.org/wiki/Software_package_metrics)
- [Dependency Inversion Principle](https://en.wikipedia.org/wiki/Dependency_inversion_principle)
- [Connascence](https://en.wikipedia.org/wiki/Connascence)
- [SOLID principles](https://en.wikipedia.org/wiki/SOLID)

---

## Conference Talks & Videos

| Talk                                                                                                             | Speaker       | What You'll Learn                                                 |
| ---------------------------------------------------------------------------------------------------------------- | ------------- | ----------------------------------------------------------------- |
| [Balancing Coupling in Software Design](https://coupling.dev/posts/learning-resources/conference-talks/)         | Vlad Khononov | The three dimensions of coupling — conference presentation format |
| [Making Your C# Code More Object-oriented](https://codinghelmet.com/go/making-your-cs-code-more-object-oriented) | Zoran Horvat  | Practical OOP techniques that reduce coupling in C#               |
| [Refactoring to Design Patterns](https://codinghelmet.com/go/refactoring-to-patterns)                            | Zoran Horvat  | How design patterns emerge from refactoring coupled code          |
| [Design Patterns in C# Made Simple](https://codinghelmet.com/go/design-patterns)                                 | Zoran Horvat  | When and which pattern to apply to reduce coupling                |

---

## Podcasts

Check the [coupling.dev podcasts page](https://coupling.dev/posts/learning-resources/podcasts/) for interviews and discussions about coupling in software design.

---

## Tools by Language

### TypeScript / JavaScript

| Tool                                                                      | Purpose                                                     |
| ------------------------------------------------------------------------- | ----------------------------------------------------------- |
| [dependency-cruiser](https://github.com/sverweij/dependency-cruiser)      | Visualize and validate module dependencies with rules       |
| [madge](https://github.com/pahen/madge)                                   | Generate dependency graphs, detect circular dependencies    |
| [eslint-plugin-import](https://github.com/import-js/eslint-plugin-import) | Lint rules for import/export coupling                       |
| [nx](https://nx.dev/)                                                     | Monorepo tooling with dependency graph and affected command |

### C# / .NET

| Tool                                                                                             | Purpose                                                             |
| ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------- |
| [NDepend](https://www.ndepend.com/)                                                              | Comprehensive code analysis with coupling metrics (Ce, Ca, I, A, D) |
| [ArchUnitNET](https://github.com/TNG/ArchUnitNET)                                                | Write architecture tests to enforce coupling rules                  |
| [Roslyn Analyzers](https://learn.microsoft.com/en-us/dotnet/fundamentals/code-analysis/overview) | Built-in code analysis for .NET                                     |
| [SonarQube](https://www.sonarqube.org/)                                                          | Code quality platform with coupling metrics                         |

### Java

| Tool                                                          | Purpose                                                       |
| ------------------------------------------------------------- | ------------------------------------------------------------- |
| [ArchUnit](https://www.archunit.org/)                         | Write architecture tests for Java and Kotlin                  |
| [JDepend](https://github.com/clarkware/jdepend)               | Calculate Ce, Ca, I, A, D metrics for Java packages           |
| [Structure101](https://structure101.com/)                     | Visualize coupling and architecture                           |
| [SonarQube](https://www.sonarqube.org/)                       | Code quality platform with coupling metrics                   |
| [Spring Modulith](https://spring.io/projects/spring-modulith) | Module boundaries and interaction verification in Spring Boot |

---

## Design Principles Related to Coupling

| Principle                                 | Relationship to Coupling                                                      |
| ----------------------------------------- | ----------------------------------------------------------------------------- |
| **Single Responsibility Principle (SRP)** | Reduces efferent coupling by limiting reasons to change                       |
| **Open/Closed Principle (OCP)**           | Enables extension without modification — reduces cascading changes            |
| **Liskov Substitution Principle (LSP)**   | Ensures polymorphic substitution works — enables contract coupling            |
| **Interface Segregation Principle (ISP)** | Reduces model coupling by providing tailored interfaces                       |
| **Dependency Inversion Principle (DIP)**  | Inverts dependency direction — makes stable components depend on abstractions |
| **Stable Dependencies Principle (SDP)**   | Depend in the direction of stability                                          |
| **Stable Abstractions Principle (SAP)**   | Stable packages should be abstract                                            |
| **Acyclic Dependencies Principle (ADP)**  | No circular dependencies between packages                                     |
| **Law of Demeter (LoD)**                  | "Don't talk to strangers" — reduces integration strength                      |
| **Tell, Don't Ask**                       | Push behavior to the object that has the data — increases cohesion            |

---

## Training & Workshops

- [coupling.dev Training](https://coupling.dev/posts/learning-resources/training/) — Workshops by Vlad Khononov on balancing coupling
- [Coding Helmet](https://codinghelmet.com/) — Courses by Zoran Horvat on OOP, design patterns, and refactoring in C# and Java

---

## Glossary

| Term                                     | Definition                                                                                             |
| ---------------------------------------- | ------------------------------------------------------------------------------------------------------ |
| **Afferent Coupling (Ca)**               | Number of external types that depend on this component                                                 |
| **Efferent Coupling (Ce)**               | Number of external types this component depends on                                                     |
| **Instability (I)**                      | Ce / (Ce + Ca) — ratio of outgoing to total dependencies                                               |
| **Abstractness (A)**                     | Ratio of abstract types to total types in a package                                                    |
| **Integration Strength**                 | How much knowledge is shared between coupled components                                                |
| **Distance**                             | Physical and logical separation between coupled components                                             |
| **Volatility**                           | Likelihood that a component will change                                                                |
| **Connascence**                          | Two components are connascent if changing one requires changing the other                              |
| **Bounded Context**                      | A DDD concept — a boundary within which a domain model is consistent                                   |
| **Anti-Corruption Layer (ACL)**          | A translation layer that prevents one model from leaking into another                                  |
| **Dependency Inversion Principle (DIP)** | High-level modules should not depend on low-level modules; both should depend on abstractions          |
| **Distributed Monolith**                 | A system with separately deployed services that are tightly coupled (worst of both worlds)             |
| **Temporal Coupling**                    | Components must be available at the same time for the system to work                                   |
| **Lifecycle Coupling**                   | Components must be built, tested, and deployed together                                                |
| **Saga**                                 | A pattern for managing distributed transactions via a sequence of local transactions and compensations |

---

[← Back to Main Guide](README.md)
