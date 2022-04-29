# Design Pattern In C-Sharp

## 1. Design Patterns Overview

Overview

- What is a design pattern
- Where do they come from
- Why should we learn design patterns
- How should we learn design patterns
- When should we apply design patterns
- What are some specific patterns to start with

### 1.1. What

A software design pattern is a general,
reusable solution to a commonly occurring
problem with in a given context

### 1.2. Where do they come from

- 1977: Architect Christohper Alexnder introduces
patterns in his book
- 1987: Cunningham and Beck leverage patterns
for a client; present at OOPSLA87
- 1991: Erich Gamma pursues Ph.D. dissertation on patterns
- 1994: Gang of Four publish Design Patterns

### 1.3. Why should we learn design patterns?

- Avoid reinventing wheels: many of the problems you'll face
in your career have been solved before. Learn
to recognize them and the patterns that can be
used to address them.

- Improve communication: understanding the patterns
your team uses is critical to communicating
effectively with your team.

- Deliver better software: often, difficult problems
or duplicate code implementations can be solved
elegantly using a design pattern.

- Advance your career: Today, most senior developers
and certainly every architect, should be familiar
with the concept of design patterns and should know at
least a few of them well enough to
implement them without assistance.

### 1.4. How should we learn design patterns?

Stages of Learning

- Ignorance: you don't know that a concept, technique, or pattern exists.
- Awakening: in this stage, you become aware of
the thing about which you want to learn. You've
probably never actually applied the pattern;
you've only heard about it from others.
- Overzealous: you try to use the pattern. Generally,
it's less painful to practice new techniques in
a controlled environment rather than in production or
on game day.
- Mastery: you've internalized the skill or
pattern. You've developed a kind of muscle memory for
applying it that no longer requires you to break down
the steps and consciously go through them one by one.

T-Shaped Pattern Knowledge: have a board understanding
of general concepts, but also have deep
practical understanding of a few specific things.

### 1.5. What makes up a design pattern?

Pattern definition sections

- Name and Classification
- Intent: what is the problem that it's trying to solve?
- Also known as ... (other name of the pattern)
- Motivation or Scenario: a scenario or problem that this pattern applies to
- Applicability or Context: different situations in which this pattern could be usable
- Structure: class diagrams and interaction diagrams or sequence diagrams
- Participants
- Collaboration
- Consequences
- Implementation
- Sample code
- Known uses
- Related patterns

The bare minimum

- Names
- Intent
- Motivation or applicability

### 1.6. Pattern structure

Often described using UML diagrams

### 1.7. When should we apply design patterns?

It's a good idea to start in a controlled
practice environment.

Practice:

- Do a coding exercise or kata
- Write tests to verify understanding: write tests
for the code before you apply the pattern,
and then apply the pattern and verify that
those tests continue to pass and work just the
way the did before.
- Repeat several times with variations
- Practice on real code in a separate branch - then
delete it

In real code:

- Follow refactoring fundamentals
- Make sure you have test coverage
- Do the work in a seperate branch - use a pull request
or similar tool to merge
- Verify behavior is consistent after completing the
refactoring

### 1.8. A few good design patterns?

- Strategy: is definitely one of my favorites. If you're working
with systems that use dependency injection, you're
already somewhat familiar with the strategy design pattern.
- Repository: is a data access pattern
- Adapter
- Factory
- Proxy/Decorator
- Singleton

Also, if you're looking to learn domain-driver design,
checkout the DDD Fundamentals course, which also
introduces the basic design patterns that are used in DDD.

## 2. Key takeaways

- Design patterns are genral solutions to existing problems
- Avoid reinventing the wheel
- Communicate more richly with your team
- Get familiar with a broad range of patterns
- Go deep on the patterns most relevant to your wokrk
- Use refactoring to apply patterns
- Look for ways to combine patterns
