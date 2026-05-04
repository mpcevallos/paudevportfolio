---
layout: ../../layouts/post.astro
title: PowerZone Gym Website Subscription App
description: PowerZone is a comprehensive platform that serves as both a gym information portal and an e-commerce application. Users can access information about gym locations and trainers, purchase training plans, and shop for fitness products online.
dateFormatted: Dec 31, 2024
---

![PowerZone Gym Website Subscription App](../../../public/assets/images/projects/powerzone-website.png)

> **Why is finding a gym and subscribing still so complicated in Latin America? That question was the starting point for PowerZone — a fitness web platform designed for young users who want to explore locations, meet trainers, and choose their plan without friction. I led the full UX/UI and contributed to frontend development within a team of five.**

### Project Overview

PowerZone was born from a simple observation: in the Latin American fitness market, the digital experience of gyms tends to fall far behind the physical experience they offer. Subscribing to a plan, finding the nearest location, or getting to know the trainers should be intuitive — and it rarely is.

---

### Role

UX/UI Lead · Frontend Developer · Team of 5

---

### User Persona

Young adults between 18 and 30 — digitally native, active, and expecting a seamless experience when choosing a gym and a plan. No patience for confusing flows or cluttered interfaces.

---

### Discovery & Research

Competitive analysis of the fitness market across Latin America to identify navigation patterns, subscription models, and usability gaps — no direct user interviews, but a clear picture of where existing platforms were failing their users.

---

### Design Process

Proposed the full visual system independently, validated it with the team in a consensus session, and ran 2 to 3 iteration rounds in Figma — from low-fidelity wireframes to a high-fidelity interactive prototype.

---

### Usability Iteration

The Subscription Plans section wasn't communicating the options clearly. Redesigned it from scratch to reduce cognitive load and make plan comparison feel effortless — the single change with the most impact on the overall experience.

---

### Design to Development Handoff

Contributed to frontend implementation using React, JavaScript, and Tailwind CSS — ensuring design consistency between the Figma prototype and the live product.

---

### Core Experience

- Competitive research across the Latin American fitness market
- User persona definition focused on young, digitally native users
- Full visual system proposed and executed independently
- Subscription Plans section redesigned for clarity and ease of decision-making
- Responsive UI built in Figma — from wireframes to final prototype
- Frontend implementation with React, JavaScript, and Tailwind CSS

---

### Figma Prototype

**Early prototype**

The first iteration focused on mapping the core user flows before any visual decisions were made. This phase covered the foundational design system — typography, color palette, buttons, and icons — alongside the key screens: homepage, hero section, CTA, gym locations, trainer profiles, and subscription plan browsing. Together, these established the structure, visual language, and navigation logic that would guide every decision moving forward.

<!-- Desktop: visible solo en pantallas >= 768px -->

<div style="display: none;" class="figma-desktop">
  <div style="position: relative; width: 100%; padding-bottom: 56.25%; height: 0; overflow: hidden;">
    <iframe
      style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; border: 1px solid rgba(0,0,0,0.1);"
      src="https://embed.figma.com/design/pl1FmD9aQCRQmASY08gO8w/PowerZone?node-id=0-1&embed-host=share"
      allowfullscreen
      loading="lazy"
    ></iframe>
  </div>
</div>

<!-- Mobile -->
<div class="figma-mobile">
  <img src="/assets/images/projects/home-first-iteration.png" style="width: 100%; border-radius: 8px;" />
  <a href="https://figma.com/proto/pl1FmD9aQCRQmASY08gO8w/" target="_blank"
     style="display: inline-block; margin-top: 12px; color: #a855f7; text-decoration: underline;">
  </a>
</div>

[Preview Prototype→](https://www.figma.com/design/pl1FmD9aQCRQmASY08gO8w/PowerZone?node-id=0-1&t=4bM2VAZhDih0UACy-1)

---

**Final Interactive Prototype**

After 2 to 3 iteration rounds — including a full redesign of the Subscription Plans section to reduce cognitive load — the design expanded to cover both desktop and mobile versions. Special attention was given to maintaining visual consistency and responsive behavior across breakpoints, ensuring the experience felt equally polished on every screen size. The final prototype reflects a complete, handoff-ready design system.

<!-- Desktop: visible solo en pantallas >= 768px -->

<div style="display: none;" class="figma-desktop">
  <div style="position: relative; width: 100%; padding-bottom: 56.25%; height: 0; overflow: hidden;">
   <iframe style="border: 1px solid rgba(0, 0, 0, 0.1);" width="800" height="450" src="https://embed.figma.com/design/u8mlRPtDkIS3321W3Ndei1/PowerZone---Gimnasios?node-id=4791-419&embed-host=share" allowfullscreen></iframe>
  </div>
</div>

<!-- Mobile -->

<div class="figma-mobile">
  <img src="/assets/images/projects/powerzone-home.png" style="width: 100%; border-radius: 8px;" />
  <a href="https://figma.com/proto/pl1FmD9aQCRQmASY08gO8w/" target="_blank"
     style="display: inline-block; margin-top: 12px; color: #a855f7; text-decoration: underline;">
  </a>
</div>

<style>
  @media (min-width: 768px) {
    .figma-desktop { display: block !important; }
    .figma-mobile { display: none; }
  }
</style>

[Preview Prototype→](https://www.figma.com/design/u8mlRPtDkIS3321W3Ndei1/PowerZone---Gimnasios?node-id=4463-3029&t=aV4P6klwCkE2Ei5R-1)
<br>
[Preview Interactive Prototype→](https://www.figma.com/proto/u8mlRPtDkIS3321W3Ndei1/PowerZone---Gimnasios?node-id=4463-5812&starting-point-node-id=4463%3A5812)

---

**Mobile-First**

Mobile-first was the foundation of every design decision in PowerZone. Building with Tailwind CSS made it natural to start from the smallest viewport and scale up — ensuring that browsing plans, exploring locations, and meeting trainers felt seamless on the device most users actually reach for.

<div class="powerzone-mobile">
  <img
    src="/assets/images/projects/powerzone-mobile-preview.png"
    style="width: 270px; border-radius: 8px; display: block; margin: 0 auto;"
  />
</div>

### Tech Stack

**Frontend**

- Design: Figma — wireframes, UI mockups, interactive prototype
- Framework: React + Node.js
- Styling: Tailwind CSS

[Frontend Git Repository →](https://github.com/mpcevallos/Frontend_gym2)

**Backend**

- Framework: Express.js
- Database: PostgreSQL
- Authentication: JWT (JSON Web Tokens)

[Backend Git Repository →](https://github.com/mpcevallos/Backend_gym)

---

### Value Delivered

A fully deployed frontend that solves the core fitness user journey: discover, compare, and subscribe. The visual system was designed from scratch, validated with the team, and refined based on real feedback — with people saying the platform made them actually want to sign up for a gym. The architecture is ready to scale toward active authentication and membership management once backend hosting is reinstated.

## Deployment

[Preview →](https://powerzonefitness.netlify.app/)
