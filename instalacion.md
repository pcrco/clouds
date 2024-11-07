# Instalació d'ownCloud amb IsardVDI

# Instal·lar la versió 7.4 de php

[1](1.png)

[2](2.png)

[3](3.png)

[4](4.png)

Ara, hem de seleccionar la versió de php que volem instal·lar, que és la 7.4. Escrivim, en aquest cas, "1" per seleccionar-la i li donem a enter.

[5](5.png)

[6](6.png)

Ara sí, anem amb ownCloud. El primer que hem de fer és actualizar la màquina i instal·lar apache2, el servidor web i mysql, el servidor de bases de dades.

[7](7.png)

Instal·larem algunes llibreries de php i reiniciem apache2.

[9](9.png)

[10](10.png)

[11](11.png)

Accedim a la consola de mysql, on creem la base de dades, un usuari i li donem privilegis. Seguit, probarem la connexió a la base de dades.

[12](12.png)

[13](13.png)

Per permetre la connexió des d'una màquina remota, hem de canviar un paràmetre

[14](14.png)

