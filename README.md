# NGR-clickhouse
Clickhouse golang driver with custom fixes

fixed:
- support Array(Nullable(TypeName)) Parse() (excluding FixedString)

# import
```
import (
  _ "github.com/NGRsoftlab/NGR-clickhouse"
)
```
