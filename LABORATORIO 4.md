# Mantenimiento Correctivo en Hardware 
<p><code>Fundamentos de Mantenimiento</code></p>

<p>Creado por <code>Jsotelo</code> para fortalecer los fundamentos de la <code>reparacion de los equipos de computo</code> en los cursos de mantenimiento y reparacion </p>

# Practica de laboratorio 04

## Objetivos

### Objetivo General
Proporcionar el conocimiento y generar las habilidades necesarias para realizar un buen mantenimiento correcitvo del hardware y software. 

### Objetivos Específicos:
- Conocer los metodos de instalacion de sistemas operativos.
- Realizar la evaluacion adecuada para la reparacion del equipo informatico.
- Identificar las piezas dañadas y dar un diagnostico correcto del equipo informatico.

---
## 1. [Configurar el entorno de trabajo](#) ✔
1. Cree si no existe el repositorio [__"Mantenimiento"__][1_2] en su cuenta de github. ✔
1. Agregue un archivo llamado [__"laboratorio_4.md"__][1_2] a este repositorio. ✔
1. Invite a los compañeros de grupo como colaboradores en este repositorio. ✔
1. Documente cada uno de los items a continuación con capturas de pantalla y código . ✔


## 2. [Preguntas reflexivas de ambientación](#) ✔

<ol type="a">

<li>¿Cual es la importancia de tener una backup de controladores?</li>

[RESPUESTA]()

Tener una copia de seguridad de los controladores es crucial para mantener la estabilidad y funcionamiento adecuado del sistema. En resumen respaldar tus controladores es una practica para garantizar la estabilidad y rendimiento optimo del sistema.

<li>¿Como sacamos los drivers de nuesto equipo?.</li>

[RESPUESTA]()

Crear una nueva carpeta para copiar los drivers con el nombre de Copia-de-seguridad-drivers.

Abre CMD como administrador.

Escribe la siguiente linea de codigo 
 dism /online /export-driver /destination:C:/Copia-seguridad-drivers

 Damos enter 

 Esto creara una copia de seguridad de los controladores en la ubicacion especificada.

Copiar la carpeta donde se guardaron los driver a una memoria USB.

<li>¿Que licencias tiene nuestro equipo informatico?.</li>

[RESPUESTA]()

Licencias de propietario

<li>¿Por que la importancia de las licencias del software?.</li>

[RESPUESTA]()

La importancia de las licencias de software radica en varios aspectos:

LEGALIDAD Y CUMPLIMIENTO las licencias garantizan que estamos utlizazndo el software de manera legal y conforme a los terminos establecidospor los propietarios.

PROTECCION DE DERECHO DE AUTOR las licecias protegen los derechos de autor y propiedad intelectual de los desarroladores.Sin licencia no tenemos derecho a usar, copiar, o distribuir el software.

ESTABILIDAD Y RENDIMIENTO aseguran que estemmos utilizando versiones estables y confiables de software.

GESTION EFICIENTE DE ACTIVOS las empresas puededn rastrear y administrar sus licencias para evitar el uso exesivo o insuficiente de software.

En resumen las licencias son fundamentales para garantizar un uso legal, seguro y eficiente de las aplicaciones en nuestros equipos.

<li>¿Que tipo de licencias existen para nuestro software?.</li>

[RESPUESTA]()

Existen varios tipos de licencia, cada una con sus caracteristicas particulares.

SOFTWARE LIBRE: Carece de copyrighnt y otorga a los usuarios libertades fundamentales como ejecutar, estudiar, adaptar, copiar, redistribuir, compartir y mejorar el programa.

SOFTWARE DE PROPIETARIO: es aquel cuyo creador o dueño legal limita o prohibe la copia, redistribucion y modificacion sin permiso o pago previo ejm: MIcrosoft Office, Adobe Phothoshop, Windows.

SOFTWARE GRATUITO O DE DOMINIO PUBLICO: No tiene copyright y se puede utilizar. El autor puede imponer restricciones en la redistribucion ejm: LibreOffice.

<li>¿Que licencia recomienda para un cliente?</li>

[RESPUESTA]()

Para recomendar una licencia de software a un cliente, es importante considerar sus necesidades especificas y el contexto en el que se utilizara el software. 

LICENCIA DE CODIGO ABIERTO si el cliente busca flexibilidad, transparencia y colaboracion.

LICENCIA PROPIETARIA si el cliente necesita software comercial con soporte tecnico y actualizaciones garantizadas.

