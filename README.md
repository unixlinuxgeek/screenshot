### Библиотека для создания скриншотов

Устанавливаем зависимости:
```bash
go get github.com/unixlinuxgeek/screenshot
```


Пример использования:
```go
package main

import (
	"github.com/unixlinuxgeek/screenshot"
	"log"
)

func main() {
	err := screenshot.Capture()
	if err != nil {
		log.Fatal(err)
	}
    // do something...
}
```