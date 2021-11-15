# Proyecto: RASPBERRY 
## Descripción : Instalación de un sistema operativo(debian/ubuntu)en Raspberry Pi 4
### Indice
-Introducción
  

-Instalación


-Conclusiones


## Introducción
   El problema con el sistema operativo Raspberry Pi es que sigue siendo un sistema operativo de 32 bits. Debido a que el entorno grafico GNOME en Ubuntu requiere de más 
   hardware, mientras que MATE consume menos recursos de hardware. Aunque la variante Pi de 4GB debería ser suficiente, el rendimiento es muy bajo si quieres ejecutar
   aplicaciones de escritorio. Para empezar necesitamos de estos requisitos:
   
     1. Una tarjeta MicroSD rápida con adaptador SDHC / lector USB.
     2. Una máquina con Linux.
     3. Software Raspberry Pi Imager.
     4. Archivo de imagen de Ubuntu-mate para ARM.
     5. Una Raspberry Pi 4 con al menos 4 GB de RAM.
     6. Un monitor, un teclado, un cable micro HDMI a HDMI de tamaño completo, un cargador oficial Raspberry Pi y un cable tipo C.
     7. Paciencia.
     
  ## Instalación
     Es un proceso de 7 pasos :
     
   ### 1.Extrae la imagen de Ubuntu-mate
          Para extraer la imagen utiliza el comando unxz "nombre de la imagen" .xz
    
   ### 2. Descargar el generador de imágenes de Raspberry Pi
          Para empezar, el generador de imágenes Raspberry Pi es una herramienta que se utiliza para flashear imágenes del sistema operativo en la tarjeta SD que se utilizará en
          el Pi. Puedes descargar la herramienta para Linux y Windows desde el sitio web oficial de descargas de Raspberry Pi. También puedes usar el comando “sudo apt install
          rpi-imager” para instalarlo en Ubuntu.
   ### 3. Instala el procesador de imágenes Raspberry Pi
          Una vez que se complete la descarga, haz doble clic para instalar el software.
   ### 4. Abre el generador de imágenes de Raspberry Pi
          Busca la aplicación “Imager” en su lista de aplicaciones con el logotipo de Raspberry y ábrela.
   ### 5. Añadir la tarjeta SD.
          Ahora, inserta la tarjeta SD en un adaptador SDHC o un lector de tarjetas USB y conéctalo al PC. En el generador de imágenes Raspberry Pi, selecciona la tarjeta SD que
          deseas flashear. También puedes utilizar otras herramientas de flasheo como Balena Etcher.
   ### 6. Utiliza la opción “Elija una imagen personalizada”
          En el menú largo que aparece al hacer clic en la opción “Elegir sistema operativo”, desplázate hacia abajo y selecciona la opción “Elegir una imagen personalizada”.
   ### 7. Último paso
          Después de seleccionar la imagen, haz clic en el botón “Escribir” en el generador de imágenes. El proceso de actualización puede tardar entre 15 y 20 minutos o más, 
          dependiendo de la velocidad de tu tarjeta SD.

          1.  Insertar la tarjeta SD en tu Raspberry Pi 4
              Antes de encender el Pi, asegúrate de haber conectado el cable Micro HDMI al primer puerto micro HDMI y accesorios como teclado y mouse.

          2.  Instalación de Ubuntu-mate
              Espera pacientemente hasta que veas la pantalla de presentación de MATE. Seguir los pasos de instalación es bastante sencillo. Todo lo que necesitas hacer es hacer               clic en siguiente, y el instalador hará todo por ti.
              
              Una vez realizada la instalación, enciende el terminal con la combinación de teclas Ctrl + Alt + T y escribe el siguiente comando.
                " sudo apt update && sudo apt upgrade "
              Esto actualizará todas las aplicaciones y repositorios y puede llevar mucho tiempo.

              Eso es todo con el proceso de instalación. Dado que una Raspberry Pi usa tarjetas SD para leer los sistemas operativos, puedes tener muchas tarjetas SD con                       diferentes sistemas operativos que puede intercambiar y usar en un abrir y cerrar de ojos.
              
  ## Conclusiones
     Aunque esta claro que no es una herramienta sin mucha potencia nos sirve para familiarizarnos con el entorno computacional a niveles basicos  pero muy completo a nivel 
     formativo.    
              
   

### Referencias
[Raspberry] (https://www.linuxenespañol.com/tutoriales/como-instalar-ubuntu-mate-en-raspberry-pi-4/)
