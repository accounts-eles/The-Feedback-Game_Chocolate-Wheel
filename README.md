🎡 The Feedback Game Template

An interactive, gamified reflection tool designed to facilitate debriefing sessions and project reviews. The Feedback Game uses a randomized wheel-spin mechanic to prompt players with critical thinking questions, making professional or educational reflection an engaging team activity.

🚀 Live Demo

Explore The Feedback Game Here

✨ Project Overview

The Feedback Game is optimized for group environments where structured reflection is required. It transforms traditional "lessons learned" meetings into a competitive yet collaborative game where participants earn points for insightful responses.

Key Features

Dynamic Setup Interface: A dedicated setup screen allowing teams to add/remove players before commencing the game.

Weighted Spin Wheel: A custom-rendered HTML5 Canvas wheel featuring 12 segments:

Reflection Prompts: Focused on goals, challenges, perspectives, and future applications.

Special Segments: "Spin Again" and "Skip Turn" to add unpredictability and excitement.

Integrated Scoreboard: Real-time tracking of player scores, turn counts, and remaining spins per participant.

Celebratory Finish: A custom confetti physics engine and winner's modal to celebrate the highest-scoring participant.

🛠️ Technical Implementation

Canvas Animation Engine: Uses requestAnimationFrame and CSS cubic-bezier transitions to simulate a realistic physical wheel deceleration.

Intelligent Randomization: The getAvailableSegment function ensures that players don't receive repetitive questions by tracking answeredQuestions per player state.

Visual Design Tokens:

Midnight Blue (#1f2a52): Primary branding and high-importance UI elements.

Teal (#00bec7): Call-to-action color and special wheel segments.

Light Aqua (#d2f0f0): Secondary background and subtle borders.

Confetti Physics: A custom particle system that simulates gravity, terminal velocity, and drag for a high-performance victory animation.

🎮 How to Play

Setup: Enter participant names in the Setup Screen (minimum 2 players).

Spin: Players take turns clicking the "SPIN" button.

Reflect: If the wheel lands on a question, the player must answer it to earn 1 point.

Win: After 5 spins per player, the individual with the most points is crowned the winner.

📂 Project Structure

The-Feedback-Game/
├── index.html          # Full application (HTML/Tailwind/Vanilla JS)
├── assets/             # SVG icons and brand assets
└── .github/workflows/  # Automated deployment and preview scripts


🤖 Catalog Integration

This repository is part of the Catalog of Repos ecosystem. It is configured for seamless deployment and automated visual testing of the setup and gameplay states.

📄 License

MIT License - Created for the accounts-eles ecosystem.
