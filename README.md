# Optimización de Android en Modo de Programador

Este repositorio proporciona herramientas para optimizar tu dispositivo Android en modo de programador, mejorando su rendimiento y eficiencia. Las optimizaciones abarcan aspectos clave que influyen en la velocidad, capacidad de respuesta y duración de la batería de tu dispositivo.

## Características y Optimizaciones

Este repositorio ofrece configuraciones que impactan positivamente en el rendimiento de tu dispositivo Android:

- Ajuste del tamaño del buffer del registro para una depuración efectiva.
- Desactivación de animaciones para una experiencia ágil.
- Limitación de procesos en segundo plano para liberar recursos.
- Configuración de la velocidad de CPU máxima para equilibrio entre rendimiento y batería.
- Desactivación de la ubicación en segundo plano para ahorro energético.
- Desactivación de actualizaciones automáticas de aplicaciones para control total.
- Activación de 4x MSAA para gráficos más nítidos.
- Habilitación de GPU rendering para un mejor rendimiento gráfico.
- Desactivación del modo "No molestar" automático para evitar interrupciones.
- Reducción de la escala de DPI para mayor espacio en pantalla y legibilidad.

## Instrucciones de Uso

Puedes optimizar tu dispositivo Android de dos formas:

### Método 1: Configuración Manual desde el Móvil

Configura manualmente tu dispositivo Android en modo de programador siguiendo estos pasos:

- **Configuración Manual de Optimizaciones desde el Modo de Programador:**
   - En tu dispositivo Android, abre la aplicación "Configuración".
   - Busca y selecciona "Opciones de desarrollador" o "Programador".

   - **Desactivar Animaciones:**
     - Encuentra las opciones de animación (como "Scales de animación de ventana", "Scales de animación de transición" y "Scales de duración del animador").
     - Ajusta cada opción a "Desactivado" o a un valor bajo (por ejemplo, 0.5) según tus preferencias.

   - **Limitar Procesos en Segundo Plano:**
     - Busca la opción "Límite de procesos en segundo plano" o similar.
     - Ajusta el límite a 1 o según tu preferencia.

   - **Configurar Velocidad de CPU Máxima:**
     - Encuentra la opción "Velocidad de CPU máxima" o similar.
     - Ajusta la velocidad según tus necesidades, considerando el equilibrio entre rendimiento y consumo de batería.

   - **Desactivar Ubicación en Segundo Plano:**
     - Busca la opción "Ubicación en segundo plano" o similar.
     - Desactiva la opción para ahorrar energía.

   - **Desactivar Actualizaciones Automáticas de Aplicaciones:**
     - Encuentra la opción "Actualizaciones automáticas de aplicaciones" o similar.
     - Desactiva la opción para tener control total sobre las actualizaciones.

   - **Activar 4x MSAA:**
     - Busca la opción "4x MSAA" o similar.
     - Activa la opción para mejorar la calidad de los gráficos.

   - **Habilitar GPU Rendering:**
     - Busca la opción "GPU rendering" o similar.
     - Activa la opción para un mejor rendimiento gráfico.

   - **Desactivar Modo "No Molestar" Automático:**
     - Encuentra la opción "No molestar" o similar.
     - Desactiva el modo automático para evitar interrupciones no deseadas.

   - **Reducir Escala de DPI:**
     - Busca la opción "Escala de DPI" o similar.
     - Ajusta la escala a un valor menor para obtener más espacio en pantalla y mayor legibilidad.

- **Desactivar Datos Móviles Siempre Activos:**
  - Activa las "Opciones de Desarrollador" siguiendo los pasos mencionados anteriormente.
  - En "Opciones de Desarrollador", busca la configuración "Datos móviles siempre activos" y desactívala.
  - Esto evitará que las aplicaciones utilicen datos móviles en segundo plano de manera constante, permitiéndote un mayor control sobre su uso.

- **Habilitar Volumen Absoluto:**
  - Activa las "Opciones de Desarrollador" como se explicó anteriormente.
  - Dentro de "Opciones de Desarrollador", busca la configuración "Volumen Absoluto" y actívala.
  - Esto permitirá tener un control independiente del volumen para los auriculares y el altavoz, lo que facilita los ajustes según tus necesidades.

- **Desactivar Forzar Modo Oscuro:**
  - Activa las "Opciones de Desarrollador" según las instrucciones mencionadas.
  - Encuentra la opción "Nocturno" dentro de "Opciones de Desarrollador" y desactívala.
  - Al desactivar esta opción, permitirás que las aplicaciones sigan el modo oscuro según su configuración individual.

2. Reinicia tu dispositivo nuevamente para aplicar todas las optimizaciones manualmente desde el Modo de Programador.

### Método 2: Configuración Automatizada desde el Archivo

