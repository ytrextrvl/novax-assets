# Touch-First Interaction SSOT (NOVAX)

Authoritative interaction standard for:
- Web (Customer)
- Admin
- Mobile (Flutter UI guidelines)
- Any embedded UI surfaces

## Non-negotiable rules
1) No hover-only UX:
   - Any action revealed on hover must also be accessible via touch and keyboard.
2) Tap targets:
   - Minimum 44×44 px for any interactive element (icons included).
3) Spacing:
   - Interactive clusters must have enough spacing to avoid mis-taps.
4) Focus & keyboard parity:
   - All interactive controls must be reachable with Tab and operable with Enter/Space.
   - Visible focus ring required.
5) Pointer modes:
   - For touch screens (coarse pointer), increase paddings and row heights.
6) Motion:
   - Respect prefers-reduced-motion for animations and transitions.
7) Scroll & drag:
   - No drag-only interactions. Provide alternative controls (buttons/menu).
8) Feedback:
   - Pressed/active state must be visible instantly.
9) Accessibility:
   - ARIA labels where needed; contrast and readable font sizes.

## Verification checklist (UI)
- All actions work on touch (phone/tablet) + mouse + keyboard
- No hidden hover-only menus
- 44×44 minimum targets
- Focus ring visible
- Reduced motion supported
