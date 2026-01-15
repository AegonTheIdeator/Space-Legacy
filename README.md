🚀 Space-Legacy

Space-Legacy is a fast-paced, arcade-style space shoot ’em up built entirely in JavaScript, designed around a smart, addictive game-loop algorithm that dynamically balances challenge, reward, and player engagement.

⚡ Simple to play. Hard to master. Impossible to quit.
ou control a lone space fighter in hostile territory. Enemies spawn relentlessly, difficulty scales in real time, and survival depends on reaction speed, positioning, and decision-making.

Core mechanics:
Continuous enemy waves
Real-time difficulty scaling
Projectile-based combat
Score-driven progression
Instant feedback loop (kill → reward → escalate)

🧠 The Smart Game Loop (Core Innovation)
At the heart of Space-Legacy lies a well-structured game loop algorithm that ensures gameplay never feels static or predictable.
This loop runs continuously using browser-optimized rendering (requestAnimationFrame) for smooth, consistent gameplay.

⚙️ Adaptive Difficulty Algorithm

Unlike fixed-difficulty arcade shooters, Space-Legacy adapts in real time:

🔼 Enemy spawn rate increases with score
⚡ Enemy speed scales progressively
🎯 Player skill is indirectly measured through survival time
⏳ No hard levels → infinite progression model with progressive levels
The game subtly pushes the player to their limit without ever feeling unfair.

🧩 Architecture Highlights
Modular update functions (movement, collision, scoring)
Single-source game state management
Frame-rate independent motion
Minimal memory overhead
Clean separation of logic & rendering
The codebase is intentionally kept lightweight and readable, making it ideal for:
Learning game loops
Experimenting with mechanics
Extending into power-ups

🛠 Tech Stack
JavaScript 
HTML5 Canvas
requestAnimationFrame API
CSS
