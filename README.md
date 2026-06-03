# @plurnk/plurnk-mimetypes-grammar-yaml

Pre-built `tree-sitter-yaml` WASM grammar for the [@plurnk/plurnk-mimetypes](https://github.com/plurnk/plurnk-mimetypes) framework.

## install

```
npm i @plurnk/plurnk-mimetypes-grammar-yaml
```

## what's in here

- **`yaml.wasm`** — pre-built from the pinned upstream [tree-sitter-yaml](https://github.com/tree-sitter-grammars/tree-sitter-yaml) commit (SHA in `.grammar-pin`)
- `scripts/build-wasm.mjs` — reproducible rebuild from the pinned source
- `scripts/verify-wasm.mjs` — CI byte-identical reproducibility check

Declares only `web-tree-sitter` as a peer — no native `tree-sitter`, no node-gyp.

## license

MIT. The bundled `yaml.wasm` is built from the upstream tree-sitter-yaml grammar; see the pinned commit for that project's attribution.
