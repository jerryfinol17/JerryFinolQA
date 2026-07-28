---
title: Building Automation That Survives Change
date: 2026-6-28
subtitle: Framework Design
image: '/images/11.jpg'
---
Something I've learned while building automation is that writing tests isn't the difficult part.
Keeping them reliable as the application evolves is.
This project wasn't built to maximize the number of test cases.
It was built to answer a more important question:

How do you create automation that teams can actually trust before every release?

<div class="gallery-box">
  <div class="gallery">
    <img src="{{'/images/08-1.jpg' | relative_url}}" loading="lazy" alt="Project">
  </div>
</div>

## Overview

This framework validates the complete user experience of a modern Kanban task management application using Playwright and TypeScript.
Rather than focusing on isolated user journeys, the project validates the application across multiple dimensions simultaneously:

Desktop, tablet, and mobile layouts
Light and dark themes
Board management
Task lifecycle
Responsive navigation
Drag and drop
Persistence
Edge cases
Known product defects

In total, every execution expands into 252 automated UI tests running across six independent Playwright projects.

<div class="gallery-box">
<div class="gallery">
    <img src="{{'/images/taskflow-cov.png' | relative_url}}" loading="lazy" alt="Project">
</div>
</div>

## The Challenge

Modern interfaces rarely behave the same across every device.
A button might move.
A mobile menu replaces a desktop sidebar.
Dark mode introduces different rendering.
Responsive layouts change interactions entirely.
Many automation suites quietly ignore those differences.
I wanted this framework to embrace them instead.

## Engineering Decisions

Several architectural decisions shaped the project.
Instead of storing every selector directly inside test files, the framework separates responsibilities through Page Objects and Component Objects.
Factories generate realistic dynamic data.
Custom Playwright fixtures inject themes before the application loads.
Responsive navigation is abstracted so tests don't need separate desktop and mobile implementations.
The goal wasn't simply cleaner code.
It was making future maintenance dramatically easier.

<div class="gallery-box">
<div class="gallery">
    <img src="{{'/images/taskflow-architecture.png' | relative_url}}" loading="lazy" alt="Project">
</div>
</div>


## Evidence Matters

One thing I care deeply about is evidence.
Passing tests are useful.
Understanding failures is even more valuable.
The framework automatically generates:

Playwright HTML Reports
Monocart Reports
Screenshots
Videos
Traces
Custom visual evidence

So when something fails, developers immediately know what happened instead of trying to reproduce it manually.

## Testing Isn't Only About Passing

One feature I'm particularly proud of is how the framework handles known product bugs.
Instead of deleting failing tests or commenting them out, known defects remain documented as expected-risk scenarios.
This means the automation reflects the actual state of the product rather than pretending everything is perfect.
Once a bug is fixed, the corresponding test simply becomes part of the normal regression suite.
For me, automation shouldn't hide reality.
It should document it.


<div class="gallery-box">
<div class="gallery">
    <img src="{{'/images/bug-report-example.png' | relative_url}}" loading="lazy" alt="Project">
</div>
</div>

## What I Learned

This project completely changed the way I think about automation.
Automation isn't writing scripts.
It's software engineering.
Every architectural decision affects future maintenance.
Every duplicated selector becomes technical debt.
Every flaky test reduces confidence.
Building reliable automation requires thinking months ahead, not just until the next successful execution.


## Final Reflection

One sentence kept coming back while I built this framework.
Reliable automation isn't measured by how many tests you write. It's measured by how confidently a team can deploy because those tests exist.
That's ultimately what this project represents.
Not a collection of Playwright scripts.
A maintainable quality engineering asset.


Repository

Explore the complete framework, architecture, and implementation on [GitHub](https://github.com/jerryfinol17/taskflow-playwright-typescript-framework.git).