# Corne Wireless Keyboard Reference

**Board:** nice_nano_v2  
**Firmware:** ZMK v0.3  
**ZMK Studio:** Enabled (runtime keymap editing)

---

## Quick Reference: Layer Access

| Thumb Key | Hold Action |
|-----------|-------------|
| Left inner thumb | **Layer 1 (Lower)** — Navigation + Numpad |
| Right inner thumb | **Layer 2 (Raise)** — Symbols |

---

## Layer 0: Base (QWERTY)

Your default typing layer.

```
┌───────┬─────┬─────┬─────┬─────┬─────┐   ┌─────┬─────┬─────┬─────┬─────┬───────┐
│  Tab  │  Q  │  W  │  E  │  R  │  T  │   │  Y  │  U  │  I  │  O  │  P  │  Esc  │
├───────┼─────┼─────┼─────┼─────┼─────┤   ├─────┼─────┼─────┼─────┼─────┼───────┤
│ Ctrl  │  A  │  S  │  D  │  F  │  G  │   │  H  │  J  │  K  │  L  │  ;  │   '   │
├───────┼─────┼─────┼─────┼─────┼─────┤   ├─────┼─────┼─────┼─────┼─────┼───────┤
│  Alt  │  Z  │  X  │  C  │  V  │  B  │   │  N  │  M  │  ,  │  .  │  /  │   `   │
└───────┴─────┴─────┼─────┼─────┼─────┤   ├─────┼─────┼─────┼─────┴─────┴───────┘
                    │ GUI │ LWR │ Bksp│   │ Ent │ RSE │ RAlt│
                    └─────┴─────┴─────┘   └─────┴─────┴─────┘
```

**Thumb Cluster:**
- **Left:** `GUI` (Super/Win) | `LWR` (hold for Layer 1) | `Backspace`
- **Right:** `Enter` | `RSE` (hold for Layer 2) | `Right Alt`

---

## Layer 1: Lower (Navigation + Numpad)

*Hold left inner thumb to access*

```
┌───────┬─────┬─────┬─────┬─────┬─────┐   ┌─────┬─────┬─────┬─────┬─────┬───────┐
│  ▽    │  ←  │  ↑  │  →  │  ▽  │  ▽  │   │  7  │  8  │  9  │  {  │  }  │ Bksp  │
├───────┼─────┼─────┼─────┼─────┼─────┤   ├─────┼─────┼─────┼─────┼─────┼───────┤
│  ▽    │  ▽  │  ↓  │  ▽  │ PgUp│ PgDn│   │  4  │  5  │  6  │  -  │  \  │   ▽   │
├───────┼─────┼─────┼─────┼─────┼─────┤   ├─────┼─────┼─────┼─────┼─────┼───────┤
│  ▽    │  ▽  │  ▽  │  ▽  │  ▽  │  ▽  │   │  1  │  2  │  3  │  ▽  │  ▽  │   ▽   │
└───────┴─────┴─────┼─────┼─────┼─────┤   ├─────┼─────┼─────┼─────┴─────┴───────┘
                    │  ▽  │█████│  ▽  │   │  0  │  ▽  │  ▽  │
                    └─────┴─────┴─────┘   └─────┴─────┴─────┘
```

**Legend:** `▽` = transparent (passes through to base layer) | `█████` = layer key (held)

### Lower Layer Highlights

| Left Side | Right Side |
|-----------|------------|
| Arrow keys (↑↓←→) | Numpad (7-8-9 / 4-5-6 / 1-2-3) |
| Page Up / Page Down | `0` on right thumb |
| | Curly braces `{ }` |
| | Minus `-` and Backslash `\` |

---

## Layer 2: Raise (Symbols)

*Hold right inner thumb to access*

```
┌───────┬─────┬─────┬─────┬─────┬─────┐   ┌─────┬─────┬─────┬─────┬─────┬───────┐
│   `   │  1  │  2  │  3  │  4  │  5  │   │  6  │  7  │  8  │  {  │  }  │ Bksp  │
├───────┼─────┼─────┼─────┼─────┼─────┤   ├─────┼─────┼─────┼─────┼─────┼───────┤
│ Ctrl  │  =  │  =  │  9  │  0  │  \  │   │  -  │  _  │  +  │  \  │  `  │   ▽   │
├───────┼─────┼─────┼─────┼─────┼─────┤   ├─────┼─────┼─────┼─────┼─────┼───────┤
│ Shift │  !  │  @  │  #  │  $  │  %  │   │  ^  │  &  │  *  │  /  │  ?  │   ▽   │
└───────┴─────┴─────┼─────┼─────┼─────┤   ├─────┼─────┼─────┼─────┴─────┴───────┘
                    │ GUI │  ▽  │Space│   │ Ent │█████│ RAlt│
                    └─────┴─────┴─────┘   └─────┴─────┴─────┘
