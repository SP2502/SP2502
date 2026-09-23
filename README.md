# Hi, I'm Shreyansh 👋

I'm a student who likes building things.

Most of my projects start because I have a question, an idea, or a problem I want to understand. I usually learn by building the first version, finding out what breaks, and then figuring out how to make it better.

Right now I'm working on **Cortex**, an open deep-research system, while also building **Universal**, a weather-data layer, and **AEGIS**, a Windows content blocker.

I also have a Minecraft bot that is already built, deployed, and running.

---

## 🚀 Projects

| Project | What it is | Status |
|---|---|---|
| **Cortex** | Open deep-research system | 🚧 Building |
| **Universal** | Weather-data infrastructure | 🧪 Early development |
| **AEGIS** | Free Windows content blocker | 🚧 Building |
| **Minecraft Bot** | Hosted Minecraft automation | ✅ Running |

---

## 🧠 Cortex

### Open Deep Research

**Cortex** is my current AI project.

I'm building it around a simple idea: asking a difficult question should not end with an AI giving one quick answer. A useful research system should be able to figure out what it needs to know, find the information, compare it, and build an answer from the evidence.

Cortex is being designed to work through research in stages:

```text
Question
   ↓
Understand the problem
   ↓
Break it into research tasks
   ↓
Plan the research
   ↓
Search & gather information
   ↓
Compare sources
   ↓
Reason over the evidence
   ↓
Produce the final research
```

Things I'm working on include:

- Research planning
- Breaking complex questions into smaller tasks
- Multi-step research workflows
- Searching across different sources
- Evidence collection
- Source comparison
- Reasoning over gathered information
- Structured research output
- Different AI models and tools
- Handling long-running research tasks

I'm also interested in the less visible parts of a research system — reliability, tool failures, bad sources, conflicting information, prompt injection, and what happens when one step of the process doesn't go as expected.

Cortex is still being built, so the architecture is changing as I learn what actually works.

**Status:** 🚧 Active development

---

## 🌍 Universal

### Weather Data Without Being Locked to One Provider

**Universal** is a weather-data infrastructure project.

The idea came from a simple problem: applications shouldn't have to care about which weather provider is working underneath them.

A developer can provide coordinates, and Universal handles the rest.

```text
Latitude + Longitude
        ↓
Location Resolution
        ↓
Weather Provider Selection
        ↓
Best Available Provider
        ↓
Normalized Weather Data
        ↓
Application
```

Universal is designed around multiple weather providers instead of depending on a single source.

The system can:

- Resolve a location from coordinates
- Work with multiple weather providers
- Select an appropriate provider
- Fall back to another provider when needed
- Normalize data between providers
- Give applications a consistent way to access weather information

The fallback part is important.

If one provider has a problem, the application shouldn't necessarily have to stop working with it.

I'm building Universal to be the layer between an application and the providers underneath it.

**Status:** 🧪 Early development

---

## 🛡️ AEGIS

### Free Windows Content Blocker

**AEGIS** is a free Windows application I'm building to block unwanted and adult content.

The goal is to make it a practical desktop application that can actually be used on a normal Windows machine, rather than just making a proof-of-concept filter.

I'm currently working on things such as:

- Content blocking
- Windows integration
- Privacy
- Security
- Reliability
- Performance
- System-level behavior
- Handling edge cases
- Usability

There is still a lot to build, and I'm treating reliability as an important part of the project.

**Status:** 🚧 Building

---

## 🎮 Minecraft Bot

### Completed & Hosted

This is one of my earlier projects, and one of the first projects where I took something from an experiment to a running system.

The bot is **currently hosted and running**.

Working on it taught me about things that are easy to miss when writing small programs:

- Minecraft APIs
- Automation
- Event-driven systems
- State management
- Server interaction
- Deployment
- Debugging
- Keeping a program running continuously

It started as:

> "Can I make a bot do this?"

and eventually became an actual hosted system.

**Status:** ✅ Completed & Hosted

---

## 🌐 ARGUS

### Autonomous Minecraft AI Agent

I also built **ARGUS**, a website for my Minecraft AI agent project.

**Website:** [argus-website-nu.vercel.app](https://argus-website-nu.vercel.app/)

ARGUS represents another part of what I'm interested in: software that can interact with an environment instead of only responding to a user.

---

## 🔧 What I'm Interested In

A lot of my projects end up sharing the same ideas.

I like software that can:

- Take information in
- Understand what is happening
- Make decisions
- Use tools
- Interact with other systems
- Recover when something fails
- Keep working without someone constantly watching it

That's probably why my projects have moved from Minecraft bots toward AI agents, research systems, and infrastructure.

I'm interested in the point where **software stops being just a collection of functions and starts behaving like a system.**

---

## 🧰 Things I'm Learning

I learn most of this by actually building projects.

Some of the areas I'm spending time on:

- Python
- AI / LLM systems
- Agents and automation
- APIs
- Backend development
- Web development
- Software architecture
- System design
- Security
- Privacy
- Testing
- Evaluation
- Open-source development

I don't consider myself an expert in all of these.

Some things I know well enough to build with. Other things I'm still figuring out.

That's one of the reasons I keep building projects instead of waiting until I "know enough."

---

## ⚙️ How I Build

I don't have a perfect process.

Usually it looks more like:

```text
Idea
 ↓
Build something
 ↓
It breaks
 ↓
Figure out why
 ↓
Fix it
 ↓
Find another problem
 ↓
Understand the system better
 ↓
Rebuild parts of it
```

I try to keep a few things consistent:

- Keep the code understandable
- Avoid unnecessary complexity
- Separate things that should be separate
- Test important behavior
- Think about failure cases
- Care about privacy and security
- Document things that future-me will forget

And if an approach is wrong, I'm okay with throwing it away and trying again.

---

## 📚 Learning Through Projects

Each project has taught me something different.

**Minecraft Bot** taught me about automation and keeping software running.

**AEGIS** is teaching me about Windows, system-level software, reliability, and security.

**Universal** is making me think about APIs, providers, fallbacks, and infrastructure.

**Cortex** is pushing me into AI systems, research planning, tool use, evaluation, and long-running workflows.

The projects are getting more complicated as I learn.

That's probably the most accurate description of what this GitHub is.

---

## 🌱 Open Source

A lot of the code here is still evolving.

You may find:

- Experiments
- Incomplete features
- Refactors
- Architectural changes
- Failed approaches
- Temporary solutions
- Things that I later decide to replace

I'm okay with that.

I'd rather keep the development process visible than make everything look finished when it isn't.

When something becomes stable enough to be useful, I'll document and clean it up.

---

## 🗺️ What's Next

My current focus is mainly on:

**Cortex → Universal → AEGIS**

while keeping the Minecraft project running.

There are plenty of other ideas I'd like to build, but I'm trying to get better at taking projects further instead of constantly starting new ones.

---

## 👋 A Little About This GitHub

I'm still a student, and this repository is basically my workshop.

Some projects work.

Some don't.

Some start small and become much bigger than I expected.

Some get completely rebuilt.

That's fine.

The interesting part for me is seeing what happens between:

> "I have an idea."

and

> "It's actually running."

---

**Still building. Still learning. Still breaking things.**
