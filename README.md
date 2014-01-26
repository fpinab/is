Documentación
==
20-01-2014 

0.47 Documentación inicial, probando el scroll down.

2.50 Leyendo mucho, no funciona el scroll suave. Al parecer estoy enlazando mal con el bootstrap el enlace, pero el jQuery no está pescándome nada.

4.24 He logrado adaptar el bootstrap pero con un tiempo de movimiento no agradable, más bien rápido. El error es que la fuente no usa un template, entonces al adaptarlo a bootstrap había que modificar el archivo css/style.css que era propio del ejemplo. Eso no permitía que me saliera.

15.07 Pruebo nueva barra. http://getbootstrap.com/examples/navbar-fixed-top. Me gusta que no quede en la orilla el nombre, pero habría que solucionar lo del logo pues tengo que poner el logo.

21-01-14

2.17 He visto un millar de ejemplos. Creo que lo definitivo será una single page con jumbotron y un carrusel en la primera página. Dada mi novatez, empezaré haciendo el banner con logo y colores. Sé que puede ser poco productivo, pero así me empiezo a manejar con algo de css. Pretendo terminarlo en un día.

Herramientas:

http://startbootstrap.com/logo-nav
Importante, responsive retina display: http://retinajs.com/

Design Recommendations:
Use a retina-ready, responsive image option for the logo in the navigation bar, for example, retina.js.
The menu items are centered with a faux center. You will need to edit the logo-nav.css file if you change the size of the logo or the size of the menu items in order to recenter the menu items.

4.04 Un éxito la creación del logo en el sitio, para Chrome.

Dudas:

5.56 Las referencias (#) se quitan cuando las ocupo...interesante. He encontrado una jumbotron carrousel page, sin smooth scrolling, muy llamativa. Usaré el banner definitivamente hasta que haga la maqueta de la página, el cambiar el banner será fácil si logro hacer la maqueta restante.

RESPUESTA: hay que hacer un filtro con javascript. Eso elimina el path que viene tras el enlace principal.

17.56 Estaré probando bootply cómo hacer el carrousel en hero.

22.01.14

3.25 Tras largas horas de indecisión, he avanzado, pero no en carrousel. Tengo el banner inverse default, con smooth scroll. He aprendido lo básico de jquery y javascript.

24.01.14

4.24 Uf, cómo empezarlo. He logrado obtener el carrousel dentro del jumbotron y sin el.

Las medidas CON jumbotron son 250x200 para el logo y 760x200 para el carousel. Margen odioso. Con container.
Las medidas SIN jumbotron son 250x330 para el logo y 850x330 para el carousel. Sin márgenes. Con container.

6.15 Logrado para abmos casos, y con linkeo. Problemas con el desplazamiento vertical por la barra que, está desplazándose ante cualuiqer #. Tengo que ser selectivo a la hora filtrar en el javasript.

7.15 Vista general de ambas páginas.

20.54 Ya han sido presentadas ambas versiones ante los clientes. Ha sido preferida la que no tiene jumbotron. Trabajando en ella.

25.01.14

2.30 Hablar con cliente, mostrarle los avances y situaciones. Pedir referencias acerca de cada título de texto. "Nuestro enfoque es la auditoría de fraude y BDO tiene un perfil más contable".

Términos valiosos: 

- Evaluación de impactos financieros
- Evaluación de sistemas de control interno

Borré: peritajes criminalísticos*.

4.04 Font Awesome para el banner listo y detalles de justificación de íconos.

26.01.14

6.46 Gran avance! Arreglé corrimiento de página en linkeos (#, del js). No muestra dropdown list tras pinchar una vez. En Chrome corre sin ningún problema. Google fonts tiene una interesante familia de fuentes para jugar con ellas. 

FALTA:

- Creación del logo con isotipo.
- Hacer responsive imágenes y texto, incluyendo la página principal. Separación entre logo y carousel para responsive.
- Modificar tipografía e inconografía del centro y del texto. Banner OK!
* Slider dropdown menu.
