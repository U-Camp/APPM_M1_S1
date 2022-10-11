![Banner](https://github.com/U-Camp/APPM_M1_S1/blob/main/imagenes/Banner_APPM.png?raw=true)

# APPM_M1_S1
¡Hola, te damos la bienvenida al Bootcamp de Aplicaciones móviles multiplataforma en Flutter! 
Espero te encuentres muy bien y con mucha motivación para empezar el recorrido del diseño y creación de apps multiplataforma empresariales e industriales para sistemas operativos móviles como iOS y Android, así como de escritorio para Windows, MacOS, Linux o para la web, utilizando la plataforma de Dart y Flutter.

El objetivo de este primer módulo es que domines las bases tanto teóricas como prácticas sobre el desarrollo de aplicaciones multiplataforma, así como la sintaxis en el lenguaje de Dart. Además, conocerás las ventajas de desarrollar este tipo de aplicaciones y aprenderás a instalar las herramientas de desarrollo de Flutter, configurar un nuevo proyecto y cargarlo en un simulador y/o en un dispositivo físico.

Iniciemos con la semana 1 de contenido. En esta conocerás los inicios del desarrollo de una app de forma nativa y multiplataforma; no te preocupes, entenderás todos estos conceptos muy pronto, así mismo se te ayudará a configurar tu entorno para poder crear apps en Windows, Mac o Linux.

¡Comencemos!

## Desarrollo de aplicaciones nativas (móviles, web y escritorio)

El desarrollo de aplicaciones nativas hace alusión a que se emplea el lenguaje nativo de la plataforma para su construcción. Por ejemplo, el desarrollo de aplicaciones en el sistema operativo en Android sería en los lenguajes tales como Java y Kotlin. En el caso de Apple (iOS), el desarrollo sería en los lenguajes Objective-C y Swift o en el framework SwiftUI. Un último ejemplo sería el desarrollo de aplicaciones en Windows, que puede realizarse con el lenguaje de C# y Visual Basic Net, por mencionar los principales.

A continuación, enumeramos las siguientes ventajas de utilizar el desarrollo de aplicaciones nativas:
- Se trabaja directamente con las funciones y el SDK (software development kit) oficial del sistema operativo, en el que se puede utilizar toda función sin límites.
- Se puede acceder a los sensores y hardware del dispositivo.
- La experiencia de diseño y desarrollo corresponde al 100 % del rendimiento que cada sistema ofrece.

Sin embargo, también hay desventajas, que varios autores y expertos relatan:
- Es necesario contar con un equipo multidisciplinario que conozca varios lenguajes de programación para cada plataforma o sistema operativo.
- Será necesario dar mantenimiento a cada desarrollo que se vaya haciendo y contar con las personas con el nivel de expertise adecuado para llevarlo a cabo.
- En ningún momento se demerita el desarrollo nativo, sino que se debe tomar en cuenta para la toma de decisiones en la creación de una app o un sistema.

![M1S1_1](https://github.com/U-Camp/APPM_M1_S1/blob/main/imagenes/M1_AppsFlutter_5.png)
Figura 1. Las plataformas con su propio lenguaje de programación

Quizá tengas varias preguntas en este primer tema, ya que se habla de varias tecnologías, tecnicismos y lenguajes de programación. A continuación, te vamos a ayudar a entender todos estos términos.

**Lenguaje de programación**. Muchos lo definen de la siguiente manera: es la forma de comunicarnos con una computadora, tableta o celular para indicarle qué queremos hacer.

**Framework**. Puede definirse como un esquema o marco de trabajo que ofrece una estructura base para elaborar un proyecto con objetivos específicos; es una especie de plantilla que sirve como punto de partida para la organización y desarrollo de software. 

Hay varias clasificaciones de estos lenguajes, como alto nivel y bajo nivel, compilados e interpretados, pero hablaremos más adelante sobre estos y otros términos. ¡Avancemos!

A continuación, se muestra un ejemplo de desarrollo de una app en iOS y Android utilizando el lenguaje de programación Swift y Kotlin, respectivamente. Esto para brindar el contexto sobre cómo se desarrolla con tecnología nativa. En próximas lecciones, se observará cómo se lleva a cabo empleando Flutter.

[![Alt text](https://img.youtube.com/vi/u6nl1_Pd83Y/0.jpg)](https://www.youtube.com/watch?v=u6nl1_Pd83Y)

## Actualidad sobre el desarrollo de aplicaciones multiplataforma

El desarrollo multiplataforma se define como un proceso mediante el cual se lleva a cabo una aplicación independiente al sistema operativo, ya sea móvil o de escritorio, con un mismo lenguaje de programación. Esto facilita su exportación y visualización en cualquier dispositivo de los sistemas operativos ya mencionados. 

Todo se lleva a cabo con un mismo lenguaje de programación. Pueden desarrollarse apps multiplataforma que de manera nativa requerirían que manejáramos de uno a tres lenguajes.

Al respecto, la Universidad Europea menciona: "Aunque las aplicaciones nativas tienen un buen rendimiento y un elevado nivel de personalización, el desarrollo de aplicaciones multiplataforma se está imponiendo porque permite ahorrar tiempo, energía y recursos a las empresas, ya que no es necesario programar diferentes apps" (Universidad Europea, 2022).

El desarrollo móvil multiplataforma es una tendencia que crece año tras año, ya que permite, a partir de un código común, generar aplicaciones para los sistemas operativos móviles más usados actualmente: Android e iOS.

Esto hace posible que una empresa, especialmente si es relativamente pequeña, desarrolle su aplicación móvil y la publique en la tienda de aplicaciones de ambos sistemas operativos sin la necesidad de dos equipos distintos, cada uno especializado en una de las plataformas, reduciendo así los costes. Además, el tiempo de desarrollo disminuye y la cantidad de código duplicado, dado que las funciones solo se programan una vez y funcionan en ambas plataformas.

No obstante, optar por un desarrollo móvil multiplataforma también tiene dos desventajas principales: el rendimiento, el cual, en la mayoría de los casos, se ve afectado por el uso de componentes no nativos, dado que la comunicación de estos con los distintos componentes nativos de cada plataforma suele ser inconsistente. La otra desventaja es la experiencia de usuario, dado que los componentes de la interfaz no pueden aprovechar el potencial que podrían al no ser componentes nativos de la propia plataforma.

Actualmente, algunos de los frameworks de desarrollo móvil multiplataforma más utilizados son React Native y Xamarin. A estos se ha unido recientemente Flutter, que soluciona los principales problemas del resto de frameworks de desarrollo móvil multiplataforma, y que se analizará en el tema siguiente.

![M1S1_1](https://raw.githubusercontent.com/U-Camp/APPM_M1_S1/ae5087e4aedb605c6a4827ceeb750179e9f52c4b/imagenes/M1_AppsFlutter_6.png?token=A3GACYVYVD5INOZNF5C7N6LDIXJEY)
Figura 2. Desarrollo multiplataforma actual en todos los dispositivos con la misma base de código

## ¿Qué es Flutter y por qué usarlo?

Flutter se define como un SDK de Google, creado para diseñar interfaces nativas iOS y Android. Su uso se ha extendido en los últimos años. Al 2022, es posible desarrollar aplicaciones de escritorio y web con la misma base de código. 

Se decidió lanzarlo como un proyecto de código abierto, lo cual fue muy bien adoptado por la comunidad. Emplea el lenguaje de programación DART, que tiene gran parecido con varios lenguajes de programación existentes en el mercado.

- Estas son algunas de las principales ventajas de utilizar Flutter:
- Compila en nativo.
- La creación de interfaces gráficas es muy flexible.
- El desarrollo es muy rápido.
- En el desarrollo de aplicaciones, toda vista es un widget y la conformación de estos pueden crear vistas atractivas. 
- Utiliza un motor gráfico, llamado Skia, que renderiza en 2D los elementos gráficos. 
- Está escrito en C, C++ y, en su mayor parte, en Dart. 
- De forma resumida, la capa del motor está escrita en C++ y la de los widgets en Dart.

 A continuación, dejamos un ejemplo de cómo se ve el código de Flutter y su resultado en un dispositivo móvil.
 
 ![APPM1]([https://raw.githubusercontent.com/U-Camp/APPM_M1_S1/ae5087e4aedb605c6a4827ceeb750179e9f52c4b/imagenes/M1_AppsFlutter_6.png?token=A3GACYVYVD5INOZNF5C7N6LDIXJEY](https://github.com/U-Camp/APPM_M1_S1/blob/main/imagenes/APPM1.png?raw=true))
 

