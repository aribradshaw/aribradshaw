<p align="center">
  <img src="./assets/twitter-header.jpg" alt="Phoenix skyline framed by desert mountains and saguaro cacti" width="100%" />
</p>

<h1 align="center">ARI BRADSHAW</h1>

<p align="center">
  <strong>Engineer · Musician · Consultant</strong><br />
  Phoenix, Arizona
</p>

I build software for organizing work, understanding complex systems, and making things people can use, play, or hear.

My work spans open-source tools, browser audio, campaign technology, and games. I'm interested in the whole product: how it works, how it feels, and what happens when people actually depend on it.

## Currently building: [Flow](https://github.com/aribradshaw/flow)

An open-source workspace that connects people, projects, timelines, delivery boards, and AI-agent organization.

Map the structure, plan the work, and track it through completion. Run locally without an account, or self-host with sign-in and private workspaces. AgentFlow maps agents, responsibilities, and workflows; external runners carry out the work.

[![Flow timeline with fictional projects and milestones](https://raw.githubusercontent.com/aribradshaw/flow/main/docs/media/timeline.png)](https://github.com/aribradshaw/flow)

**[Explore Flow](https://github.com/aribradshaw/flow)** · **[Self-hosting guide](https://github.com/aribradshaw/flow/blob/main/docs/self-hosting.md)** · **[Animated walkthrough](https://github.com/aribradshaw/flow/blob/main/docs/media/timeline-views.gif)**

Built by [Flygon LC](https://flygonlc.com). MIT-licensed.

## Selected work

### [Audio Browser Lab](https://aribradshaw.github.io/audio-browser-lab/)

Browser-audio forensics for the moments when the same file behaves differently across browsers. Inspect MP3 structure, compare playback clocks, investigate seeking, and export reproducible evidence. Includes a web lab, reusable packages, a CLI, and Howler and WaveSurfer integrations. Files selected in the web lab stay in your browser.

**[Open the lab](https://aribradshaw.github.io/audio-browser-lab/)** · **[Source](https://github.com/aribradshaw/audio-browser-lab)** · **[Howler case study](https://github.com/aribradshaw/audio-browser-lab/blob/main/docs/HOWLER-CASE-STUDY.md)**

### Open-source contributions

Merged upstream fixes in music and browser-audio software:

- **[WaveSurfer recording](https://github.com/katspaugh/wavesurfer.js/pull/4352):** keep paused time out of recording duration.
- **[WaveSurfer playback](https://github.com/katspaugh/wavesurfer.js/pull/4353):** make early media seeking reliable on WebKit.
- **[Verovio](https://github.com/rism-digital/verovio/pull/4434):** restore correct page lookup for timed score elements.

### [1976: Election Simulation](https://aribradshaw.github.io/1976/)

A playable Carter-Ford campaign strategy game. Manage scarce resources, navigate sourced historical decisions, and build a path to 270 electoral votes in a retro television interface. Seeded simulation, campaign strategy, and election-night results meet responsive browser-game design.

**[Play in your browser](https://aribradshaw.github.io/1976/)** · **[Source](https://github.com/aribradshaw/1976)**

### [The Forest Grows Back!](https://aribradshaw.itch.io/the-forest-grows-back)

A strategic incremental game about trees, taxes, and cosmic ambition, with original music and a mobile-friendly browser interface. **Ranked 2nd of 17 entries in [The Blank Jam](https://itch.io/jam/blank-jam-summer/results).**

### [Music and production](https://aribradshaw.music)

Releases, collaborations, engineering, production work, and music videos spanning independent artists and my own catalog.

## Bradshaw Versioning

**A calendar-based versioning convention I use across production projects.**

Bradshaw Versioning gives every production commit a permanent `YEAR.MONTH.UPDATE` identity, while recording compatibility and deployment status separately. A version tells you where the code belongs in the release history, not whether it is backward-compatible or successfully deployed. Retries keep the same source version; rollbacks preserve the original artifact's identity.

The convention builds on Calendar Versioning, with explicit rules for calendar boundaries, concurrent release coordination, failures, and recovery. It is actively used in production projects, not a replacement for every use of Semantic Versioning.

**[Read the specification](https://github.com/aribradshaw/devlog/blob/main/docs/bradshaw-versioning.md)** · **[Explore DevLog](https://github.com/aribradshaw/devlog)**, a headless TypeScript toolkit for release histories.

## Companies

**[Flygon LC](https://flygonlc.com)**  
Technology consulting, open-source tools, and internal systems

**[Sunbelt Solutions Consulting LLC](https://sunbeltsolutions.org)**  
Political strategy and campaign software

**Brickstone Studio LLC**  
Music, audio, and games

<p align="center">
  <sub>You can learn anything in this world by using the Socratic method and following cause-effect chains.</sub>
</p>