LICENCIA GRATUITA O DE DOMINIO PUBLICO para proyectos con presopuesto limitado o necesidades basicas

</ol>


## 3. [Caracterizar del Pc de Practica](#) ✔
|Parámetro||Valor|
|--|:--:|--:|
|Marca|-->|hp|
|Referencia|-->|xxxxx|
|Velocidad de la CPU|-->|2.5 GHz|
|Tamaño de la memoria RAM|-->|8GB|
|Sistema Operativo|-->|windows 10 pro|
|Tipo de WIFI|-->|red inalambrica|
|Voltaje DC|-->|240 w|


## 4. [Configurar básica de PC](#) ✔
1. Conecte los equipos a la red eléctrica.
2. [Reiniciar][4_1] el dispositivo para ingresar a la BIOS.

[![IMG-20240304-104649-032-2.jpg](https://i.postimg.cc/WzS92C3P/IMG-20240304-104649-032-2.jpg)](https://postimg.cc/N298DNmN)

3. Conectar una usb que contenga el sistema a instalar.

[![IMG-20240304-104809-965-2.jpg](https://i.postimg.cc/7Zz9jzVM/IMG-20240304-104809-965-2.jpg)](https://postimg.cc/hXSVdfNf)

4. [Acceder][4_2] a la bios del dispositivo mediante las teclas recomendadas.

[![IMG-20240224-083852-515.jpg](https://i.postimg.cc/V6XXMk9v/IMG-20240224-083852-515.jpg)](https://postimg.cc/k6XVP9pP)

5. [Escoger][4_3] el medio de Booteo.

[![fig-02.png](https://i.postimg.cc/nLB0pt8s/fig-02.png)](https://postimg.cc/NyG1kSjY)


6. Configurar el sistema para la instalacion del sistema.

[![IMG-20240224-085402-239.jpg](https://i.postimg.cc/WbFWRWvx/IMG-20240224-085402-239.jpg)](https://postimg.cc/dLFmr9D9)

7. Particionar El disco duro.

[![IMG-20240224-091349-626.jpg](https://i.postimg.cc/43V3X6B1/IMG-20240224-091349-626.jpg)](https://postimg.cc/xkjQRzrk)

8. Configurar las opciones de configuracion inicial.
9. Configurar el usuario de sesion.

[![image-13-1.png](https://i.postimg.cc/gJZJMd70/image-13-1.png)](https://postimg.cc/KkmxjXxX)

10. Verificacion de sistema.

[![tutorials-1-0-02288600-1541027641.png](https://i.postimg.cc/sf772wFk/tutorials-1-0-02288600-1541027641.png)](https://postimg.cc/4n4mLvxP)

11. Elimincaion de complemento basura.


12. instalacion de licencias.

[![Licencias-Terminal-04.png](https://i.postimg.cc/htcxwcKk/Licencias-Terminal-04.png)](https://postimg.cc/hfZfQFzs)

13. Destapár el equipo con cuidado

[![IMG-20240302-092405-070.jpg](https://i.postimg.cc/yYXtSFFp/IMG-20240302-092405-070.jpg)](https://postimg.cc/D80B94p1)

[![IMG-20240302-092710-166.jpg](https://i.postimg.cc/BvFvJrJy/IMG-20240302-092710-166.jpg)](https://postimg.cc/nsHxkwjY)

14. Revisar el equipo y dar una evaluacion rapida.

[![IMG-20240302-093751-565.jpg](https://i.postimg.cc/wvg0zrr6/IMG-20240302-093751-565.jpg)](https://postimg.cc/FfCjgTmq)

15. Desarmar los componentes y hacer una limpieza.


[![IMG-20240302-093756-601.jpg](https://i.postimg.cc/NjL0Jfft/IMG-20240302-093756-601.jpg)](https://postimg.cc/HrDHjmyv)

[![IMG-20240302-093112-001.jpg](https://i.postimg.cc/bYVZvmnz/IMG-20240302-093112-001.jpg)](https://postimg.cc/CdDhPHJt)

[![IMG-20240302-094354-368.jpg](https://i.postimg.cc/NjCLcSM1/IMG-20240302-094354-368.jpg)](https://postimg.cc/CRDwCvb1)

[![IMG-20240302-092128-823.jpg](https://i.postimg.cc/FF6PYsBq/IMG-20240302-092128-823.jpg)](https://postimg.cc/PNmbchhz)

[![IMG-20240302-094206-639.jpg](https://i.postimg.cc/zGQWjVnZ/IMG-20240302-094206-639.jpg)](https://postimg.cc/Yv1h22nb)

[![IMG-20240302-094250-889.jpg](https://i.postimg.cc/g0xbbnfz/IMG-20240302-094250-889.jpg)](https://postimg.cc/5HWRwN4T)


16. Cambiar la pasta termica con cuidado y mucha delicadeza.

[![IMG-20240302-115547-722.jpg](https://i.postimg.cc/g0xDm3yN/IMG-20240302-115547-722.jpg)](https://postimg.cc/rdLW90Pr)

[![IMG-20240302-093504-356.jpg](https://i.postimg.cc/8C826HJJ/IMG-20240302-093504-356.jpg)](https://postimg.cc/sMcHF5Js)


17. volver a armar el equipo y ensamblar adecuadamente.

[![IMG-20240302-093019-210.jpg](https://i.postimg.cc/DfWKh6Pk/IMG-20240302-093019-210.jpg)](https://postimg.cc/hhqYb9Yp)

[![IMG-20240302-113406-048.jpg](https://i.postimg.cc/HLSfD8Jk/IMG-20240302-113406-048.jpg)](https://postimg.cc/sBhn5X9k)

[![IMG-20240302-092405-070.jpg](https://i.postimg.cc/XNKK9fxT/IMG-20240302-092405-070.jpg)](https://postimg.cc/3WRDTDsB)

[![IMG-20240302-124033-424.jpg](https://i.postimg.cc/YqqFgJvW/IMG-20240302-124033-424.jpg)](https://postimg.cc/Sj3jb17S)

## 5. [Caracterizas del sistema final](#) ✔

|Parámetro||Valor|
|--|:--:|--:|
|Sistema Operativo|-->|windows|
|Arquitectura de sistema|-->|x64|
|version de producto|-->|windows 10 pro|
|Version del sistema|-->|22.04H|
|Licencia|-->|wordgrouo|
|Codigo de Licencia|-->|nombre del equipo|
|Componente corregido|-->|pasta termica|
|Codigo del corregido|-->|hp|
|Codigo de placa base|-->|hp|




[psk]:https://es.wikipedia.org/wiki/Pre-shared_key
[dhcp]:https://es.wikipedia.org/wiki/Protocolo_de_configuraci%C3%B3n_din%C3%A1mica_de_host
[wlan]:https://es.wikipedia.org/wiki/Red_de_%C3%A1rea_local_inal%C3%A1mbrica
[4_1]:https://www.elespanol.com/elandroidelibre/tutoriales/20230620/truco-oculto-reiniciar-ordenador-windows-bloqueado-conoce/772922871_0.html#:~:text=En%20ese%20caso%2C%20el%20truco,acceso%20al%20administrador%20de%20tareas.
[4_2]:https://www.ionos.es/digitalguide/servidores/configuracion/entrar-en-la-bios/
[4_3]:https://support.microsoft.com/es-es/windows/crear-medios-de-instalaci%C3%B3n-de-windows-99a58364-8c02-206f-aa6f-40c3b507420d

[4_4]:https://learn.microsoft.com/en-us/windows-server/administration/windows-commands/tracert
[4_5]:https://www.tp-link.com/co/home-networking/wifi-router/tl-wr840n/
[6_1]:https://consumer.huawei.com/co/support/content/es-us15855743/
[6_2]:https://forum.huawei.com/enterprise/es/%C2%BFc%C3%B3mo-iniciar-sesi%C3%B3n-en-ont-de-huawei/thread/636939-100243
[6_3]:https://play.google.com/store/apps/details?id=com.lipinic.ping&hl=es_419&gl=US
[6_4]:https://docs.python.org/3.10/library/http.server.html
[6_5]:https://support.huawei.com/enterprise/es/access-network/echolife-hg8546m-pid-21465065
[8_1]:https://wiki.mikrotik.com/wiki/Manual:Reset
[8_2]:https://wiki.mikrotik.com/wiki/Manual:Winbox
[8_3]:https://wiki.mikrotik.com/wiki/Manual:Interface/Ethernet
[8_4]:https://wiki.mikrotik.com/wiki/Manual:Interface/Bridge
[8_5]:https://wiki.mikrotik.com/wiki/Manual:IP/Address
[8_6]:https://wiki.mikrotik.com/wiki/Manual:IP/Pools
[8_7]:https://wiki.mikrotik.com/wiki/Manual:Tools/Ping
[8_8]:https://wiki.mikrotik.com/wiki/Manual:Troubleshooting_tools
