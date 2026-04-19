# 🎮 TextRpg

A modular, scalable text-based RPG built with **C# and .NET**, designed to simulate classic role-playing game mechanics while following clean architecture principles.

---

## 🚀 Overview

**TextRpg** is a console-based role-playing game where players can explore, battle enemies, and progress their character.

This project focuses on:

* Clean architecture (Domain-driven design)
* Separation of concerns
* Testable and maintainable code
* Backend-focused game logic

---

## 🧱 Architecture

The project is structured using a layered approach:

```
TextRpg/
├── TextRpg.Api        # Entry point / game runner
├── TextRpg.Domain     # Core game logic (entities, rules)
├── TextRpg.Tests      # Unit tests
└── TextRpg.sln
```

### Key Concepts

* **Domain Layer**: Contains all core game logic (player, enemies, combat rules)
* **API Layer**: Handles interaction (console/game loop)
* **Tests**: Ensures reliability of core mechanics

---

## ⚔️ Features

* 🧙 Player creation and progression *(in progress / extend as needed)*
* ⚔️ Combat system (turn-based logic)
* 🧠 Domain-driven design structure
* 🧪 Unit testing support
* 🔌 Easily extendable for:

  * Inventory systems
  * Skills & abilities
  * AI enemies
  * Story systems

---

## 🛠️ Tech Stack

* **Language:** C#
* **Framework:** .NET
* **Architecture:** Clean Architecture / Domain-Driven Design
* **Testing:** xUnit (or update if you're using something else)

---

## ▶️ Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/james-thegreat/text-rpg.git
cd text-rpg
```

### 2. Build the project

```bash
dotnet build
```

### 3. Run the game

```bash
cd TextRpg.Api
dotnet run
```

---

## 📌 Roadmap

Planned improvements:

* [ ] Inventory system
* [ ] Save/load game state
* [ ] Enemy AI improvements
* [ ] Story / quest system
* [ ] UI improvements (console polish or web frontend)
* [ ] Multiplayer (long-term idea)

---

## 🎯 Purpose

This project was built as part of my journey to becoming a software developer.
It serves as a practical way to:

* Apply backend development concepts
* Practice clean architecture
* Build real-world, scalable systems

---

## 👤 Author

**James Dunlop**
Aspiring Software Developer
GitHub: https://github.com/james-thegreat

---

## 📄 License

This project is open-source and available under the MIT License.
