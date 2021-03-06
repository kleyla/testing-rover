# Test rover
Esta es una guía acerca del test que se realizaran para la selección del nuevo integrante de telemetria.


Como se había mencionado en las entrevistas, se tiene planeado realizar un test a cada uno de los postulantes, de manera que, nos demuestren sus habilidades, y asi poder seleccionar al ganador.

El test es algo sencillo y básico respecto a las tecnologías consultadas en la entrevista.

### Se tomará en cuenta en general:

- Buenas prácticas.
- Código sencillo de leer (Esto quiere decir que no es necesario hacer maravillas de codigo).
- Reusabilidad y capacidad para escalar el codigo.

En cuanto al test, este se dividirá en dos partes; Frontend y "Backend".

## Test Frontend

#### Los criterios a tomar en cuenta en frontend son:

- UX Design: Muy deseable, ya que necesitamos hacer una aplicacion eficaz y sencilla.
- Uso de Hooks en React JS: Si no tiene conocimientos en ello puede realizar todo simplemente con componentes, pero este punto de uso de Hooks aumenta mucho su puntuacion, ya que se trabajará con ello.
- Uso de Bootstrap o Material UI: Simplemente se pide algo sencillo, como un Navbar, tamaños de letra adecuados y poco mas, aunque se puntuará muy bien que la responsividad este bien implementada.

### Entrega del trabajo:

El trabajo se recibira mediante (Elegir solo uno):
- El link al repositorio, ya sea en github, bitbucket, gitlab, etc (Esto queda a su criterio, con el que mas se sientan cómodos). 
- El link a la web subida en algun servicio de hosting, osea, la aplicacion web funcionando en internet.


### Idea General:

Como usuario final, requiero una aplicacion web que me muestre distintas ubicaciones mediante mapas dinámicos, las distintas ubicaciones a mostrar son:

- La plaza 24 de Septiembre en Santa Cruz de la Sierra, Bolivia.
- La plaza principal de la ciudad de La Paz.
- Copacabana, La Paz.

#### Detalles técnicos.

En cuanto al barra de navegacion, requiero:

- Un navLink que me lleve al Home.
- Un navLink que me lleve al About.

En cuanto a pantallas, requiero:

- Una pantalla principal que sera el Home y debe cumplir: 
  - Esta sera la pantalla donde se me redireccionara cuando en la barra de navegacion yo de click sobre el navLink Home.
  - Que me muestre mediante cards las tres ubicaciones mencionadas anteriormente, y cuando yo de click sobre alguna de las cards, me lleve a su pantalla correspondiente con el mapa mostrando la ubicacion que la card muestra.
  - Cada card en esta pantalla principal solo deberia mostrar un texto con la ubicacion la cual contiene.
- Una pantalla acerca de, que sera el About y debe cumplir:
  - Mostrar mas detalles acerca del postulante, este punto se va mas a presentarse mediante esta pantalla, aca se vera sus habilidades de hacer diseño y tratar de hacerlo lo mas "bonito" posible.
  
#### Recursos.

Para conseguir el uso de los mapas dinamicos ocupar la libreria leaflet y su integracion a React JS:
- https://leafletjs.com/
- https://react-leaflet.js.org/
  
 Como se habia mencionado, para el diseño, hacer uso de BootStrap o Material Design:
 - Bootstrap: https://getbootstrap.com/
 - Material Design: https://material.io/design
 
Puedes optar por cualquiera de las dos, te lo dejo a tu criterio, aunque te aconsejaria hacer uso de bootstrap ya que es algo mas rapido y sencillo de implementar y entender.

La importacion y el uso de las librerias, tambien te las dejo a tu criterio, puedes usar el gestor de paquetes npm, asi como tambien instalaciones CDN, sientete libre, al final lo que tomare en cuenta nada mas, es lo mencionado alla arriba, en "Los criterios a tomar en cuenta en frontend" y los criterios en general.

Tambien puedes hacer retrospectiva de tus trabajos realizados para sumar puntos, haznos llegar en una lista de los proyectos que tienes ya realizados y de ser posible, de acuerdo a la politica de privacidad de tu trabajo, pasar el codigo, cabe recalcar que solo tienes que pasar trabajos realizados en React JS.

## Test Backend

### Entrega del trabajo:

Los trabajos se recibiran mediante:
- Los links a los repositorios, ya sea en github, bitbucket, gitlab, etc (Esto queda a su criterio, con el que mas se sientan cómodos, esto es necesario para demostrar su conocimiento de git y las plataformas de servicios de repositorios).

Debido a que el backend es de implementacion, este requiere de componentes y dispositivos fisicos (ciertamente con costos), y el objetivo del test es solamente confirmar y apreciar los conocimientos del postulante y de esta manera no cargarle gastos, se realizara una retrospectiva a sus trabajos realizados, haznos llegar toda la documentacion de tus trabajos como ser videos de demostracion, codigos, documentos, etc. Si son videos de demostracion dedicados especialmente para este test sumara mas puntos.

Se aceptaran trabajos realizados bajo las distintas plataformas de microcontroladores:

- Arduino
- Atmel
- PIC
- STMicroelectronics

- Se apreciaran trabajos de telecomunicacion y transmision de datos (Inalambricamente).

#### Los criterios a tomar en cuenta en backend son:

Se calificara segun el codigo (Por tanto el codigo debe ser pasado obligatoriamente).

- Programacion Orientada a Objetos.
- El uso y conocimiento del lenguaje en si; Esto quiere decir por ejemplo, a traves del lenguaje, la administracion de recursos del microcontrolador (Ahorro de memoria RAM, ahorro de memoria ROM, etc).
- El uso y conocimiento que nos brinda la plataforma para poder manejar los microcontroladores, por ejemplo; Los microcontroladores en general tienen ciertas instrucciones en registros que nos sirven para poder ponerlo en modo Sleep (Ahorro de energia).

## Notas

Es necesario mencionar que si no completas los trabajos o tu fuerte solo es frontend o backend, envia lo que tengas, todo puede sumar puntos, si no completas algun test, como dije, envia lo que has podido realizar y concretar, nuevamente TODO SUMA.

Si tienes alguna duda respecto a las instrucciones, hazme llegar un email a mi correo personal: cancioalmaraz@gmail.com (SOLO para dudas de este test)

Sin mas, espero nos hagas llegar tus respuestas y tus trabajos, buena suerte y muchos exitos :grin: :grin: :grin:


