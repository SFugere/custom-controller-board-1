# Tasks

- Read the current schematic/board and locate any layout-dependent references.
- Edit docs/BRIEF.md and docs/SPEC.md to state 60% keyboard layout.
- If schematic/PCB references the old 40% layout, update only the necessary s-expressions and keep net names/refdes consistent.
- Run ERC (and DRC if board edits are made).
- Run check_drift and record decisions/constraints for the layout change.
