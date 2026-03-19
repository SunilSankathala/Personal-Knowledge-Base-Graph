# Knowledge Graph v3 - Assignment 1

A personal knowledge base graph viewer with cyberpunk neural aesthetic.

## How to Run

### Option 1: Direct Browser (Simplest)
Just double-click `knowledge-graph.html` and open it in Chrome or Firefox.

### Option 2: Local Server
```bash
npx serve .
# Then open http://localhost:3000
```

## Features
- Physics simulation — nodes repel/attract naturally
- Circular nodes with hex dot pattern and pulse animations
- Directed edges with curved arrows and relationship labels
- Animated particles travel along selected edges
- Star field background with parallax effect
- Scan line animation
- Full CRUD: add/edit/delete nodes and edges
- localStorage persistence (survives page refresh)
- Drag nodes to reposition and persist layout
- Sidebar: node list, edge list, add forms, inline editing
- Zoom in/out, fit-to-screen, scatter/reset layout
- Connected nodes highlighted on selection

## Tech Stack
- Vanilla HTML5 + CSS3 + JavaScript (Canvas API)
- Zero dependencies, no build step, open in browser directly

## Assignment Requirements Covered
- Graph view with directed edges and relationship labels
- Node click opens detail panel — edit title and note inline
- CRUD: add node, add edge, delete node (removes its edges), delete edge
- localStorage persistence
- Stretch goals: drag reposition, connected node highlight, physics animation

## File Structure
```
knowledge-graph.html   ← Complete app (open this)
README.md              ← This file
```

## Seed Data (pre-loaded)
Nodes: React, Next.js, TypeScript, State Mgmt, Component Design, Performance, Testing, CSS & Styling
Edges: built on, pairs with, uses, guides, improves, requires, styled with, impacts

## Author
Sunil — Internship Assignment, CloudMotiv IT Technologies
