# Stille brand foundations

## Name and voice

**Stille** is German for silence. The product should feel clear, calm, and on the user's side—not punitive or competitive.

- Use direct, short explanations of boundaries and timers.
- Make time for breaks as visible as time for work.
- Avoid guilt, streak pressure, and claims that attention is a moral achievement.

Working tagline: **Weniger Ablenkung. Mehr Raum für das Wesentliche.**

English expression: **Less distraction. More room for what matters.**

## Main color

The primary brand color is a deliberately vivid purple: **`#A020FF`**.

| Role | Color |
| --- | --- |
| Primary accent | `#A020FF` |
| Primary hover | `#8A0DE8` |
| Text on primary | `#FFFFFF` |
| Light canvas | `#FAF8FF` |
| Light surface | `#FFFFFF` |
| Light text | `#1A1125` |
| Dark canvas | `#0E0914` |
| Dark surface | `#1A1224` |
| Dark text | `#F8F5FF` |

Use purple for primary actions, selected controls, and focus-session emphasis. Keep large surfaces neutral so the accent remains intentional rather than overwhelming.

Use [the CSS tokens](../branding/tokens.css) as the single source of truth when an interface is introduced. Dark mode is explicitly selected with `data-theme="dark"`; automatic system-theme handling is not implemented yet.

## Accessibility

White text on `#A020FF` has a calculated WCAG contrast ratio of approximately **5.07:1**, meeting the WCAG AA contrast threshold for normal text. This does not establish accessibility of a complete interface.

- Do not use purple text directly on a dark canvas for small labels; use the theme's foreground color.
- Never communicate blocking, progress, or errors through color alone.
- Provide visible keyboard focus, text alternatives, and reduced-motion behavior.
- Check actual component states and adjacent colors when implementing controls.

## Draft mark

The original [draft SVG mark](../branding/mark.svg) uses two rounded pause bars on a purple square. It represents an intentional pause and is a starting point, not a finalized or uniqueness-cleared logo.

## Naming status

The name was selected with awareness that other software products use **Stille** or similar names, including a meditation app and a focus app called **Still**. No trademark clearance or domain-availability claim is made. Review the intended launch markets before a branded public release.
