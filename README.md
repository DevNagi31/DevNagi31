<h1 align="center">Dev Nagi</h1>
<p align="center"><i>Computer Science graduate student at Binghamton University, SUNY</i></p>
<p align="center">Open to software and machine learning engineering roles</p>
<p align="center">I build agent tooling and full stack systems, and I care most about making them measurable.</p>

<p align="center">
<a href="https://portfolio-sandy-pi-24.vercel.app/"><b>Portfolio and Resume ↗</b></a>
</p>

<hr>

### About

Most of what I build starts from the same annoyance: agent based systems tend to fail quietly. By the time you notice something is wrong, the actual cause is several tool calls and a couple of retries in the past, buried in a log nobody read. So a good chunk of my work is writing tools that make that failure visible again, plus a steady stream of full stack apps where I get to play with live systems: sockets, job queues, geospatial search, that kind of thing.

<hr>


### Agent tooling

<table>
<tr>
<td width="50%">
<a href="https://github.com/DevNagi31/agent-autopsy"><img src="assets/agent-autopsy.svg" alt="Agent Autopsy"/></a>
<br/>
<b><a href="https://github.com/DevNagi31/agent-autopsy">Agent Autopsy</a></b><br/>
Inspects AI agent traces and flags the failures that go unnoticed: hallucinated steps, swallowed errors, tool call loops, stale context. Parses LangChain, CrewAI, and OpenAI SDK output.
<br/><br/>
<code>Python</code>
</td>
<td width="50%">
<a href="https://github.com/DevNagi31/mcphub"><img src="assets/mcphub.svg" alt="mcphub"/></a>
<br/>
<b><a href="https://github.com/DevNagi31/mcphub">mcphub</a></b><br/>
A research crew on Anthropic's Model Context Protocol. Researcher, analyst, writer, and fact checker pass a task down the line, each with its own tools, and the reasoning trace streams back live.
<br/><br/>
<code>TypeScript</code>
</td>
</tr>
<tr>
<td width="50%">
<a href="https://github.com/DevNagi31/agent-debugger"><img src="assets/agent-debugger.svg" alt="Agent Debugger"/></a>
<br/>
<b><a href="https://github.com/DevNagi31/agent-debugger">Agent Debugger</a></b><br/>
A time travel debugger for agent loops. Grab any tool call in a run, edit its input or output, and replay execution from that exact point instead of rerunning the whole session.
<br/><br/>
<code>TypeScript</code>
</td>
<td width="50%">
<a href="https://github.com/DevNagi31/token-analysis"><img src="assets/token-analysis.svg" alt="Token Analysis"/></a>
<br/>
<b><a href="https://github.com/DevNagi31/token-analysis">Token Analysis</a></b><br/>
A prompt cost optimizer and eval benchmark. Compresses prompts with rule based methods and an LLM, then scores semantic similarity against the original across ten models.
<br/><br/>
<code>TypeScript</code>
</td>
</tr>
</table>


### Full stack

<table>
<tr>
<td width="50%">
<a href="https://github.com/DevNagi31/devpulse"><img src="assets/devpulse.svg" alt="devpulse"/></a>
<br/>
<b><a href="https://github.com/DevNagi31/devpulse">devpulse</a></b><br/>
Developer analytics you can ask in plain English. Turns a question into SQL and runs it through AST checks first, so a generated statement can never touch anything it should not.
<br/><br/>
<code>TypeScript</code> &nbsp;·&nbsp; <a href="https://devpulse-orpin-five.vercel.app">Live demo ↗</a>
</td>
<td width="50%">
<a href="https://github.com/DevNagi31/eventhub"><img src="assets/eventhub.svg" alt="EventHub"/></a>
<br/>
<b><a href="https://github.com/DevNagi31/eventhub">EventHub</a></b><br/>
An event discovery platform. Faktory job queues, Haversine geospatial search, live chat over Socket.io, and a Claude recommendation layer. 15+ REST endpoints, Redis, Postgres.
<br/><br/>
<code>JavaScript</code>
</td>
</tr>
<tr>
<td width="50%">
<a href="https://github.com/DevNagi31/leetcode-arena"><img src="assets/leetcode-arena.svg" alt="LeetCode Arena"/></a>
<br/>
<b><a href="https://github.com/DevNagi31/leetcode-arena">LeetCode Arena</a></b><br/>
A competitive LeetCode platform with live rankings, streak tracking, activity heatmaps, and university leaderboards. MERN stack, Socket.io for the live parts.
<br/><br/>
<code>JavaScript</code> &nbsp;·&nbsp; <a href="https://leetcode-arena-seven.vercel.app">Live demo ↗</a>
</td>
<td width="50%">
<a href="https://github.com/DevNagi31/url-shortner"><img src="assets/url-shortner.svg" alt="URL Shortener"/></a>
<br/>
<b><a href="https://github.com/DevNagi31/url-shortner">URL Shortener</a></b><br/>
A link shortening service backed by Redis for caching and Postgres for persistence.
<br/><br/>
<code>Redis · Postgres</code>
</td>
</tr>
</table>


