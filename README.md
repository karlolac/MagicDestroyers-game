# ⚔️ .NET RPG Character & Combat Engine

A C# / .NET project focused on demonstrating core **Object-Oriented Programming (OOP)** principles through a modular role-playing game (RPG) combat framework. Developed as a practical application of foundational C# and software design concepts.

---

## 🎯 Key Objectives

* **Mastering OOP Principles:** Hands-on implementation of Encapsulation, Inheritance, and Polymorphism.
* **Clean Code & Extensibility:** Designing a flexible architecture where new character classes can be added with minimal code changes.
* **Engine & Business Logic:** Building scalable game mechanics using clean domain models.

---

## 🧱 Software Architecture & OOP Implementation

### 🛡️ Encapsulation
Data integrity is enforced across domain models (e.g., `Player`, `Character`). Internal state attributes such as health points, attack power, and player statistics are strictly protected and exposed only through controlled public methods and properties.

### 🧬 Inheritance
Code reusability is achieved through a base `Character` class that encapsulates common entity behavior (health tracking, status management). Specialized combat classes derive from this base:
* **Melee / Physical:** `Warrior`, `Knight`, `Assassin`
* **Casters / Hybrid:** `Mage`, `Necromancer`, `Druid`

### 🎭 Polymorphism & Interfaces
Combat behaviors are driven by polymorphic design. Every character class overrides the core `Attack()` method to execute class-specific combat logic and ability modifiers. The system interacts with characters through abstract types and interfaces, allowing dynamic behavior resolution at runtime.

---

## ⚙️ Tech Stack & Concepts

* **Language:** C#
* **Framework:** .NET Core / .NET Console
* **Paradigm:** Object-Oriented Programming (OOP)


