
---
title: "AI Is Reading Our Docs. Are We Writing for It?"
date: 2026-10-29
draft: false
description: "Reflections from LavaCon 2026 on writing documentation for AI, improving content quality, and the importance of human expertise."
tags:
  - Technical Writing
  - AI
  - Content Strategy
  - LavaCon
showDate: true
showReadingTime: true
---

# AI Is Reading Our Docs

*Reflections from LavaCon 2026 on AI, documentation quality, and technical writing.*

I recently attended the [LavaCon 2026](https://www.lavacon.org/2026-conference-program/) confernce curious about how other technical writers are adapting to AI. The conference certainly had no shortage of AI discussions! A lot of the session talks and breakouts centered on the latest AI tools, how to automate docs with AI, and how to use AI to find documentation gaps. These are all things I've been working on recently as well, but one central theme kept coming up: **Are we changing the way we write documentation to reflect how it's actually being consumed?**

We've spent years generally thinking about how people navigate our documentation. Now we also need to consider how AI retrieves and interprets it.

## AI Is a Reader Now

One of the sessions I attended, *AI Is Your New Top Reader. Are You Ready?*, explored how AI is changing the way documentation is retrieved and consumed.

With retrieval-augmented generation (RAG), AI can retrieve relevant chunks of documentation to generate answers. MCP servers also provide a way for AI applications to access documentation as they work through a task.

A person reading a documentation page can scroll up, look at a screenshot, or follow a link to understand what came before. An AI system might retrieve a single section without any of that surrounding information.

I was thinking about how often we use phrases like "as mentioned above" or "see the example below." What happens when the referenced content isn't retrieved along with that section?

Writing self-contained content isn't necessarily a new concept in technical writing, but I hadn't given much thought until recently to how some of these seemingly harmless phrases could affect the quality of an AI-generated answer.

## Quality Matters More, Not Less

Another session, *The Docs Are Not Alright, and AI Alone Won't Fix Them*, addressed a concern I have about the growing reliance on AI: the quality of the documentation it uses.

If our documentation contains outdated instructions or incomplete information, an AI assistant can confidently pass that information along to a customer. When several AI tools rely on the same documentation, a single inaccuracy can become a much bigger problem.

It made me think about how we can continue to automate checks that catch problems at the end of a process while also introducing guardrails that help prevent them in the first place. Tools like Vale, build checks, and link checkers already help us catch many of these issues.

Thinking about this in terms of docs-as-code workflows, I wondered whether we could extend our existing style checks to flag references that might be problematic when content is retrieved out of context.

Adding a section to an existing style guide about writing for AI might be a good starting point, but how do we know which guidelines actually improve the quality of AI-generated answers? We'd need to test how our content is retrieved and interpreted before deciding what rules to enforce.

It's an interesting concept I'd like to explore further.

## What Ada Lovelace Reminded Me About Technical Writing

One of my favorite sessions was *Ada Lovelace the Tech Writer*.

Ada Lovelace's notes on the Analytical Engine were substantially longer than the paper she translated. She expanded on the original material, explained concepts, and contributed her own insights.

Of the five principles discussed in this session, my favorite was **adding what the source doesn't have: your expertise**.

This is something I can relate to, particularly coming from an extensive technical support background. Some of my most rewarding documentation projects have started with a customer question that didn't have a good answer.

Sometimes that means testing a workflow myself, digging into product behavior, or working with engineers to understand why something works the way it does. Other times, it means discovering that information exists across several places but hasn't been brought together in a way that's useful to the customer. This happens more than you think!

AI can certainly help with research, drafting, and organizing information, but a writer still needs to recognize what's missing and determine whether the documentation actually solves the customer's problem.

## Bringing the Ideas Back to My Work

My favorite part of attending a conference is coming home with ideas I can experiment with.

Since LavaCon, I've been thinking about a few areas I'd like to explore further:

- How well does our documentation hold up when individual sections are retrieved by AI?
- Could we use automated checks to identify content that is outdated or no longer reflects product behavior?
- Can we test codebase against the documentation to flag areas that are incorrect, missing, or inaccurate?
- Can we use the questions customers ask AI assistants to uncover gaps in our documentation?
- Which repetitive tasks could we automate to give writers more time to research and test the products they document?

## What I'm Taking Away

I went into LavaCon wanting to learn more about AI. I came away thinking just as much about the fundamentals of technical writing.

I'm excited about what AI can do for documentation, especially when it comes to maintenance, identifying content gaps, and making information easier to find. 

As technical writers, we now have another reason to question what we write, how we structure it, and whether it answers the questions our customers are actually asking.

I'm looking forward to experimenting with some of these ideas and seeing what works.

And yes, there were llamas! Because apparently no content strategy conference is complete without them. 🦙 Oh, and there were puppies too! 