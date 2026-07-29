# FLIK Checkout Experience — Case Study

**Evolving the checkout flow to reduce friction and improve conversion rates**

---

## Overview

| | |
|---|---|
| **Project** | Checkout Experience Redesign |
| **Company** | FLIK |
| **Role** | Product Designer & Researcher |
| **Duration** | 6 months |
| **Industry** | Checkout & Merchant Enablement Platform |
| **Live** | [Landing page](https://flik.co.id/en) · [Merchant Dashboard](https://merchant.flik.co.id/register/) |

---

## Problem Statement

FLIK's checkout user journey contained unnecessary friction points that were limiting conversion rates. The challenge was to **streamline the flow, reduce friction, and improve the checkout page to boost conversion**.

---

## Research Methodology

### Phase 1: Heuristic Evaluation
Observation-based analysis using Google Chrome on Android devices to manually identify usability issues.

- **Approach:** Device-based testing
- **Feedback loops:** 4 rounds of iteration with CEO
- **Outcome:** Identified key friction points for redesign

### Phase 2: Unmoderated Usability Testing
Large-scale remote testing to validate guest checkout preference and button placement.

- **Tool:** Maze
- **Sample:** 100 users (50 guest checkout, 50 logged-in)
- **Recruitment:** Email blast and push notifications
- **Device:** Android mockup
- **Research questions:** Guest checkout preference, button placement optimization

**Key Finding:** 68% of participants chose Guest Checkout, perceiving it as faster despite contradictory performance data.

### Phase 3: Guerrilla Usability Testing
In-person testing to validate drop-off hypothesis and test simplified flow.

- **Sample:** 10 on-site recruits (non-targeted sampling)
- **Prototyping:** Figma
- **Devices:** Android and laptops
- **Methodology:** In-person testing with context-setting ice-breakers

**Key Finding:** Significant drop-off at login/guest checkout decision point due to session reset (48-hour timeout).

### Phase 4: Iterative Refinement Testing
Three additional usability testing rounds to fine-tune UI balance between guest checkout accessibility and login incentivization.

---

## Key Insights

### Perception vs. Reality Gap
Users perceived guest checkout as faster, but actual performance data showed the opposite. This perception-reality mismatch drove checkout abandonment.

### Silent Business Value Loss
Users didn't realize that logging in with FLIK offered extra cashback and faster checkout. The reward benefits were unclear on the login page, reducing login incentive.

### Session Reset Friction
The 48-hour session timeout was causing logged-in users to re-authenticate mid-flow, creating unexpected friction for the intended "faster" path.

### Flow Simplification Opportunity
The explicit login/guest checkout decision point was a major drop-off trigger. Removing this step could simplify the flow for both user types.

---

## Design Process

### Phase 1: Initial Redesign
- Low-fidelity iterations incorporating stakeholder feedback
- High-fidelity development post-approval
- Desktop version creation to match mobile design consistency

**Outcome:** Checkout conversion rates increased; CEO approved for desktop development.

### Phase 2: Guest Checkout Feature Addition
- Feature implementation based on Phase 1 learnings
- Data-driven iteration following 3-month post-launch observation
- Reward messaging refinement

**Outcome:** Average checkout ease rating: 9.1/10; guest checkout selection: 68%.

### Phase 3: Flow Simplification
**Short-term:** Extended session persistence from 48 hours to 1 month, reasoning that FLIK's low market prominence made account compromise unlikely.

**Long-term strategy:** Remove the intermediate login/guest checkout decision step, allowing direct checkout access for logged-in users.

**Outcome:** Quantified drop-off issue; validated simplified approach through testing.

### Phase 4: Fine-Tuning
- Three additional usability testing rounds
- UI refinement to balance guest checkout accessibility with login incentivization
- Iterative adjustments based on click-rate data

**Outcome:** Successfully balanced click rates between guest checkout and login options.

---

## Design Decisions

### 1. Maintain Button Position (Phase 2)
**Decision:** Keep current button placement while improving reward messaging clarity.

**Rationale:** Testing showed position was not the primary friction; lack of clarity around benefits was the issue.

### 2. Extended Session Persistence (Phase 3, Short-term)
**Decision:** Extend session timeout from 48 hours to 1 month.

**Rationale:** Addresses immediate drop-off by reducing re-authentication friction. Security risk mitigated by FLIK's limited market prominence and fraud monitoring.

### 3. Remove Intermediate Step (Phase 3, Long-term)
**Decision:** Eliminate the explicit login/guest checkout decision page.

**Rationale:** Direct access to checkout for logged-in users reduces decision fatigue and drop-off at this critical juncture.

### 4. Iterative UI Refinement (Phase 4)
**Decision:** Balance guest checkout accessibility with login encouragement through careful UI design.

**Rationale:** Avoid guest checkout becoming overly dominant, which would reduce login rates and long-term retention.

---

## Outcomes & Metrics

| Phase | Metric | Result |
|-------|--------|--------|
| **1** | Conversion increase | ✓ Improved post-redesign |
| **2** | Checkout ease (1–10) | 9.1/10 |
| **2** | Guest checkout selection | 68% |
| **2** | Login/register selection | 32% |
| **3** | Drop-off identification | Quantified at decision point |
| **4** | Click-rate balance | Successfully achieved |

---

## Tools & Technologies

- **Browser Testing:** Google Chrome
- **Usability Testing:** Maze
- **Prototyping:** Figma
- **Recruitment:** Email, push notifications

---

## Key Learnings

1. **Perception drives behavior** — Users' mental models of flow speed matter as much as actual performance. Test and communicate.

2. **Session design has outsized impact** — A 48-hour timeout is invisible until it causes friction. Consider user lifetime in session design.

3. **Simplification beats feature completeness** — Removing the login/guest decision step was more powerful than optimizing either option.

4. **Balance trumps extreme optimization** — Over-optimizing for one path (guest checkout) can harm long-term business goals (login + retention).

5. **Iteration compounds insights** — Each phase revealed hidden assumptions and validated new approaches. No single round of testing was conclusive.

---

## Impact

**Conversion Rate:** Measurable improvement in checkout completion rates through friction reduction.

**User Satisfaction:** 9.1/10 checkout ease rating demonstrates strong product-market fit for redesigned flow.

**Business Alignment:** Successfully balanced UX simplicity with business objectives of login incentivization and customer retention.

---

## Reflection

This project exemplifies iterative, research-driven design under real-world constraints. The challenge wasn't identifying what to fix—it was **reconciling user needs (simplicity) with business needs (login/retention)**. The solution required multiple research methodologies (heuristic, unmoderated, guerrilla) to build confidence in decisions that had trade-offs.

The willingness to extend session timeouts and simplify the flow—despite security and short-term analytics implications—demonstrates the importance of aligning design decisions with long-term product strategy and user behavior.
