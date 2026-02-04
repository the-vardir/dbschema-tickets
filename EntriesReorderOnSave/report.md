# Bug Report

## Problem Description
When making minor adjustments to elements in a diagram, such as moving them slightly, saving the diagram causes the entries to be reordered unexpectedly.
This behavior is undesirable as it disrupts the files structure resulting in unnecessary conflicts on merge operations.

## Expected Result
Insignificant changes to diagram should not trigger reordering of entries on save.

## Actual Result
Changes such as moving an element slightly in a diagram cause the entries to be reordered upon saving, which is not desired.

## Steps to Reproduce
1. Open any diagram with multiple entries.
2. Move an element on canvas.
3. Save the diagram.
4. Observe that the entries have been reordered in file.

## Environment
- 10.0.2
- Linux Kubuntu 25.10, Windows 11
- PostgreSQL

