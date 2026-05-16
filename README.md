# pi-exit

A minimal [pi](https://github.com/earendil-works/pi) extension that registers `/exit` as a first-class slash command (alias for the built-in `/quit`).

## Features

- Adds `/exit` command that cleanly shuts down pi
- No conflicts with built-in commands
- Works exactly like `/quit`

## Installation

### Quick test
```bash
pi -e ~/Developer/ai-ecoverse/pi-exit
```

### Permanent install (recommended)

**Option 1: Symlink (easiest)**
```bash
mkdir -p ~/.pi/agent/extensions
ln -s ~/Developer/ai-ecoverse/pi-exit ~/.pi/agent/extensions/pi-exit
```

**Option 2: Copy**
```bash
cp -r ~/Developer/ai-ecoverse/pi-exit ~/.pi/agent/extensions/
```

Then restart pi or run `/reload`.

## Usage

Just type:

```
/exit
```

It will exit pi the same way `/quit` does.

## Development

The extension source is a single file:

- `index.ts` — registers the `/exit` command using `pi.registerCommand()`

## License

MIT