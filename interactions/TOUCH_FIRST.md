# Touch-First Interaction System (SSOT)

This document defines **mandatory interaction rules** for ALL NOVAX systems:
- Admin Panel
- Web (Desktop + Tablet + Mobile)
- Mobile Apps
- Touch-enabled laptops

## Core Principle
🟢 **Every interactive element MUST be usable by touch**
No hover-only logic. No mouse-only assumptions.

---

## Touch Targets (MANDATORY)
- Minimum size: **44×44 px** (Apple / Google standard)
- Preferred: **48×48 px**
- Spacing between targets: **≥ 8 px**

---

## Gestures Support
- Tap → Primary action
- Long-press → Secondary / context action
- Swipe → Navigation (where applicable)
- Drag → Reordering (explicit only)

❌ Hover is OPTIONAL, never REQUIRED.

---

## Input Rules
- All inputs must support:
  - Touch keyboard
  - Focus ring
  - Large tap area

---

## Accessibility
- WCAG AA minimum
- Visible focus for touch & keyboard
- No hidden actions behind hover only

---

## Enforcement
Any UI PR violating touch rules MUST be rejected.

SSOT Owner: novax-assets
