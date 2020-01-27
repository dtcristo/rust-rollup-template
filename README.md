<div align="center">
  <h1><code>rust-rollup-template</code></h1>
  <strong>Kickstart your Rust, WebAssembly, and Rollup project!</strong>
</div>

## About

This template is designed for creating monorepo-style Web applications with
Rust-generated WebAssembly and Rollup without publishing your WASM to NPM.

Be sure to check out [other `wasm-pack` tutorials online][tutorials] for other
templates and usages of `wasm-pack`.

[tutorials]: https://rustwasm.github.io/docs/wasm-pack/tutorials/index.html

## 🚴 Using This Template

You can use `npm init` to clone this template:

```sh
npm init rust-rollup my-app
```

## 🔋 Batteries Included

This template comes pre-configured with all the boilerplate for compiling Rust
to WebAssembly and hooking into a Rollup build pipeline.

- `script/start` -- Serve the project locally for development at
  `http://localhost:10001`. It auto-reloads when you make any changes.

- `script/build` -- Bundle the project (in production mode).

- `script/test` -- Run the project's unit tests.
