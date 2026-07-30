---
title: Building Better Tools Doesn't Mean Forgetting the Old Ones
date: 2026-07-30
featured: true
subtitle: Selenium • Python • Page Object Model
image: 'images/pexels-peaky-31343288.jpg'
---
## Every mechanic has a favorite wrench.

Even after buying newer tools.

I'm a big fan of mechanics.

Whenever I have some free time, you'll probably find me watching car videos, learning how engines work, or thinking about the next tool I'd like to add to my toolbox.
And something I've noticed is that good mechanics rarely throw away their oldest tools.
Not because they're the fastest.
Not because they're the newest.
But because those tools helped them become the mechanic they are today.

I think software engineering works exactly the same way.

<div class=" gallery-box">
    <div class="gallery">
        <img src="{{'images/pexels-aedrian-10497629.jpg' | relative_url}}" loading="lazy" alt="shop">   
    </div>
</div>

## This Was My First Production-Style Framework

More than four months ago, I built this Selenium framework.
At the time, I wasn't trying to build "another automation project."
I wanted to understand what made automation maintainable.

How should Page Objects be organized?
Where should configuration live?
How do reusable components reduce duplication?
How can reports actually help developers instead of simply showing red and green tests?

Those questions shaped this project.
Looking back today...
I can see dozens of things I would do differently.

And that's exactly why I like it. 

## Technology Keeps Moving

Something funny happened while updating this repository recently.

The CI pipeline suddenly stopped passing.
Not because the framework was broken.
Not because the tests had become unreliable.
GitHub had simply evolved.
The Actions used by this project were originally built around an older runtime, and after GitHub updated its infrastructure, the workflow needed a small refresh to keep running.
It reminded me of something that's true far beyond software.

Sometimes your tools aren't failing.
The environment around them has simply moved forward.

<div class=" gallery-box">
    <div class="gallery">
        <img src="{{'images/Selenium-CICD.png' | relative_url}}" loading="lazy" alt="CICD">   
    </div>
</div>

## Selenium Still Has a Place

These days I build most new projects using Playwright.

Not because Selenium is bad.
Far from it.
Selenium remains one of the most reliable automation tools ever created.
It has powered enterprise automation for years and continues to do so.

But newer tools solve problems that didn't exist when Selenium first appeared.
Playwright, for example, handles modern web applications more naturally.
Automatic waiting.
Multiple browser contexts.
Better handling of modern frontend frameworks.
Faster execution.
Cleaner APIs.

Every generation of tools teaches us something new.

## New Tools Don't Erase Old Knowledge

One mistake I see sometimes is treating technology like fashion.

A new framework appears...
and suddenly everything that came before is considered obsolete.

I don't see it that way.
Knowing Selenium helped me understand why Playwright feels different.
Understanding Page Object Model made me appreciate fixtures.
Building synchronous frameworks helped me understand asynchronous ones.

Every project built on top of the previous one.

<div class="gallery-box">
    <div class="gallery">
        <img src="{{'images/Selenium-arquitecture.png' | relative_url}}" loading="lazy" alt="screenshot">
    </div>
</div>

## Looking Back

When I open this repository today...

I notice little things.
Naming conventions I'd change.
Architectural decisions I'd simplify.
Utilities I'd rewrite.
Reporting I'd improve.

And honestly...
I'm happy I can see those things.
Because it means I've grown.
If I opened this repository and thought it was perfect...
I'd probably have stopped learning months ago.

## What This Project Still Demonstrates

Although it was my first independent framework, it still reflects principles I continue using today:

Clean Page Object Model architecture
Reusable page components
Centralized configuration
Data-driven testing
Automatic evidence collection
Professional reporting
CI/CD automation

The technologies have evolved.
The engineering principles haven't.

## Final Reflection

Mechanics don't stop respecting an old wrench because they bought a better one.

Engineers shouldn't forget the projects that taught them how to think.

This repository may no longer represent how I would build a framework today.
But it represents something even more valuable.
The moment I stopped writing tests...
and started designing software.

> **<em>Good engineers don't just upgrade their tools. They upgrade the way they think.</em>**

## Repository

Explore the complete framework, architecture, and implementation on [GitHub](https://github.com/jerryfinol17/selenium-python-saucedemo-pom-framework.git).