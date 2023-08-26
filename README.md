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
@package packageName.util
@package packageName.color

@package packageName.types.*
# or
@package packageName.types.string
@package packageName.types.int
```