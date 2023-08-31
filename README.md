# stringutils

stringutils is a collection of small utility tools for `string` type.

---

## Installation

...bash
go get github.com/eayavas/stringutils-demo@latest
...

---

## Usage
...go
package main

import (
    "fmt"

    "github.com/vigo/stringutils-demo"
)

func main(){
    reversed, err := stringutils.Reverse("vigo")
    if err != nil {
        log.Fatal(err)
    }
    fmt.Println(reversed) // ogiv
}
...

---

## Contributor(s)
* [Efe Arda YAVAŞ](https://github.com/eayavas) -- Maintainer

---

## Contribute

All PR’s are welcome!

1. `fork` (https://github.com/vigo/stringutils-demo/fork)
1. Create your `branch` (`git checkout -b my-feature`)
1. `commit` yours (`git commit -am 'add some functionality'`)
1. `push` your `branch` (`git push origin my-feature`)
1. Than create a new **Pull Request**!

---

## License
This project is licensed under GPLv3

