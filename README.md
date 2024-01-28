[image_0]: https://pfst.cf2.poecdn.net/base/image/fbffa378ad64885dde237292fbc2148151a1987a28760bf35cc5ad9ff8e1504a?w=640&h=640&pmaid=30592288

# Nutriperfec App

![Nutriperfec Logo][image_0]

## Estructura de los archivos

**Package.json**
Contiene toda la información sobre las librerías que se deben instalar para que funcione la app, al ejecutar en la consola "npm install" (con nodejs instalado) automáticamente instala las dependencias que necesita, de igual forma si instalamos algo nuevo se agrega solo al package.json

**eas.json**
El archivo "eas.json" es un archivo de configuración que se utiliza en proyectos con Expo. En términos simples, es como una hoja de instrucciones para la herramienta de construcción de Expo, que ayuda a generar y administrar la aplicación móvil.

En este archivo, se especifican diferentes configuraciones y opciones que afectan cómo se construye y se ejecuta la aplicación en tu dispositivo o simulador. Por ejemplo, puedes definir cosas como el nombre de la aplicación, las versiones mínimas y máximas de los dispositivos que pueden ejecutarla, las configuraciones específicas para iOS y Android, y muchas otras opciones.

Básicamente, el archivo "eas.json" es una forma de personalizar y ajustar las características y el comportamiento de tu aplicación móvil creada con Expo. Al configurar y modificar las opciones en este archivo, puedes adaptar la aplicación según tus necesidades y preferencias.

Es importante tener en cuenta que, aunque el archivo "eas.json" puede ser fundamental para los desarrolladores que trabajan en el proyecto, los usuarios finales de la aplicación no necesitan preocuparse por este archivo.

**app.json**
El archivo "app.json" es un archivo de configuración importante en un proyecto con Expo. Podrías pensar en él como un documento que contiene información sobre tu aplicación móvil.

En este archivo, puedes especificar diferentes aspectos de tu aplicación, como su nombre, descripción, versión, icono y colores de la interfaz. También puedes configurar la orientación de la pantalla, definir permisos necesarios para acceder a ciertas funciones del dispositivo y establecer preferencias de accesibilidad, entre otras cosas.

Además, el archivo "app.json" también permite configurar características específicas de la plataforma, como las notificaciones push, los íconos de la aplicación para iOS y Android, las rutas de navegación y los enlaces profundos.

En resumen, el archivo "app.json" es como una ficha de identificación de tu aplicación móvil. Contiene información importante y configuraciones que se utilizan para personalizar y definir cómo se ve y se comporta tu aplicación cuando se ejecuta en un dispositivo móvil.

Es importante tener en cuenta que, aunque el archivo "app.json" es crucial para los desarrolladores que trabajan en el proyecto, los usuarios finales de la aplicación no necesitan preocuparse por este archivo. Solo se utiliza durante el proceso de desarrollo para configurar y ajustar la aplicación según las necesidades del proyecto.

**App.js**
El archivo "App.js" es uno de los archivos más importantes en un proyecto con Expo. Contiene el código fuente principal de tu aplicación móvil.

En términos simples, el archivo "App.js" actúa como el punto de entrada de tu aplicación. En él, puedes escribir código para definir la estructura y el comportamiento de tu aplicación. Puedes pensar en él como el "cerebro" de la aplicación, ya que controla cómo se ve y cómo responde a las interacciones del usuario.

Dentro de "App.js", puedes escribir código para crear componentes visuales, como botones, texto, imágenes y pantallas. También puedes definir la lógica y la interacción de la aplicación, como la navegación entre diferentes pantallas, la gestión de datos y la respuesta a eventos del usuario.

En resumen, el archivo "App.js" es donde se escribe el código principal de tu aplicación móvil. Es el lugar donde puedes definir cómo se ve y cómo se comporta tu aplicación, y es fundamental para el desarrollo de la misma.

Es importante tener en cuenta que, dependiendo de la estructura de tu proyecto, es posible que haya otros archivos relacionados con "App.js", como archivos de componentes adicionales, estilos o configuraciones específicas. Sin embargo, "App.js" suele ser el archivo principal y central en el desarrollo de una aplicación móvil con Expo.

