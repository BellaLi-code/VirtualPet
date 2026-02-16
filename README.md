# VirtualPet 🐾
Java Desktop Application | MVC Architecture | Event-Driven Design

## Overview
VirtualPet is a Java Swing desktop application that simulates interactive pet gameplay.  
The project demonstrates clean architectural separation (MVC), event-driven programming, JSON-based persistence, and structured unit testing.

## Tech Stack
- Java
- Swing / AWT
- Google Gson (JSON serialization)
- JUnit (unit testing)

## Core Engineering Highlights

### 🧩 MVC Architecture
Implemented a clear separation between:
- **Model** – Pet state and business logic
- **View** – Swing-based UI components
- **Controller** – Event handling and state transitions

This structure improved maintainability, reduced coupling, and enabled modular feature development.

### ⚙️ Event-Driven State Management
- Implemented interactive UI events (feed, play, sleep, etc.)
- Managed dynamic pet state updates
- Debugged state synchronization issues between UI and model layer

### 💾 Data Persistence
- Integrated Google Gson for JSON-based save/load functionality
- Ensured consistent object serialization and restoration

### 🧪 Testing & Debugging
- Wrote JUnit tests for core logic validation
- Identified and resolved state inconsistency bugs during integration
- Improved application stability through iterative debugging

## Development Approach
The project followed an iterative development process:
- Feature breakdown into modular components
- Incremental implementation and integration
- Continuous testing and refinement

## Project Structure
```
VirtualPet/
├── Code and Test/     # Source code and unit tests
├── resources/         # Images and audio assets
├── JavaDoc/           # Generated documentation
├── Testing Documentation ver3.pdf
└── README.md
```

## What This Project Demonstrates
- Object-Oriented Design
- Event-driven UI architecture
- State management complexity handling
- Clean modular Java application structure
