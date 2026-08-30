# 🌌 Hanna Universe ❤️

> **A little universe made for Hanna.**

**Hanna Universe** is a cinematic, interactive romantic web experience built from scratch with HTML, CSS and Vanilla JavaScript.

It isn't just a webpage.

It's a tiny universe filled with stars, memories, letters, hidden messages, interactive elements, puzzles, music, flowers, secrets, and a few things that are intentionally waiting to be discovered.

Made by **Erfan (Blaydrax)**, especially for **Hanna**. ❤️

---

## ✨ What is Hanna Universe?

The project is designed as a journey rather than a traditional website.

The visitor moves through different sections of a fictional little universe, discovering new interactions along the way.

Every section has its own atmosphere and purpose, from the cinematic opening sequence to the final hidden surprise.

The goal is simple:

> **Make Hanna open the website and think:**
> *"Wow... Erfan really loves me."* ❤️

---

# 🌠 Features

## 🎬 Cinematic Intro

The experience begins with a full-screen cinematic introduction.

* Animated meteor impact
* Fade-in storytelling
* Atmospheric lighting
* Cinematic typography
* Animated transition into the main universe
* Personalized welcome message

The intro automatically transitions into the main experience.

---

## 🌌 Animated Universe

The main environment includes a dynamic night-sky atmosphere.

* Procedurally generated stars
* Twinkling star animations
* Animated nebula
* Floating atmospheric effects
* Responsive cosmic background
* Moon with glow and crater details

The star field is rendered dynamically using the **HTML Canvas API**.

---

## 🌙 Interactive Moon

The moon isn't just decoration.

It can be:

* Clicked
* Dragged around the screen
* Interacted with multiple times

Repeated interaction with the moon triggers a hidden response.

Because apparently even the moon needed to participate in this relationship.

---

## ❤️ Interactive Heart

The central heart is interactive.

Clicking it triggers:

* Falling hearts
* Particle-like effects
* Personalized messages
* Additional visual feedback

Rapidly interacting with the heart also unlocks one of the project's hidden Easter Eggs.

---

# 💌 Interactive Love Letters

The website contains multiple letters.

## First Letter

A physical-looking envelope opens when clicked.

Inside is a personalized letter written specifically for Hanna.

The envelope uses:

* 3D perspective
* CSS transforms
* Animated flap
* Layered paper
* Glassmorphism
* Responsive layout

Opening the letter also triggers additional visual effects.

---

## 🔐 Second Secret Letter

There is another letter hidden behind an unlock system.

To access it, the visitor must:

1. Find the hidden constellation message
2. Open the first letter
3. Interact with the moon
4. Enter the secret word:

```text
HANNA
```

Once everything is completed, the second letter is revealed.

The second letter revolves around the symbolism of a flower and contains another personal message.

---

# ✨ Reasons Section

A collection of animated cards explaining different reasons why Hanna is special.

Each card contains:

* Custom icon
* Title
* Personalized message
* Glassmorphism styling
* Scroll-triggered animation

Cards appear progressively as they enter the viewport.

---

# 🌠 Constellation Memories

A dedicated constellation contains several interactive stars.

Each star contains a hidden message.

Clicking a star reveals its message through the site's notification system and triggers additional particle effects.

The constellation includes:

* Multiple orbital rings
* Interactive stars
* Central heart
* Hidden messages
* Animated cosmic styling

One of the messages even contains a little identity twist hidden inside the universe.

---

# 📜 The Confession Timeline

The website includes a chronological storytelling section.

It presents important moments as a cosmic timeline, including:

* The confession
* The reason behind the feelings
* The emotional meaning of the relationship

The timeline is responsive and automatically changes layout on smaller screens.

---

# 🧩 Interactive Heart Puzzle

A small 3×3 puzzle is hidden inside the experience.

The player swaps pieces by clicking two tiles.

The goal is to restore the correct cosmic arrangement:

```text
🌙 🌙 🌙
❤️ ❤️ ❤️
🚀 🚀 🚀
```

Once solved, a full-screen success scene appears with:

* 💋 animation
* Falling hearts
* A personalized message
* Additional interaction

A hint is intentionally provided for anyone who decides that solving a 3×3 puzzle is somehow an unreasonable demand.

---

# 🌸 Visual Memory Capsule

The project also contains a small visual memory experience.

A central polaroid-style card sits inside an animated orbital environment.

It includes:

* Rotating orbital ring
* Floating planets
* Moon
* Flowers
* Stars
* Interactive polaroid

Clicking the image changes its appearance and reveals another message.

---

# 🌷 Interactive Garden

The garden starts empty.

As the visitor reaches the section, flowers gradually grow from the ground.

The animation includes:

* Multiple flowers
* Different growth timings
* Glowing petals
* Animated stems
* Personalized `Hanna` typography

The result is a small visual metaphor:

> Even empty space can bloom.

---

# 🌌 Easter Eggs

The website contains multiple hidden interactions.

### ⌨️ Keyboard Easter Egg

Typing:

```text
HANNA
```

in sequence unlocks a hidden full-screen message.

---

### ❤️ Heart Easter Egg

