# Catalog Pattern: Background Refresh

| Field | Value |
|---|---|
| Pattern ID | CP-20260527-background-refresh |
| Project | maat |
| Slug | background-refresh |
| Title | Background refresh |
| Category | background refresh |
| Tags | #tui #refresh #state |

## Problem

Long-running terminal sessions can become misleading when the screen does not reveal stale or refreshed state.

## Observed In

- btop
- gh-dash

## Maat Relevance

Maat should make reloads, storage freshness, and refresh failures clear while preserving navigation context.

## Implementation Notes

Keep refresh state visible, recoverable, and safe for concurrent Markdown updates.

## Related Goals

- G-20260526-220308-c0d2

## Related Tickets

- T-20260526-220336-a45d
