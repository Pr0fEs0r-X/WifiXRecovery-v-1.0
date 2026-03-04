# WifiXRecovery v 1.0
Herramienta diseñada para auditores, administradores de sistemas y usuarios que necesitan recuperar las contraseñas de redes WiFi guardadas en sus equipos.  A diferencia de otros scripts, WiFi X Recovery está construida para ser universal: funciona en los tres principales sistemas operativos y detecta claves en múltiples idiomas automáticamente. (por el momento se ha sacado la version para Windows)

![Made with Python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg?logo=python&logoColor=white)


A diferencia de otros scripts, WiFi X Recovery está construida para ser universal: funciona en los tres principales sistemas operativos y detecta claves en múltiples idiomas automáticamente. <B>(si necesitas el script para LINUX- MAcos !CONTACTAME!)</B>


<img width="502" height="432" alt="ventana" src="https://github.com/user-attachments/assets/3d4735f9-8d97-4295-b22f-38ad18a3a711" />

<br>
<br><b>🚀 Características Principales</b>

    ✅ Multi-OS: Un solo archivo para Windows, Linux y macOS.
    ✅ Multi-Language: Detecta claves en Windows independientemente del idioma del sistema (EN, ES, PT, FR, DE, RU, CN).
    ✅ GUI Moderna: Interfaz estilo "Aqua Dark" con tema tecnológico oscuro y acentos azules.
    ✅ Splash Screen: Pantalla de carga profesional.
    ✅ Exportación: Guarda resultados en archivos .txt.
    ✅ Detección de Hardware: Lista interfaces de red activas.
    ✅ Zero Dependencies: No requiere instalar librerías externas (usa Python Standard Library).

<b>🛠️ Instalación y Uso</b>

Al no requerir librerías externas, la instalación es inmediata.
Prerrequisitos

Tener Python 3.x instalado en el sistema.
Pasos


    Ejecuta la aplicación:
    bash
     
     
    python wifi_hydra_recovery.py
     
    (En Linux/macOS puede que necesites python3 y permisos de administrador para ver las claves). 

<b>💻 Uso por Sistema Operativo</b> 
Windows 

Simplemente ejecuta el script. La herramienta usará netsh para extraer los perfiles y claves. 

     

    Nota: Si hay caracteres extraños, asegúrate de que la terminal soporte la codificación de tu región (la app maneja cp850 y utf-8 automáticamente). 
     

<b>Linux</b> 

Requiere nmcli (NetworkManager). Para ver las contraseñas, es recomendable ejecutar con permisos de administrador: 
bash
 
sudo python3 wifi_hydra_recovery.py
 
<b>macOS </b>

Utiliza el llavero del sistema (security y airport). 

    Nota: macOS solicitará permisos de administrador a través de una ventana emergente del sistema al intentar ver las contraseñas. 
     

📂 Estructura del Proyecto 
text
 
  
 

│<img width="548" height="127" alt="estructura" src="https://github.com/user-attachments/assets/7592e7d4-2488-49d6-9e5b-ee6bd19254a1" />


 
 
 
<b>⚠️ Aviso Legal y Ético </b>

WiFi Hydra Recovery es una herramienta de recuperación de credenciales propias. Está diseñada para ayudar a usuarios a recordar sus contraseñas de WiFi o para auditorías de seguridad en redes propias. 

El uso de esta herramienta para acceder a redes ajenas sin autorización es ilegal. El desarrollador no se hace responsable del mal uso de este software. Úsalo bajo tu propia responsabilidad y siempre dentro del marco legal de tu país. <br> <br>

<b>📜 Licencia</b> 

Este proyecto está bajo la Licencia MIT. Consulta el archivo LICENSE para más detalles. 
<br><br><b>Desarrollado por:</b> 

Rodolfo Hernández Baz aka Pr@fEs0r X
<br>

Rhino Forensic & Reverse Toolkit  
