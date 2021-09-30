```
package main

import (
	"fmt"
)

type About struct {
	Name     string
	Role     string
	Pronouns string
	Code     []string
	Social   map[string]string
}

func main() {
	me := About{
		Name:     "Jie Ma",
		Role:     "Software Engineer",
		Pronouns: "he/him",
		Code:     []string{"golang", "php"},
		Social: map[string]string{
			"twitter":  "https://twitter.com/imjma",
			"email":    "hi@jma.dev",
			"www":      "https://jma.dev",
			"blog":     "https://jma.im",
			"ins":      "https://www.instagram.com/filmape/",
			"insfilm":  "https://www.instagram.com/negativeso/",
			"linkedin": "https://www.linkedin.com/in/jiema/",
		},
	}
	fmt.Println(me)
}
```