```

### Symbol Quick Reference

| Symbol | Key Position | Notes |
|--------|--------------|-------|
| `!` | Shift + 1 position (Z row, left) | Direct access |
| `@` | Shift + 2 position | Direct access |
| `#` | Shift + 3 position | Direct access |
| `$` | Shift + 4 position | Direct access |
| `%` | Shift + 5 position | Direct access |
| `^` | Shift + 6 position (Z row, right) | Direct access |
| `&` | Shift + 7 position | Direct access |
| `*` | Shift + 8 position | Direct access |
| `{ }` | Top row, right side | Curly braces |
| `[ ]` | Not mapped in Raise | Use Lower layer |
| `- _` | Home row, right side | Minus and underscore |
| `+ =` | Home row, right middle | Plus and equals |
| `\ |` | Multiple positions | Backslash |
| `` ` ~ `` | Top-left and home row right | Backtick/grave |
| `/ ?` | Bottom row, right side | Slash and question |

---

## Layer 3: Colemak-DH

Alternative base layout (toggle access not shown in current config).

```
┌───────┬─────┬─────┬─────┬─────┬─────┐   ┌─────┬─────┬─────┬─────┬─────┬───────┐
│  Tab  │  Q  │  W  │  F  │  P  │  B  │   │  J  │  L  │  U  │  Y  │  ;  │  Esc  │
├───────┼─────┼─────┼─────┼─────┼─────┤   ├─────┼─────┼─────┼─────┼─────┼───────┤
│ Ctrl  │  A  │  R  │  S  │  T  │  G  │   │  M  │  N  │  E  │  I  │  O  │   '   │
├───────┼─────┼─────┼─────┼─────┼─────┤   ├─────┼─────┼─────┼─────┼─────┼───────┤
│  Alt  │  Z  │  X  │  C  │  D  │  V  │   │  K  │  H  │  ,  │  .  │  /  │   `   │
└───────┴─────┴─────┼─────┼─────┼─────┤   ├─────┼─────┼─────┼─────┴─────┴───────┘
                    │ GUI │ LWR │ Bksp│   │ Ent │ RSE │ RAlt│
                    └─────┴─────┴─────┘   └─────┴─────┴─────┘
```

### Colemak-DH vs QWERTY Differences

| QWERTY | Colemak-DH | New Position |
|--------|------------|--------------|
| E | F | Top row, left middle |
| R | P | Top row, left ring |
| T | B | Top row, left pinky |
| Y | J | Top row, right pinky |
| U | L | Top row, right ring |
| I | U | Top row, right middle |
| O | Y | Top row, right index |
| P | ; | Top row, right outer |
| F | T | Home row, left index |
| G | G | (unchanged) |
| H | M | Home row, right pinky |
| J | N | Home row, right ring |
| K | E | Home row, right middle |
| L | I | Home row, right index |
| ; | O | Home row, right outer |
| N | K | Bottom row, right pinky |
| M | H | Bottom row, right ring |

---

## Common Symbol Combos for Python/SQL

### Brackets & Braces

| Symbol | Layer | Position |
|--------|-------|----------|
| `{ }` | Lower or Raise | Top-right |
| `[ ]` | Lower | `LBRC` / `RBRC` top-right |
| `( )` | Raise + Shift | `9` and `0` on home row |

### Python Patterns

| Pattern | How to Type |
|---------|-------------|
| `['']` | Lower: `[` → Base: `'` `'` → Lower: `]` |
| `df['column']` | Base + Lower for brackets |
| `"""` | Base: `"` × 3 (Shift + `'`) |
| `->` | Raise: `-` → Raise: Shift + `.` for `>` |
| `:=` | Base: `:` → Raise: `=` |

### SQL Patterns

| Pattern | How to Type |
|---------|-------------|
| `<>` | Raise: Shift for `<` `>` |
| `>=` | Raise: Shift + `.` → `=` |
| `--` | Raise: `-` `-` (comment) |
| `/* */` | Raise: `/` `*` ... `*` `/` |

---

## Configuration Notes

### Current Settings (from corne.conf)

| Setting | Value | Purpose |
|---------|-------|---------|
| TX Power | +8 dBm | Extended wireless range |
| Debounce Press | 1ms | Fast key registration |
| Debounce Release | 10ms | Prevents chatter |
| ZMK Studio | Enabled | Runtime keymap editing |
| Studio Locking | Disabled | No unlock required |
| 2M PHY | Disabled | Linux compatibility |
| Max Connections | 6 | Bluetooth profiles |

### Bluetooth Profiles

Your keyboard supports 6 Bluetooth profiles for switching between devices.

---

## What's Missing from This Config

Based on your previous work, your full setup includes features not present in this keymap file:

- [ ] **Home row modifiers** (tap for letter, hold for Shift/Ctrl/Alt/GUI)
- [ ] **Tap-dance behaviors** (Tab/Escape, Ctrl/Caps Word)
- [ ] **Mouse emulation layer** (Layer 4?)
- [ ] **Text macros** for Python/SQL patterns (`df['']`, `.groupby().agg()`, etc.)
- [ ] **Bluetooth profile controls** (BT_SEL, BT_CLR)
- [ ] **Workspace management combos** (Super+Ctrl+Shift+Arrow)
- [ ] **Toggle for Colemak-DH** base layer

If this config file is outdated, you may want to pull your latest version from GitHub or check ZMK Studio for your current runtime configuration.

---

*Generated from `config/corne.keymap` • ZMK v0.3*
