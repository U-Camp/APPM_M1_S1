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

![M1S1_1](https://github.com/U-Camp/APPM_M1_S1/blob/main/imagenes/M1_AppsFlutter_6.png?raw=true)
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
 
![M1S1_1](https://github.com/U-Camp/APPM_M1_S1/blob/main/imagenes/APPM1.png?raw=true)
Figura 3. Código de Flutter y su resultado en un dispositivo móvil

La siguiente infografía te permitirá comprender mejor cómo está estructurado el SDK de Flutter y sus tecnologías.
![M1S1_1](https://github.com/U-Camp/APPM_M1_S1/blob/main/imagenes/M1_AppsFlutter_9_infografia.png)

##  Herramientas LowCode/NoCode para Flutter

Muchas personas en la actualidad quieren crear apps con o sin conocimientos de programación, por lo cual han surgido plataformas que permiten crearlas sin necesidad de escribir alguna línea de código, y otras se complementan con las dos formas. A partir de estas tendencias, surgen los conceptos *LowCode* y *NoCode*.

Desarrollar aplicaciones con métodos y modelos visuales es más rápido que realizarlo usando código. Con el fin de que se lleven a cabo desarrollos con capacidades de modelado visual, las plataformas LowCode utilizan componentes integrados para representar cualquier información de manera legible para cualquier persona, desde usuarios comerciales habituales sin conocimientos técnicos hasta desarrolladores profesionales; algunas de estas herramientas pueden exportar el código para seguir trabajándolo.

Las plataformas *NoCode*son las que te solicitan arrastrar directamente los elementos visuales, cuyo resultado no es un código sino una app que cuenta ya, en la medida de lo posible, lo necesario para ser publicada.

![M1_AppsFlutter_4](https://user-images.githubusercontent.com/114032994/195194266-a98357c5-1d42-4150-a84f-b953540d9c01.png)
Figura 4. Diferencias entre LowCode/NoCode. Adaptación de U Camp de https://www.moveoapps.com/blog/decoding-low-code-app-development/

En Flutter existen varias herramientas tanto online como para instalar de manera local y, con ello, poder crear aplicaciones con dicha tecnología. Lo cierto es que, dependiendo de lo que ofrezcan, garantizará el éxito.

A continuación, te presentamos algunas de las herramientas LowCode y NoCode que podrías revisar.

1. https://flutterstudio.app

![APPM5](https://github.com/U-Camp/APPM_M1_S1/blob/main/imagenes/M1_AppsFlutter_1.png)

2. https://teta.so/

![APPM51](https://github.com/U-Camp/APPM_M1_S1/blob/main/imagenes/M1_AppsFlutter_2.png?raw=true)

3. https://www.waoo.co/

![APPM6](https://github.com/U-Camp/APPM_M1_S1/blob/main/imagenes/M1_AppsFlutter_9.png?raw=true)

4. https://flutterflow.io/

![APPM7](https://github.com/U-Camp/APPM_M1_S1/blob/main/imagenes/M1_AppsFlutter_8.png?raw=true)

Si quieres explorar más sobre las herramientas LowCode y NoCode te compartimos el siguiente video del canal del maestro Felipe Hernández, experto en desarrollo web y móvil: https://www.youtube.com/watch?v=nB_-Dpr_8yc 

## Requisitos previos para crear aplicaciones con Flutter

Para desarrollar aplicaciones con la tecnología Flutter, debes considerar los requerimientos técnicos del equipo que vas a usar y los requerimientos de conocimiento que podrían facilitarte comprender mejor esta tecnología. A continuación, los describiremos.

**Requisitos técnicos**

Los requisitos mínimos son los siguientes:

- PC con sistema operativo Linux (Ubuntu), Windows 10 o superior o MacOS.
- Mínimo de 4 GB a 6 GB de memoria RAM.
- Procesador equivalente a i3 o superior.
- Smartphone Android o iOS para pruebas.
- Espacio en disco duro de 30 gigabytes libres
- Tener instalados los SDK de Dart y Flutter.

Los requisitos ideales serían los siguientes:

- PC con sistema operativo Linux (Ubuntu), Windows 10 o superior o MacOS.
- Mínimo de 12 GB a 16 GB de memoria RAM.
- Procesador equivalente a i7 o superior.
- Smartphone Android o iOS para pruebas.
- Espacio en disco duro de 30 gigabytes libres
- Tener instalado los SDK de Dart y Flutter.

En caso de Mac, se debe de tener instalado:

- VSCode
- Xcode
- Android Studio

En caso de Windows: 

- VSCode
- Android Studio

**Requisitos de conocimiento**

Para aprender Flutter desde cero realmente no necesitas conocer su sintaxis, sin embargo, te serviría mucho haber tomado un curso de lógica y de estructura de datos para entender mejor cómo organizar los widgets. Es prioridad desarrollar tu lógica.

Algo más que podría ser útil es entender cómo funciona la programación orientada a objetos, ya que Flutter trabaja 100 % de esta manera, aunque en Flutter se les llama widgets.

## Configuración del entorno de desarrollo en Windows

Contamos con cuatro opciones de configuración para Flutter: Windows, MacOS, Linux y ChromeOS. Cabe resaltar que pueden surgir más sistemas operativos o más configuraciones; dependerá mucho de los avances tecnológicos que tenga Flutter.

Veamos la configuración del entorno de desarrollo en Windows: 

Primero, ubica la página que te permitirá instalar Flutter; es la siguiente: https://docs.flutter.dev/get-started/install

----- ANEXAR FOTO DE PAGINA DE INSTALACION

Figura 5. Página para instalar Flutter

En este link del blog de Giancarlo, se describen los pasos de la instalación. Es importante que sigas todos para lograr la configuración correcta. (Cómo instalar Flutter en Windows 10 en Android Studio y Visual Studio Code, 2019)

También puedes revisar el siguiente video: https://youtu.be/zuuPGu1BjHM

## Configuración del entorno de desarrollo en MacOS

La configuración en el sistema operativo de MacOS tiene ciertas particularidades. A continuación, se deja el link del blog de Dazzet, en el cual se describe de manera general cómo instalar y configurar.(Instalar Flutter en Mac - Guía completa usando la terminal, 2020).

--SE MODIFICA EL VIDEO PARA EDICIÓN
También puedes consultar el siguiente video: https://youtu.be/KhY4ie8R-Y8

Ahora que ya tienes Flutter instalado, seguimos con la creación de nuestro primer programa.

##  El primer programa realizado en Flutter (Hola mundo desde Flutter!)

Durante el desarrollo de aplicaciones en Flutter siempre nos encontraremos con varios cuestionamientos: ¿qué es un widget?, ¿a qué se refiere que todos son widgets?, ¿por qué muchos elementos visuales tienen la propiedad Child?, ¿puedo crear mi propio widget? Pues bien, responderemos algunos de ellos.

**¿Qué es un widget?**

Es un elemento visual, por ejemplo, un botón, caja de texto o barra de título, que permite modificar sus propiedades y comportamiento en algunos casos.

**¿A qué se refiere que todos son widgets?**

Todos los elementos visuales de Flutter son widgets que tú puedes modificar si estos te lo permiten. Revisemos un ejemplo:

--- AQUI VA UNA IMAGEN DE WIDGETS 

**¿Por qué muchos elementos visuales tienen la propiedad Child?**

Por lo general, todos los elementos visuales o widgets tienen una opción de personalización, lo cual hace que tengas mayor control de este elemento para diseñarlo como creas más conveniente.

Una vez contestadas las principales interrogantes, vamos a descubrir que con el lenguaje Dart se pueden hacer aplicaciones de manera más rápida y que la curva de aprendizaje es menor cuando ya vienes de tener otro lenguaje de desarrollo. En caso de no tener conocimiento, no te preocupes, lo vamos a descubrir muy pronto, conforme avancen las sesiones.

A continuación, vemos un ejemplo de código sobre un “Hola mundo” con Flutter.

```Dart
// Se agrega la librería de material
 import 'package:flutter/material.dart';

// Comienza el método main donde sera elprimer método que se ejecutara de nuestro proyecto
void main(List<String> args) {
  runApp( // Widget runApp 
     MaterialApp( // Widget MaterialApp, que sera aun aplicación de material desing 
      debugShowCheckedModeBanner: false, // quita el banner que esta en la parte superior derecha estando frente de la pantalla
      home: Scaffold( // Widget donde se encarga de dar la estructura de nuestra App
        body: Center( // Widget que se encarga de centrar su contenido
          child: Column( // Widget que permite que todos los elementos que esten dentro de este esten en modo columna
            mainAxisAlignment: MainAxisAlignment.center,  // propiedad de alineacion de los elementos del Widget Column
            children: [
              //Widget Text, simbolicamente muestra informacion como si fuera un dato en la pantalla
              const Text('Hola mundo', style: TextStyle( 
                color: Colors.blue,
                fontSize: 20
              )),
              holaMundo()
            ],
          ),
        )
      ),
    )
  );
}

// Método o función holaMundo, esto se hace para empezar a tener una nosion de separacion de lógica de nuestra App
Widget holaMundo(){
  return const Center(
          child: Text('Hola mundo', style: TextStyle(
            color: Colors.orange,
            fontSize: 20
          )
        ),
      );
}


```
