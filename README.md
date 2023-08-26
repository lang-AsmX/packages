# packages
This is the package database center for AsmX

# Examples:

Structure:
```
package-name/
    util/
        index.asmX
    color/
        index.asmX
    types/
        string/
            index.asmX
        int/
            index.asmX
    [index | main].asmX (Optional)
    settings.json
```

AsmX:
```
@package packageMame.util
@package packageMame.color

@package packageMame.types.*
# or
@package packageMame.types.string
@package packageMame.types.int
```