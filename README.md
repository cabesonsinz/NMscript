# Nscript 
Nscript es un sencillo script escrito en python que nos ayuda a acceder a algunas funcionalidades de  nmap de manera rapida y sencilla el codigo de este es extremadamente sencillo  y muy mejorable  lo subo porque fue uno de mis primeros proyectos  y  le tengo mucho cariño (Pronto subire  el mismo proyecto con la libreria de nmap)

<IMG SRC = "https://github.com/cabesonwiliams/Nscript/blob/main/gif.gif">

# Menu  



     _________________________________________________________________________________________
    | [0] Nmap help                                                                           |
    | [1] Scanear 1000 puertos famosos                                                        |
    | [2] Scanear todos los puertos existentes                                                |
    | [3] Escaneo de servicios estandar                                                       |
    | [4] Escaneo de servicios agreviso                                                       |
    | [5] Scan Detallado                                                                      |
    | [6] Scanear de OS                                                                       |
    | [7] Scanear SubRed                                                                      |
    | [8] Scanear un solo puerto                                                              |
    | [9] Scaneo silencioso - No deja rastros en el servidor...                               |
    | [10] Host activos en la web + trace route (RH)                                          |
    | [11] Host activos en una red (LH)                                                       |
    | [12] Identidicar IP                                                                     |
    | [13] Confundir al firewall para que suelte datos importantes                            |
    | [14] Utilizar seÃ±uelos - para que un IDS no nos detecte - Host fake                    |
    | [15] Detectar Firewall                                                                  |
    | [16] Deteccion de Firewall exacta                                                       |
    | [17] Escaneo agresivo - Puede dejar rastros en el servidor                              |
    | [18] Escanear todos los puertos - [TCP]                                                 |
    | [19] Escanear todos los puertos - [UDP]                                                 |
    | [20] Mandar paquetes ICMP                                                               |
    |_________________________________________________________________________________________|
    |                                                                                         |
    | [001] FTP brute force  -- (Script usado para la fuerza bruta en el protocolo ftp)       |
    | [002] Safe script nmap -- (Script que permite un escaneo silencioso)                    |
    | [003] Vuln script --  (Script que busca vulnerabilidades)                               |
    | [004] Dns Search --  (Script utilizado para la busqueda de subdominios)                 |
    | [005] MySql DB -- (Script que nos permite buscar contrasenias en servicios mysql)       |
    | [000] Salir                                                                             |
    |_________________________________________________________________________________________|
 <IMG SRC = "https://github.com/cabesonwiliams/Nscript/blob/main/Nscript2.PNG">   
    
# Nmap
Nmap, abreviatura de Network Mapper, es una herramienta gratuita de código abierto para el escaneo de vulnerabilidades y el descubrimiento de redes. Los administradores de red utilizan Nmap para identificar qué dispositivos se están ejecutando en sus sistemas, descubrir hosts que están disponibles y los servicios que ofrecen, encontrar puertos abiertos y detectar riesgos de seguridad. Nmap se puede utilizar para monitorear hosts individuales, así como redes extensas que abarcan cientos de miles de dispositivos y multitudes de subredes.

Aunque Nmap ha evolucionado a lo largo de los años y es extremadamente flexible, en el fondo es una herramienta de escaneo de puertos que recopila información mediante el envío de paquetes sin procesar a los puertos del sistema. Escucha las respuestas y determina si los puertos están abiertos, cerrados o filtrados de alguna manera por, por ejemplo, un firewall. Otros términos utilizados para el escaneo de puertos incluyen descubrimiento o enumeración de puerto





--------------------------------
> Instalación
> 
 (ejecutar como root)
 
     $ git clone https://github.com/cabesonwiliams/Nscript.git 
    
     $ cd Nscript
     
     $ chmod + x Nscript.py
	
     $ python3 Nscript.py
	
     /Para su correcto funcionamiento usar kali lunux o parrot os de lo contrario instalar nmap en su sistema operativo/
	

--------------------------------
	
# by cabeson sin z
