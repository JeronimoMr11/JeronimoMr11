### Hi there 👋

<!--
**JeronimoMr11/JeronimoMr11** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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
		"- 📖  Breve biografia:":              "Ingeniero en Sistemas Computacionales, tengo 22 años, tecnologia, y videojuegos",
                "- ⚡  Skills :":                      "Programacion, Redes, Soporte IT, Hacking",
		"- 🔭 Actualmente estudio en ":          "Tecnologico Nacional de Mexico Campus - Tantoyuca, Ver.",
		"- 🌱 Actualmente estoy aprendiendo":   "Javascript, BackEnd y IA)",
}
-->
