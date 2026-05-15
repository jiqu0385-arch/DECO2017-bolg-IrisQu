---
title: My-fifth-blog
date: 2026-05-08
author: Jingru Qu
summary: This week focuses on developing the Liminal anonymous chat prototype using HTML, CSS, and JavaScript, refining user flow, visual style, and interaction design to move from wireframe and system structure into a functional website.
tags:
  - UI design
  - interaction
---
### Introduction
This week focuses on turning the wireframe and system planning into a working prototype. Instead of only analysing structure through DDD and ERD, the project now starts to focus on how the interface actually behaves when users interact with it. The transition from design to implementation reflects constraint-driven decision making.The main goal is to build a usable version of the Liminal anonymous chat website with basic navigation, interaction, and visual style.

---
### Core Function Development

This week, we used HTML, CSS, and JavaScript to start building the actual working prototype of the Liminal anonymous chat system. The focus was on making sure the basic structure of the website can run, and that users can move between pages smoothly.
This helped turn earlier ideas and diagrams into something that can actually be used and tested.

---
### Navigation and User Flow Restructure

We reorganised the navigation logic to make the user flow clearer. The updated flow now goes from the welcome page to the room selection page, where users can choose to join a room, create a room, or enter randomly.
Before this step, the page connections felt a bit separated, but now the flow is more direct and easier to follow.

---
### Room Selection Page Redesign

We changed the room selection page layout from a simple vertical list into a card-based layout. Each room is displayed as a visual card with a background image and title, similar to Pinterest-style browsing.
This made the page feel more visual and easier to explore, instead of just reading text options.Floating action and card-based design improve usability but reduce feature discoverability and accessibility.

---
### Interaction Design Improvement

We added a floating “+” button to handle main actions like creating a room or joining randomly. When clicked, it expands into options.
This keeps the interface clean while still making important actions easy to access. It also reduces clutter on the main screen.

---
### Visual Style Refinement

We refined the visual style by using gradient backgrounds and soft glow effects instead of flat bright colours. The goal was to create a more “liminal space” feeling that feels quiet, floating, and slightly surreal.
We also adjusted card transparency and blur effects to make the interface feel more layered and less solid, which matches the anonymous atmosphere of the system.

---
### Technical Interaction Implementation

We used JavaScript to handle page switching, room selection, and floating menu interactions. Local storage was also used to temporarily store room data during development.
This helped simulate how users move through the system even before a full backend is implemented.

---
### Reflection
This week helped connect design ideas with actual implementation. Instead of only planning how the system should work, we started building a version that can be interacted with.

The next step will focus on improving the chat interface, refining responsive design for different screen sizes, and gradually connecting the prototype with the earlier DDD and ERD structure so that the system becomes more consistent and complete.
