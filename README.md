# Bobby Ziglings

## Overview

This is my working copy of Ziglings.
I may put some Zig notes in here too, not sure yet.

## Commands

```bash
# Run single exercise (with tests)
zig build -Dn=17

# Run all exercises (with tests and can start anywhere
# From start
zig build -Ds=1
# From 17 on
zig build -Ds=17

# Run directly, good for seeing compile issues
zig run ./exercises/016_for2.zig
# With added reference
zig run ./exercises/016_for2.zig -freference-trace=10
```
