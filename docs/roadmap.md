# Initial roadmap

This is a planning outline, not a list of existing capabilities.

## 1. Define the first release

- Agree on initial target platforms and minimum OS versions.
- Select the implementation stack and document the decision.
- Specify blocking scope, permissions, and failure behavior using public platform documentation.
- Define focus/break timing, schedule boundaries, and local-time behavior.

## 2. Build the focus-session foundation

- Start, pause, and end a focus session with clear state transitions.
- Add configurable work and break intervals.
- Store settings locally and restore state predictably after restarts.

## 3. Add distraction blocking

- Implement website blocking with transparent coverage and limitations.
- Explore app blocking where supported by the selected platform.
- Ensure users understand permissions and have a documented recovery path.

## 4. Add schedules

- Support selected weekdays and timed windows.
- Support all-day schedules with local calendar-day semantics.
- Specify behavior for daylight-saving transitions, sleep, restarts, and overlapping schedules.

## 5. Prepare a public app release

- Validate light and dark themes, keyboard navigation, and accessibility.
- Review dependencies and preserve required third-party notices.
- Review naming and branding before release.
- Establish a tested release process appropriate to the selected platform.
