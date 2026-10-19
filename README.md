# Hoja de vida web - Juan David Paz Santos

Holaa, este es mi sitio, aqui esta mi hoja de vida, unos proyectos que he hecho y como contactarme. Lo hice solo con HTML y CSS, con grid y media queries pa que se vea bien en el cel y en el compu. Todo en negro y rojo porque asi es mas melo ;)

**Sitio publicado:** https://pazzz200.github.io/hoja-de-vida_Paz/

## Paginas

- index.html: mi hoja de vida
- proyectos.html: mis proyectos
- contacto.html: mi correo y mi github

Las 3 tienen el mismo menu arriba (Inicio, Proyectos, Contacto) asi que uno puede ir y volver entre ellas.

## Mockups

Primero hice un boceto a la loca pa saber donde iba cada cosa:

![Boceto de las paginas](mockups/Mockups%20de%20la%20hoja%20de%20vida%20web.jpg)

Y despues hice uno ya bonito con los colores, ahi estan las 3 paginas en compu y en cel:

![Mockup final](mockups/mockup%20de%20paz%202.0.png)

Los nombres de las areas que use en el grid-template-areas son:

- en todas las paginas: cabecera, menu, principal y pie
- en la hoja de vida: hero, sobre, resumen, formacion, habilidades y competencias (y adentro del hero: texto y arte)
- en contacto: intro, medios y arte

## Capturas de la pagina

Asi se ve en el compu:

![Pagina en el compu](mockups/Captura%20de%20pantalla%202026-10-19%20011427.png)

Y asi se ve en el cel:

![Pagina en el cel](mockups/pagina%20web%20desde%20celu.png)

## Breakpoints

- **Cel (la base):** todo va en una sola columna, uno debajo del otro. El portatil va debajo del texto y en contacto no sale el sobre.
- **Desde 600px:** la hoja de vida se pone en 2 columnas, sobre mi al lado del resumen y habilidades al lado de competencias. El texto y el portatil quedan lado a lado y los botones en fila.
- **Desde 1024px:** la columna de la izquierda se vuelve mas ancha (2fr y 1fr) y en contacto aparece el sobre rojo grandote a la derecha.

Las tarjetas usan repeat(auto-fit, minmax()) entonces se acomodan solitas segun el espacio.

## Como lo publique

1. Cree el repo en github y lo deje publico.
2. Fui subiendo los cambios con git add, git commit y git push.
3. En el repo me fui a Settings y despues a Pages.
4. Ahi escogi "Deploy from a branch", la rama main y la carpeta root, y le di Save.
5. Espere unos minutos y salio el link. Cada vez que hago push se actualiza solo pero se demora un ratico.

Algo que aprendi es que la pagina principal se tiene que llamar index.html porque es la que abre github pages por defecto, y que hay que tener cuidado con las mayusculas en los nombres porque si no sale error 404.

## Fuentes

- https://docs.github.com/es/pages/quickstart
- https://docs.github.com/es/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
- https://developer.mozilla.org/es/docs/Web/CSS/CSS_grid_layout
- https://validator.w3.org/
