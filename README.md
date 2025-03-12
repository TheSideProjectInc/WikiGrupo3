# WikiGrupo3

Pequeña wikipedia desarrollada por el grupo numero 3

# Java

## Introducción

Java es un lenguaje de programación de propósito general, orientado a objetos y diseñado para ser portable, robusto y seguro. Fue creado con el principio de "escribir una vez, ejecutar en cualquier lugar" (WORA, por sus siglas en inglés), lo que significa que el código escrito en Java puede ejecutarse en cualquier plataforma que tenga una Máquina Virtual de Java (JVM) instalada.

Gracias a su versatilidad y rendimiento, Java se utiliza en una amplia variedad de aplicaciones, desde aplicaciones de escritorio y sistemas empresariales hasta desarrollo web, aplicaciones móviles (especialmente en Android) y soluciones en la nube. Su ecosistema incluye una extensa colección de bibliotecas y frameworks que facilitan el desarrollo eficiente de software.


## Historia

- **Origen:** Java fue desarrollado por Sun Microsystems a mediados de la década de 1990.
- **Evolución:** Desde su lanzamiento, Java ha evolucionado significativamente, adaptándose a las nuevas demandas tecnológicas y consolidándose en el desarrollo de aplicaciones web, móviles y de escritorio.
- **Adquisición por Oracle:** En 2010, Oracle Corporation adquirió Sun Microsystems y con ello los derechos de Java, continuando su desarrollo y lanzando nuevas versiones con soporte a largo plazo (LTS).
- **Presente y futuro:** Actualmente, Java sigue siendo uno de los lenguajes de programación más utilizados en la industria. Con actualizaciones frecuentes y una comunidad activa, sigue adaptándose a las necesidades del desarrollo moderno, incluyendo mejoras en rendimiento, compatibilidad con la nube y soporte para programación modular y reactiva.

### Versiones Importantes

- **Java 8:** Introdujo expresiones lambda, API de Streams, java.time y los _default methods_
- **Java 11:** Versión LTS[^1] con mejoras de rendimiento, limpieza de caracteristicas obsoletas.
- **Java 17:** Versión LTS con mejoras de seguridad.
- **Java 21:** Versión LTS actual, contiene mejoras en la sintaxis y se agergaron los hilos virtuales.

[^1]: LTS(Long-Term Support) es el termino utilizado para indicar que esta version dispone de soporte a largo plazo.



## Características

Algunas de las principales características de Java son:

- **Orientado a objetos:** Facilita la modularización y reutilización del código.
- **Portabilidad:** "Write Once, Run Anywhere" permite ejecutar aplicaciones en diferentes plataformas.
- **Seguridad:** Cuenta con robustas medidas de seguridad integradas.
- **Gestión de memoria:** Administración automática de memoria a través del garbage collector.
- **Multihilo:** Java permite la ejecución de múltiples hilos de manera concurrente, lo que mejora el rendimiento en aplicaciones que requieren procesamiento paralelo.
- **Biblioteca estándar rica:** Java cuenta con una amplia biblioteca estándar (Java API), que proporciona funcionalidades listas para usar en estructuras de datos, entrada/salida, redes, concurrencia y más.
- **Gran comunidad y soporte:** Al ser uno de los lenguajes más utilizados, Java tiene una comunidad activa y una gran cantidad de documentación, foros y recursos disponibles para los desarrolladores.


## **Herramientas y Entornos de Desarrollo (IDEs)**  

Entre los entornos de desarrollo más populares para Java se encuentran:  

- **IntelliJ IDEA**  
  - **Ventajas:** Interfaz moderna e intuitiva, soporte avanzado para frameworks como Spring y Hibernate, potente autocompletado y análisis de código.  
  - **Desventajas:** La versión gratuita (Community) tiene menos funciones, y en proyectos grandes puede consumir muchos recursos.  

- **Eclipse**  
  - **Ventajas:** Código abierto y completamente gratuito, altamente personalizable mediante plugins, buen rendimiento en proyectos grandes.  
  - **Desventajas:** La interfaz es menos intuitiva que la de IntelliJ, y su configuración inicial puede ser complicada.  

