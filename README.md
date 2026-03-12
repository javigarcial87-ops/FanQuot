FANQUOT


Este proyecto se realizaría con un frontend y un backend por separado (una carpeta  para el backend y una carpeta el frontend, pero los dos juntos hacen la app)

 
- El frontend se realizaría mediante react + vite.
- El backend se realizaría mediante node JS y express.
- La base de datos mediante mongo atlas.
- El deploy de momento se realizaría en render.
- Los estilos mediante CSS dentro del proyecto.
- Que visualmente, a parte del navegador, sea responsive y funcional en móvil o Tablet. 

Contaría en principio con:

- Una serie de cards previamente creadas en un array de objetos que se mostrarían en pantalla.

- Un Login y un logout, donde:...:

- El usuario logeado puede crear sus cards en un formulario en el que cuenta con inputs para introducir: nombre del personaje, imagen del personaje, tipo de medio(pelicula, serie de TV, libro o videojuego) y titulo del medio y un cuadro de  texto con la frase o cita, con un numero limitado de caracteres, correspondiendo al tamaño standart de la card. Contarían con un botón de tipo "submit" para añadir la card creada al resto de cards. Los datos de cada usuario se gauardarian en localstorage.

-El administrador, mediante unas credenciales especificas, a parte de contar con poder crear cards nuevas, es el único que puede borrar cards a placer desde un menú especial para administrador, en el que aparecerán  las cards con un botón extra "delete" para eliminar la card deseada permanentemente. 


"FanQuot"

Una app que muestra frases o citas famosas de personajes ficticios de películas, videojuegos,
 libros o series, mediante "Cards" en las que se muestran los datos por este orden:

- Nombre del personaje.

- Imagen de referencia del personaje, dentro de un cuadro limitado al tamaño standart (provisional) de la card.

- Tipo de medio (película, libro, serie de tv o videojuego) junto con 
el título de dicho medio.

- Frase celebre o cita famosa de tal personaje con un máximo de unos 600 caracteres (provisional según tamaño de card).



- Que consumirá APIS (gratuitas o de libre acceso) con base de datos de películas, libros, series(TV) o videojuegos  solo para referenciarse del tipo de medio o su titulo. 

- Que muestre mediante un input de texto buscador, introduciendo el nombre del personaje o el titulo del medio donde aparecen,  y que muestre  
todas las coincidencias con la búsqueda, pudiendo repetirse el mismo medio. Es decir: 
- En un mismo medio puede haber varias frases o varios personajes con frases o citas o que un solo personaje tenga
varias frases o citas, mostrando en pantalla las cards que coincidan con la búsqueda. 
	


- Que tanto administrador como usuario, al logarse puedan crear, mediante un formulario, sus propias cards con nombre de personaje, imagen, medio y título del medio en el que aparecen y la frase o cita, solo accesible al logarse.

- El administrador puede borrar las cards que quiera desde un menú administrador por el que se accede mediante unas credenciales especificas donde se muestran todas las cards y un input para buscarlas por nombre de personaje o nombre del medio, ignorando mayúsculas, minúsculas, tildes o caracteres especiales. al acceder a la card, solamente el método administrador, cuenta con un botón de eliminar en cada card, para poder borrarlas permanentemente según la necesidad.



EXTRAS:
- En la pagina principal se mostraran las ultimas  10 cards añadidas por los usuarios o por el administrador.
- Un input de texto para busqueda por título de medio o nombre de personaje, para mostrar las cards que coinciden con la búsqueda, podrás buscar tu referencia por nombre de personaje o título del medio en el que aparecen, sin importar mayusculas, minusculas o caracteres especiales.

- Sistema de votación que mediante un botón de me gusta en cada card. Haga que aparezcan en la pantalla principal las cards mas votadas. Es decir, cada card mostrada, cuenta con un botón de me gusta donde el usuario logado pueda votar una sola vez por cada card.

- La card más votada (por número de likes) aparecerá  en un apartado en la pagina principal llamado: "Frase destacada"(provisional)