**Utils**
En términos sencillos, los archivos en la carpeta "utils" contienen funciones, métodos o clases reutilizables que se utilizan en diferentes partes de la aplicación. Estas funciones y utilidades suelen ser pequeñas piezas de código que realizan tareas específicas y pueden ser utilizadas en múltiples lugares dentro del proyecto.

Por ejemplo, puedes encontrar archivos en la carpeta "utils" que contienen funciones para formatear fechas, validar entradas de usuario, realizar cálculos matemáticos comunes, realizar solicitudes de red, manejar autenticación, entre otros.

La idea detrás de tener una carpeta "utils" es mantener un lugar centralizado para almacenar y organizar estas funciones de utilidad, lo que facilita su reutilización en diferentes partes del proyecto. Esto ayuda a mantener un código más limpio, modular y eficiente.

Es importante tener en cuenta que el contenido exacto de la carpeta "utils" puede variar dependiendo del proyecto y las preferencias del equipo de desarrollo. Algunos proyectos pueden tener subcarpetas adicionales dentro de "utils" para organizar aún más las funciones según su propósito o alcance.

**Stack**
React Navigation es una biblioteca popular utilizada en el desarrollo de aplicaciones móviles con React Native. Proporciona una forma fácil de gestionar la navegación entre diferentes pantallas de la aplicación.

Dentro de la carpeta "Stack", es posible que encuentres archivos que definen las pilas de navegación, como "HomeStack.js" o "ProfileStack.js". Estos archivos contienen la configuración de las rutas y opciones de navegación para un conjunto específico de pantallas.

Cada archivo de pila dentro de la carpeta "Stack" se encarga de definir las rutas y las opciones de navegación para un flujo de la aplicación. Por ejemplo, un archivo "HomeStack.js" puede definir las rutas y opciones de navegación para las pantallas relacionadas con la página de inicio de la aplicación, mientras que un archivo "ProfileStack.js" puede hacer lo mismo para las pantallas relacionadas con el perfil del usuario.

Estos archivos de pila suelen utilizar componentes proporcionados por React Navigation, como "StackNavigator", para definir las rutas y configuraciones de navegación. Estas pilas se pueden combinar y anidar para crear una estructura de navegación compleja en la aplicación.

En resumen, la carpeta "Stack" en un proyecto de React Navigation contiene archivos que definen las pilas de navegación, que son conjuntos de rutas y configuraciones de navegación para diferentes flujos o secciones de la aplicación. Estos archivos ayudan a organizar y gestionar la navegación entre las pantallas de la aplicación.

**screens**
La carpeta "screens" es una convención común en proyectos de desarrollo de aplicaciones para almacenar archivos relacionados con las pantallas de la aplicación.

En el desarrollo de aplicaciones, una pantalla se refiere a una interfaz de usuario visible y funcional que muestra contenido específico al usuario. Por ejemplo, una aplicación de redes sociales puede tener pantallas como "Inicio", "Perfil", "Explorar" y "Configuración".

Dentro de la carpeta "screens", encontrarás archivos que representan cada una de estas pantallas. Por ejemplo, puedes tener archivos como "HomeScreen.js", "ProfileScreen.js", "ExploreScreen.js" y "SettingsScreen.js". Cada archivo representa una pantalla de la aplicación y contiene la lógica y los componentes necesarios para mostrar y gestionar esa pantalla específica.

En estos archivos de pantalla, puedes encontrar componentes de React Native que definen la interfaz de usuario de la pantalla, como botones, texto, imágenes y formularios. También puedes encontrar lógica adicional para manejar eventos, realizar llamadas a la API, gestionar el estado de la pantalla y realizar otras acciones específicas de esa pantalla.

La carpeta "screens" se utiliza para organizar y mantener separadas las diferentes pantallas de la aplicación. Esto facilita la navegación y la comprensión del flujo de la aplicación, ya que cada pantalla tiene su propio archivo y se puede modificar y mantener de forma independiente.

Es importante tener en cuenta que la estructura y los nombres de los archivos en la carpeta "screens" pueden variar según las preferencias del equipo de desarrollo y la arquitectura del proyecto. Algunos proyectos pueden tener subcarpetas adicionales dentro de "screens" para organizar aún más las pantallas según su funcionalidad o secciones de la aplicación.

