# Genesys Brand Devo

![license](https://img.shields.io/github/license/devoinc/genesys-brand-devo)
![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/devoinc/genesys-brand-devo/ci.yml)
[![npm version](https://img.shields.io/npm/v/@devoinc/genesys-brand-devo?label=%40devoinc%2Fgenesys-brand-devo)](https://www.npmjs.com/package/@devoinc/genesys-brand-devo)

_Devo_'s main brand schemes of design tokens defined by _Genesys Design System_.

This package contains the brand schemes as `json` files, required to generate
Devo's **light** and **dark** brands.

A preview of the generated tokens can be found in
[this page](https://devoinc.github.io/genesys-brand-devo/).

## Usage

```typescript
import { dark, light } from "@devoinc/genesys-brand-devo";

console.log(light.cmp.appBar);
console.log(dark.cmp.appBar);
```

## Quick start

To generate the brands from the available schemas, this project uses the `gyt`
CLI from [@devoinc/genesys-tokens-cli](https://github.com/DevoInc/genesys-tokens/tree/master/tokens-cli).
Please refer to the `gyt` package [documentation](https://github.com/DevoInc/genesys-tokens/blob/master/tokens-cli/README.md)
for further information.

```sh
npm ci
npm run dist
```

The brands are now available in the `dist/` folder.
