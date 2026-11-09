# Cócteles Don Eustaquio
Breve descripción del sitio web y de su temática.
## Autoría
- Nombre y apellidos: Iván Montoro Ruiz
- Curso: 1º DAM
- Módulo: LMSGI
- Fecha: 
## Sitio publicado
- Web en GitHub Pages: [Abrir sitio](URL-DE-GITHUB-PAGES)
- Repositorio: [Abrir repositorio](URL-DEL-REPOSITORIO)
## Estructura del proyecto
- `index.html`: Pequeña introdución al mundo de la mixología y cócteleria.
- `blog.html`: Origen y evolución de la mixología y la cócteleria. 
- `tabla.html`: Explicación de los 5 cocteles mas pedidos por todo el mundo, especificando, ingredientes, graduación y tipo de cristaleria. 
- `galeria.html`: Recursos multimedia sobre la mixología y el trabajo relacionado a ella, recursos con imagenes, videos, audios y un enlace a google maps.
- `formulario.html`: Un formulario de satisfacción del consumidor y interes personal en la calificaion de la pagina y cóctel que le gustaría probar.
- `rss.xml`: descripción del canal RSS.
- `css/estilos.css`: La plantilla que estaba en la documentación, asi que ese es el estilo que he utilizado.
## Tecnologías utilizadas
- HTML5
- CSS
- XML y RSS
- Git
- GitHub
- GitHub Pages
## Características principales
- Navegación entre cinco páginas.
- Uso de HTML semántico.
- Tabla accesible.
- Galería con varios formatos.
- Contenido multimedia.
- Formulario con validación HTML.
- Canal RSS.
## Validación
### HTML
![Resultado de validación HTML](img/validacionHTML.png)
### CSS
![Resultado de validación CSS](img/validacionCSS.png)
### RSS
![Resultado de validación RSS](img/validaciónXML.png)
## Dificultades encontradas
Describe al menos tres dificultades reales:
1. La primera dificultad fue mas bien un mal entendido, que se ve refflejado en los commits, comencé el proyecto de arriba hacia abajo sin leer el documento entero al principio, por lo tanto, cuando ya tenía casi todo el proyecto terminado, llegue a la sección de los commits y git, asi que para cumplir con esos requisitos tuve que hacer commits artificiales poniendo y quitando manualmente los elementos html y haciendo commits de estos pasos, por eso los tiempos son irreales.
2. En la galería con el uso de "usemap" y "map", las coordenadas me costaron bastante y desistí, utilice la IA para que me calculase las coordenadas y las pegue.
3. Al hacer la validación de mis paginas webs, tuve muchos errores a la hora de insertar las imagenes con el width="300px" y height="auto", ya que estoy acostumbrado a usar css y pensaba que se debia indicar el formato y la altura, pero no es necesario, simplemente era dejarlo en width="300" y no poner height, fue mas bien una pequeña confusion.
4. Con los subtitulos use una IA especial a la que le pasabas el video y te generaba los subtitulos en el idioma que prefieras, tuve problemas porque no veía los subtitulos cuando los visualizaba desde mi maquina local, pero luego al usar el live server, vi que este error se solucionaba.
5. El enlace del video era muy aprecido al error 4, en local youtube me rechazaba la conexion pero en live server lo aceptaba.
## Decisiones técnicas
Explica brevemente:
- Los archivos estan organizados tal y como se especificó en la documentación.
- Todo lo que se repite es el nav y el head, siendo este el unico que cambien en la etiqueta title.
- La estructura se queda mas o menos si tocar, la diferencia es que en tabla.html, obviamente se ha integrado la etiqueta table, con sus respectivos thead, tbody y tfoot. En galería la estructura es muy parecida pero dentro de cada section, hay etiquetas figure, 
- Los he elegido porque me lo pedia lo documentación, pero si tuviese que elegir exclusivamente solo un formato elegiría webP, ya que la relacion calidad-peso es excelente, y de hecho ese formato esta creado justamente para paginas web.
- Las rutas relativas las he hecho como cualquier mortal las haría, miras tu proyecto y la jerarquía de carpetas que tiene y pones en img/ejemplo.jpeg.
- He linkeado todas las partes de la pagina web a una misma hoja de estilos para que cuando vaya a editarla, deba de aplicarse el cambio a todas las paginas, cuando empezemos con css, probablemente empezare con el uso de id y class
## Fuentes y licencias
[Historia de la Coctelería](https://bonviveur.com/es/actualidad/origenes-e-historia-de-la-cocteleria)
[Origen de la Coctelería](https://dkristal.es/conoce-el-origen-de-la-cocteleria/)
