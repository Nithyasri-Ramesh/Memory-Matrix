# 🌌 Flux Pairs: Memory Matrix

A high-performance, single-file arcade memory puzzle built using vanilla HTML5, pure CSS3, and ES6+ JavaScript. Moving away from traditional turn-based grids, **Flux Pairs** challenges your spatial mapping and memory capacity across a dynamic square matrix. Play solo against a modular imperfect AI engine or go head-to-head in offline multiplayer.

## 🎮 Game Features

- **Custom Match Targets ($M$):** Break the traditional pairs rhythm. Toggle your target objective between matching **2 (Pairs), 3 (Triplets), or 4 (Quads)** identical tiles to score.
- **Difficulty-Linked Matrix Sizing:** The perfect square grid dynamically adjusts to scale with your chosen threat level. Clear a compact $4\times4$ grid on Easy, or attempt to survive a massive, dense $10\times10$ system layout on Super Hard.
- **Simulated Cognitive AI Layers:** Battle against 4 distinct AI profiles built around a restricted memory coordinate buffer. Easy mode mimics human forgetfulness, while Super Hard tracks every cell reveal perfectly with mathematical precision.
- **Premium Cyber-Arcade UX:** Features fully custom hardware-accelerated 3D card flips, native responsive grid scaling (`min(85vw, 65vh)` container bounds), and a custom canvas confetti rendering engine.
- **Zero Asset Dependencies:** Powered entirely by an inline JavaScript **Web Audio API Synthesizer** that dynamically generates vintage retro sound design blips, clicks, and failure buzzes with zero external media loading.

## 🛠️ Technical Stack

- **Frontend Architecture:** Semantic HTML5, CSS Grid & Flexbox, CSS Custom Properties for real-time player theme variables.
- **State Management:** Modular, tightly scoped JavaScript (ES6+) with IIFE encapsulation to prevent global namespace pollution.
- **Asynchronous Logic:** Strict pointer-locking execution loops using `setTimeout` and conditional checking queues to block cheating or inputs during evaluation states.