- **NetBeans**  
  - **Ventajas:** Instalación sencilla y configuración fácil, buena integración con Java EE y GlassFish, soporte nativo para múltiples lenguajes.  
  - **Desventajas:** Desarrollo más lento comparado con otros IDEs, y cuenta con menos plugins y soporte que Eclipse e IntelliJ.

Estos IDEs ofrecen potentes herramientas para la depuración, compilación y gestión de proyectos en Java.


## Frameworks Asociados

Java cuenta con una gran variedad de frameworks que facilitan el desarrollo de aplicaciones, entre los que destacan:

- **Spring Framework:** Para el desarrollo de aplicaciones empresariales.
- **Hibernate:** Para la gestión y mapeo de bases de datos.
- **Struts:** Para el desarrollo de aplicaciones web basadas en el patrón MVC.
- **Jakarta EE:** Un conjunto de especificaciones para el desarrollo de aplicaciones empresariales escalables y robustas.
- **Micronaut:** Un framework ligero y de alto rendimiento diseñado para aplicaciones en la nube y microservicios.
- **Quarkus:** Optimizado para Kubernetes y entornos en la nube, ideal para aplicaciones con tiempos de arranque rápidos y bajo consumo de memoria.



## Ejemplo Básico

A continuación, se muestra un ejemplo sencillo de un programa en Java:

```java
public class HolaMundo {
    public static void main(String[] args) {
        System.out.println("¡Hola, mundo!");
    }
}
```

# Referencias y Enlaces Útiles

