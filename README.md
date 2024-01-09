<!-- Comentarios -->



# Mi Titulo
## Mi titulo 2 xd
### Mi titulo 3 B
#### titulo 4
##### titulo 5

<!-- aaaa xdxd -->
podemos tener un previsuador en visual studio code, para usarlo hay que presionar **ctrl + shirt + p** y de hay buscar **markdown** y buscamos el que diga **markdown open preview**

this is an *italic* text

this is an **stronrsd**

este es un ~~texto~~ tachado


<!-- UL -->
* apple
    * apple 2
* orange
    * asaasdasasd
* etc

1. apple
    1. apple 2
2. orange
3. etc


[faztweb.com](https://www.faztweb.com "CUSTRON TATILE")

> ESTO ES UNA CITA

---

___


`console.log("hello woerd")`

```typescript
import { type Doc ,type APISpace } from '../types/api'

export const getLastesBy = async ({id} : {id : string}) => {
    const res = await fetch(`https://api.spacexdata.com/v5/launches/${id}`)

    const launch = (await res.json()) as Doc
    return launch
}
```

| Tablas    | XD | a |
|-----------|----|---|
| cols      |saas|sadsd |
|xd | xd | xs|

![visucla estudio lof](meme.webp)


<!-- GITHUB MARKDOWN -->

Significa que de aqui para alante solo sirve para github

* [x] tarea 1
* [ ] tarea 2
* [ ] tarea 3
* [x] tarea 4

@faztweb :smiley:

Lista de todos los emojis para github : [aqui](https://github.com/markdown-templates/markdown-emojis "emojis :smiley:")

para mas informacion de [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)]