# PRACTICA1_REDES_1S_2022 
# Introducción
__A lo largo del tiempo, las empresas se han visto en la necesidad de implementar un manejo de conexiones en sus redes debido a su crecimiento bastante grande como empresa__

__Como estudiantes de la Universidad de San Carlos de Guatemala, nos han contratado para realizar un modelo de conexiones entre dos niveles que consiste en tener:__

_Primer nivel:_

* 1PC para la recepción
* 2PC para la gerencia
* 2PC para atención al cliente
* 6PC para la oficina

_Segundo nivel:_

* 2PC para oficina A
* 3PC para oficina B
* 5PC para oficina C 

__Los factores mencionados previamente, se deben lograr conectar a través de dos switches y que estos muestren comunicación a través de pings a diferents PC's de distintas areas y niveles__

## Configuración VCP's

__Configuración PC1__

_Configurando la ip de la PC1 del primer nivel, correspondiente a la recepción:_

[![Recepci-n.jpg](https://i.postimg.cc/BnvMwLpf/Recepci-n.jpg)](https://postimg.cc/zV9Cyf4x)

_Hacemos  ping a la PC1:_

[![Ping-Recepcion.jpg](https://i.postimg.cc/0jqVtVWV/Ping-Recepcion.jpg)](https://postimg.cc/vg37Ttdn)

__Configuración PC2__

_Configurando la ip de la PC2 del primer nivel, correspondiente a la gerencia:_

[![Gerencia.jpg](https://i.postimg.cc/ZnkMGbRF/Gerencia.jpg)](https://postimg.cc/1nHB6ZDf)

_Hacemos  ping a la PC2:_

[![Ping-Gerencia.jpg](https://i.postimg.cc/FK8WSrj5/Ping-Gerencia.jpg)](https://postimg.cc/nsKGbtR0)

__Configuración PC4__

_Configurando la ip de la PC4 del primer nivel, correspondiente a atención al cliente:_

[![Atenci-n-Al-Cliente.jpg](https://i.postimg.cc/fbrFvjQP/Atenci-n-Al-Cliente.jpg)](https://postimg.cc/94yJm9MP)

_Hacemos  ping a la PC4:_

[![Ping-Atencion-al-cliente.jpg](https://i.postimg.cc/pL012Yrd/Ping-Atencion-al-cliente.jpg)](https://postimg.cc/FYLxpSjt)

__Configuración PC8__

_Configurando la ip de la PC8 del primer nivel, correspondiente a la oficina:_

[![Oficina.jpg](https://i.postimg.cc/hPBYMtNK/Oficina.jpg)](https://postimg.cc/Hj63kdpN)


_Hacemos  ping a la PC8:_

[![Ping-Oficina.jpg](https://i.postimg.cc/NMXN734y/Ping-Oficina.jpg)](https://postimg.cc/S2y7mtHq)

__Configuración PC21__

_Configurando la ip de la PC21 del segundo nivel, correspondiente a la Oficina A:_

[![Oficina-A-S2.jpg](https://i.postimg.cc/DfsDqXjC/Oficina-A-S2.jpg)](https://postimg.cc/6TWYKyNR)


_Hacemos  ping a la PC21:_

[![Ping-Oficina-A.jpg](https://i.postimg.cc/qqXjW2W4/Ping-Oficina-A.jpg)](https://postimg.cc/1VXGqV9j)

__Configuración PC23__

_Configurando la ip de la PC23 del segundo nivel, correspondiente a la Oficina B:_

[![OficinaB.jpg](https://i.postimg.cc/7hgWDFJv/OficinaB.jpg)](https://postimg.cc/0Kyf0HCZ)


_Hacemos  ping a la PC23:_

[![Ping-Oficina-B.jpg](https://i.postimg.cc/XNwHZ0qm/Ping-Oficina-B.jpg)](https://postimg.cc/PN5zc9mQ)

__Configuración PC27__

_Configurando la ip de la PC27 del segundo nivel, correspondiente a la Oficina C:_

[![OficinaC.jpg](https://i.postimg.cc/ncGPWttB/OficinaC.jpg)](https://postimg.cc/sv1mBqxg)

_Hacemos  ping a la PC27:_

[![Ping-Oficina-C.jpg](https://i.postimg.cc/3JYLmbDR/Ping-Oficina-C.jpg)](https://postimg.cc/qgDXdwwV)


## Ping entre hosts 

__Ping gerencia - oficina A__

_Vista desde el modelo general:_

[![Pinggerencia-oficina-a.jpg](https://i.postimg.cc/sX2W37B3/Pinggerencia-oficina-a.jpg)](https://postimg.cc/jWG2XWQ1)

_Ping PC3 del primer nivel del area de gerencia, hacia la PC1 del segundo nivel de la oficina A:_

[![Ping1.jpg](https://i.postimg.cc/VNgMyDk7/Ping1.jpg)](https://postimg.cc/rddzxGWW)

_Ping con vista de wirkshare_

[![Ping111.jpg](https://i.postimg.cc/QNyP5rrq/Ping111.jpg)](https://postimg.cc/xqLtDh8k)

__Ping atención al cliente - oficina C__

_Vista desde el modelo general:_

[![Ping-Atencion-al-cliente-Oficina-C.jpg](https://i.postimg.cc/kG6tbCFZ/Ping-Atencion-al-cliente-Oficina-C.jpg)](https://postimg.cc/QKDM2Rzk)

_Ping PC4 del primer nivel del area de atención al cliente, hacia la PC10 del segundo nivel de la oficina C:_

[![Ping-2.jpg](https://i.postimg.cc/fRxmCwnQ/Ping-2.jpg)](https://postimg.cc/Jszs4Czp)

_Ping con vista de wirkshare_

[![Ping-11.jpg](https://i.postimg.cc/sxqNR5JL/Ping-11.jpg)](https://postimg.cc/hQ8rLz68)

__Ping oficina primer nivel  - oficina B__

_Vista desde el modelo general:_

[![Ping-Oficina-a-Oficna-B.jpg](https://i.postimg.cc/76Q2hh70/Ping-Oficina-a-Oficna-B.jpg)](https://postimg.cc/S2Cstygx)

_Ping PC6 del primer nivel de la oficina , hacia la PC5 del segundo nivel  de la oficina B:_

[![Ping3.jpg](https://i.postimg.cc/CKSD6WSB/Ping3.jpg)](https://postimg.cc/rDZKDZdM)

_Ping con vista de wirkshare_

[![Ping22.jpg](https://i.postimg.cc/zXHQFPzY/Ping22.jpg)](https://postimg.cc/kB9wnsRT)


## Captura de un paquete ARP

_Empezamos la captura de paquetes desde Wirkshare_

[![Captura-paquete.jpg](https://i.postimg.cc/tTncvZX4/Captura-paquete.jpg)](https://postimg.cc/1nPMfznk)

_Iniciamos la captura de paquetes_

[![Inicio-Captura-Paquetes.jpg](https://i.postimg.cc/jSqF0ks9/Inicio-Captura-Paquetes.jpg)](https://postimg.cc/9rSpybwt)

__Ping gerencia hacia la Oficina A__

_Realizamos el ping de la PC2 a la PC22_

[![Ping-PC2-PC22.jpg](https://i.postimg.cc/tCkB5thz/Ping-PC2-PC22.jpg)](https://postimg.cc/Tpyj2bNy)


_Buscamos los paquetes ARP_

[![Paquetes-ARP.jpg](https://i.postimg.cc/BvX7tLPB/Paquetes-ARP.jpg)](https://postimg.cc/XZ6kzv8r)

_Filtramos por paquetes ARP_

[![Filtrado.jpg](https://i.postimg.cc/05TnP5sh/Filtrado.jpg)](https://postimg.cc/kDyKymDy)


# Topologia


[![Topologia.jpg](https://i.postimg.cc/9fLwMbqr/Topologia.jpg)](https://postimg.cc/nsQhSv2J)


