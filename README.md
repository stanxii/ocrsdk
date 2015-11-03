ocrsdk
======

ABBYY Cloud OCR SDK

### Install

`go get github.com/poorny/ocrsdk`

### Usage


Export to env `APPLICATION_ID` and `PASSWORD`.

_See [Docs](http://ocrsdk.com/documentation/)_

```go
package main

import (
	"fmt"

	"github.com/poorny/ocrsdk"
)

func main() {
	path := "/path/to/file.pdf"
	lang := "English"

	result, err := ocrsdk.Ocrsdk(path, lang)
	fmt.Println(result)
}
```