**test**
Imagina que tu aplicación es como un sofisticado reloj de pulsera, compuesto de muchas piezas pequeñas y precisas que trabajan juntas para mantener el tiempo exacto. En el mundo de la programación, cada una de estas pequeñas piezas es creada por desarrolladores y recibe el nombre de “componentes”. Para asegurarse de que cada pieza funcione perfectamente y el reloj dé la hora correcta, los creadores del reloj deben verificar cada parte individualmente y también cómo interactúan entre sí.

La carpeta de pruebas es como el taller del relojero, donde se llevan a cabo estas comprobaciones. Esta carpeta contiene una serie de archivos especiales. Cada uno de estos archivos es como un conjunto de herramientas que ayudan a examinar y probar un componente específico o una funcionabilidad de la aplicación para confirmar que todo está funcionando perfectamente.

Por ejemplo, si uno de los componentes es una alarma, hay un archivo de prueba que asegura que la alarma se activa a la hora que se configura. Otro archivo puede enfocarse en probar si todos los botones en la pantalla reaccionan cuando se presionan. La idea es simular situaciones reales en un entorno controlado para detectar y corregir fallas antes de que el usuario final, en este caso, el propietario del reloj, se encuentre con algún problema.

Cada vez que el equipo de desarrollo crea o modifica una parte de la aplicación, los archivos de prueba automáticamente ejecutan sus comprobaciones para garantizar que todo sigue funcionando como se espera. Esto es crucial para mantener la aplicación confiable y fácil de usar, incluso mientras se le añaden nuevas funciones y mejoras.

En resumen, la carpeta de pruebas es un espacio vital para asegurar que la aplicación sea como un reloj bien aceitado, donde cada “tic” es justo como se espera y todo “tac” llega a tiempo.

**node_modules**
La carpeta "node_modules" es una carpeta generada automáticamente en proyectos de desarrollo de aplicaciones JavaScript que utilizan administradores de paquetes como npm (Node Package Manager). Esta carpeta contiene las dependencias externas de tu proyecto, es decir, los paquetes y módulos de código que tu aplicación utiliza y que no han sido escritos por ti.

Cuando instalas una dependencia en tu proyecto utilizando un administrador de paquetes, como npm, estas herramientas descargan los archivos necesarios de la dependencia y los almacenan en la carpeta "node_modules". Cada paquete o módulo tiene su propia carpeta dentro de "node_modules", donde se encuentran los archivos relacionados con esa dependencia específica.

La carpeta "node_modules" puede contener una gran cantidad de archivos y carpetas, especialmente en proyectos más grandes con múltiples dependencias. Estos archivos y carpetas no suelen ser modificados directamente por el desarrollador, ya que son gestionados y actualizados por el administrador de paquetes.

Es importante tener en cuenta que la carpeta "node_modules" no debe ser incluida en el control de versiones de tu proyecto. Esto se debe a que los archivos en esta carpeta pueden ocupar mucho espacio y pueden ser fácilmente regenerados descargando las dependencias nuevamente utilizando el administrador de paquetes.

En resumen, la carpeta "node_modules" es donde se almacenan las dependencias externas de tu proyecto JavaScript. Estas dependencias son descargadas e instaladas automáticamente por el administrador de paquetes y contienen el código necesario para que tu aplicación funcione correctamente.

**components**
La carpeta "components" es una convención común en proyectos de desarrollo de software para almacenar archivos relacionados con componentes reutilizables.

En el contexto de la programación, los componentes son bloques de construcción modulares que encapsulan la funcionalidad y la interfaz de usuario de una parte específica de una aplicación. Estos componentes se pueden utilizar en diferentes partes de la aplicación para lograr consistencia, reutilización de código y facilitar el mantenimiento.

Dentro de la carpeta "components", encontrarás archivos que representan diferentes componentes de la aplicación. Por ejemplo, puedes tener archivos como "Button.js", "InputField.js" o "Card.js", donde cada archivo define la estructura y el comportamiento de un componente específico.

Los archivos de componentes suelen contener código que define la apariencia visual del componente utilizando HTML, CSS o alguna sintaxis específica del framework o biblioteca que se esté utilizando. Además, pueden incluir lógica adicional para manejar interacciones, eventos y datos relacionados con ese componente.

Organizar los componentes en una carpeta separada, como "components", ayuda a mantener el código organizado y modular. Además, facilita la reutilización de componentes en diferentes partes de la aplicación, ya que se pueden importar y utilizar en otros archivos según sea necesario.