- [Documentación Oficial de Java](https://docs.oracle.com/javase/)
- [Tutoriales de Java en Oracle](https://docs.oracle.com/javase/tutorial/)
- [Comunidades y Foros de Java](https://stackoverflow.com/questions/tagged/java)
- [Tutoriales y artículos sobre Java desde conceptos básicos hasta avanzados](https://www.geeksforgeeks.org/java/)
- [Explicaciones detalladas sobre Java, Spring y otros frameworks populares](https://www.baeldung.com)
- Otros recursos y enlaces pueden ser agregados conforme se identifiquen más fuentes útiles.

# Colaboradores

- **Billy Joshua Cornejo Flores** – Entrada inicial de Java y estructura base.
- **Paul Gomez Zubizarreta:** - Adiciones en los distintos apartados.
- **Yovan Irenov Bozhanov :** - Apartado de Versiones Importantes

# JavaScript

## Introducción

JavaScript es un lenguaje de programación de alto nivel, interpretado y orientado a objetos, principalmente utilizado para añadir interactividad y dinamismo a las páginas web. Es uno de los pilares fundamentales del desarrollo web moderno, junto con HTML y CSS. Además de su uso en el navegador, JavaScript también se emplea en el desarrollo de aplicaciones móviles, servidores y aplicaciones de escritorio.

## Historia

- **Origen:** JavaScript fue creado por Brendan Eich en 1995 mientras trabajaba en Netscape Communications Corporation.
- **Evolución:** Inicialmente diseñado para ser un lenguaje sencillo para añadir interactividad a las páginas web, JavaScript ha evolucionado enormemente, convirtiéndose en un lenguaje versátil y potente utilizado en una amplia gama de aplicaciones.

### Versiones Importantes

- **ES5 (2009):** Introdujo '_strict_' y métodos como '_forEach_', '_map_' y '_filter_'.
- **ES6 (2010)** Introdujo '_let/const_', funciones de flecha, clases y promesas.
- **ES8 (2017)** Agregó '_async/await_'.

## Características

Algunas de las principales características de JavaScript son:

- **Interpretado:** No requiere compilación, se ejecuta directamente en el navegador.
- **Orientado a objetos:** Aunque basado en prototipos, permite la programación orientada a objetos.
- **Asíncrono:** Soporta operaciones asíncronas mediante callbacks, promesas y async/await.
- **Multiplataforma:** Puede ejecutarse en cualquier navegador y también en servidores (Node.js).

## Herramientas y Entornos de Desarrollo (IDEs)

Entre los entornos de desarrollo más populares para JavaScript se encuentran:

- **Visual Studio Code**
- **WebStorm**
- **Atom**

## Frameworks y Librerías

### Principales

JavaScript dispone de una amplia gama de frameworks y librerías que simplifican y aceleran el desarrollo de aplicaciones. Algunos de los más destacados son:

- **React:** Una librería para construir interfaces de usuario.
- **Angular:** Un framework para el desarrollo de aplicaciones web.
- **Vue.js:** Un framework progresivo para construir interfaces de usuario.
- **Node.js:** Un entorno de ejecución para JavaScript en el servidor.
- **jQuery:** Una libreria que simplifica el uso de JavaScript.

### Otros

- **Three.js:** Una librería que permite crear y mostrar gráficos animados en una web.
- **Chart.js:** Una librería para la visualización de datos en graficos de barra, línea, area, etc...
- **Howler.js:** Una librería que facilita el uso de audio en JavaScript.

## Ejemplo Básico

A continuación, se muestra un ejemplo sencillo de un programa en JavaScript:

```javascript
console.log("¡Hola, mundo!");
```

# Referencias y Enlaces Útiles

- [Documentación Oficial de JavaScript (MDN)](https://developer.mozilla.org/es/docs/Web/JavaScript)
- [Tutoriales de JavaScript (MDN)](https://developer.mozilla.org/es/docs/Web/JavaScript/Guide)
- [Comunidades y Foros de JavaScript](https://stackoverflow.com/questions/tagged/javascript)

# Colaboradores

- **Billy Joshua Cornejo Flores** – Estructura base para entrada
- **Yovan Irenov Bozhanov** - Redacción del texto de JavaScript

# Python

## Introducción

Python es un lenguaje de programación interpretado, de alto nivel y con una sintaxis clara y concisa. Se utiliza en múltiples áreas, como desarrollo web, análisis de datos, inteligencia artificial, automatización y más.

## Historia

- **Origen:** Python fue creado por **Guido van Rossum** y lanzado en 1991.
- **Evolución:** Ha experimentado diversas actualizaciones, con Python 2 y Python 3 siendo las versiones más destacadas. Actualmente, **Python 3** es el estándar y sigue evolucionando con mejoras en rendimiento y características modernas.

## Características

Algunas de las principales características de Python son:

- **Sintaxis sencilla y clara:** Facilita la lectura y escritura del código.
- **Multiparadigma:** Soporta programación orientada a objetos, funcional e imperativa.
- **Tipado dinámico:** No es necesario declarar el tipo de las variables.
- **Interpretado:** No requiere compilación previa, lo que agiliza el desarrollo.
- **Gran comunidad y bibliotecas:** Existen múltiples frameworks y bibliotecas que extienden sus funcionalidades.

## Herramientas y Entornos de Desarrollo (IDEs)

Entre los entornos de desarrollo más populares para Python se encuentran:

- **PyCharm**
- **Visual Studio Code (VS Code)**
- **Jupyter Notebook**
- **IDLE** (Entorno ligero integrado con Python)
- **Cursor** Ide con integracion de IA

Estos IDEs ofrecen herramientas avanzadas para depuración, ejecución interactiva y gestión de proyectos.

## Frameworks Asociados

Python cuenta con numerosos frameworks que facilitan el desarrollo de aplicaciones:

- **Django:** Framework web de alto nivel que permite construir aplicaciones escalables y seguras.
- **Flask:** Framework minimalista para desarrollo web rápido.
- **TensorFlow y PyTorch:** Para inteligencia artificial y aprendizaje automático.
- **Pandas y NumPy:** Para análisis y manipulación de datos.
- **FastAPI:** Para el desarrollo de APIs modernas y eficientes.

## Ejemplo Básico

A continuación, se muestra un ejemplo sencillo de un programa en Python:

```python
def hola_mundo():
    print("¡Hola, mundo!")

hola_mundo()
```

## Referencias y Enlaces Útiles

- **Documentación Oficial de Python:** [Documentación de Python](https://docs.python.org/3/)
- **Blogs:**

  - [Real Python](https://realpython.com/)
  - [Python Insider](https://blogs.python.org/)

- **Videos:**
  - [Corey Schafer - Python Tutorials (YouTube)](https://www.youtube.com/c/Coreyms)
  - [Programming with Mosh - Python (YouTube)](https://www.youtube.com/c/programmingwithmosh)

# Colaboradores

- **Billy Joshua Cornejo Flores** – 1º Entrada de Python (historia, caracteristicas, herramientas, framework, etc, etc).

# PHP

## Introducción

PHP es un lenguaje de programación de código abierto diseñado principalmente para el desarrollo web. Su facilidad de integración con HTML y su capacidad para interactuar con bases de datos lo han convertido en una opción popular para la creación de sitios y aplicaciones web dinámicas.

Gracias a su versatilidad y rendimiento, PHP es ampliamente utilizado en plataformas como WordPress, Laravel y Symfony. A lo largo de los años, ha evolucionado incorporando características modernas como la programación orientada a objetos, el manejo de excepciones y un ecosistema de frameworks que facilitan el desarrollo de software.

## Historia

- **Origen:** PHP fue desarrollado por Rasmus Lerdorf en 1994 como un conjunto de scripts en C para manejar páginas web personales.
- **Evolución:** Con el tiempo, PHP se expandió significativamente, agregando soporte para bases de datos, programación orientada a objetos y frameworks que facilitan el desarrollo de aplicaciones web.
- **Presente y futuro:** Actualmente, PHP sigue siendo un lenguaje clave en el desarrollo web. Con actualizaciones constantes y una comunidad activa, continúa mejorando su rendimiento, seguridad y compatibilidad con nuevas tecnologías.

### Versiones Importantes

- **PHP 5.3:** Introdujo namespaces y funciones anónimas.
- **PHP 7.0:** Mejoras en rendimiento y tipado escalar.
- **PHP 8.0:** Incorporó atributos, JIT y mejoras en el manejo de errores.
- **PHP 8.2:** Versión actual, con mejoras en tipado y rendimiento.

## Características

Algunas de las principales características de PHP son:

- **Multiparadigma:** Soporta programación estructurada y orientada a objetos.
- **Interpretado:** No requiere compilación, se ejecuta directamente en el servidor.
- **Integración con bases de datos:** Compatible con MySQL, PostgreSQL, SQLite, entre otros.
- **Portabilidad:** Funciona en la mayoría de servidores web y sistemas operativos.
- **Comunidad activa:** Gran cantidad de recursos, frameworks y soporte.

## Herramientas y Entornos de Desarrollo (IDEs)

Entre los entornos de desarrollo más populares para PHP se encuentran:

- **PHPStorm**
- **Visual Studio Code**
- **NetBeans**
- **Eclipse PDT**

Estos IDEs ofrecen herramientas avanzadas para la depuración, edición y gestión de proyectos en PHP.

## Frameworks Asociados

PHP cuenta con una gran variedad de frameworks que facilitan el desarrollo de aplicaciones, entre los que destacan:

- **Laravel:** Framework moderno y flexible con soporte para MVC.
- **Symfony:** Enfoque modular y escalable para proyectos grandes.
- **CodeIgniter:** Ligero y rápido para aplicaciones simples.
- **Zend Framework:** Potente y orientado a aplicaciones empresariales.

## Ejemplo Básico

A continuación, se muestra un ejemplo sencillo de un programa en PHP:

```php
<?php
echo "¡Hola, mundo!";
?>
```

# Referencias y Enlaces Útiles

- [Documentación Oficial de PHP]([https://docs.oracle.com/javase/](https://www.php.net/docs.php)
- [Manual de PHP](https://www.php.net/manual/es/)
- [Comunidades y Foros de PHP](https://www.php.net/support.php)

  # Colaboradores

- **Paul Gómez Zubizarreta** - Entrada PHP
