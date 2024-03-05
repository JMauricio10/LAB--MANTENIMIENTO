# Mantenimiento Correctivo en Hardware 
<p><code>Fundamentos de Mantenimiento</code></p>

<p>Creado por <code>Jsotelo</code> para fortalecer los fundamentos de la <code>reparacion de los equipos de computo</code> en los cursos de mantenimiento y reparacion </p>

# Practica de laboratorio 03

## Objetivos

### Objetivo General
Proporcionar el conocimiento y generar las habilidades necesarias realizar un buen mantenimiento correcitvo de sistemas.

### Objetivos Específicos:
- Conocer los metodos de instalacion de sistemas operativos.
- Realizar la instalacion adecuada de los sistemas operativos.
- Identificar las caracteristicas de los equipos, y sus apropiado sistema operativo.

---
## 1. [Configurar el entorno de trabajo](#) ✔
1. Cree si no existe el repositorio [__"Mantenimiento"__][1_2] en su cuenta de github. ✔
1. Agregue un archivo llamado [__"laboratorio_3.md"__][1_2] a este repositorio. ✔
1. Invite a los compañeros de grupo como colaboradores en este repositorio. ✔
1. Documente cada uno de los items a continuación con capturas de pantalla y código . ✔


## 2. [Preguntas reflexivas de ambientación](#) ✔

<ol type="a">

<li>¿Por que es mejor Instalar el sistema desde cero que montarlo en otro ya existente?</li>

[RESPUESTA]()

Instalar un sistema desde cero es mejor por que al instalar comienzas con un sistema limpio, sin residuos de programas antiguos o configuraciones inecesarias.
Un sistema limpio tiende a ser mas rapido y eficiente ya que no arrastra conflictos o problemas anteriores.

Tenemos un control total de personalizacion en donde podemos elegir la opciones de instalacion, particionar el disco sugun nuestras necesidades y configurar todo a nuestro gusto.

Estabilidad y fiabilidad: un sistema recien instalado tiene menos probabilidades de errores, mayor confiabilidad al evitar problemas heredados.

Actualizacion de controladores y Software: al instalar desde cero podemos asegurarnos de que los controladores esten actualizados 

Seguridad: un sistema limpio es menos propenso a vulnerabilidades de seguridad, se reduce el riesgo de tener malware o virus ocultos en el sistema existente.

<li>¿Que significa MBR?.</li>

[RESPUESTA]()

MBR es un componente fundamental en la estructura de almacenamiento de un disco duro.

FUNCION: el MBR es el primer registro del disco duro. Contiene un programa ejecutable y una tabla donde se definen las particiones del disco.

UBICACiON FISICA: el MBR ocupa el primer sector fisico del disco.

ARRANQUE DEL SISTEMA OPERATIVO: cuando se inicia el sistema desde el disco duro, la BIOS copia el contenido dela MBR en una direccion fija de la memoria y luego le da el control. Este codigo arranca el sistema operativo o gestor de arranque mas complejo.

<li>¿Que significa GPT?.</li>

[RESPUESTA]():

Es un estandar utilizado para organizar la estructura de particiones en discos duros. Forma parte de la UEFI (interfaz de Firware Extendible Unificada), que remplaza al antiguo Bios de los sistemas modernos.

La GPT utiliza se utiliza para configurar las tablas de las particiones en discos duros, especialmente en aquellos de con gran capacidad 

Ofrece mayor estabilidad capacidad y estabilidad en comparacion con el antiguo MBR.

<li>¿Que ventajas tiene usar la instalacion del sistema por medio de UEFI?.</li>

[RESPUESTA]():

Las ventajas de utilizar UEFI son:

PROGRMACION DE LENGUAJE EN C: UEFI se programa en lenguaje C, lo que facilita su desarrollo y permite una mayor flexibilidad en comparacion del BIOS.

VELOCIDAD DE ARRANQUE: UEFI ofrece un arranque mas rapido en comparacion con el BIOS. Esto es especialmente util para reducir el tiempo de espera al encender la computadora.

SOPORTE PARA DISPOSITIVOS DE ALMACENAMIENTO GRANDES: UEFI permite el arranque desde dispositivos de almacenamiento de mayor capacidad.

PERMITE AÑADIR EXTENCIONES DE TERCEROS

SEGURIDAD CON SECURE BOOT: incluye la funcion de Secure Boot lo que proporciona un capa adicional de seguridad al verificar la autenticidad de los componentes del sistema durante el arranque.

PERSONALIZACION Y OPCIONES AVANZADAS: permite cargar controladores antes de que el sistema operativo se inicie, lo que brinde mas opciones de configuracion.

<li>¿Que ventajas tiene instalar sin UEFI?.</li>

[RESPUESTA]():

SIMPLICIDAD: el BIOS es mas simple en terminos de diseño y configuracion. No tiene una interfaz grafica sofisticada y se maneja principalmente con el teclado.

COMPATIBILIDAD CON SISTEMAS OPERATIVOS ANTIGUOS:algunos sistemas operativos mas antiguos pueden no ser compatibles con UEFI.Si necesitas ejecutar un sistema operativo mas antiguo, el BIOS podria ser el mas adecuado.

RECUPERACION DE DATOS: en caso de fallas, la recuperacion de datos puede ser mas sencilla con el BIOS debido a su simplicidad.

<li>¿Que es mas recomendable?</li>

[RESPUESTA]():

Desde mi punto de vista es recomendable instalar en modo UEFI para aprovechar sus ventajas de seguridad y personalizacion.

</ol>


## 3. [Caracterizar del Pc de Practica](#) ✔
|Parámetro||Valor|
|--|:--:|--:|
|Marca|-->|Lenovo|
|Referencia|-->|196802802109|
|Velocidad de la CPU|-->|3.5Ghz|
|Tamaño de la memoria RAM|-->|8GB|
|Sistema Operativo|-->|windows 10 professional|
|Tipo de WIFI|-->|red inalambrica|
|Voltaje DC|-->|20V C 4.5A|

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
[![image-8.png](https://i.postimg.cc/qRbLGs9r/image-8.png)](https://postimg.cc/mz9CLHLp)

9. Configurar el usuario de sesion.

[![image-13-1.png](https://i.postimg.cc/gJZJMd70/image-13-1.png)](https://postimg.cc/KkmxjXxX)

10. Verificacion de sistema.

[![tutorials-1-0-02288600-1541027641.png](https://i.postimg.cc/sf772wFk/tutorials-1-0-02288600-1541027641.png)](https://postimg.cc/4n4mLvxP)

11. Elimincaion de complemento basura.
12. instalacion de licencias.




## 5. [Caracterizas del sistema final](#) ✔

|Parámetro||Valor|
|--|:--:|--:|
|Sistema Operativo|-->|windows|
|Arquitectura de sistema|-->|x64|
|version de producto|-->|windows 10 pro|
|Version del sistema|-->|22.04H|
|Licencia|-->|wordgrouo|
|Codigo de Licencia|-->|Lenovo Ideapad|





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
