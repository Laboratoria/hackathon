## Retos

### 1. Crear un *styleguide* de Laboratoria con componentes en React

Crea un *styleguide* de componentes para Laboratoria utilizando el nuevo branding. Puedes proponer nuevos elementos o
mejoras a los elementos existentes. En este [link](http://laboratoria.la/) puedes encontrar algunos componentes hechos
con el nuevo branding.  

La propuesta de *styleguide* es libre. Si quieres una referencia, [esta](https://polaris.shopify.com/components/get-started/ ) es la que más nos gusta.

### 2. Crear un app de clima

Crea una app para chequear las condiciones del clima y compararlas com la perceción individual del usuario, puedes usar cualquier API de clima para ayudarte.

La idea es que todos los días muestre cómo será el clima del día y le pregunte al suario cómo siente el clima (percepción), por ejemplo: "tengo frío", "tengo mucho frío", "Me derrito de calor", "Está perfecto", etc. 

La app deberá guardar las respuestas para luego relacionarlas con el pronóstico y decirte cómo se sentirá el usuario ese día. 

### 3. Bikesantiago

La app de [Bikesantiago](https://play.google.com/store/apps/details?id=com.bikesantiagoapp) tiene solo 2.1 estrellas en la *Play Store*. Ayúdanos a entender por qué tiene tan bajo rating y cómo podemos hacer para mejorar la experiencia y el rating. 

* Si estás fuera de Santiago, piensa en un servicio similar para tu ciudad.

### 4. Eventos

Vamos a crear una web app para organizar eventos considerando:
1. Existen al menos 2 sesiones simultáneas. Por ejemplo, dos speakers en dos lugares diferentes a la misma hora.
2. Hay cupos limitados para los asistentes para cada sesión.
3. Hay un “Admin” que crea los eventos y define la cantidad de cupos para cada sesión.
4. Los usuarios se pueden registrar en los eventos que quieran.
  - No puede registrarse a la misma hora en más de un evento
  - Los cupos se van agotando (o aumentando si alguien cancela su registro).
5. Bonus:
  - Chat general para cada sesión.
  - Ping a asistentes para pedir contacto para networking. El que recibe el ping, acepta o no el pedido.

### 5. Integrarse con un backend

Tenemos un app construida en Ruby on Rails que utiliza una base de datos en Postgres. El app no está completa, por lo que es necesario trabajar en back-end y front-end para tener un app más completa.

Tendrás que clonar este [reposotorio](https://github.com/Laboratoria/hackathon-rails). 

En la rama `master` del repositorio están las instrucciones de cómo instalar ruby, ruby on rails y postgres en tu computador, ya sea Windows o Ubuntu. Sigue las instrucciones y estarás lista. En la rama `main` está el proyecto sobre el cual tendrás que trabajar. 

El app en el que vas a trabajar es un catálogo de productos de una tienda donde existen 2 tipos de usuarios: el administrador del catálogo y los compradores. El administrador del catálogo tiene un acceso privado (login) a varios formularios donde puede agregar, editar, eliminar o actualizar productos. Estos productos pertenecen a distintas categorías. Cada producto tiene su propia descripción, precio, stock e imagen(es). Por otro lado, los compradores podrán ver el catálogo de productos y entrar en el detalle de cada uno.

- Crear un seed de categorias y productos para que el app pueda tener una base de datos más grande y diversa.
- Mantener Materialize como *framework*.
- Trabajar en todas las vistas del app para que sean más amigables y puedan transmitir conexión con la marca a los usuarios.
- Agregar validaciones en los formularios.
- Agregar paginaciones cuando la lista de productos sea mayor a 10 (puedes hacerlo desde el back-end o desde el front-end).
- Agregar *breadcrumbs* (migas de pan) a las vistas.
- Sustituir o crear una vista de productos donde se pueda filtrar por categoría.
- Desplegar el app en Heroku

### 6. Replicar la app de Square POS

Square POS es una de las mejores apps para punto de venta, sin embargo, no tiene aún soporte para latinoamérica.[Esta](https://squareup.com/pos) es la app y [aquí](https://www.youtube.com/watch?v=D3uwIww7flw 
) puedes ver un video de sus principales funciones. La idea es que crees una app parecida pero adaptada a las necesidades de tu país en términos de flujos, monedas e impuestos.

¿Qué funcionalidades debes priorizar?
- Catálogo de productos con precios y stocks.
- Cobros en efectivo y tarjeta de crédito (intenta usar un API).
- Cuadre de caja al final del día.

### 7. "The bible app" o aplicaciones similares

Elige una app del *App Store o Play Store* que tenga muchas descargas pero que su experiencia no sea tan buena. Testéala, re-diséñala e impleménta tu versión mejorada.
