# Proposal: usb-only-v1-scope

> Marker: AUTO (autonomous mode; auto-approved, reviewable after the fact)

## Why

The first iteration should reduce scope to generic USB support only, deferring OLED and Bluetooth so the initial design stays buildable and constrained.

## What Changes

- Update the brief to state that v1 uses generic USB connectivity only and explicitly excludes OLED and Bluetooth for this iteration.
- Record the scope change in the decisions log with a rationale.
- Add a specification note that the current iteration omits OLED and Bluetooth and must preserve the 60% layout and USB-first scope.
- Append a changelog entry summarizing the scope reduction.