Es importante tener en cuenta que la estructura y los nombres de los archivos en la carpeta "components" pueden variar según las preferencias del equipo de desarrollo y la arquitectura del proyecto. Algunos proyectos pueden tener subcarpetas adicionales dentro de "components" para organizar aún más los componentes según su propósito o alcance, como "components/Header" o "components/Forms".

En resumen, la carpeta "components" se utiliza para almacenar archivos que contienen componentes reutilizables en un proyecto de desarrollo de software. Estos componentes encapsulan la funcionalidad y la interfaz de usuario de partes específicas de la aplicación y se utilizan para lograr consistencia y eficiencia en el desarrollo.

**assets**
La carpeta "assets" es una convención común en proyectos de desarrollo de software para almacenar recursos estáticos utilizados en una aplicación, como imágenes, archivos de audio, archivos de video, fuentes tipográficas, hojas de estilo CSS, archivos JSON y otros tipos de archivos multimedia.

La carpeta "assets" se utiliza para organizar y almacenar estos recursos de manera estructurada y accesible dentro del proyecto. Al mantener los recursos estáticos en una carpeta separada, se facilita su gestión y referencia en el código de la aplicación.

Dentro de la carpeta "assets", es común encontrar subcarpetas adicionales para organizar los diferentes tipos de recursos. Por ejemplo, puedes tener subcarpetas como "images" para almacenar imágenes, "fonts" para almacenar fuentes tipográficas, "audio" para almacenar archivos de audio, y así sucesivamente.

La estructura y los nombres de las subcarpetas y archivos dentro de "assets" pueden variar según la preferencia del equipo de desarrollo y la naturaleza del proyecto. Es posible que también encuentres subcarpetas adicionales para organizar los recursos según su funcionalidad o sección de la aplicación.

Cuando se utiliza una biblioteca o framework específico, como React o Angular, es posible que haya recomendaciones o convenciones específicas sobre cómo organizar y acceder a los recursos en la carpeta "assets".

En resumen, la carpeta "assets" se utiliza para almacenar recursos estáticos, como imágenes, archivos de audio y otros archivos multimedia, en un proyecto de desarrollo de software. Proporciona una estructura organizada para acceder y gestionar estos recursos dentro de la aplicación.

**api**
AsyncStorage es una API proporcionada por React Native que permite almacenar datos de forma asíncrona en el dispositivo. Es común utilizar AsyncStorage para almacenar datos localmente en la aplicación, como configuraciones, preferencias del usuario o información temporal.

La carpeta "api" en tu proyecto sirve como un lugar centralizado para definir las funciones que interactúan con AsyncStorage o archivos JSON para obtener información almacenada. Estas funciones pueden incluir lógica para leer los datos almacenados en AsyncStorage o cargar archivos JSON desde el sistema de archivos de la aplicación.

Por ejemplo, puedes tener una función en tu carpeta "api" llamada "getUserData" que se encargue de obtener los datos del usuario desde AsyncStorage. Esta función puede utilizar los métodos proporcionados por AsyncStorage, como "getItem", para recuperar los datos almacenados previamente.

De manera similar, puedes tener otra función llamada "loadJSONData" que cargue un archivo JSON específico desde el sistema de archivos de la aplicación y devuelva los datos obtenidos.

Organizar estas funciones en la carpeta "api" puede ayudar a mantener una estructura clara y coherente en tu proyecto, separando la lógica de acceso a datos de otras partes de la aplicación.

Recuerda que la estructura y los nombres de las carpetas y archivos pueden variar según las preferencias y la arquitectura específica de tu proyecto. La carpeta "api" es solo una convención común utilizada para organizar funciones relacionadas con la obtención de datos desde AsyncStorage o archivos JSON.

## Requisitos previos

-Instalar Node.js

## Instalación

en una consola
comandos:
-ls:ver en la carpeta en la que estoy y que archivos/carpetas están
-cd:forma de moverme entre carpeta ej "cd Escritorio" (entro al escritorio) o "cd .."(vuelvo a la carpeta anterior)

Ej: mi proyecto esta en el escritorio en una carpeta
en la consola puede ser: cd Escritorio/nombredecarpetadelproyecto

cuando estés en el proyecto
ejecuta "npm install", esto instala todas las dependencias
luego ejecuta "npx expo start --web" y de esta forma pueden ver los cambios mientras escriben código
