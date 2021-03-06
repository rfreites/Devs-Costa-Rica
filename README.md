# Desarrolladores Web Costa Rica
Un listado de desarrolladores Web (y de otras áreas) costarricenses quienes tienen disponibilidad para contribuir con proyectos a manera de freelance o full-time.

El formato que deberemos seguir será el siguiente:

###Manuel Ro: Front End Development
```javascript
{
    "Devs-Costa-Rica":{
        "El formato que debes seguir, colocalo en la sección que corresponda (Web, Mobile, Desktop)":{
            "id":"Coloca tu id consecutivo al anterior valor del tipo entero",
            "nombre":"Nombre y Apellido",
            "contacto":[
                {
                    "telefono":"+506 8888 8888",
                    "email":"tucorreo@dominio.com",
                    "disponibilidad":[
                        {
                            "freelance":true,
                            "part-time":false,
                            "full-time":false
                        }
                    ]
                }
            ],
            "website":"https://www.sitioweb.com",
            "proyectos":[
                "http://un-proyecto.com",
                "http://otro-proyecto.com"
            ],
            "web":{
                "experiencia":[
                    "Front-End",
                    "Back-End"
                ],
                "Stack":[
                    "html5",
                    "css3",
                    "Javascript",
                    "jQuery",
                    "SASS",
                    "Gulp",
                    "WordPress",
                    "Magento",
                    "Laravel",
                    "PHP",
                    "JSON",
                    "Git",
                    "Git-Hub"
                ],
                "idiomas":[
                    "en",
                    "es"
                ]
            }
        }
    },
    "web":{
        
    },
    "mobile":{

    },
    "desktop":{

    }
}
```

##Cómo agregar mi información de contacto
Junto con este archivo encontraras tres archivos más, estos son `Web.md`, `Mobile.md` y `Desktop.md`. Cada uno de esos archivos representa un área generalizada de experiencia o especialización. Para agregar tu informacion de contacto deberás clonar este repositorio y proponer los cambios mediante un pull request.

Tu información de contacto deberá ser insertada debajo del último contacto existente, y deberás encerrar el objeto de JavaScript con un fence, o tres ‘```’ para que sea reconocido como código y tenga una mejor presentación. Los requests que no cumplan con este formato no serán aceptados.

###Heading
El heading estará compuesto por tu nombre completo, seguido de dos puntos (:) y la especialización, es decir, `{nombre} : {especializacion}`. Este heading deberá ser de grado 3, es decir, precedido por `###`.

###Experiencia
La experiencia previa, nombre de la compañía o nombre del título. Si no tienes experiencia deberás dejar el arreglo vacio (`experiencia: []`).

###Stack
Las tecnologías con las que te sientes cómodo trabajando, pueden ser lenguajes de programación, frameworks o herramientas en general. Este arreglo deberá tener un máximo de 5 elementos.

###Idiomas
Los idiomas con lo que te sientes cómodo, y aquellos que conoces en más de un 50%.

###Nombre
Tu nombre completo, para que de esta manera la persona interesada te pueda diferenciar más fácilmente.

###Teléfono
Un teléfono vigente al cual te puedan contactar.

###Email
Un email vigente al cual te puedan contactar.

###Disponibilidad
Es un booleano mediante el cual podrás expresar tu disponibilidad, `true` nos indica que estas disponible.

###Website
Un sitio Web, blog o perfil de alguna red social donde la persona interesada pueda saber mas de vos.

###Proyectos
Un arreglo con los últimos 5 proyectos que has realizado. Asegurate de agregar solo los mejores. Si no tienes proyectos puedes dejarlo vacío.

##Solicitando ser agregado a la lista
Una vez hayas completado los datos, puedes hacer un pull request. 

###El formato del commit y su mensaje
El nombre del commit deberá tener el siguiente formato: `Add { nombre }`, deberás reemplazar `{ nombre }` con tu nombre completo.
