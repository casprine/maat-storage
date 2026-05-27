# Catalog Pattern: Empty States

| Field | Value |
|---|---|
| Pattern ID | CP-20260527-empty-states |
| Project | maat |
| Slug | empty-states |
| Title | Empty states |
| Category | error and empty states |
| Tags | #tui #empty-states #readability |

## Problem

Empty panes and filtered-out lists can look broken unless they explain the current state and next useful action.

## Observed In

- lazygit
- superfile

## Maat Relevance

Maat should make empty projects, no matching tickets, and missing catalog entries understandable without relying only on color.

## Implementation Notes

Use concise text, stable panel dimensions, and no-color indicators for selected or empty states.

## Related Goals

- G-20260527-104618-2535

## Related Tickets

- T-20260527-104802-f29d
