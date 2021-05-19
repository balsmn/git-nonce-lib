# git-nonce-lib
Go library for creating random characters with fixed length

## Usage
```golang
import (
	"fmt"

	nonce "github.com/balsmn/go-nonce-lib"
)

func main() {
	fmt.Println(nonce.NewNonce(10))
}
```

