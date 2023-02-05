> # CtrlCmd

## Control output and input terminal from golang
## program - this easy !

</br>

> Install
```
go get -u github.com/YuranIgnatenko/CtrlCmd/ctrlCmd
```

***
> Use

``` go
package main

import (
	cmd "github.com/YuranIgnatenko/CtrlCmd/ctrlCmd"
	"time"
)

func main() {
    // send command and prind result
    cmd.Line("clear")
}

```
> If output print color text
``` go
cmd.LineColor("hello", "red", "bg")
cmd.LineColor("hello", "green", "bg")
```


> If need get output and save var
``` go
result := cmd.LineGet("ls")
```

***

