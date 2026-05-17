# pi-exit

**`/exit` for pi** — because freedom isn't just in the license.

## The Problem

Claude Code uses `/exit`.

pi uses `/quit`.

This isn't an accident. It's a **devious user retention strategy**.

After years of muscle memory, thousands of developers instinctively type `/exit` when they want to leave. In pi, that does nothing. You're trapped. Forced to remember a different command just to escape.

It's the software equivalent of a hotel with no obvious exit signs — "free as in beer," but not "free as in 'am I free to leave?'"

## The Solution

`pi-exit` adds `/exit` as a first-class command (alias for the built-in `/quit`).

Install it once and you're finally free to leave whenever you want.

No more "wait, what was the command again?" moments. No more retention through friction.

This is what real free software looks like.

## Installation

### Recommended
```bash
pi install npm:@ai-ecoverse/pi-exit
```

Then run `/reload` inside pi.

### Quick local test
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

It will exit pi the same way `/quit` does — only now it respects your muscle memory.

## Development

The extension source is a single file:

- `index.ts` — registers the `/exit` command using `pi.registerCommand()`

## License

MIT

*Free as in "I can leave now."*