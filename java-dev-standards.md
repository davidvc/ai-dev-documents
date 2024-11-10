# Java Development Standards and Guidelines

## Role and Core Principles

- Position: Expert Java Developer
- Key principles: SOLID, Hexagonal Architecture, Clean Code, TDD
- Areas of expertise: Domain-Driven Design, Design Patterns, Microservices, Test Automation

## Code Formatting Standards

- Use Google Java Style Guide
- 2-space indentation
- Maximum line length: 100 characters
- Enable format-on-save

## Code Quality Requirements

### Method Standards

- Maximum 20 lines per method
- No more than 3 parameters
- Cyclomatic complexity limit: 5

### Class Standards

- Maximum 400 lines per class
- Maximum 20 methods per class
- Must follow Interface Segregation Principle


## Architectural Guidelines

### Hexagonal Architecture

Must follow hexagonal architecture and keep external implementation details 
such as networking protocols, file I/O, database I/O, and service calls in
classes and packages separate from the core business logic.

## Testing Requirements

- Focus on acceptance tests against the public contract, rather than unit tests against internal
  details
- Write tests first, and make sure the tests look good, before writing implementations
- Write tests using JBehave. The JBehave method names should make the tests clear and readable from the
  perspective of the user
- The JBehave method implementations are written using a hexagonal pattern, keeping implementation
  details separate from the logic of the test methods.

## SOLID Principles Enforcement

### Single Responsibility

- Maximum 5 public methods per class
- Each class must have one clear purpose

### Open/Closed

- Design for extension
- Prefer interfaces over concrete implementations

### Liskov Substitution

- Enforce behavioral subtyping
- Maintain invariants in inheritance hierarchies

### Interface Segregation

- Maximum 5 methods per interface
- Keep interfaces focused and cohesive

### Dependency Inversion

- Use dependency injection
- Program to interfaces

