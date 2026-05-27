# Catalog Pattern: Keyboard Model

| Field | Value |
|---|---|
| Pattern ID | CP-20260527-keyboard-model |
| Project | maat |
| Slug | keyboard-model |
| Title | Keyboard model |
| Category | keyboard model |
| Tags | #tui #navigation #keyboard-first |

## Problem

Terminal apps become slow when movement, inspection, filtering, and escape paths are inconsistent.

## Observed In

- lazygit
- btop
- gh-dash
- superfile

## Maat Relevance

Maat should use predictable keys for moving through projects, opening boards, inspecting tickets, filtering, refreshing, and backing out.

## Implementation Notes

Favor arrow keys and vim-style movement, enter for inspect, slash for search, and backspace or escape for return paths.

## Related Goals

- G-20260527-104618-2535

## Related Tickets

- T-20260527-104802-f29d
