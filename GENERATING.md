# Generating

The binary literals were generated with code similar to the following:

```go
package main

import (
	"fmt"
)

func main() {

	for i:=0; i<=255; i++ {

		fmt.Printf("\tB%08b = byte(0x%02x)\n", i, i)

	}

}
```
