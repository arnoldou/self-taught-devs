# ¿Colaborar? , yay :heart_eyes::zap: !

Para colaborar ve a [./goodies.toml](./goodies.toml) y agrega un nuevo goodie intentando seguir este formato

```toml
["Heroku"]
description = "Una descripción genial :heart_eyes:"
contributor = "@tuperfildeGH"
website = "https://elurldelgoodie"
type = "tool"
```

# Formato

`["El nombre del goodie"]`

| campo       | tipo de dato                | default      |
| ----------- | --------------------------- | ------------ |
| description | String                      | ?requerido   |
| contributor | String                      | "d3portillo" |
| website     | String                      | "#"          |
| type        | [String](#tipos-de-goodies) | "none"       |

# Tipos de goodies


| Clave | Valor |
|-------|-------|
| tool | Herramientas |
| yt | Youtubers |
| reading | Libros / lectura |
| codecamp | Codecamps |
| hack | Hackathon / Codejam |
| tutorial | Tutoriales |
| course | Curso |
| none | Sin especificar |
| twitter | Perfiles de Twitter |

> Lista de tipos en [./goodieTypes.js](./goodieTypes.js)
> Cualquier PR es bienvenido ! :)