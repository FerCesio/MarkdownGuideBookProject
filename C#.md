# Simplemente C#
# 0. Intro 
El lenguaje de programación C# o también conocido como C++++ fue creado en abril de 1999 por Anders Hejlsberg quien formó un equipo con la misión de desarrollar un nuevo lenguaje orientado a objetos. 
# 1.  Programación Orientada a Objetos (POO) 
La Programación Orientada a Objetos (POO) es un paradigma de programación, es decir, un modelo o un estilo de programación que nos da unas guías sobre cómo trabajar con él. Se basa en el concepto de clases y objetos. Este tipo de programación se utiliza para estructurar un programa de software en piezas simples y reutilizables de planos de código (clases) para crear instancias individuales de objetos. 

#### Algunos ejemplo de lenguajes orientadas a objetos
+ C++
+ Objective C
+ Visual Basic, Visual C Sharp 
+ Java
+ Ruby
+  TypeScript, 
+ Smalltalk, 
+ PHP o Python

# 2. Estructura
## Espacio de nombres (Namespace):

+ Un espacio de nombres es una forma de organizar y agrupar clases y otros tipos relacionados en C#. Ayuda a evitar conflictos de nombres y facilita la organización del código.
    + Por ejemplo, using System; es una declaración de espacio de nombres común en C# que te permite acceder a tipos definidos en el espacio de nombres System, como Console, que se utiliza para entrada y salida en la consola.

## Clase principal (Main Class):

En C#, el punto de entrada de un programa es un método llamado Main. Este método debe estar dentro de una clase.
La clase que contiene el método Main se denomina clase principal.
La firma del método Main suele ser: 
+ static void Main(string[] args) { }

El modificador static indica que el método es un miembro de la clase en sí misma, no de instancias individuales de la clase.
void indica que el método no devuelve ningún valor.
string[] args es un parámetro que recibe argumentos de línea de comandos.

#### Cuerpo del método Main:
Aquí es donde se escribe el código principal del programa.
Puedes llamar a otros métodos, crear objetos, realizar operaciones y cualquier otra cosa que necesites para que tu programa funcione correctamente.

# 3. Aplicaciones
C# es un lenguaje de programación versátil que se utiliza en una amplia gama de aplicaciones, desde el desarrollo de aplicaciones de escritorio hasta aplicaciones web, juegos, aplicaciones móviles y más. Aquí tienes una descripción de algunas de las aplicaciones más comunes de C#:

+ Desarrollo de aplicaciones de escritorio:

    + C# se utiliza ampliamente para desarrollar aplicaciones de escritorio utilizando el framework .NET, especialmente con la tecnología Windows Presentation Foundation (WPF) o Windows Forms.
    Las aplicaciones de escritorio desarrolladas en C# pueden abarcar una amplia gama de funciones, como herramientas de productividad, software empresarial, aplicaciones de gestión, software de contabilidad, y más.

+ Desarrollo de aplicaciones web:

    + C# es un componente clave en el desarrollo de aplicaciones web utilizando ASP.NET, un marco de trabajo web de Microsoft.
    Con ASP.NET, los desarrolladores pueden crear aplicaciones web dinámicas y escalables, desde sitios web simples hasta aplicaciones empresariales complejas.
    ASP.NET ofrece características como la gestión de sesiones, la autenticación de usuarios, la integración con bases de datos y la generación dinámica de contenido web.

+ Desarrollo de servicios web y API:
    + C# se utiliza para crear servicios web y API (Interfaces de Programación de Aplicaciones) utilizando tecnologías como ASP.NET Web API.
    Estos servicios web permiten a las aplicaciones comunicarse entre sí a través de la web, facilitando la integración de sistemas y la creación de aplicaciones distribuidas.

+ Desarrollo de juegos:

    + C# se ha vuelto cada vez más popular en el desarrollo de juegos, especialmente en el ámbito de los juegos para PC y consolas.
    La plataforma Unity, una de las herramientas de desarrollo de juegos más populares, utiliza C# como lenguaje de programación principal.
    C# proporciona un entorno de desarrollo robusto y flexible para la creación de juegos, con características como soporte multiplataforma, gráficos avanzados, física, sonido y más.

+ Desarrollo de aplicaciones móviles:
    + A través de tecnologías como Xamarin, C# se puede utilizar para desarrollar aplicaciones móviles multiplataforma para iOS, Android y Windows Phone.
    Xamarin permite a los desarrolladores escribir una vez el código en C# y luego compilarlo para ejecutarse en múltiples plataformas, lo que facilita el desarrollo de aplicaciones móviles con un código compartido significativo.

+ Desarrollo de aplicaciones de Internet de las cosas (IoT):

    + C# se utiliza en el desarrollo de aplicaciones para dispositivos de Internet de las cosas (IoT) gracias a su integración con plataformas como Azure IoT y Windows IoT.
Con C# y las herramientas adecuadas, los desarrolladores pueden crear aplicaciones para controlar y monitorear dispositivos IoT, procesar datos de sensores, y más.

Estas son solo algunas de las aplicaciones más comunes de C#, pero su versatilidad y potencia lo convierten en una opción popular para una amplia variedad de proyectos de desarrollo de software.