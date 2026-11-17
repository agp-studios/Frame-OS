# Frame OS — Architecture

## Status

This document records the current conceptual direction. It is not a final technical architecture. Frameworks, languages, libraries, APIs and implementation details have not yet been selected.

## Initial product scope

The first product focus is **Frame OS TV for Android TV only**.

The implementation must be planned around Android TV platform requirements and television use, including remote-based navigation, readable layouts and device compatibility.

## Conceptual areas

The product architecture will be evaluated across these areas:

1. **Presentation and interaction**
   - Television interface and screen layouts.
   - Navigation designed for a remote control.
   - Clear focus states, readable text and accessible interaction.

2. **Application behaviour**
   - Core product features and user-facing workflows.
   - State handling and predictable behaviour.
   - Error and empty states.

3. **Platform integration**
   - Android TV APIs and platform capabilities.
   - Application lifecycle and device compatibility.
   - Permissions and system integration only where required.

4. **Data and preferences**
   - Storage requirements for settings and user preferences.
   - Data minimisation and appropriate protection.
   - Clear handling of data that may be reset or removed.

5. **Quality and maintenance**
   - Testing strategy.
   - Logging and diagnostics that avoid exposing sensitive information.
   - Performance, stability and maintainability.

## Architecture decisions still required

Before implementation, the project must evaluate and document:

- Whether Frame OS TV will be an Android TV application, launcher-style experience or another technically viable form.
- The supported Android TV versions and device requirements.
- The programming language, UI framework and build tooling.
- The data-storage approach, if local persistence is needed.
- Testing devices, emulator coverage and release process.
- Any third-party dependencies and their licenses.

## Decision policy

Do not treat an option as selected until it has been researched, tested where practical and recorded as a decision. Significant choices should include the reason, alternatives considered and any trade-offs.

## Scope boundary

This architecture currently covers Frame OS TV on Android TV. Other Frame products and television platforms are not part of this initial technical design.
