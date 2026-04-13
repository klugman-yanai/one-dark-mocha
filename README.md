# Eventide

A muted dark theme built for long coding sessions. Inspired by One Dark Modern Pro and Catppuccin Mocha.

## Design

- **Surfaces**: One Dark blue-gray hierarchy (`#21252b` → `#282c34` → `#2c313a`)
- **Syntax**: 12 distinct colors from Catppuccin Mocha, all below 0.5 saturation
- **Accessibility**: Every syntax token passes WCAG AA (4.5:1) — including comments
- **Philosophy**: Variables are neutral. Keywords, functions, types, and strings are what pop.

## Language Optimizations

| Language | Coverage |
|---|---|
| **Python** | 13 semantic tokens — decorators, self/cls, magic methods, type hints, f-strings, parameters |
| **Rust** | 23 semantic tokens + 18 textmate scopes — lifetimes, traits (italic), unsafe (bold), macros, derive helpers, mutable underline |
| **TypeScript/TSX** | 16 semantic tokens + 12 textmate scopes — component tags (yellow) vs HTML tags (rose), JSX expression braces, interface vs type distinction |
| **C/C++** | 5 semantic tokens + existing textmate — concepts, operators, POSIX types, sizeof |
| **Shell/Bash** | 11 textmate scopes — builtins, external commands, variables, keywords, shebangs |
| **CSS/Tailwind** | 22 textmate scopes — `@apply`/`@layer`, pseudo-classes, CSS variables, `!important` |
| **Dockerfile** | 3 textmate scopes — instruction keywords, source body |
| **YAML/JSON/TOML** | Dedicated key/value coloring |
| **Makefile/Justfile** | Target names as functions |

## Syntax Color Map

| Role | Color | Hex |
|---|---|---|
| Keywords | Mauve | `#cba6f7` |
| Functions | Blue | `#89b4fa` |
| Strings | Green | `#a6e3a1` |
| Types/Classes | Yellow | `#f9e2af` |
| Builtin types | Teal | `#94e2d5` |
| Variables | Neutral | `#abb2bf` |
| Parameters | Peach italic | `#fab387` |
| Properties | Maroon | `#eba0ac` |
| Constants/Numbers | Peach | `#fab387` |
| Operators | Teal | `#94e2d5` |
| Comments | Gray italic | `#909298` |
| Tags/Labels | Rose | `#f38ba8` |

## Install

### Cursor / VS Code

Search "Eventide" in the Extensions marketplace, or:

```
ext install your-publisher-id.eventide-theme
```

### Zed

Open the command palette → `zed: extensions` → search "Eventide".

Or manually: copy `themes/eventide.json` to `~/.config/zed/themes/`.

## Lineage

Eventide descends from Two Monokai Flat (a One Monokai + One Dark Pro fusion), modernized with One Dark Modern Pro's surface architecture and Catppuccin Mocha's syntax palette. Research-validated against WCAG 2.1, the VS Code 2026 Theme Refresh design pillars, and academic studies on syntax highlighting and cognitive load.
