# WEATHER IS SWEET YEAH! BY PABLO FERNÁNDEZ

El proyecto "Weather is sweet!" planteado en la asignatura "Desarrollo de interfaces", nos anima a crear nuestra propia página web para consultar el tiempo y clima.
Es gracias a la API suministrada por "https://openweathermap.org/" y sus clausulas que podemos generar nuestra propia web haciendo diferentes consultas en las funciones además
de utilizar nuestros propios estilos y bootstrap.

Las tareas planteadas que debíamos realizar son las siguientes:
  - Diseño de la página (HTML, Bootstrap, SCSS, CSS, img...)
  - Funcionalidad de la página (JS, jQuery, jQuery Ajax...)
  
  
# Diseño de la página
La página podía tener el diseño deseado por cada uno haciendo uso de SCSS y CSS pasando por el compilador "Koala" e implementando tantas clases de bootstrap como cada uno 
quisiese, sin importar los colores, la tipografía, los márgenes, etc. Eso sí, debía contener un menú de navegación que mostrase los diferentes elementos de la web:
  - Home: Sección principal de la página que mostrase un título y una pequeña explicación de la página 
  - Buscar: Botón que hace aparecer una sección oculta y que nos permite buscar ciudades a través de un input y un botón "buscar"
  - Ubicación: Más adelante trabajeros en esta sección (Requiere al usuario su ubicación, si la respuesta es correcta muestra los datos del clima y temperatura de la ciudad en la que está actualmente)
  - Bandera: Imagen-botón con la bandera de España o el Reino Unido respectivamente, al hacer "click" sobre una de estas el href nos dirige a otra página traducida al idioma elegido.

# Funcionalidad de la página
Los diferentes botones esparcidos por la web permiten al usuario un cómodo e intuitivo desplazamiento por la misma además de ejecutar sus funciones.
Los botones de secciones permiten ocultar y desocultar estas, haciendo que un gran código no se vea y la web parezca más limpia y ordenada.

Por otro lado, el boton de búsqueda de una ciudad, ejecuta dos funciones:
  - Mostrar el clima en forma de descripción y un icono de esta.
  - Mostrar el clima en forma de descripción, un icono de la misma y en que día de la semana será (Los días posteriores a hoy, que es el día que se busca)
  - Mostrar todo lo anterior, pero solicitando la ubicación al usuario. Si este acepta, la mostrará.
  
Para poder realizar todas estas consultas hemos tenido que utilizar una API y su respectivo "token" de activación. Gracias a las propiedades que incluye somos capaces de recorrer 
y seleccionar aquellos parámetros necesarios y mostrarlos por pantalla en nuestra web.
