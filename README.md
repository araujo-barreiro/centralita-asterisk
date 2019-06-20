# Centralita Asterisk
Proyecto final de la asignatura Redes Multimedia de Teleco. Centralita telefónica VoIP y proxy SIP en Asterisk. El proyecto consiste en los archivos de configuración necesarios para implementar la centralita en Asterisk. 

## Funcionalidades

* 10 extensiones de voz: de la 100 a la 109, con contraseñas 100rmm - 109rmm (`sip.conf`), y cada una con su respectivo buzón de voz asociado, con contraseñas 1000 - 1090 (`voicemail.conf`).
* Música de espera mientras no se contesta a la llamada, con timeout de 12 segundos (`musiconhold.conf`).

## Menú interactivo
En la extensión 800 hay un menú interactivo IVR que ofrece las siguientes opciones:

  1. Acceso al buzón de voz del usuario
  2. Activar/desactivar el servicio no molestar (DND)
  3. Activar/desactivar el desvío de llamadas
  4. Servicio de despertador: el usuario graba un mensaje y la centralita le llama y se lo reproduce a la hora deseada.

Esta configuración se encuentra en el archivo `extensions.conf`

## Autores
<li>Diego Araújo Novoa: <a href="https://github.com/diegoara96">@diegoara96</a>
<li>Guillermo Barreiro Fernández: <a href="https://github.com/gbarreiro">@gbarreiro</a>
