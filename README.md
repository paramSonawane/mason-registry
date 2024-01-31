Mason Registry for [codespell_columns](https://github.com/paramSonawane/codespell_columns) support.

To include the registry, add following in config:
```lua
require("mason").setup({
    registries = {
        "github:mason-org/mason-registry",
        "github:paramSonawane/mason-registry",
    },
})
```
