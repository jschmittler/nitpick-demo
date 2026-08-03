# Nitpick prototype

This repository contains the generated static files for the public Nitpick prototype at [jschmittler.github.io/nitpick-demo](https://jschmittler.github.io/nitpick-demo/).

The application source, product strategy, and heuristic definitions remain in a separate private repository. This repository is a deployment artifact and should not be edited by hand.

## Publishing an update

Build the private Nitpick project with `pnpm build:pages`, then replace this repository's generated files with the contents of its `out/` directory and push the result to `main`.
