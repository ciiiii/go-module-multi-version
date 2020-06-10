# go-module-multi-version
exmaple for maintaining of mutli version Go Module Project.

branches:
+ v1
+ v2
+ v3

tags:
+ v1.0.0
+ v1.0.1
+ v2.0.0
+ v2.0.1
+ v3.0.0

import example
```golang
package main

import (
	"github.com/ciiiii/go-module-multi-version/example"
	v2Example "github.com/ciiiii/go-module-multi-version/v2/example"
	v3Example "github.com/ciiiii/go-module-multi-version/v3/example"
)

func main()  {
	example.Example()
	v2Example.Example()
	v3Example.Example()
}
```