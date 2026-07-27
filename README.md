# Wornpage

**Svelte 5 component library + development toolkit.**
Personal, paper-textured, deterministically tested.

---

### Get started

```bash
# Browse everything
git clone https://github.com/wornpage/wornpage.git
cd wornpage && bun install && bun test  # 60 tests

# Use in your app
bun add github:wornpage/sidebar
bun add github:wornpage/cmdk
```

### Packages

| Component | | | Tool | |
|---|---|---|---|---|
| [sidebar](https://github.com/wornpage/sidebar) | Collapsible nav | | [cli](https://github.com/wornpage/cli) | Scaffold + ship |
| [cmdk](https://github.com/wornpage/cmdk) | Command palette | | [workflow](https://github.com/wornpage/workflow) | State machine |
| [toast](https://github.com/wornpage/toast) | Notifications | | [sync](https://github.com/wornpage/sync) | Code sharing |
| [theme](https://github.com/wornpage/theme) | 8-palette themes | | [undo](https://github.com/wornpage/undo) | Undo/redo |
| [receipt](https://github.com/wornpage/receipt) | Action cards | | | |

### Philosophy

Every package is **one repo, one concern, zero surprises**.
- Pure Svelte 5 (runes, snippets, $props)
- Tested with bun
- Themed via `--cockpit-*` CSS custom properties
- Web component builds for framework-agnostic use
- MIT licensed

[Monorepo →](https://github.com/wornpage/wornpage)