### Collaboration and data

<table>
<tr>
<td width="50%">
<a href="https://github.com/DevNagi31/syncpad"><img src="assets/syncpad.svg" alt="syncpad"/></a>
<br/>
<b><a href="https://github.com/DevNagi31/syncpad">syncpad</a></b><br/>
A collaborative Markdown editor that keeps working with no connection. Edits sync through Yjs CRDTs over server sent events and queue in IndexedDB while you are offline.
<br/><br/>
<code>TypeScript</code> &nbsp;·&nbsp; <a href="https://syncpad-delta.vercel.app">Live demo ↗</a>
</td>
<td width="50%">
<a href="https://github.com/DevNagi31/pulselab"><img src="assets/pulselab.svg" alt="pulselab"/></a>
<br/>
<b><a href="https://github.com/DevNagi31/pulselab">pulselab</a></b><br/>
An experimentation platform for people who take A/B tests seriously. Always valid sequential testing, CUPED variance reduction, sample ratio mismatch detection, and a Monte Carlo proof.
<br/><br/>
<code>Python</code>
</td>
</tr>
<tr>
<td width="50%">
<a href="https://github.com/DevNagi31/chess-toxicity-analysis"><img src="assets/chess-toxicity-analysis.svg" alt="Chess Toxicity Analysis"/></a>
<br/>
<b><a href="https://github.com/DevNagi31/chess-toxicity-analysis">Chess Toxicity Analysis</a></b><br/>
An NLP project that ran 164,000+ posts from Reddit and 4chan through Google's Perspective API to measure toxicity in chess adjacent discourse. Flask dashboard, Postgres.
<br/><br/>
<code>Python</code>
</td>
<td width="50%">
<a href="https://github.com/DevNagi31/BU-Map"><img src="assets/BU-Map.svg" alt="BU Campus Map"/></a>
<br/>
<b><a href="https://github.com/DevNagi31/BU-Map">BU Campus Map</a></b><br/>
An interactive 3D map of the Binghamton University campus. 115 buildings, 700+ searchable rooms, GPS navigation, plus parking, dining, and bus routes on MapLibre GL JS.
<br/><br/>
<code>JavaScript</code>
</td>
</tr>
</table>


<hr>

### Tools I reach for

<p align="left">
<img src="https://skillicons.dev/icons?i=py,ts,js,java,cpp,dart,react,nextjs,tailwind,nodejs,express,flask,postgres,mongodb,redis,docker,aws,git,githubactions" alt="tech icons" />
</p>

<hr>

<p align="center">
<a href="https://linkedin.com/in/dev-nagi31"><img src="https://skillicons.dev/icons?i=linkedin" alt="LinkedIn" height="40" /></a> &nbsp;
<a href="https://portfolio-sandy-pi-24.vercel.app/"><img src="https://skillicons.dev/icons?i=vercel" alt="Portfolio" height="40" /></a> &nbsp;
<a href="mailto:dnagi@binghamton.edu"><img src="https://skillicons.dev/icons?i=gmail" alt="Email" height="40" /></a>
</p>
