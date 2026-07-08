# Sliding Window Visualizer

An interactive demo that visualizes the Sliding Window algorithm. Built during Day 14 of my 180-day software engineering sprint.

## Live Demo
[View on Netlify](https://visualiser-sliding-w.netlify.app/)

## Tech Stack
- HTML5
- CSS3 (Flexbox)
- Vanilla JavaScript (DOM Manipulation)

## Features
- Visual array representation with colored boxes
- Red highlight shows the current window
- Step-by-step window sliding
- Real-time sum and max sum updates
- Custom array input support

## What I Learned
- Sliding Window pattern: subtract leaving element, add entering element (O(n))
- Index arithmetic: the leaving element is at `i - k`
- DOM manipulation: createElement, classList, appendChild
- State management in vanilla JS

## Bugs I Fixed
- Zero-sum reset (sum was resetting to 0 each iteration)
- Arbitrary baseline (maxSum initialized to 0 instead of real data)
- Missing anchor window (first window must be built before sliding)

## Project Structure
window-visualizer/
├── index.html
└── README.md
