# Proposal: sixty-percent-layout-update

> Marker: AUTO (autonomous mode; auto-approved, reviewable after the fact)

## Why

The requested form factor changes from 40% to 60%, so the docs and hardware implementation must be updated to avoid a stale layout mismatch.

## What Changes

- Update the project brief/spec to describe a 60% keyboard layout instead of a 40% layout.
- Review the schematic/PCB for any footprint, switch matrix, connector, or labeling assumptions that depend on the old 40% arrangement and adjust them as needed.
- Preserve all existing electrical and interface constraints unless the 60% layout forces a documented change.
