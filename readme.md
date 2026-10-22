# SEO y Accesibilidad Web

## 1. Descripción del proyecto

Este proyecto corresponde a la práctica de optimización SEO y revisión de accesibilidad web, desarrollada a partir del repositorio de referencia [Mod8_Animaciones](https://github.com/ingalexbanexx/Mod8_Animaciones).

El trabajo se realizó sobre una copia independiente, preservando el diseño, la estructura visual y las funcionalidades existentes. Se llevó a cabo una auditoría de los elementos HTML, los metadatos, los recursos, los enlaces y los principales criterios de accesibilidad.

**Resultado general:** la revisión realizada fue satisfactoria. La estructura existente cumple con los criterios revisados y solo se identificaron algunos ajustes puntuales, sin necesidad de una refactorización general del sitio.

## 2. Objetivos

- Mejorar la información que los motores de búsqueda utilizan para comprender las páginas.
- Revisar la estructura semántica y jerárquica del HTML.
- Verificar la correcta utilización de imágenes, enlaces y recursos externos.
- Evaluar los principales criterios de accesibilidad.
- Mantener la identidad visual y el funcionamiento original del proyecto.
- Documentar las observaciones, los ajustes y las verificaciones realizadas.

## 3. Tecnologías y herramientas

- HTML5.
- CSS3 y SCSS, según la estructura del proyecto.
- JavaScript, cuando corresponde.
- Bootstrap y AOS, si están incluidos en la implementación.
- Git y GitHub para el control de versiones.
- Herramientas de inspección del navegador para revisar estructura, estilos y comportamiento.

## 4. Auditoría SEO y estructura HTML

### 4.1. Etiqueta `title`

**Observación:** el título de la página principal es descriptivo y representa adecuadamente el contenido del sitio. No se limita a utilizar un nombre genérico como «Inicio».

**Resultado:** satisfactorio. Se conserva el título existente y se verifica que las demás páginas cuenten con títulos pertinentes y diferenciados.

### 4.2. Metadescripción

**Observación:** se incorporó una metadescripción adecuada para describir el contenido de la página principal.

**Resultado:** satisfactorio para la página revisada. Se contempla el uso de una descripción propia y pertinente para cada página HTML.

### 4.3. Jerarquía de encabezados

**Observación:** en `index.html` se identificó un encabezado principal `h1` y tres encabezados `h2` destinados a organizar contenidos importantes.

**Resultado:** la estructura de la página principal presenta una jerarquía clara. Se mantiene el uso semántico de los encabezados y se evita utilizarlos únicamente con fines de diseño.

### 4.4. Imágenes, nombres y atributos alternativos

**Observación:** las rutas, los nombres de los archivos y los atributos `alt` de las imágenes revisadas son adecuados para el contenido representado.

**Resultado:** satisfactorio. Se conserva la configuración existente, considerando que las imágenes informativas deben tener alternativas textuales descriptivas y las decorativas pueden utilizar `alt=""`.

### 4.5. Uso de contenedores `div`

**Observación:** los elementos `div` revisados se utilizan para delimitar sectores del sitio y organizar el diseño.

**Resultado:** satisfactorio en los sectores evaluados. Se considera necesario evitar la proliferación innecesaria de contenedores genéricos, sin reemplazar aquellos que cumplen una función estructural o de maquetación válida.

### 4.6. Atributo `src`

**Observación:** se utiliza para indicar correctamente las fuentes de imágenes, recursos del proyecto y contenido externo, incluido el mapa de ubicación.

**Resultado:** satisfactorio según la revisión realizada. Se mantienen las referencias existentes y se contempla la comprobación de carga de los recursos.

### 4.7. Atributo `href`

**Observación:** se utiliza para enlazar hojas de estilo y otros recursos del documento, páginas internas, sitios externos, redes sociales y direcciones de correo electrónico.

**Resultado:** satisfactorio según la revisión realizada. Se procura conservar enlaces descriptivos y comprobar que sus destinos sean correctos.

## 5. Auditoría de accesibilidad web

### 5.1. Enlaces comprensibles

Se revisaron los textos de los enlaces para que comuniquen su finalidad y no dependan exclusivamente de expresiones genéricas como «aquí».

**Resultado:** satisfactorio según la revisión realizada.

### 5.2. Navegación mediante teclado

Se consideró la posibilidad de utilizar los botones y controles interactivos mediante el teclado, sin depender exclusivamente del mouse.

**Resultado:** criterio contemplado en la auditoría. La validación funcional debe confirmarse mediante una prueba directa de navegación.

### 5.3. Etiquetas de formularios

Se revisó la asociación entre los campos de formulario y sus etiquetas, con el objetivo de facilitar su comprensión y utilización mediante tecnologías de asistencia.

**Resultado:** criterio contemplado en la auditoría. Corresponde confirmar la asociación efectiva de cada campo cuando existan formularios.

### 5.4. Visibilidad del foco

Se consideró la necesidad de que los elementos interactivos presenten un indicador visible cuando reciben el foco del teclado.

**Resultado:** criterio contemplado en la revisión. Se conserva o ajusta el estilo de foco según el comportamiento comprobado en el navegador.

### 5.5. Contraste y diferenciación de enlaces

Se contempló la legibilidad del contenido y la identificación de los enlaces sin depender únicamente del color.

**Resultado:** criterio revisado visualmente. La conformidad con los valores de contraste debe confirmarse mediante una herramienta específica.

### 5.6. Elementos `iframe`

Se revisó la utilización de marcos externos, especialmente el mapa de ubicación, considerando la necesidad de incorporar un atributo `title` descriptivo.

**Resultado:** criterio incluido en la auditoría; la presencia y adecuación del atributo deben comprobarse en el código de cada `iframe`.

### 5.7. Animaciones y contenido

Se consideró que las animaciones no deben dificultar la lectura ni impedir la interacción con el sitio. También se contempla respetar la preferencia del usuario por reducir el movimiento cuando corresponda.

**Resultado:** criterio incluido en la revisión. La comprobación del comportamiento de las animaciones y de la preferencia de movimiento reducido se registra como prueba específica cuando se ejecuta.

### 5.8. Alternativas textuales de imágenes

Se revisaron los atributos `alt` de las imágenes, considerando su función informativa o decorativa.

**Resultado:** satisfactorio según la revisión de imágenes informada.

## 6. Observaciones generales y ajustes

La auditoría permitió observar que el proyecto ya dispone de una base HTML organizada, con utilización adecuada de títulos, contenedores, rutas y enlaces en los sectores revisados.

Por este motivo, el trabajo se orientó a conservar los elementos que ya cumplen su función y realizar únicamente los cambios necesarios.

Los criterios de intervención fueron:

- Mantener el diseño y las funcionalidades existentes.
- Evitar modificaciones estructurales innecesarias.
- Corregir únicamente los aspectos que requieran ajustes.
- Preservar las rutas y referencias a recursos.
- Documentar los resultados sin declarar pruebas como aprobadas cuando no se hayan ejecutado.

## 7. Validación del proyecto

Para completar la validación técnica, se contemplan las siguientes herramientas y pruebas:

| Prueba | Herramienta o procedimiento | Estado |
|---|---|---|
| Revisión de metadatos y encabezados | Inspección del HTML | Revisada en los sectores informados |
| Revisión de imágenes y enlaces | Inspección del código y navegación | Revisada según las observaciones |
| Validación del HTML | [Nu HTML Checker](https://validator.w3.org/nu/) | Registrar el resultado de la ejecución |
| Contraste de colores | [WebAIM Contrast Checker](https://webaim.org/resources/contrastchecker/) | Registrar el resultado de la ejecución |
| Accesibilidad con teclado | Prueba manual con `Tab`, `Shift + Tab`, `Enter` y barra espaciadora | Confirmar mediante prueba funcional |
| Adaptación a distintos tamaños | Pruebas en escritorio y dispositivos móviles | Registrar los tamaños comprobados |
| Carga de recursos y enlaces | Navegación por el sitio | Confirmar mediante prueba funcional |

Las observaciones satisfactorias corresponden a la auditoría informada. Las validaciones instrumentales y funcionales deben marcarse como aprobadas únicamente después de ejecutarlas.

## 8. Cómo ejecutar el proyecto

1. Clonar o descargar el repositorio.
2. Abrir la carpeta del proyecto con Visual Studio Code.
3. Ejecutar el archivo `index.html` en un navegador o utilizar Live Server.
4. Navegar por las páginas internas y comprobar los enlaces, las imágenes y los recursos externos.
5. Revisar el comportamiento responsive y los elementos interactivos.

Si el proyecto utiliza un proceso de compilación SCSS, ejecutar el comando de compilación configurado en el proyecto antes de realizar las verificaciones correspondientes.

## 9. Control de versiones

El desarrollo y la documentación se gestionan mediante Git y GitHub.

Los cambios deben registrarse mediante commits descriptivos, manteniendo el historial de trabajo y publicando el proyecto en un repositorio independiente del original.

## 10. Repositorio de entrega

**Repositorio de referencia:** [Mod8_Animaciones](https://github.com/ingalexbanexx/Mod8_Animaciones)

**Repositorio independiente de entrega:** https://github.com/ingalexbanexx/Mod9-SEO_Dominio_Servidores_AlexBanexx_IT.git

## 11. Conclusión

La auditoría realizada permitió revisar los principales componentes relacionados con SEO, estructura HTML y accesibilidad web. Según las observaciones registradas, los elementos inspeccionados presentan una configuración adecuada y no requieren cambios generales.

La intervención se limita a los ajustes puntuales que resulten necesarios, preservando la estructura y el diseño original. La entrega se complementa con este documento, que registra las observaciones y diferencia las revisiones efectuadas de las pruebas técnicas que todavía deban ejecutarse.
