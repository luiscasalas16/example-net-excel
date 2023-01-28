# net-openxml-excel

Proyecto de ejemplo de lectura y escritura de archivo excel, utilizando DocumentFormat.OpenXml.

El Helper tiene la implementación de los métodos para realizar la lectura y escritura de datos, que se hace utilizando DataTable como estructura genérica.

El Data contiene la definición de las clases de Usuarios y Ordenes; y realiza la generación de datos de prueba utilizando Bogus. Además, tiene los métodos para hacer las transformaciones entre listas de objetos y DataTable.

Referencias:
- (https://www.nuget.org/packages/DocumentFormat.OpenXml/)
- (https://github.com/bchavez/Bogus/)