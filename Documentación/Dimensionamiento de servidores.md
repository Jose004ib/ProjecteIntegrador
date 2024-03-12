|<a name="docs-internal-guid-4fbf7805-7fff-2a76-8324-49390b4fbedd"></a>**SERVIDOR FÍSICO - DELL 1**||||
| :-: | :- | :- | :- |
|S.O|Nuclis|Ram|Discos|
|Lubuntu 22.04 LTS|6|4 GB|<p>1 disc NVMe de 256 GB </p><p>- / (raíz): 50 GB (montaje: /).</p><p>- /home: 100 GB (montaje: /home).</p><p>- swap: 8 GB (montaje: swap).</p><p>- /mnt/virtualbox (128 Gb restantes)</p><p>3 discos SSD de 128 GB </p><p>- /mnt/virtualbox1</p><p>- /mnt/virtualbox2</p><p>- /mnt/virtualbox3</p>|
|||||
||1\. Servidor Empresarial|4\. Monitorització|8\. Còpies de Seguretat|
|Funcionalitat|<p>Utilizando Active Directory facilita la gestión de usuarios y recursos, permitiendo despliegues automatizados con WDS, almacenamiento de imágenes ISO vía iSCSI y actualizaciones automáticas centralizadas para equipos Windows en la red.</p><p></p>|<h4>El servidor Zabbix supervisa y recopila datos de equipos y dispositivos de red, ofreciendo alertas, informes y análisis para mejorar la disponibilidad y el rendimiento de la infraestructura.</h4>|<p>Gestionar copias de seguridad, proteger datos críticos mediante políticas regulares y almacenamiento seguro, asegurando la continuidad operativa y rápida recuperación.</p><p></p>|
|S.O|Windows Server 2022 Standard|Ubuntu Server 22.04  LTS|<p>Truenas 12.0</p><p></p>|
|Nuclis|4|2|2|
|Ram|6 GB|4 GB|2 GB|
|Discos|<p>S.O:</p><p>1 Disco de 64Gb</p><p>RAID 1:</p><p>1 Disco de 32Gb</p><p>1 Disco de 32Gb</p>|<p>S.O:</p><p>1 Disco de 128Gb</p>|<p>S.O:</p><p>1 Disco de 64Gb</p><p>RAID 5:</p><p>1 Disco de 16Gb</p><p>1 Disco de 16Gb</p><p>1 Disco de 16Gb</p><p>1 Disco de 16Gb</p>|
|Targetes de Xarxa|2|1|1|
|Servidor Físic|DELL 1|DELL 1|DELL 1|




<table><tr><th colspan="4"><b>SERVIDOR FÍSICO - DELL 2</b></th></tr>
<tr><td colspan="1">S.O</td><td colspan="1">Nuclis</td><td colspan="1">Ram</td><td colspan="1">Discos</td></tr>
<tr><td colspan="1">Lubuntu 22.04 LTS</td><td colspan="1">6</td><td colspan="1">6GB</td><td colspan="1"><p>- 1 disc NVMe de 256 GB </p><p>- /: 30 GB</p><p>- /home: 20 GB</p><p>- /var: 10 GB</p><p>- Swap: 2GB</p><p>- /mnt/VirtualBox 188Gb</p><p>- 62Gb para lubuntu </p><p>- 138Gb para montarlo en mnt/VirtualBox</p><p></p><p>3 discos SSD de 128 GB: Haremos un grupo de volúmenes con esos 3 discos montados en /mnt/VirtualBox</p></td></tr>
<tr><td colspan="3"></td><td colspan="1" rowspan="1"></td></tr>
<tr><td colspan="1"></td><td colspan="1">2\. Servidor secundario</td><td colspan="1">6\. Servidor Intranet y Web</td></tr>
<tr><td colspan="1">Funcionalitat</td><td colspan="1">Respaldar al servidor principal  en caso de fallara el mismo.</td><td colspan="1">Alojar y servir páginas web para usuarios de la red interna y externos a la red</td></tr>
<tr><td colspan="1">S.O</td><td colspan="1">Windows Server 2022 Core</td><td colspan="1">Debian 12 Bookworm</td></tr>
<tr><td colspan="1">Nuclis</td><td colspan="1">4</td><td colspan="1">2</td></tr>
<tr><td colspan="1">Ram</td><td colspan="1">6 GB</td><td colspan="1">4 GB</td></tr>
<tr><td colspan="1">Discos</td><td colspan="1"><p>S.O:</p><p>1 Disco de 200 Gb</p></td><td colspan="1"><p>S.O:</p><p>1 Disco de 184 Gb</p></td></tr>
<tr><td colspan="1">Targetes de Xarxa</td><td colspan="1">1</td><td colspan="1">1</td></tr>
<tr><td colspan="1">Servidor Físic</td><td colspan="1">DELL 2</td><td colspan="1">DELL 2</td></tr>
</table>


