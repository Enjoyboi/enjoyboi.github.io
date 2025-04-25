---
layout: essay  
type: essay  
title: "Design Patterns: Like Recipes, But for Code"  
date: 2025-04-24  
published: true  
labels:  
  - Software Engineering  
  - Design Patterns  
---

<img width="200px" class="rounded float-start pe-4" src="../img/design-patterns/recipe-code.jpg">

**Design Patterns: Like Recipes, But for Code**

When I first started writing code, I thought being a good developer meant doing everything from scratch. No shortcuts, no templates just me, VS Code, and vibes. But the more I coded, the more I realized I was basically making spaghetti every time — messy, tangled, and not super reusable.

That’s when I learned about design patterns. And honestly, they kind of changed how I see code. If I had to explain them in a way that makes sense, I’d say they’re like recipes for common problems in programming. They don’t tell you exactly what to cook, but they give you a solid structure like “hey, if you’re trying to bake a cake, here’s a method that won’t burn the kitchen down.”

### The Singleton Surprise

One of the first patterns I ended up using (without even knowing it had a name) was the **Singleton Pattern**. In a group project, we needed a config file that every part of the app could use. So I made a little module that loaded the config once and returned the same data every time. At the time I was just like, “Cool, it works.” Later in class, I realized: “Wait… that’s literally the Singleton Pattern.” And it made sense why it worked so smoothly.

### The Observer Pattern in Real Time

Another one I actually used on purpose was the **Observer Pattern**. We had this dashboard that needed to update when the backend data changed. Instead of making the frontend constantly check for updates (which would’ve been a laggy mess), I set up a system where components “subscribed” to updates and got notified when something changed. It worked way better than my first idea (which was basically a loop that never ended).

### Factories: Like Burger Builders for Components

The last one I’ve used a lot recently is the **Factory Pattern**. In our Next.js app, we had different types of content cards jobs, events, blogs, stuff like that. Instead of doing a bunch of `if/else` statements everywhere, I made a factory function that just returned the right component based on the type. Super clean. Easy to expand later. And it didn’t turn into a giant mess when we needed to add new types.

### Why Design Patterns Actually Matter

I think the coolest part about design patterns is that they save you from re-inventing the wheel. Developers before us already ran into the same problems — design patterns are basically their way of saying “here’s how I solved this, so you don’t have to suffer too.”

If someone asked me in an interview, “What are design patterns?” I’d probably say, “They’re like battle-tested strategies for solving coding problems that show up a lot.” And if they asked which ones I’ve used, I’d tell them: Singleton, Observer, and Factory. Not just because I studied them, but because I actually used them — and they genuinely made my projects better.

---

I used ChatGPT to help brainstorm and organize this essay, but all the experiences and examples are from my own projects.