1. Asegúrate de tener **[ADB (Android Debug Bridge)](https://developer.android.com/studio/command-line/adb)** instalado en tu computadora.
2. Activa el **Modo de Desarrollador** y la **Depuración USB** en tu dispositivo Android:
   - Abre la aplicación "Configuración".
   - Busca "Acerca del teléfono" o "Información del software".
   - Toca repetidamente en "Número de compilación" hasta que veas un mensaje indicando que el Modo de Desarrollador está habilitado.
   - Regresa atrás y busca "Opciones de desarrollador".
   - Habilita la opción "Depuración USB".

3. Conecta tu dispositivo a la computadora mediante un cable USB.
4. Descarga el archivo `configurar_android.bat` desde este repositorio.
5. Abre una ventana de comandos en la ubicación del archivo descargado.
6. Ejecuta el archivo `configurar_android.bat` y sigue las instrucciones en pantalla.
7. Reinicia tu dispositivo para aplicar los cambios.

### Versiones de Android Compatibles

Las configuraciones mencionadas son compatibles con las siguientes versiones de Android:

- **Desactivar Animaciones:** Android 4.0 y versiones posteriores.
- **Limitar Procesos en Segundo Plano:** Android 7.0 y versiones posteriores.
- **Desactivar Ubicación en Segundo Plano:** Android 8.0  y versiones posteriores.
- **Reducir Escala de DPI:** Android 7.0 y versiones posteriores.

# ROMs para Optimizar tu Experiencia en Android

## Paranoid Android

**Repositorio GitHub**: [Paranoid Android](https://github.com/AOSPA)

Paranoid Android es una ROM personalizada excepcionalmente diseñada para dispositivos Android, con el propósito principal de brindar a los usuarios una experiencia de usuario distintiva y enriquecedora que supera a las ROMs oficiales proporcionadas por los fabricantes. Esta ROM es un referente en términos de personalización, estabilidad y rendimiento. A lo largo de su evolución, Paranoid Android ha introducido innovadoras características que han dejado huella, como el revolucionario modo "Hover" que permite la aparición de ventanas emergentes de aplicaciones sin importar cuál esté en primer plano. Explora nuestro repositorio para descubrir cómo nuestra comunidad de desarrolladores sigue redefiniendo la forma en que los usuarios interactúan con sus dispositivos Android.

## Pixel Extended

**Repositorio GitHub**: [Pixel Extended](https://github.com/PixelExtended)

Pixel Extended es una ROM personalizada diseñada para capturar la esencia de la experiencia proporcionada por los dispositivos Pixel de Google en el mundo de los dispositivos Android. Estamos comprometidos en llevar esa sensación distintiva a una variedad más amplia de dispositivos, ofreciendo no solo una interfaz de usuario similar, sino también las características y funciones que los usuarios asocian con la línea Pixel. Además de preservar la estética visual, Pixel Extended a menudo agrega un toque personal con características adicionales y mejoras de personalización que se ajustan a las preferencias individuales de cada usuario. Explora nuestro repositorio para experimentar la fusión entre la elegancia de Pixel y la potencia de la personalización extendida.

## Pixel Experience

**Repositorio GitHub**: [Pixel Experience](https://github.com/PixelExperience)

Pixel Experience es la culminación de nuestra pasión por emular la experiencia brindada por los dispositivos Pixel de Google. Nuestra ROM personalizada busca no solo imitar el aspecto estético de los dispositivos Pixel, sino también la fluidez y el desempeño que los usuarios adoran. Nuestra comunidad de desarrolladores trabaja incansablemente para ofrecer una experiencia cercana a la que se experimenta con dispositivos Pixel, y esto incluye tanto la interfaz de usuario distintiva como la selección cuidadosamente curada de aplicaciones y características. Explora nuestro repositorio para sentir la familiaridad de los dispositivos Pixel en tu propio dispositivo Android y descubre cómo podemos mejorar tu experiencia móvil cotidiana.

## Instrucciones de Instalación

1. **Desbloqueo del Bootloader**: Asegúrate de desbloquear el bootloader de tu dispositivo siguiendo las instrucciones del fabricante.

2. **Instalación de Recovery Personalizado**: Flashea un recovery personalizado (por ejemplo, TWRP) en tu dispositivo para permitir la instalación de ROMs personalizadas.

3. **Copia de Seguridad**: Realiza una copia de seguridad completa de tus datos importantes antes de proceder.

4. **Descarga de la ROM**: Elige la ROM personalizada de tu preferencia y descárgala desde el enlace proporcionado.

5. **Flasheo de la ROM**: Reinicia en el recovery personalizado y selecciona la opción para flashear la ROM desde el archivo descargado.

6. **Wipe y GApps**: Realiza un wipe de datos, caché y dalvik-cache antes o después de flashear la ROM. Si es necesario, flashea las aplicaciones de Google (GApps).

7. **Reinicio**: Reinicia tu dispositivo después de flashear la ROM y las GApps.

8. **Configuración Inicial**: Configura tu dispositivo según tus preferencias y disfruta de una experiencia optimizada.

Recuerda que la instalación de ROMs personalizadas puede variar según el dispositivo. Consulta las instrucciones específicas proporcionadas por la comunidad de desarrollo para tu dispositivo antes de comenzar. ¡Explora y personaliza tu dispositivo Android con estas emocionantes ROMs!

## Licencia

Este proyecto está bajo la licencia [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/). Puedes compartir, adaptar y utilizar estos archivos siempre que des el crédito correspondiente al autor original.

## Dando Estrella

Si encuentras útiles estos scripts o te han ayudado de alguna manera, ¡por favor considera darle una estrella a este repositorio! Tu apoyo es muy apreciado y nos ayuda a seguir compartiendo recursos útiles con la comunidad.

