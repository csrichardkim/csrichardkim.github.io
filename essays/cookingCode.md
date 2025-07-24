---
layout: essay
type: essay
title: "Cooking in Code"
# All dates must be YYYY-MM-DD format!
date: 2025-7-24
published: true
labels:
  - Design patterns
---

<div class="text-center mt-5 mb-5">
  <img src="../img/cookingcode.png" width="400px" class="img-fluid rounded" alt="Cooking image">
</div>



## Cooking in Code

If you've ever cooked a meal, you know that good food doesn’t happen by accident. Even simple dishes like pasta or stir fry follow patterns: preheat the pan, chop your ingredients, season as you go, and don’t burn the onions. Experienced cooks don’t follow step by step instructions every time, what they do follow are techniques and structures that work across many recipes.
In the world of software development, we do something similar. We use design patterns, reusable solutions to common problems. Like the best cooking methods, design patterns aren’t fixed recipes. They’re more like flexible guidelines proven to help us work efficiently. Developers may not always know they are using them. However, it is an essential part of being a developer and something everyone can incorporate in their own kitchen space.

Some common examples include:

- Prototype Pattern: Like making one great sauce and using it as a base for multiple dishes. In code, you create one object and clone it instead of starting from scratch every time.
- Reactive Pattern: Like adjusting the heat when food starts to bubble too fast. In code, this means your interface responds to data changes instantly no manual refresh needed.
- Front Controller Pattern: Like a kitchen expediter who directs all orders through one central point before they go out. In web apps, it’s the pattern of routing all user requests through one handler.

Once you learn these techniques, you start to see them everywhere, just like how a home cook learns to sauté before any good stew.

## Cooking a Final Project 

Right now, I’m working on an ICS314 project: a centralized student club directory for UH Mānoa. The goal is to allow users to browse clubs by interest (like sports, STEM, or cultural orgs), and give club admins and super admins tools to manage listings. I’m building it with Next.js, PostgreSQL, and deploying it on Vercel. This project has shown me how essential design patterns are to keeping everything organized, functional, and scalable. 

For this project I am using a version of the Prototype pattern when generating test data. I created one "template" club object, then reuse and modify it to mock up dozens of different entries. I use the Front Controller pattern through Next.js routing and the app.tsx file. It’s designed to process each page request, whether you're browsing clubs or logging in and perform some further action. The Reactive pattern is everywhere in the UI. When users search or apply filters, React updates the view instantly


## Conclusion

Chefs are developers of taste. In the same way great cooks rely on consistent methods to whip up something delicious, great developers rely on design patterns to write clean, reliable code. In the end, both good food and good software come down to recognizing these design patterns and whipping up something beautiful. 

Mahalo for listening.




## Note on AI

AI used for formatting
