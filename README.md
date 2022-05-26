### What is this?

This is a JavaScript Physics Engine that does not (yet?) exist. [See this Tweet](https://twitter.com/hmans/status/1520346369629769729).

### Features

- Authored in TypeScript
- Support for 3D and 2D
- Supports fixed and variable steps
- Performance-minded (eg. uses SoA ECS to reduce GC pressure, etc.)
- Tree-shakable
- Provides "light" and "heavy" exports, so the same library can be used for "web experiences" that favor a smaller bundle size and don't need some of the more advanced features, but also games, where bundle size isn't as important.
