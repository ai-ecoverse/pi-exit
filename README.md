# pi-exit

A minimal [pi](https://github.com/earendil-works/pi) extension that registers `/exit` as a first-class slash command (alias for the built-in `/quit`).

## Features

- Adds `/exit` command that cleanly shuts down pi
- No conflicts with built-in commands
- Works exactly like `/quit`

## Installation

### From npm (recommended)
```bash
pi install npm:@ai-ecoverse/pi-exit
```

Then run `/reload` inside pi.

### Quick test (local development)
```bash
pi -e ~/Developer/ai-ecoverse/pi-exit
```

### Uninstall
```bash
pi remove npm:@ai-ecoverse/pi-exit
```

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