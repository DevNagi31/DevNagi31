<h1 align="center">Dev Nagi</h1>
<p align="center"><i>Computer Science graduate student at Binghamton University, SUNY</i></p>
<p align="center">Open to software and machine learning engineering roles</p>

<hr>

### About

Most of what I build starts from the same annoyance: agent based systems tend to fail quietly. By the time you notice something is wrong, the actual cause is several tool calls and a couple of retries in the past, buried in a log nobody read. So a good chunk of my work is writing tools that make that failure visible again, plus a steady stream of full stack apps where I get to play with live systems: sockets, job queues, geospatial search, that kind of thing.

<hr>

### Agent tooling

**[Agent Autopsy](https://github.com/DevNagi31/agent-autopsy)**
A command line tool that inspects traces from AI agents and flags the failure patterns that usually go unnoticed: hallucinated steps, swallowed errors, tool call loops, contradictions, context that has gone stale. It parses output from LangChain, CrewAI, and the OpenAI SDK, has a watch mode for running agents, and produces HTML or JSON reports.

**[mcphub](https://github.com/DevNagi31/mcphub)**
A small research crew built on Anthropic's Model Context Protocol. A researcher, an analyst, a writer, and a fact checker pass a task down the line, each with its own set of tools, and the whole reasoning trace streams back to you as it happens.

**[Agent Debugger](https://github.com/DevNagi31/agent-debugger)**
A time travel debugger for agent loops. You can grab any tool call in a run, edit its input or output, and replay execution from that exact point rather than rerunning the whole session from the top.

**[Token Analysis](https://github.com/DevNagi31/token-analysis)**
A prompt cost optimizer and evaluation benchmark. It compresses prompts using both rule based methods and an LLM, then scores the result for semantic similarity against the original across ten different models, so you can tell whether you actually saved tokens or just broke the prompt.

### Full stack

**[devpulse](https://github.com/DevNagi31/devpulse)**
Developer analytics you can ask in plain English. It turns a question like "which reviews are slowing us down" into SQL for you, and runs that query through AST checks first, so a generated statement can never touch or drop anything it should not.

**[EventHub](https://github.com/DevNagi31/eventhub)**
An event discovery platform. Faktory handles the job queues, geospatial search runs on the Haversine formula, chat happens live over Socket.io, and Claude powers the recommendation layer. 15+ REST endpoints, Redis for caching, Postgres underneath.

**[LeetCode Arena](https://github.com/DevNagi31/leetcode-arena)**
A competitive LeetCode platform with live rankings, streak tracking, activity heatmaps, and university leaderboards. MERN stack, Socket.io for the live parts.

**[URL Shortener](https://github.com/DevNagi31/url-shortner)**
A link shortening service backed by Redis for caching and Postgres for persistence.

### Collaboration and data

**[syncpad](https://github.com/DevNagi31/syncpad)**
A collaborative Markdown editor that keeps working with no connection. Edits sync through Yjs CRDTs over server sent events and queue in IndexedDB while you are offline, and there are tests that prove two people typing at once end up in the same place.

**[pulselab](https://github.com/DevNagi31/pulselab)**
An experimentation platform for people who take A/B tests seriously. Always valid sequential testing so you can watch results without inflating false positives, CUPED to cut variance, sample ratio mismatch detection, and a Monte Carlo run that checks the math actually holds up.

**[Chess Toxicity Analysis](https://github.com/DevNagi31/chess-toxicity-analysis)**
An NLP project for CS 515 that ran more than 164,000 posts from Reddit and 4chan through Google's Perspective API to measure toxicity patterns in chess adjacent discourse. Results sit behind a Flask dashboard backed by Postgres.

### Interactive

**[BU Campus Map](https://github.com/DevNagi31/BU-Map)**
An interactive 3D map of the Binghamton University campus. 115 buildings, more than 700 searchable rooms, GPS navigation, and info on parking, dining, and bus routes, all built on MapLibre GL JS.

<hr>

### Tools I reach for

<p align="left">
<img src="https://skillicons.dev/icons?i=py,ts,js,java,cpp,dart,react,nextjs,tailwind,nodejs,express,flask,postgres,mongodb,redis,docker,aws,git,githubactions" alt="tech icons" />
</p>

<hr>

<p align="center">
<a href="https://linkedin.com/in/dev-nagi31"><img src="https://skillicons.dev/icons?i=linkedin" alt="LinkedIn" height="40" /></a> &nbsp;
<a href="https://dev-portfolio-murex-five.vercel.app/"><img src="https://skillicons.dev/icons?i=vercel" alt="Portfolio" height="40" /></a> &nbsp;
<a href="mailto:dnagi@binghamton.edu"><img src="https://skillicons.dev/icons?i=gmail" alt="Email" height="40" /></a>
</p>
