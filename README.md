# Descarga_MC_AFIP

Bot de descarga de Mis Comprobantes Emitidos y Recibidos del servicio Mis Comprobantes de AFIP de manera masiva.

---

El licenciamiento es bajo PL (es decir que no se puede distribuir comercialmente, solamente GRATIS). y si se utiliza este el código, su derivado también debe ser distribuido abierta y gratuitamente.

---

## Ejecución del BOT

Los pasos para ejecutar el bot son los siguientes:

1. Crearse una cuenta en UiPath ([https://www.uipath.com/](https://www.uipath.com/)).

2. Descargar el Uipath Studio (https://www.uipath.com/studio) en la versión Community (es gratuita).

3. Instalar la version el Studio (no la Studio X).

  - Si se instala la versión Studio X se debe cambiar la versión del proyecto a Studio X con desde las configuraciones

  ![Configuración de versión](https://github.com/abustosp/Configuraciones/blob/master/Uipath/Cambiar-a-Studio.png?raw=true "Configuración de versión")

  - Si no permite hacer este cambio se debe:

    1. Iniciar sesión en Uipath cloud.

    2. Eliminar la organización.

    3. Crear una nueva organización.

4. Descargar el BOT. Acá hay 3 opciones:
   
   1. Descargar el ZIP.
   
   2. Descargarlo con la integración de GIT desde el Uipath.

     - Si no aparece la opción de GIT en el Uipath se debe instalar el GIT desde las configuraciones de Uipath

     ![Configuración de GIT](https://github.com/abustosp/Configuraciones/blob/master/Uipath/Habilitar-GIT.png?raw=true "Configuración de GIT")
   
   3. Descargar el repositorio con GIT utilizando el comando `git clone https://github.com/abustosp/Descarga_MC_AFIP.git`

5. Una vez Descargados los archivos se debe:
   
   1. Abrir el project.json o archivo .xaml
   
   2. Ejecutarlo desde el botón de Run File (hacer click abajo del boton de "Play").

      ![Ejecución del BOT](https://raw.githubusercontent.com/abustosp/Configuraciones/master/Uipath/Run-File.png "Ejecución del BOT")

---

## Requisitos del BOT:

- El Bot corre únicamente en Firefox (se puede adaptar para Chrome pero se recomienda el primero por temas de rendimiento) y en Windows 10 cómo mínimo.

- Para Ejecutar el BOT se debe completar la información en el Excel

- En caso que no se guarden los Archivos con el nombre y/o ubicación definidas en el Excel, en la columna ST del Excel se debe colocar "NO" (ST hace referencia a Simulate Type. Es uno de los métodos de ingresar información en los distintos programas).

- Las ubicaciones del Excel deben ir desde el Disco hasta la Ubicación completa con un backslash final (ejemplo: `C:\Users\Agustin Bustos\Desktop\TEST\`)
  
  - Los de la ventana emergente inicial van sin el último backslash (ejemplo: `C:\Users\Agustin Bustos\Desktop\Test`) y es importante que esa ubicación exista. Esta ubicación se utiliza solamente cuando la dirección de descarga del Excel este vacío

- Firefox se debe configurar de la siguiente manera:

  1. El idioma tiene que estar en Español de Argentina

  ![Configuración de idioma](https://github.com/abustosp/Configuraciones/blob/master/Firefox/Idioma-Espa%C3%B1ol-ARG.png?raw=true "Configuración de idioma")

  2. La descarga de archivos debe estar configurada para que se pregunte donde guardarlos

  ![Configuración de descarga](https://github.com/abustosp/Configuraciones/blob/master/Firefox/Ubicacion-de-descargas.png?raw=true "Configuración de descarga")

  3. La descarga de archivos debe estar configurada para que no se pregunte si se quiere guardar el archivo (si el archivo aparece en la lista tiene que estar configurado con la opción de "Guardar Archivo" por ejemplo en el caso de los PDF y XLSX o planillas de cálculo)

  ![Configuración de descarga](https://github.com/abustosp/Configuraciones/blob/master/Firefox/Descarga-de-Archivos.png?raw=true "Configuración de descarga")

---

## Aclaraciones

- La utilización del bot corre bajo la responsabilidad del que lo ejecuta.

- Si se comparte debe ser de manera GRATUITA, ya que la licencia es bajo PL. También los bots derivados deben seguir la misma licencia gratuita.

---

## Links de Interés:

- Link de invitación al grupo de RPA en Discord: https://discord.gg/KVYyryvAcD

- Link de invitación al grupo de RPA en WhatsApp: https://chat.whatsapp.com/IekktfvfTNLCkdIagO6xz3

- Tutorial de Descarga de Bots desde Uipath: https://youtu.be/hD5BH7YzABw

- Tutorial de Instalación y descarga de Repositorios con Git: https://youtu.be/ujk27tRdA80

---

Cualquier cosa pueden contactarme en:

- https://www.linkedin.com/in/agust%C3%ADn-bustos-piasentini-468446122/

- https://www.youtube.com/user/agustinbustosp

- whatsapp al https://wa.me/+5493764224695

---


### 💰 Acepto donaciones para mantener el proyecto libre y gratuito


[![PayPal](https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white)](https://paypal.me/agustinbustosp)

[![Invitame un café en cafecito.app](https://cdn.cafecito.app/imgs/buttons/button_5.svg)](https://cafecito.app/abustos)

---
### 💰 Y También en Pesos Argentinos


[![Mercado Pago](https://img.shields.io/badge/Mercado%20Pago%20100-009ee3?style=for-the-badge&logo=mercadopago&logoColor=white)](https://mpago.la/2JBdGez)

[![Mercado Pago](https://img.shields.io/badge/Mercado%20Pago%20500-009ee3?style=for-the-badge&logo=mercadopago&logoColor=white)](https://mpago.la/2CwfjKE)

[![Mercado Pago](https://img.shields.io/badge/Mercado%20Pago%201.000-009ee3?style=for-the-badge&logo=mercadopago&logoColor=white)](https://mpago.la/21Xvpig)

[![Mercado Pago](https://img.shields.io/badge/Mercado%20Pago%205.000-009ee3?style=for-the-badge&logo=mercadopago&logoColor=white)](https://mpago.la/1s4D4mM)

[![Mercado Pago](https://img.shields.io/badge/Mercado%20Pago%2010.000-009ee3?style=for-the-badge&logo=mercadopago&logoColor=white)](https://mpago.la/1n9cimr)
