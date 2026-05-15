# Heliox OS Daemon

This is the backend system for Heliox OS.

It’s basically the part that runs in the background and actually makes things happen — planning tasks, executing them, checking results, and talking to the UI.

The idea is to build a modular AI system that can break down problems and handle them step by step instead of just being a chatbot.

---

## What this is trying to do

Heliox OS is built around a simple agent loop:

- **Planner** → figures out what needs to be done  
- **Executor** → runs the actual steps  
- **Verifier** → checks if things worked properly  
- **Sanitizer** → makes sure nothing unsafe or broken gets executed  

There’s also a frontend UI (Tauri-based) that connects to all of this.

---

## Requirements

Before you start, make sure you have:

- Python 3.10 or above  
- Node.js + npm  
- Git  

That’s pretty much it.

---

## Getting started

Clone the repo first:

```bash
git clone https://github.com/VyomKulshrestha/Heliox-OS.git
cd Heliox-OS