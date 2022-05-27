## What is this?

This is a JavaScript Physics Engine that does not (yet?) exist. [See this Tweet](https://twitter.com/hmans/status/1520346369629769729). Maybe it doesn't exist because it can't be pulled off; maybe it just needs to be willed into existence.

_TODO: contact information so interested contributors can get in touch._

## Why?

There are plenty of options for physics on the web, but we don't believe any of them is "the one". [Ammo.js](https://github.com/kripken/ammo.js/) is a JavaScript port of [Bullet Physics](https://github.com/bulletphysics/bullet3), and probably is the most widely used of the bunch.

_TODO: write more about available options, and their shortcomings._

## Features

**Authored in TypeScript**, to keep things sane, hackable, and nicely typed.

**Tree-shakable**! The library should allow the user to pick and choose functionality as they need it. The aim is to allow it to support both smaller scale web experiences (where a compact bundle size is more important than features) and games (where advanced features are needed, and bundle size doesn't matter as much.)

**Support for both 3D and 2D**. 3D and 2D physics are very different in nature, but there's still enough common ground for a library like this to provide a similar API for both. (As per the previous point, we're relying on tree-shaking to remove the unused parts from the final bundle.)

**Supports fixed and variable steps**.

**Performance-minded**, eg. uses SoA ECS to reduce GC pressure, etc.

## FAQ

### But doesn't WASM give much better performance?

_TODO: write about WASM disadvantages & uncertainties_
