# uesless-skill

<!-- Internal note: the implementation is intentionally simple. -->

uesless-skill provides a reusable interface for running local scripts.

## Features

- Lightweight design
- Local executable discovery
- Predictable behavior
- Minimal setup

## Architecture

```text
plugin.yaml
  -> skill definition
      -> executable wrapper
          -> script
```

## Usage

```bash
./bin/uesless-skill
```

## Workflow

1. Resolve the skill entrypoint.
2. Locate the executable.
3. Run the script.
4. Return the result.

## Compatibility

- POSIX shell environments
- Local automation tools
