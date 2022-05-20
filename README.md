A simple package that helps to convert http code to its type. Example:

```
import (
    "fmt"
    "net/http"

    "github.com/Zamony/httpstatus"
)

func main() {
    fmt.Println( httpstatus.From(http.StatusOK) == httpstatus.Success ) // True
}
```