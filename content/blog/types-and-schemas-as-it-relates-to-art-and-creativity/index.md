---
title: "Types and Schemas as it relates to Art and Creativity"
description: "A bridge between two styles"
lead: "I’ve always preferred implicit schemas and types."
date: 2021-09-03T9:22:00-00:00
lastmod: 2021-09-03T9:22:00-00:00
draft: false
weight: 50
images: []
contributors: []
---

I’ve always preferred implicit schemas and types. Preferring these kinds of systems is usually looked down upon by some technical leaders. There are exceptions but in general well-established technical organizations prefer explicit types and schemas. For years, I’ve been confused as to why they prefer these systems and what’s more why they look down on them. Moreover, why have I the preferred the implicit?

My hope in this article is to cross the isle and make friends. I hope to explain myself and give validation for those who love explicit systems because now days I’m one of them.

## Explaining my historical preference

Recently, I’ve come across one possible answer for my preference. I’ve always preferred tools which allow me to express creative ideas, change my mind, and allow me to iterate quickly. Bret Victor has a value that I’ve loved since I first heard it, “Creators need an immediate connection with their creations.” This value put another way becomes a question of, “How long does it take for me to see my idea in the real world?” A creative wants immediate feedback.

My opinion then is that implicit systems grant you more freedom to explore ideas. You do not need to know where you’ll end up. They allow you to make a mess and deal with cleanup in later cycles of the project. They allow you to make mistakes and change your mind. At the root, implicit systems prefer changeability.

On the flip side, explicit systems prefer reliability. An explicit system ensures that what you asked for is exactly what you get. It keeps everyone safe through type-safety. If you want to add an attribute to a model, explicit systems force you to adjust all the parts of the application which use that type. Expanding the scope of the change could force many changes before the code compiles. It’s an all-or-nothing approach to software engineering. It does has the word, “safety” in it’s name.

## Addressing creativity in an explicit system

Someone may take issue with the fact that I’m suggesting that you cannot be creative in an explicit system. I don’t think that’s true. It’s just easier to be creative in an implicit	system. You get more time to explore ideas since parts of the system may be broken and you don’t have to focus on them immediately. Think of it as FPS or frames per second of creative work. The closer to real-time an idea may be expressed, the you’re more likely to end up with of a higher quality idea.

## Defining Terms

### Implicit

An implicit schema is a type that is resolved at runtime. Many of these systems use duck-typing. If it walks like a duck and quacks like a duck then it’s a duck. Examples of duck-typing include languages such as JavaScript, Ruby, Python, and PHP. Data storage examples include most document stores such as MongoDB and CouchDB. You could also argue that JSON is implicitly typed.

```javascript
// Example of undeclared type:
let point = { x: 123, y: 456 };
```

### Explicit

Explicit schemas need to be declared up front. The compiler will enforce consistency before the code is executed. If you use an ambiguous type the compiler will complain. Common examples of explicit typing are relational databases such as Postgres, MySQL, and Microsoft SQL Server. Language examples include TypeScript, Java, C#, C++, and Go.

```typescript
// Example of declared type:
let point:Point = { x: 123, y: 456 };
```

## Art and Creativity

A creative working on a new project works in layers. The first layer is a rough guide. It’s usually a bit of a mess. Through the process of refinement your idea begins to take shape. The type of work you do is molding work. A little here, a little there, oh, what if… and so the story goes. The process is one of exploration and experimentation. It’s essential for a creative to be able to go through this process. It’s unclear where you’ll end up and that’s exactly what makes it creative.

## Reliable Systems

If you happen to know what a system needs to be then it’s likely a mature idea. What’s need at this stage in the ideas lifecycle is reliability. This is where type systems rule the day. Types allow you to ensure that things are mostly working. Don’t believe the hype, type-safety does not automatically grant you bug free code since they do nothing to solve for logical or algorithmic errors. I’ll grant however that they are more safe than implicit systems.

## The Bridge

The two worlds of changeability and reliability are not at odds. They are just at different legs of the race. Creative work is needed to discover what the system could be. Reliable systems are later in the process when the system has taken shape. It’s a baton that is passed to a fellow team member.

Consider a simplified system lifecycle:

1. Explore - this is when creatives are most needed
2. Maturity, cashing in on value - this is when safety is most needed
3. Sunset - where we begin a new race

## Takeaways

If you are a creative but happen to be working in a mature system then you need to adjust your style since the expectations are one of safety. If you are a type loving guru but are in the early stages of a system perhaps you could lessen the reigns and enjoy not knowing where things will end up.

There are also different workflows for the two styles of systems design. I think this is a key issue when crossing the isle. If you don’t know how to think in the styles workflow you’ll struggle to be productive. Unfortunately, I cannot list the two workflows here since they vary depending on the system. This is something that is learned by pairing with someone across the isle. It requires experience. Sometimes asking the question, “How would you go about X?”, is enough to understand the workflow but knowing they are different is the most important takeaway.

I hope this will help us all get along a bit better. Go team.
