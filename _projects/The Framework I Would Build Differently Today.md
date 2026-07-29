---
title: The Framework I Would Build Differently Today
date: 2026-07-26 
subtitle: Python • Playwright • Learning Through Practice
image: '/images/pexels-paras-4218883.jpg'
---
One of the strangest things about software engineering is how quickly your own work starts teaching you.

I built this framework only a few months ago.
It still runs.
The architecture is still solid.
The tests still pass.
But today, I'd build parts of it differently.
Not because it was wrong.
Because I've learned better ways since then.
And strangely enough...

That's exactly why I'm proud of it.

<div class="gallery-box">
  <div class="gallery ">
    <img src="{{'/images/08-2.jpg' | relative_url}}" loading="lazy" alt="Project">
  </div>
</div>

## Overview

This project was my first production-style automation framework built with Python, Playwright Async, and pytest.

Rather than writing isolated automation scripts, I wanted to build something that looked and felt like a framework a real QA team could maintain.

It includes:

Full asynchronous Playwright architecture.
Page Object Model.
Parallel execution.
CI/CD with GitHub Actions.
Automatic screenshots and videos.
Strategic code coverage.
Cross-browser execution.

Looking back, I realize this project taught me much more than Python syntax.

It taught me how to think about maintainability.

<div class="gallery-box">
  <div class="gallery ">
    <img src="{{'/images/CICD-PPSPF.png' | relative_url}}" loading="lazy" alt="Project">
  </div>
</div> 

## My Goal

When I started this project, I wasn't trying to create the biggest automation suite.
I wanted to answer a much simpler question.

**If someone hired me tomorrow, what kind of framework would I want them to inherit?**

That question shaped almost every engineering decision.

Reusable page objects.
Clean abstractions.
Evidence generation.
Meaningful test coverage.
Reliable execution.

<div class="gallery-box">
  <div class="gallery ">
    <img src="{{'/images/E2E-gif.gif' | relative_url}}" loading="lazy" alt="Project">
  </div>
</div>

## The Engineering Decisions

Several choices still make me smile when I revisit the repository.

The framework uses:

Async Playwright.
pytest-asyncio.
Page Object Model.
Parallel execution.
GitHub Actions.
Automatic evidence collection.

At the time, these represented the best practices I knew.

Many of them still do.

Others... I'd approach differently today.

And that's the interesting part.

<div class="gallery-box">
  <div class="gallery ">
    <img src="{{'/images/Arquitectura-PPSPF.png' | relative_url}}" loading="lazy" alt="Project">
  </div>
</div>

## Looking Back

This is probably one of  the oldest framework I'll ever showcase in my portfolio.

And if I'm honest...
I can already see things I'd improve.
Maybe I'd organize certain components differently.
Maybe I'd make some abstractions cleaner.
Maybe I'd structure the fixtures another way.
That's the funny thing about software.
If six months later you don't see opportunities to improve your old code...

You probably haven't grown very much.

## Why I Didn't Rewrite It

People sometimes ask why I don't simply update old projects.

The answer is simple.
Because this repository represents a moment in my journey.
It's the framework that taught me asynchronous Playwright.
It taught me CI/CD.
It taught me Page Objects.
It taught me what maintainable automation actually looks like.
If I rewrote everything every time I learned something new...

I'd erase the evidence that I learned at all.

## What I'm Most Proud Of

Oddly enough...
It isn't the architecture.
It isn't the code coverage.
It isn't the CI pipeline.

It's that I genuinely cared.

I wasn't trying to "finish a portfolio project."
I wanted to build something I could confidently hand to another engineer.
That mindset has stayed with me ever since.

## Lessons Learned

This project taught me something that still shapes how I write software today.
Good code isn't code you'll never change.
Good code is code that makes your future self smile instead of suffer.
And every framework I've built since then exists because this one came first.

## Final Reflection

Today I know better patterns.
Cleaner abstractions.
Better engineering practices.
And that's exactly what I hoped would happen.

Because if my old projects don't make me think,
"I'd build this differently today."
then I'm probably not growing as an engineer.

I'm proud of this framework.
Not because it's perfect.
Because it tells the story of where I was—and how far I've come since then.

## Repository

Explore the complete [framework](https://github.com/jerryfinol17/Python-Playwright-Saucedemo-Pom-Framework.git) and follow the evolution yourself.