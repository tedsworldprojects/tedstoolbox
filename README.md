# TEDS TOOLBOX - Ultimate Bench Tools

A sleek and efficient web-based toolkit designed for electronics engineers, students, and hobbyists. It provides a suite of essential calculators and lookup tools in a clean, modern, and responsive user interface.

## Features

The application is divided into three main tools and a persistent history log.

### 1. Resistor Color Code Decoder
- **Decode 4 & 5-Band Resistors:** Easily find the resistance value and tolerance.
- **Flexible Input:** Enter colors as a comma-separated string (e.g., `red, red, orange, gold`).
- **Formatted Output:** Results are displayed in a human-readable format (e.g., `22.0 kΩ ±5%`).
- **Error Handling:** Get clear feedback for invalid color names or band counts.

### 2. Ohm's Law Calculator
- **Calculate V, I, or R:** Solves for voltage, current, or resistance based on Ohm's Law (V=IR).
- **Simple Interface:** Enter any two values to find the third.
- **Instant Results:** The missing value is calculated and displayed immediately.
- **Input Validation:** Ensures correct usage by requiring exactly two input values.

### 3. Standard Capacitor Lookup
- **Find Standard Values:** Get the closest commercial capacitor values for any given capacitance.
- **E12 & E24 Series:** Displays the nearest values from both the E12 (10% tolerance) and E24 (5% tolerance) series.
- **Smart Parsing:** Accepts various input formats like `100pF`, `2.2nF`, and `0.1uF`.

### Common Features
- **Calculation History:** Automatically saves the last 5 calculations from any tool.
- **Persistent State:** History is saved to your browser's local storage, so it's there when you return.
- **Copy to Clipboard:** Easily copy any result with a single click.
- **Responsive Design:** Fully usable on desktop, tablet, and mobile devices.

## Tech Stack

- **Frontend:** [React](https://react.dev/)
- **Language:** [TypeScript](https://www.typescriptlang.org/)
- **Styling:** [Tailwind CSS](https://tailwindcss.com/)

## How to Use

1.  **Select a tool** from the main view.
2.  **Enter your values** in the corresponding input fields.
3.  **Click the action button** (e.g., "Decode", "Calculate", "Find Closest").
4.  View the result in the output panel.
5.  Your calculation will be automatically added to the **History** panel on the right.
