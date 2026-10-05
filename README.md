# transport-pcg-mcp

A Model Context Protocol server in Elixir that grows tile levels by wave function collapse and solves constraint models.

## What it is for

It gives an agent tools to grow a tile grid from a sample pattern one step at a time or to completion, and to validate or solve constraint-programming models. The tool schemas the server lists say what each tool takes.

## Build and run

```sh
mix deps.get
mix mcp.server
```

The MiniZinc solver must be on the `PATH`; the `Dockerfile` builds an image that carries it.

## Licence

MIT; see `LICENSE.md`.
