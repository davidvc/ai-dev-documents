DESIGN DOCUMENT INSTRUCTIONS/TEMPLATE

Create a high-level design document that summarizes your overall high-level design approach. Use
standard github markdown

Please include the following sections

### Problem statement
Provide an overview of the problem from the perspective of the end user. What is it we 
want to achieve overall? 

### Acceptance criteria 
Describe the key acceptance criteria from the perspective of the end user of this feature.

Use the Gherkin syntax:
- GIVEN to explain any preconditions
- THEN to describe the action
- WHEN to describe the expected outcome

### Non-functional requirements
List any important non-functional requirements, such as how many requests per second it must handle,
data sizes, reliability, scalability, etc.

### Key components
List key components and provide a sentence or two for each component, describing the component's
role, why it is needed to solve the problem, and any important aspects or requirements for the component.

### Interactions
Describe how the acceptance criteria are accomplished using these components

### Error scenarios
- Describe error scenarios and how they will be addressed

### Alternatives considered
- Describe alternatives considered and why they won't work

### Security
- Identify any potential security issues and how they will be addressed

Specify the problem at hand, and your proposed design approach at a high level. Do not include class-level details or code. Explain how this appraoch solves the problem. Also make sure to cover error conditions and how you will handle them.

Apply SOLID principles and hexagonal architecture to your design. 