<table><tr><th colspan="4"><b>SERVIDOR FÍSICO - DELL 3</b></th></tr>
<tr><td colspan="1">S.O</td><td colspan="1">Nuclis</td><td colspan="1">Ram</td><td colspan="1">Discos</td></tr>
<tr><td colspan="1">Lubuntu 22.04 LTS</td><td colspan="1">6</td><td colspan="1">6 GB</td><td colspan="1"><p>1 disco NVMe de 256 GB</p><p>Particiones:</p><p>- Sistema: 60 GB, montada en <i>/</i> (raíz).</p><p>- /home: 20 GB, montada en <i>/home</i>.</p><p>- swap: 4 GB, montada en <i>swap</i>.</p><p>- 172 GB (resto) para VirtualBox, montada en <i>/mnt/vbox</i>.</p><p> </p><p>3 discos SSD de 128 GB</p><p>Grupo de volúmenes: </p><p>- Primer volumen: 64 GB, montado en <i>/mnt/vbox/srv3</i>.</p><p>- Segundo volumen: 64 GB, montado en <i>/mnt/vbox/srv5</i>.</p></td></tr>
<tr><td colspan="3"></td><td colspan="1" rowspan="1"></td></tr>
<tr><td colspan="1"></td><td colspan="1">3\. Aplicaciones</td><td colspan="1">5\. Datos</td></tr>
<tr><td colspan="1">Funcionalitat</td><td colspan="1">Gestionar aplicaciones empresariales, con capacidad para alojar, desplegar y operar aplicaciones en un entorno seguro y escalable.</td><td colspan="1"><p>Se centrará principalmente en proporcionar una gestión de datos segura y eficiente.</p><p></p></td></tr>
<tr><td colspan="1">S.O</td><td colspan="1">Windows Server 2022 Standard con entorno gráfico</td><td colspan="1">Windows Server 2022 Standard con entorno gráfico</td></tr>
<tr><td colspan="1">Nuclis</td><td colspan="1">3 núcleos de 1.8 GHz</td><td colspan="1">3 núcleos de 1.8 GHz</td></tr>
<tr><td colspan="1">Ram</td><td colspan="1">5 GB de memoria RAM</td><td colspan="1">5 GB de memoria RAM</td></tr>
<tr><td colspan="1">Discos</td><td colspan="1"><p>1 Disco para el SO con tabla GPT, arranque UEFI y particiones reservadas de sistema + para propio sistema de 50 GB.</p><p></p><p>3 Discos de 128 GB con una partición del mismo tamaño para formar un RAID tipo 5, ya que tenemos 3 discos duros en la máquina, en el que guardaremos todas las aplicaciones y utilidades que queremos instalar en los clientes.</p></td><td colspan="1"><p>1 Disco para el SO con tabla GPT, arranque UEFI y particiones reservadas de sistema + para propio sistema de 50 GB.</p><p></p><p>3 Discos de 128 GB con una partición del mismo tamaño para formar un RAID de tipo 5, porque nos permiten los 3 discos duros que tenemos, en el que guardaremos los datos del servidor.</p></td></tr>
<tr><td colspan="1">Targetes de Xarxa</td><td colspan="1">Se necesitará una tarjeta de red para acceder a la red local. Si está configurado el dominio, no tendrá problemas de acceder a internet.</td><td colspan="1">Se necesitará una tarjeta de red para acceder a la red local. Si está dentro de dominio, tendrá acceso al internet.</td></tr>
<tr><td colspan="1">Servidor Físic</td><td colspan="1">DELL 3</td><td colspan="1">DELL 3</td></tr>
</table>
