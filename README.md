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

1. **Configuración Manual de Optimizaciones desde el Modo de Programador:**
   - En tu dispositivo Android, abre la aplicación "Configuración".
   - Busca y selecciona "Opciones de desarrollador" o "Programador".

   - **Desactivar Animaciones:**
     - Encuentra las opciones de animación (como "Escala de animación de ventana", "Escala de animación de transición" y "Escala de duración del animador").
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

## Licencia

Este proyecto está bajo la licencia [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/). Puedes compartir, adaptar y utilizar estos archivos siempre que des el crédito correspondiente al autor original.
