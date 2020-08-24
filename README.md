1. Build `*.html`
2. Open dist/c.html. `y` shouldn't execture twice (in two different bundles) and `false` is printed
3. Build `c.html`
4. Open dist/c.html. `y` are executed once and `true` is printed

`true` means that the context is actually the same (`===`)