Rapidly pressing the main heart several times also unlocks the hidden Easter Egg.

The secret scene contains:

* Hidden message
* Animated heart
* Falling particles
* Special overlay

---

### 🌙 Moon Interaction

Interacting with the moon multiple times triggers a special hidden response.

---

### ✦ Wish Star

A tiny star near the end of the journey can be clicked to trigger a hidden wish message and additional star particles.

---

# 💍 Final Surprise

After reaching the end of the website, the visitor encounters the final gate.

Clicking it reveals a completely different full-screen experience.

The final scene contains:

* A glowing ring
* Animated cosmic background
* A final personal message
* Atmospheric typography
* Star and heart particles
* Return-to-stars button

The intention isn't to create a traditional ending.

It's meant to feel like the final page of a little story.

---

# 🎵 Music System

The website includes a built-in music player.

Place the music file next to `index.html`:

```text
music.mp3
```

The player provides:

* Play / pause control
* Persistent looping
* Visual equalizer
* Animated audio bars
* Mobile-friendly controls

The site also displays a visualizer that reacts while music is playing.

---

# 📱 Mobile Experience

The project is designed with mobile devices in mind.

It includes responsive layouts for:

* 📱 Phones
* 📲 Tablets
* 💻 Desktop
* 🖥️ Large displays

Mobile-specific improvements include:

* Responsive typography
* Smaller envelope layout
* Mobile constellation
* Touch-friendly controls
* Responsive puzzle
* Adaptive timeline
* Reduced spacing on small screens

The project also disables unwanted horizontal overscroll and mobile tap highlighting for a cleaner app-like experience.

---

# 📲 Progressive Web App

The project includes the foundations of a **Progressive Web App (PWA)**.

It uses:

* `manifest.json`
* `Service Worker`
* Cache Storage API
* Offline fallback
* Installable web-app metadata

The Service Worker caches the main project assets and attempts to provide the cached `index.html` when network access is unavailable.

---

# ⚡ Technologies

The project intentionally avoids large frameworks.

### Core

* HTML5
* CSS3
* Vanilla JavaScript

### APIs & Browser Features

* Canvas API
* Intersection Observer API
* Pointer Events API
* Service Worker API
* Cache Storage API
* Web Audio / HTML Audio
* CSS Animations
* CSS 3D Transforms

### External Resources

The typography uses Google Fonts:

* Cinzel
* Great Vibes
* Montserrat

---

# 📂 Project Structure

```text
Hanna-Universe/
│
├── index.html
├── music.mp3
├── manifest.json
├── sw.js
└── README.md
```

### `index.html`

Contains the entire main experience:

* HTML structure
* CSS styling
* Animations
* Canvas star system
* Interactive components
* Puzzle logic
* Easter Eggs
* Music player
* Final surprise
* PWA registration

### `sw.js`

Service Worker responsible for:

* Caching assets
* Offline fallback
* Updating cached resources
* Serving cached content when necessary

### `manifest.json`

PWA metadata used by supported browsers to describe the web application.

### `music.mp3`

Optional local soundtrack used by the built-in music player.

---

# 🚀 Running Locally

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/hanna-universe.git
```

Open the project directory:

```bash
cd hanna-universe
```

Because the project uses a Service Worker, it is recommended to run it through a local web server rather than opening the HTML file directly.

For example, with Python:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

---

# 🌐 Deploying

The project can be hosted using services such as:

* GitHub Pages
* Netlify
* Vercel
* Any static web server

Since the project is entirely client-side, no backend is required.

---

# 🎨 Design Philosophy

The visual design is built around a few ideas:

**Cosmic**
The entire website represents a small universe.

**Personal**
Almost every major interaction contains something specifically written for Hanna.

**Cinematic**
Large typography, glow effects, transitions and layered backgrounds create a story-like experience.

**Interactive**
The visitor isn't supposed to simply scroll.

They are supposed to explore.

**Hidden**
Some of the most personal parts of the website are intentionally hidden behind interactions.

---

# 🔒 No Backend

The project does not require:

* Database
* API
* Backend server
* User accounts
* Authentication

Everything happens directly in the browser.

---

# ❤️ The Story Behind It

This project started with a simple idea:

> What if instead of sending someone a normal message, you built them an entire universe?

So that's what happened.

A simple HTML page slowly became:

* a cinematic introduction
* a constellation
* multiple letters
* a puzzle
* a garden
* hidden messages
* Easter Eggs
* music
* a PWA
* and an unnecessarily dramatic final surprise

Because apparently saying **"I love you"** normally wasn't enough.

---

# 👤 Credits

### Made by

**Erfan — Blaydrax**

### Made for

**Hanna ❤️**

---

# 🌙 Final Note

This isn't meant to be the biggest website on the internet.

It isn't meant to demonstrate some revolutionary framework.

It exists for one much simpler reason:

> **To turn a feeling into something you can actually explore.**

A tiny universe.

Made for one person.

**Hanna. ❤️**

---

<p align="center">
  <i>Somewhere in an infinite universe, there is one little corner that belongs to you.</i>
</p>

<p align="center">
  🌙 ✦ ❤️ ✦ 🌸 ✦ 🪐
</p>
