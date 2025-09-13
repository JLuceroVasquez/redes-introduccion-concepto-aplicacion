<hr><img width="800" height="239" alt="Proyecto basico networking" src="https://github.com/user-attachments/assets/036486f2-787e-4f32-84ba-6fa703363762" />
<p align="center">
  <img src="https://img.shields.io/badge/Estado-Finalizado-blue">
</p>

# Proyectos del Curso de Redes

## Proyecto 1: Comunicación entre dos redes privadas mediante un router
En este proyecto se configuró la comunicación entre **dos redes privadas distintas** utilizando un router como intermediario.  
- Cada red tenía su propio rango de direcciones IP privadas.  
- Se configuraron las **interfaces del router** con direcciones IP correspondientes a cada red.  
- En cada computadora se definió la **puerta de enlace predeterminada (default gateway)**, que apuntaba a la interfaz del router de su red.  
- Finalmente, se verificó la conectividad entre computadoras de diferentes redes mediante el comando `ping`.  

Este proyecto permitió comprender cómo un router facilita la interconexión de redes privadas diferentes.

## Proyecto 2: Comunicación entre una red local DHCP y una red pública mediante un router
En este proyecto se simuló la conexión de una **red local con asignación dinámica de direcciones (DHCP)** hacia una **red pública** (representando, por ejemplo, Internet).  
- El router actuó como intermediario entre la red local y la red pública.  
- Se configuró un **servidor DHCP** para asignar automáticamente direcciones IP a los equipos de la red local.  
- En la interfaz del router conectada a la red pública se asignó una **IP pública**, utilizada como dirección de salida para la red local.  
- Mediante el mecanismo de **NAT (Network Address Translation)**, las direcciones privadas de los equipos locales fueron traducidas a la dirección pública del router para poder comunicarse con servidores externos.  
- La comunicación se verificó simulando el acceso a un servidor público (por ejemplo, un servidor con dirección IP asignada como si fuera Google).
- Se configuró un servidor **DNS (Domain Name Service)** para la traducción de nombres de dominio a direcciones IP.

Este proyecto permitió entender cómo funciona la conexión de una red privada a Internet y el rol del router en la traducción de direcciones IP.
