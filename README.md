# dmz-lab

Proyecto realizado como parte del Bootcamp de ciberseguridad de 4Geeks Academy
Mod. 22 - Construyendo y Asegurando una Red con una Zona Desmilitarizada

El presente proyecto tiene como objetivo:

Configurar una DMZ segura y funcional en Cisco Packet Tracer utilizando un router Cisco ISR como firewall central. Se aplicó NAT estático para exponer un servidor web desde la DMZ a Internet, y ACLs extendidas para controlar estrictamente el tráfico: permitir solo HTTP desde red externa a DMZ, y bloquear completamente cualquier comunicación iniciada desde DMZ hacia LAN interna. 

Se partió de la siguiente topología proporcionada por 4Geeks Academy:

Cantidad de redes: 3 subredes (/24 cada una).
Dispositivos usados: 1 Router Cisco 2911 (Router_FW), 3 Switches 2960 (Internal, DMZ, External), 1 PC_Internal, 1 Server-PT Web_DMZ, 1 PC_External.
    • LAN Interna (verde, 192.168.1.0/24): Red privada segura (PC_Internal).
    • DMZ (naranja, 192.168.2.0/24): Zona expuesta con servidor web público (Server_DMZ).
    • Red Externa/Internet (amarillo, 192.168.3.0/24): Simulación de Internet (PC_External).

Se incluye la siguiente estructura de archivos:

    • pt-lab/DMZ_PROJECT.pka: contiene el archivo final de Packet Tracer.
    • informe/Informe_DMZ_Laboratorio.md: contiene el informe de configuración de la DMZ.
    • evidencias/Informe de configuración de DMZ con Cisco Packet Tracer.pdf: contiene el informe con las evidencias recogidas en el laboratorio.
    
