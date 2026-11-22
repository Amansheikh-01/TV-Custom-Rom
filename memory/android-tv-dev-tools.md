---
name: android-tv-dev-tools
description: Python tools collection for Android TV automation testing
metadata:
  type: project
---

This is a comprehensive set of Python tools (in tools/ directory) designed for Android TV device debugging and automation. Each tool targets specific Android TV features:

**Core Automation:**
- `adb-closed.py` - ADB command wrapper/closure utilities
- `bench.py` - Benchmarking/performance testing
- `relay.py` - Relay/command forwarding

**System Debugging:**
- `check.py` - System state validation checks
- `recovery.py` - Recovery mode tools
- `privacy.py` - Privacy setting verification

**Display & UI:**
- `screendiff.py` - Screen comparison/diffing
- `scenes_wallpapers.py` - Display scene wallpaper automation
- `theme.sh` - Shell script for theme management

**Performance:**
- `flamechart.py` - Performance tracing/flame chart generation

**Utilities:**
- `readme_card.py` / `readme_featured.py` / `readme_stats.py` - README content generators
- `race_calendar.py` - Calendar comparison tool
- `tv.py` - TV device tools
- `b64push.py` - Base64 encoding/decoding utilities
- `disable.sh` / `restore.sh` - Shell scripts for disable/restore operations

**Why:** This appears to be a development toolkit for testing/debugging Android TV functionality (display, performance, system features). The tools are organized by function rather than a monolithic solution.

**How to apply:** When working on Android TV feature testing, start by reading the individual tool files in `tools/` directory to understand available debugging utilities before implementing custom scripts.

[[android-tv-dev-tools]]
[[tv.py]]
