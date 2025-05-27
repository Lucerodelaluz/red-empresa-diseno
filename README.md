# red-empresa-diseno
Repositorio para el diseño y documentación de la infraestructura de red de una empresa de diseño y marketing digital

Empresa mediana dedicada al diseño gráfico y marketing digital. Manejan archivos creativos de clientes y proyectos confidenciales.

Se establecieron 4 áreas diferentes: Marketing, administración, servicio cliente y proyectos.

Cada una cuenta con una PC y una laptop, el área de marketing tiene en añadido un access point y un smartphone.

Por lo tanto se tienen 4 VLAN:
10 - Marketing
20 - Administración
30 - Servicio al cliente
40 - Proyectos

Siendo la red WAN 192.168.X.X

------Marketing--------
1 PC - 192.168.10.10
1 Laptop - 192.168.10.11
1 Celular - 192.168.10.20

------Administración--------
1 PC - 192.168.10.11
1 Laptop - 192.168.20.10

------Servicio al cliente--------
1 PC - 192.168.30.10
1 Laptop - 192.168.30.11

------Proyectos--------
1 PC - 192.168.40.10
1 Laptop - 192.168.40.11



