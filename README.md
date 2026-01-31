# Card Atlas

Card Atlas is a Flutter application that explains **how Indian credit cards actually work**.

This project is intentionally **not** a comparison engine or a lead-generation app.  
It is a structured field guide designed to help users (and the author) build correct mental models about credit cards in India.

---

## 🎯 Problem Statement

Credit cards in India are often misunderstood not because information is unavailable, but because it is **poorly structured**.

Most existing platforms focus on:

- Comparing large numbers of cards
- Pushing applications or rankings
- Highlighting benefits without context

As a result, users struggle to answer more fundamental questions:

- _How do different reward models actually work?_
- _Why does a card feel rewarding in some situations and disappointing in others?_
- _What assumptions am I unknowingly making when I choose a card?_

Credit cards operate as **rule-based systems** — with caps, exclusions, thresholds, and behavioral constraints — but these systems are rarely explained clearly or consistently.

This project exists to address that gap by:

- Breaking credit cards down into **clear mental models**
- Explaining reward mechanisms without marketing language
- Showing realistic outcomes instead of headline benefits
- Helping users reason about cards, not just browse them

The focus is not on choosing _the best card_, but on understanding **how cards behave** and **why**.

---

## 🧭 Project Goal

The goal of this project is to:

> **Explain Indian credit cards as systems, not as products.**

This app focuses on:

- Teaching _how_ reward models work
- Showing _where_ cards succeed and fail
- Making trade-offs visible
- Encouraging correct mental models instead of impulsive decisions

This is both:

- A **learning project** for the author
- A **portfolio project** demonstrating product thinking, architecture, and restraint

---

## ❌ What This Project Is NOT

This project deliberately avoids:

- ❌ Credit card comparison catalogs
- ❌ “Best credit card” rankings
- ❌ Affiliate links or monetization
- ❌ Eligibility promises or credit score guarantees
- ❌ Bank integrations or transaction tracking
- ❌ SMS reading or financial surveillance

If a feature increases scope without increasing understanding, it is excluded.

---

## ✅ What This Project IS

### v1 Scope

- A curated set of **8 representative Indian credit cards**
- Each card chosen to demonstrate a **distinct reward or behavior model**
- Clear explanations in plain English
- Realistic examples instead of marketing claims

### Covered Reward Models

- Simple cashback
- Accelerated cashback with caps
- Reward points systems
- Travel / miles logic
- Fuel-specific reward math
- Co-branded loyalty trade-offs
- Premium spend-driven cards
- Lifestyle-focused benefit cards

---

## 🧠 Core Mental Models Taught

Every card in the app reinforces one or more of these mental models:

1. **Credit card as a short-term loan**  
   Interest-free only if paid in full; extremely expensive otherwise.

2. **Rewards engine with rules**  
   Cashback and points are conditional incentives, not free money.

3. **Trust & behavior system**  
   Usage patterns influence long-term creditworthiness and access to capital.

---

## 🧩 Card Page Structure (Standardized)

Each credit card page follows the same template to avoid confusion:

1. **Card Snapshot**  
   Quick orientation: reward model, fees, best-fit use case.

2. **How This Card Actually Works**  
   Plain-English explanation of the reward mechanism.

3. **Reward Breakdown**  
   Key categories, caps, and exclusions only.

4. **Realistic Example**  
   Step-by-step reward calculation with assumptions.

5. **Gotchas & Traps**  
   Common mistakes and disappointment points.

6. **Who This Card Is NOT For**  
   Explicit constraints to prevent misuse.

This consistency is intentional.

---

## 🏗️ Technical Architecture

This project emphasizes **clarity and restraint** over novelty.

### Flutter & State Management

- **Flutter** for cross-platform development
- **Riverpod** for explicit dependency management and testable state boundaries

### Architecture

- **Feature-first folder structure**
- **Lightweight clean architecture**
  - Domain logic isolated from UI
  - Flutter-agnostic business rules
  - Clear inward dependency flow

This structure supports:

- Content-heavy features
- Domain evolution without UI churn
- Maintainability without over-engineering

---

## 🧩 Server-Driven UI (SDUI)

Server-Driven UI is used **selectively**.

### Server-driven:

- Card content sections
- Ordering of sections
- Text explanations and scenarios

### NOT server-driven:

- Navigation
- App shell and layout
- State management
- Interaction logic

> SDUI describes _what to show_, never _how the app behaves_.

This allows content to evolve without app updates while keeping behavior predictable.

---

## 🚀 CI / CD

- **Fastlane** is used for:
  - Repeatable builds
  - Linting and formatting checks
  - Basic test execution

The goal is to demonstrate **production discipline**, not DevOps complexity.

---

## 📣 Public Development

- The repository is **public by design**
- Architecture decisions are documented
- Progress and trade-offs are shared on LinkedIn
- Updates focus on **reasoning**, not daily activity

This mirrors how senior engineers communicate work in real teams.

---

## 🔮 Future Directions (Not v1 Commitments)

Possible later explorations (out of scope for v1):

- Behavior-based card optimization
- Spend simulations across multiple cards
- Eligibility gap analysis
- Deeper educational tooling

These are intentionally deferred to preserve focus.

---

## 🧠 Why This Project Exists (Portfolio Context)

This project demonstrates:

- Ability to reason in a complex, rule-heavy domain
- Product judgment through exclusion and constraint
- Clean Flutter architecture at feature scale
- Thoughtful use of advanced patterns (SDUI, CI/CD)
- Clear communication of trade-offs

It is designed to answer one question clearly:

> **Can this engineer design systems that explain complexity instead of hiding it?**

---

## 📌 Status

- v1 scope locked
- Architecture approved
- Implementation in progress

---

## 🧑‍💻 Author

Built as a personal learning and portfolio project by a Flutter engineer focused on:

- Product thinking
- System design
- Long-term maintainability

---
