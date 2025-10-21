---
title: Vibe Coding Workshop I
description: Building An Restaurant App with Claude Code
---

## Objective

The objective of this session is to experience how software can be built through
conversation; from reading a product requirement to producing a working
prototype with tests, and documentation all by collaborating with AI in natural
language.

# Phase-1: (Restaurant Discovery App)

Steps:

Download the PRD file from Box and save it to a new local folder — your {working
directory}. Review the PRD for the Restaurant Discovery App; take a few minutes
to familiarize yourself with its contents. Ask Claude to read the PRD:

- Open VS Code
- Go to File → Open Folder → {working directory}
- Drag and drop the PRD file into the folder

## Prompt 1: Read PRD

Send below prompt to Claude:

```
Open the restaurant discovery prd.md file in your current working directory to review the requirements for the Restaurant Discovery App.
```

Now that Claude has read the PRD, we’ll define how we’ll work together - this
ensures structure and discipline before we start coding.

## First, we need to create claude.md file, this is a file that will define how we will work together on this webapp.

Claude.md defines how humans and AI collaborate effectively - our rules of
engagement.

## Prompt 2: Create Claude.md

Send below prompt to Claude:

```
Hey Claude, let's put together a CLAUDE.md file that outlines our work in four clear phases: Planning, Validation, Execute and Verify. I do have a few constraints you need to be aware of:
- This whole setup should run locally - no SaaS tools, cloud deployments, no Docker, Postgres or Kubernetes.
- Let's stay light weight and self contained, something that is easy to run on a desktop.
- Make sure it follows OpenAPI specs and good software development practices.
- The project structure should be clean and easy to follow, both for humans and AI agents.
- Keep the writing tight and purposeful — short, clear, and not verbose.
```

Now that we have both PRD and rules for development out of the way, let's get to
action. We need a project structure for our webapp. Let's ask Claude to help us
with this.

## Prompt 3: Project Scaffold

Send below prompt to Claude:

```
Create a folder structure for my project.
```

Data gives life to our app — next, we’ll add realistic restaurants and menus so
the prototype feels real.

## Prompt 4: Seed Data and Images (Approx time: )

Send below prompt to Claude:

```
Seed the project with at least 10 restaurants, each with up to 5 menu items, cuisine type, ingredients, and an image representing the cuisine.
Reference images from unsplash as hyperlink for cuisine images.
```

## Prompt 5: Backend (Approx time: )

Send below prompt to Claude:

```
Next, let's create the backend that lists restaurants along with menu details.
```

The backend is ready — now let’s see how quickly Claude can build a usable web
interface on top of it.

## Prompt 6: Web Frontend (Approx time: )

Send below prompt to Claude:

```
Amazing! Let's build a usable, responsive and snappy Web UI on top of backend. Open the URL once the app is ready.
```

Take a moment to review the retaurant discovery app.

Now that the app is functional, let’s focus on validating its quality and
ensuring it meets our testing standards.

## Prompt 7: Quality

Send below prompt to Claude:

```
- I need unit tests for my code, go ahead.
- Generate an end-to-end test relating to selecting a restaurant and reviewing the menu item using Playwright.
- Run the test in headed mode, slow them down, and run them in slow motion so I can see them.
```

## Prompt 8: README.md

Send below prompt to Claude:

```
Based on the PRD and Code Base for a restaurant discovery app write a README.md. It should include Product Features, Usage, Testing and Troubleshooting
```

## Prompt 9: Diagrams (optional)

Send below prompt to Claude:

```
Finally, create SWE visual documentation including things like system diagram, API map, mermaid diagram.
```

Note : Diagram will require Mermaid Plugin to be installed in order to display
it is in VS Code. If you need to install it. Please use this
[Link](https://marketplace.visualstudio.com/items?itemName=bierner.markdown-mermaid).
