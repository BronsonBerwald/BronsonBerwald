<img src="https://camo.githubusercontent.com/3b7c592ede97b6138ffd4b1cc1541c2f3b11fd39/687474703a2f2f33312e6d656469612e74756d626c722e636f6d2f31376665613932306666333665663466356238373764353231366137616164392f74756d626c725f6d6f39786a65387a5a34317163626975666f315f313238302e676966" height="175px" width ="175px">

```
package main

import (
	"fmt"
)

type Bio map[string]string

func main() {
	for k, v := range GetBio() {
		fmt.Printf("%+v: %+v\n", k, v)
	}
}

func GetBio() Bio {
	return Bio{
		"- ⚡ Quick bio:":                    "A kind of metalHead-melomaniac-gearAddict-amateurMusician-traveler-foodLover-gamer-coder-programmer-catLover-sportsAficionado hybrid",
		"- 🔭 I’m currently working on":      "Tredicom as a Senior Software Developer --- UAdeC as a Part Time Teacher",
		"- 🌱 I’m currently learning":        "Golang, MongoDB, RabbitMQ, K8s, GCP (Tech stack from my company) --- Sharpening my Front End Skills for the MERN stack (Personal goal)",
		"- 👯 I’m looking to collaborate on": "Python, Golang and Docker related projects",
		"- 🤔 I’m looking for help with":     "Anything related to what I am currently learning 😅",
		"- 💬 Ask me about":                  "Python, PHP, Laravel, SQL, Software Design & Architecture, Web-Dev and SEO",
		"- 📫 How to reach me:":              "https://github.com/AnhellO#you-can-reach-me-at-alien",
	}
}
```
