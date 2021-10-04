# Test Data Supply Tech-K

## Instrucciones de uso
---

1. [Duplicar](https://help.github.com/es/github/creating-cloning-and-archiving-repositories/duplicating-a-repository) el proyecto
2. Cambiar su [visibilidad](https://help.github.com/es/github/administering-a-repository/setting-repository-visibility) a privado
3. Agregar al usuario `techk-devs` como colaborador dentro del repositorio
4. Desarrollar lo que se indica en la siguiente sección en Python3. Si existen supuestos, estos deben definirse claramente en el README
5. Notificar mediante email cuando este listo y enviar el link del repositorio privado.

## Caso a desarrollar
---
Se requiere desarrollar un sitio web de arriendo de naves espaciales. Este debe contar una parte pública y una privada. La parte privada de ser un administrador que permita gestionar los clientes registrados, las naves espaciales y los estados de pagos de cada pedido de arriendo. Junto con lo anterior, cada módulo de gestión debe permitir eliminar, modificar o agregar clientes y naves espaciales, además de filtros que permitan realizar la búsqueda de un determinados elementos o conjunto de elementos de forma más rápida. Para el caso de las naves espaciales se exige la siguiente información: nombre, año de fabricación, tipo de propulsión, velocidad máxima, valor del arriendo diario en UF y el estado (arrendada, no arrendada, de baja). También, debe existir la opción para hacer una carga masiva de naves espaciales a partir de un archivo CSV. Por otra parte, el lado público debe permitir ver el home del sitio, una sección para registrarse como cliente y una sección que permita ver el listado de las naves espaciales disponibles. La sección del listado de naves espaciales debe contar con filtros que permitan una búsqueda rápida de elementos y debe contar con paginación. En está página deben poder verse una imágenes de las naves y el precio indicando el valor en UF y su valor en pesos en función de la UF del día. Las naves solo pueden ser arrendadas por un cliente registrado. Para el registro del cliente se debe exigir el nombre, RUN (debe ser uno válido con puntos y guión), año de nacimiento (solo se aceptan clientes mayores a 25 años), medio de pago (efectivo o débito) y correo electrónico. Cada cliente debe poder ver el histórico de arriendos que ha realizado y debe poder descargar un archivo CSV con esa información.


## Consideraciones

* No se permite el uso del administrador por defecto que trae Django
* Se recomienda utilizar esta API para consumir el valor diario de la UF: https://mindicador.cl/

## Bonus que suman puntos
---
* Usar las librerías [Requests](http://docs.python-requests.org/en/master/) y [Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/) para el consumo de la(s) API necesarias.
* Uso de tests unitarios

## En qué nos fijaremos
---
* Correcto uso de GIT
* Patrones de diseño
* Orden del código








