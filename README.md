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

    "github.com/eayavas/stringutils"
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

1. `fork` (https://github.com/eayavas/stringutils/fork)
1. Create your `branch` (`git checkout -b my-feature`)
1. `commit` yours (`git commit -am 'add some functionality'`)
1. `push` your `branch` (`git push origin my-feature`)
1. Than create a new **Pull Request**!

---

## License
This project is licensed under MIT

---

## Code Of Conduct

This project is intended to be a safe, welcoming space for collaboration, and
contributors are expected to adhere to the [code of conduct][coc].

[coc]: https://github.com/eayavas/stringutils-demo/blob/main/CODE_OF_CONDUCT.md
