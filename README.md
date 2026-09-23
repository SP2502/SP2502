# Hi, I'm Shreyansh 👋

I'm a Class 11 student who likes building things and figuring out how they work.

Most of my projects start with a question, an idea, or a problem I don't fully understand.

I usually learn by building the first version, seeing what breaks, understanding why it broke, and then trying to make the next version better.

I'm currently building **Universal**, an infrastructure layer for weather data, while also working on **Cortex**, an open deep-research system, and **AEGIS**, a Windows content blocker.

I also built **ARGUS**, a Minecraft bot and AI system that is already hosted and running.

### 🌐 Website

**[sp2502.github.io/Me](https://sp2502.github.io/Me/)**

---

## 🚀 Projects

| Project | What it is | Status |
|---|---|---|
| **Universal** | Weather-data infrastructure | 🧪 Early development |
| **Cortex** | Open deep-research system | 🚧 Building |
| **AEGIS** | Free Windows content blocker | 🚧 Building |
| **ARGUS** | Autonomous Minecraft bot & AI system | ✅ Hosted & running |

These aren't just projects I want to finish.

They're also how I learn.

---

# 🌍 Universal

### Weather data without provider-specific complexity

**Universal** is a weather-data infrastructure project.

The idea is simple:

> An application should not have to care which weather provider is working underneath it.

A developer provides coordinates, and Universal handles the rest.

```text
Latitude + Longitude
        ↓
Location Resolution
        ↓
Provider Selection
        ↓
Best Available Provider
        ↓
Fallback if needed
        ↓
Data Normalization
        ↓
Universal API
        ↓
Application
```

Universal is designed around multiple weather providers instead of depending completely on one source.

The system is being built to handle things like:

- Coordinate-based location resolution
- Multiple weather providers
- Provider selection
- Provider fallbacks
- Data normalization
- Consistent API responses
- Provider abstraction
- Reliability when individual providers fail

The main thing I'm exploring is the infrastructure layer between an application and the services providing its weather data.

Instead of making every application understand every provider, Universal tries to provide one consistent interface.

I'm still refining the architecture and figuring out which parts actually need to be abstracted.

**Status:** 🧪 Early development

---

# 🧠 Cortex

### Open Deep Research

**Cortex** is an open-source deep-research system I'm building around a simple question:

> What would a research system look like if it had to actually work through a difficult question instead of producing one quick answer?

The goal is for Cortex to take a complex question, determine what needs to be researched, gather information, compare evidence, and produce structured research.

The general workflow looks like:

```text
Question
   ↓
Understand the problem
   ↓
Break it into research tasks
   ↓
Create a research plan
   ↓
Search & gather information
   ↓
Collect evidence
   ↓
Compare sources
   ↓
Reason over the evidence
   ↓
Synthesize findings
   ↓
Final research
```

Some of the areas I'm working on include:

- Research planning
- Task decomposition
- Multi-step research
- Search and information gathering
- Evidence collection
- Source comparison
- Evidence-based reasoning
- Structured research output
- Tool use
- Multiple AI models
- Long-running research
- Failure recovery
- Evaluation

I'm particularly interested in what happens when things go wrong.

Real research systems have to deal with:

- Bad sources
- Conflicting information
- Search failures
- Tool failures
- Incomplete results
- Incorrect assumptions
- Prompt injection
- Models making mistakes
- Research tasks taking much longer than expected

Cortex is still changing as I experiment with different architectures.

I'm not trying to make the architecture look finished before I understand it.

**Status:** 🚧 Active development

---

# 🛡️ AEGIS

### Free Windows Content Blocker

**AEGIS** is a free Windows application I'm building to block unwanted and adult content.

The goal is to make it a practical desktop application rather than just a proof-of-concept filter.

I'm exploring areas such as:

- Content blocking
- Windows integration
- Privacy
- Security
- Reliability
- Performance
- System-level behavior
- Edge cases
- Usability

The Windows version is the current focus.

Android support is planned for a later stage.

A large part of the project is figuring out how to make the system reliable enough to run on a normal computer without constantly getting in the user's way.

**Status:** 🚧 Building

---

# 🎮 ARGUS

### Autonomous Minecraft Bot & AI System

**ARGUS** started as an experiment to see how far I could take Minecraft automation.

It eventually became a hosted, continuously running system.

```text
Observe
   ↓
Understand state
   ↓
Decide
   ↓
Act
   ↓
Observe again
```

Working on ARGUS taught me about things that don't always appear when writing small programs:

- Minecraft APIs
- Automation
- Event-driven systems
- State management
- Server interaction
- Long-running processes
- Deployment
- Debugging
- Reliability

The interesting part wasn't just making the bot perform an action.

It was keeping the entire system running and figuring out what happens when the environment behaves differently from what the program expected.

### 🌐 ARGUS Website

**[argus-website-nu.vercel.app](https://argus-website-nu.vercel.app/)**

**Status:** ✅ Hosted & running

---

# 🔧 What I'm Interested In

A lot of my projects eventually lead back to the same ideas.

I'm interested in software that can:

- Take information in
- Understand its environment
- Make decisions
- Use tools
- Interact with other systems
- Handle unexpected situations
- Recover from failures
- Continue working without constant supervision

That's probably why my projects have gradually moved from Minecraft automation toward AI systems, infrastructure, and autonomous software.

I'm especially interested in the point where:

> **software stops being just a collection of functions and starts becoming a system.**

---

# 🧰 What I'm Learning

I learn most of these things by actually using them in projects.

### Languages

- Python
- Go
- Java
- HTML / CSS
- JavaScript

### Frameworks & Runtime

- Node.js
- React

### Areas I'm exploring

- AI / LLM systems
- AI agents
- Automation
- APIs
- Backend development
- Software architecture
- System design
- Security
- Privacy
- Testing
- Evaluation
- Open-source development

I don't consider myself an expert in all of these.

Some are tools I already use regularly.

Some are things I'm still learning.

And some are things I only understand because a project forced me to figure them out.

That's how I prefer learning.

---

# ⚙️ How I Build

I don't have a perfect development process.

Usually it looks something like this:

```text
Question
   ↓
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
   ↓
Repeat
```

A few things I try to keep consistent:

- Keep the code understandable
- Avoid complexity without a reason
- Separate things that should be separate
- Test important behavior
- Think about failure cases
- Care about privacy and security
- Document things future-me will forget
- Replace bad approaches instead of protecting them

Sometimes the correct solution is to throw away what I built and start again.

That's part of building.

---

# 📚 Learning Through Projects

Each project has pushed me into a different area.

### ARGUS

Taught me about:

**automation → APIs → events → state → deployment → long-running systems**

### AEGIS

Is teaching me about:

**Windows → system integration → reliability → security → privacy**

### Universal

Is pushing me toward:

**APIs → infrastructure → provider abstraction → fallbacks → data normalization**

### Cortex

Is pushing me toward:

**AI systems → research planning → tool use → evidence → evaluation → autonomous workflows**

The projects are getting more complicated as I learn.

That's probably the simplest description of this GitHub.

---

# 🌱 Open Source

A lot of the code here is still evolving.

You may find:

- Experiments
- Incomplete features
- Refactors
- Architectural changes
- Failed approaches
- Temporary solutions
- Code that I later replace

I'm okay with that.

I'd rather show how a project is actually developing than make everything look finished when it isn't.

When something becomes stable enough to be useful, I'll document it and clean it up.

---

# 🎯 Current Focus

Right now, most of my attention is going toward:

### 01 — Universal

Refining the architecture and figuring out how a reliable weather-data layer should work.

### 02 — Cortex

Building the architecture behind an open deep-research system.

### 03 — AEGIS

Developing the Windows version and working on reliability, privacy, and system integration.

### 04 — ARGUS

Keeping the hosted Minecraft system running and continuing to experiment with it.

I'm also learning more about current AI systems through courses, experiments, and projects.

---

# 🗺️ What's Next

There are always more ideas I want to build.

I'm trying to get better at something more important:

**taking projects further instead of constantly starting new ones.**

I'd rather have a few systems that I understand deeply than a huge list of unfinished ideas.

---

# 👨‍💻 A Little About Me

I'm a Class 11 student interested in:

- AI
- Software systems
- Algorithms
- Backend development
- Infrastructure
- Automation
- Engineering

Outside programming, I enjoy **flying drones** and **playing badminton**.

I'm particularly interested in drones and would like to work in the drone industry in the future.

---

# 🧪 This GitHub Is Basically My Workshop

Some projects work.

Some don't.

Some start small and become much bigger than expected.

Some get completely rebuilt.

Some ideas turn out to be bad.

That's fine.

The interesting part for me is what happens between:

```text
"I have an idea."
        ↓
"I built something."
        ↓
"It doesn't work."
        ↓
"Now I understand why."
        ↓
"Let's build it again."
        ↓
"It's actually running."
```

That's what most of the code here represents.

Not finished products.

Not perfect projects.

Just things I'm building to understand how systems work.

---

## 🌐 Find Me

**Website:**  
[sp2502.github.io/Me](https://sp2502.github.io/Me/)

**GitHub:**  
[github.com/SP2502](https://github.com/SP2502)

**ARGUS:**  
[argus-website-nu.vercel.app](https://argus-website-nu.vercel.app/)

**Email:**  
[shreyansh2502@outlook.com](mailto:shreyansh2502@outlook.com)

---

> **Build. Break. Understand. Improve.**

Still building. Still learning. Still figuring things out.
