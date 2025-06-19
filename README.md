
<p align="center">
  <img src="https://i.pinimg.com/736x/0f/95/63/0f9563e6b55b8a9f69d907c3f716a3e5.jpg" alt="dark aesthetic banner" width="100%"/>
</p>


<p align="center">
  <span style="color: #b0b0b0; font-size: 18px;">
    Go-developer | Frontend-developer | Head of Development | Software Developer
  </span>
</p>

<p align="center">
  <a href="https://github.com/waste3d" target="_blank">
  <img src="https://komarev.com/ghpvc/?username=waste3d&color=1a1a1a&style=for-the-badge&labelColor=FFAE00" alt="Просмотры профиля"/>
</p>

## 💻 About me

```go
package main

import (
	"fmt"
)

type Developer struct {
	Name    string
	Role    string
	Skills  map[string][]string
	Passion string
}

func NewDeveloper() *Developer {
	return &Developer{
		Name: "Kolya",
		Role: "Head of Development(Human Help), Go-developer",
		Skills: map[string][]string{
			"Backend":    {"Python", "Go", "JavaScript"},
			"Microservices": {"gRPC", "Gin", "NATS"},
			"Databases":  {"MongoDB", "PostgreSQL", "Redis"},
			"Frontend":   {"HTML/CSS", "JavaScript", "VueJS"},
			"DevOps":     {"Docker", "Linux", "Git", "Kubernetes"},
		},
		Passion: "Write clean, optimized code that you can be proud of",
	}
}
func (d *Developer) String() string {
	return fmt.Sprintf("%s | %s", d.Name, d.Role)
}

func main() {
	me := NewDeveloper()

	fmt.Println(me)
}
```
🛠️ Technologies <br>
● Languages: Go, JavaScript, SQL, NoSQL<br>
● Frameworks: VueJS, Astro, gRPC, Gin, Fiber, Echo<br>
● Databases: PostgreSQL, MySQL, SQLite, MongoDB, Redis<br>
● Infrastructure: Docker, Linux, Git, Kubernetes<br>
● Other: OpenAPI, ViperConf, Logging<br>
