 
#  **¿Qué son las licencias de software?**

Una **licencia de software** es como un **contrato** que dice **qué puedes hacer y qué no** con un programa.  
Por ejemplo: ¿puedes copiarlo? ¿puedes venderlo? ¿puedes modificarlo?  
Cada licencia tiene sus reglas.


###  **1. Licencias Open Source (Código abierto)**

Permiten usar, modificar y distribuir el software, generalmente con ciertas condiciones.

*   **Apache License 2.0**
    *   Permisiva, permite uso comercial, modificación y distribución.
    *   Requiere mantener avisos de copyright y licencia.
*   **MIT License**
    *   Muy permisiva, permite casi todo con mínima restricción (solo mantener aviso de copyright).
*   **BSD (Berkeley Software Distribution)**
    *   Similar a MIT, muy permisiva, usada en proyectos como FreeBSD.
*   **EPL (Eclipse Public License)**
    *   Permite uso comercial, pero con ciertas restricciones en redistribución.
*   **MPL (Mozilla Public License)**
    *   Permite modificar, pero exige que los cambios se mantengan bajo MPL.
 

###  **2. Licencias Copyleft (Software Libre)**

Obligan a que las modificaciones se distribuyan bajo la misma licencia.

*   **GPL (GNU General Public License)**
    *   Muy popular, usada por Linux.
    *   Todo derivado debe mantenerse bajo GPL.
*   **LGPL (Lesser GPL)**
    *   Similar a GPL, pero más flexible para librerías (permite enlazar con software propietario).
*   **AGPL (Affero GPL)**
    *   Igual que GPL, pero aplica también a software usado vía red (SaaS).
 

###  **3. Licencias Propietarias**

*   No permiten modificar ni redistribuir el código.
*   Ejemplo: **Microsoft EULA**, **Oracle License**, **Adobe License**.


###  **4. Licencias Creative Commons (para contenido, no software)**

*   **CC BY**, **CC BY-SA**, **CC BY-NC**, etc.
*   Usadas para documentación, imágenes, contenido educativo.
 *


---
# Software

##  Procesamiento y Análisis de Datos
 

**Apache Kafka**

*   **Licencia:** Apache License 2.0
*   **Uso:** Plataforma distribuida para transmisión de datos en tiempo real, basada en el modelo **publish-subscribe**.
*   **Ideal para:** Integración de sistemas, pipelines de datos, análisis en streaming, microservicios, IoT.
 
1. **Apache Spark**  
   - **Licencia:** Apache License 2.0  
   - **Uso:** Procesamiento distribuido de grandes volúmenes de datos, compatible con batch y streaming.  
   - **Ideal para:** Big Data, ETL, Machine Learning.  

2. **Pandas**  
   - **Licencia:** BSD  
   - **Uso:** Manipulación y análisis de datos en Python.  
   - **Ideal para:** Dataframes, análisis exploratorio.  

3. **Dask**  
   - **Licencia:** BSD  
   - **Uso:** Procesamiento paralelo y escalable en Python.  
   - **Ideal para:** Escalar análisis de Pandas a clusters.  

4. **Apache NiFi**  
   - **Licencia:** Apache License 2.0  
   - **Uso principal:**  
     - Integración y flujo de datos (ETL en tiempo real).  
     - Conectores para múltiples sistemas (bases de datos, APIs, IoT).  
   - **Ideal para:** Arquitecturas orientadas a microservicios y streaming.  

*   **Debezium**
    *   Es un **framework open source** para **Change Data Capture (CDC)**.
    *   Se conecta a bases de datos (PostgreSQL, MySQL, MongoDB, etc.) y captura cambios en tiempo real.
    *   Publica esos cambios en **Kafka** u otros sistemas de mensajería.
    *   **Licencia:** Apache 2.0.

2.  **Apache Flink**
    *   Especializado en **streaming en tiempo real**.
    *   Muy eficiente para análisis continuo y eventos.
    *   **Licencia:** Apache 2.0.

3.  **Apache Storm**
    *   Procesamiento de datos en tiempo real.
    *   Competidor en escenarios donde Hadoop no es óptimo (Hadoop es más batch).
    *   **Licencia:** Apache 2.0.

4.  **Apache Drill**
    *   Consultas SQL sobre datos distribuidos (similar a Hive, pero más flexible).
    *   **Licencia:** Apache 2.0.

5.  **Apache Beam**
    *   Framework para procesamiento batch y streaming.
    *   Se ejecuta sobre Spark, Flink, etc.
    *   **Licencia:** Apache 2.0.

6.  **Presto (ahora Trino)**
    *   Motor SQL distribuido para Big Data.
    *   **Licencia:** Apache 2.0.


 
---

##  Bases de Datos

5. **PostgreSQL**  
   - **Licencia:** PostgreSQL License (similar a BSD)  
   - **Uso:** Base de datos relacional avanzada, soporta JSON, extensiones geoespaciales.  
   - **Ideal para:** OLTP, análisis híbrido.  

6. **MariaDB / MySQL**  
   - **Licencia:** GPLv2  
   - **Uso:** Bases de datos relacionales populares.  
   - **Ideal para:** Aplicaciones web y sistemas transaccionales.  

7. **Apache Cassandra**  
   - **Licencia:** Apache License 2.0  
   - **Uso:** Base de datos NoSQL distribuida.  
   - **Ideal para:** Alta disponibilidad y escalabilidad.  

8. **ClickHouse**  
   - **Uso:** Analytics OLAP columnar  
   - **Licencia:** Apache 2.0  

9. **etcd**  
   - **Uso:** Base de datos clave-valor distribuida (usada por Kubernetes)  
   - **Licencia:** Apache 2.0
     
###   **DuckDB**
 

*   **DuckDB** es una base de datos analítica embebida, optimizada para consultas OLAP (similar a SQLite pero para análisis).
*   **Licencia:** MIT (100% open source, sin restricciones para uso comercial).
 

###   **Hadoop**

*   **Hadoop** es un framework para procesamiento distribuido y almacenamiento (HDFS  (Hadoop Distributed File System) + MapReduce (programación para procesar datos en paralelo.) y YARN  ( Gestor de recursos y tareas en el clúster.)).
*   **Licencia:** Apache 2.0 (open source, muy permisiva).
 

****
---

##  Orquestación y Workflow

10. **Apache Airflow**  
    - **Licencia:** Apache License 2.0  
    - **Uso:** Orquestación de pipelines de datos.  
    - **Ideal para:** ETL, Data Engineering.  

11. **Luigi**  
    - **Licencia:** Apache License 2.0  
    - **Uso:** Creación de workflows complejos.  
    - **Ideal para:** Procesos batch.  

---

##  Machine Learning y Ciencia de Datos

12. **TensorFlow**  
    - **Licencia:** Apache License 2.0  
    - **Uso:** Framework para Deep Learning.  
    - **Ideal para:** IA, modelos predictivos.  

13. **Scikit-learn**  
    - **Licencia:** BSD  
    - **Uso:** Algoritmos clásicos de Machine Learning.  
    - **Ideal para:** Clasificación, regresión, clustering.  

---

##  Visualización

14. **Apache Superset**  
    - **Licencia:** Apache License 2.0  
    - **Uso:** BI y dashboards interactivos.  
    - **Ideal para:** Visualización empresarial.  

15. **Matplotlib / Seaborn**  
    - **Licencia:** BSD  
    - **Uso:** Gráficos estadísticos en Python.  
    - **Ideal para:** Análisis exploratorio.  

---

##  PBX

- **Asterisk:** El motor PBX más popular y robusto para VoIP. Permite crear sistemas telefónicos completos (IVR, colas, grabación, integración con SIP, etc.).  
- **FreePBX:** Interfaz gráfica y framework sobre Asterisk que simplifica la administración.  
  - **Licencia:** GPL v2 (algunos módulos son comerciales).  
- **Issabel (fork de Elastix):**  
  - **Qué es:** Plataforma de comunicaciones unificadas que integra PBX (Asterisk), correo, chat, CRM y más.  
  - **Licencia:** GPL v2 y GPL v3.  
- **FusionPBX:**  
  - **Qué es:** Interfaz multi-tenant sobre FreeSWITCH (competidor de Asterisk).  
  - **Licencia:** MPL (Mozilla Public License).  

---

##  Contenedores

- **Docker**  
- **Kubernetes**  


---

 
 

### Balanceadores de carga (L4/L7)

*   **HAProxy** (L7, altísimo rendimiento, health checks, stickiness).
*   **NGINX** (reverse proxy, TLS, WAF básico, HTTP/2/3).
*   **Keepalived + VRRP** (IP virtual y failover entre nodos).
*   **Linux LVS (IPVS)** (L4 de alto rendimiento para grandes volúmenes).

> Uso típico: HAProxy/NGINX al frente de apps web y APIs, Keepalived para alta disponibilidad de VIP.

 

### Proxys (forward y reverse)

*   **Squid** (forward proxy, control de acceso, caching, autenticación).
*   **NGINX / HAProxy** (reverse proxy, terminación TLS, balanceo).
*   **Traefik** (reverse proxy dinámico, ideal con Docker/K8s, auto-discovery y Let’s Encrypt).

***

### DNS

*   **BIND 9** (autoritativo y recursivo; integra con AD/Samba mediante DLZ).
*   **PowerDNS** (autoritativo modular; backends SQL; opción PDNS Recursor).
*   **Unbound** (recursivo, performance y seguridad).
*   **dnsmasq** (liviano para DNS + DHCP en sitios pequeños).

***

### DHCP

*   **ISC Kea** (DHCPv4/v6 moderno, API, HA).
*   **ISC DHCP** (clásico; estable).
*   **dnsmasq** (para entornos sencillos o edge).

***

### FTP/FTPS (si es requerido)

*   **vsftpd** (seguro y minimalista).
*   **ProFTPD** (muy configurable, módulos).
*   **Pure‑FTPd** (simple, soporta TLS).

> Nota: cuando sea posible, prefiere **SFTP** (OpenSSH) sobre FTPS.

***

### Servidor Web 

*   **NGINX** (estático + reverse proxy).
*   **Apache HTTPD** (modular; .htaccess; gran ecosistema).
*   **Caddy** (config sencillo, TLS automático).

***

### Servidor de Correo (Exchange alternativo)

*   **Postfix** (MTA robusto) + **Dovecot** (IMAP/POP3, sieve).
*   Suites integradas:
    *   **Mailcow (Docker)** (Postfix+Dovecot+Rspamd+SOGo; administración web).
    *   **iRedMail** (instalación automatizada, completa).
    *   **Zimbra OSE** (groupware, calendario, contactos; versión OSE con limitaciones).
    *   **SOGo** (groupware IMAP, CalDAV/CardDAV; integra con Postfix/Dovecot).

> Añade **Rspamd**/**SpamAssassin** (antispam), **ClamAV** (antivirus), **OpenDMARC/OpenDKIM** (firma y políticas), y **AMaViS** si necesitas pipeline tradicional.

***

### VPN

*   **WireGuard** (moderno, alto rendimiento, simple).
*   **OpenVPN** (muy compatible, madura).
*   **strongSwan** (IPsec, integración empresarial).

***

### Servidor de Archivos

*   **Samba** (compartición SMB, permisos NTFS-like en Linux con ACL).
*   **NFS** (Linux/Unix; alto rendimiento en LAN).
*   **Nextcloud** (file sharing con sincronización, web, permisos, apps colaborativas).

***

### Gestión de usuarios, grupos y políticas (AD alternativo)

*   **Samba AD DC** (Directorio activo compatible, GPO, DNS integrado; unión de máquinas Windows y Linux).
*   **FreeIPA** (Identidad, políticas, Kerberos + LDAP (389-DS), DNS, CA; excelente para Linux; puede integrar con **SSSD**).
*   **OpenLDAP** (LDAP puro; requiere más trabajo para Kerberos/políticas).
*   **Keycloak** (IdP moderno para SSO/OAuth2/OIDC/SAML; no reemplaza AD/GPO, pero complementa apps web y APIs).

> Si usas **Samba AD DC**, puedes mantener GPOs, unir PCs Windows, y usar BIND DLZ para DNS integrado.

***

### Virtualización (gestión tipo VMware)

*   **Proxmox VE** (KVM + LXC, clustering, HA, Ceph; GUI excelente).
*   **XCP‑ng** (XenServer open-source; administración vía **Xen Orchestra**).
*   **Libvirt/KVM + Cockpit** (para hosts Linux con GUI ligera).
*   **OpenNebula** (gestión de virtualización y cloud ligera).
*   **OpenStack** (cloud a gran escala; complejo, multi‑servicio).
*   **Kubernetes** (para contenedores; no VMs; úsalo con **Longhorn**/**Rook/Ceph** para storage).

> Para “gestionador como VMware”: **Proxmox VE** y **XCP‑ng + Xen Orchestra** son los mejores reemplazos con experiencias cercanas en gestión centralizada.

***

### Impresión centralizada

*   **CUPS** (servidor de impresión; drivers; integración con Samba/AD).

***

### Escritorio remoto (RDS alternativo)

*   **Apache Guacamole** (HTML5 gateway para RDP/SSH/VNC; acceso vía navegador).
*   **xrdp** (permite RDP hacia escritorios Linux).
*   **Remmina** (cliente multiplataforma).
*   **NoMachine** (gratuito, no 100% open-source; opcional).

> Para publicar apps/escritorios: Guacamole como gateway, o RDP nativo en servidores Windows unidos a Samba AD.

***

### Backup

*   **BorgBackup** / **Restic** (deduplicación, cifrado, incremental).
*   **Bacula** / **Bareos** (enterprise, agentes, cintas, catálogos).
*   **UrBackup** (imágenes y archivos; fácil para estaciones).
*   **Duplicati** (GUI sencilla; múltiples backends).
*   **Amanda** / **rsnapshot** (clásicos; simples).

 
# Seguridad

## 🔐 Seguridad de Red y Firewall

### **pfSense**

*   **Licencia:** BSD
*   **Uso:** Firewall y router avanzado, filtrado de paquetes, VPN, IDS/IPS.
*   **Ideal para:** Redes empresariales, entornos híbridos, puede ofrecerse como firewall virtual en la nube.

### **OPNsense**

*   **Licencia:** BSD
*   **Uso:** Firewall similar a pfSense, con interfaz moderna y sistema de plugins.
*   **Ideal para:** Seguridad de red con administración sencilla y extensible.



## 🛡️ Detección y Respuesta (IDS/IPS)

### **Snort**

*   **Licencia:** GPL
*   **Uso:** Sistema de detección de intrusiones, análisis de tráfico.
*   **Ideal para:** Monitoreo de seguridad en entornos cloud y on-premise.

### **Suricata**

*   **Licencia:** GPL
*   **Uso:** IDS/IPS con análisis profundo y soporte para protocolos modernos.
*   **Ideal para:** Redes de alto rendimiento y detección avanzada.



## 👤 Gestión de Identidades y Accesos

### **Keycloak**

*   **Licencia:** Apache License 2.0
*   **Uso:** Autenticación, autorización, SSO, OAuth2, OpenID Connect.
*   **Ideal para:** Aplicaciones empresariales y microservicios.



## 🔑 Cifrado y Gestión de Secretos

### **HashiCorp Vault**

*   **Licencia:** MPL 2.0
*   **Uso:** Gestión segura de secretos, cifrado de datos, control de acceso.
*   **Ideal para:** Infraestructura segura en entornos cloud y DevOps.



## 🔍 Escaneo de Vulnerabilidades

### **OpenVAS**

*   **Licencia:** GPL
*   **Uso:** Escaneo de vulnerabilidades en sistemas y redes.
*   **Ideal para:** Auditorías de seguridad y cumplimiento normativo.



## 🐳 Seguridad de Contenedores

### **Trivy**

*   **Licencia:** Apache License 2.0
*   **Uso:** Escaneo de vulnerabilidades en imágenes Docker/Kubernetes.
*   **Ideal para:** Seguridad en pipelines CI/CD.

### **Clair**

*   **Licencia:** Apache License 2.0
*   **Uso:** Análisis de vulnerabilidades en contenedores.
*   **Ideal para:** Integración con registries y plataformas cloud-native.



## 📊 Monitoreo y SIEM

### **Wazuh**
Es una solución de SIEM (Security Information and Event Management) y XDR (Extended Detection and Response) 
*   **Licencia:** GPL
*   **Uso:** SIEM, monitoreo de seguridad, cumplimiento normativo.
*   **Ideal para:** Detección de amenazas en entornos cloud y on-premise.

### **OSSEC**

*   **Licencia:** GPL
*   **Uso:** HIDS (Host-based Intrusion Detection System).
*   **Ideal para:** Protección de servidores y endpoints.



## 🌐 Seguridad de Aplicaciones Web

### **OWASP ZAP (Zed Attack Proxy)**

*   **Licencia:** Apache License 2.0
*   **Uso:** Escaneo de vulnerabilidades en aplicaciones web.
*   **Ideal para:** Pruebas de seguridad en desarrollo y QA.

### **ModSecurity**

*   **Licencia:** Apache License 2.0
*   **Uso:** WAF (Web Application Firewall) para Apache/Nginx.
*   **Ideal para:** Protección contra ataques web (SQLi, XSS).
 


# Monitoreo

### **Prometheus** 

*   **Licencia:** Apache License 2.0
*   **Uso:** Sistema de monitoreo y base de datos de series temporales; recolecta métricas mediante scraping y alerta con PromQL.
*   **Ideal para:** Entornos cloud-native y Kubernetes; monitoreo de métricas de infraestructura y contenedores. 

### **Grafana**  

*   **Licencia:** Apache License 2.0
*   **Uso:** Plataforma de visualización de datos y dashboards que se integra con Prometheus, Elasticsearch, InfluxDB y otros.
*   **Ideal para:** Crear paneles visuales y alertas a partir de múltiples fuentes de datos.  

### **Zabbix**

*   **Licencia:** GPL v2
*   **Uso:** Monitoreo integral de servidores, redes, aplicaciones con recopilación activa, SNMP y alerting.
*   **Ideal para:** Infraestructura tradicional, grandes redes, auto-descubrimiento y monitoreo centralizado.


### **Nagios Core**

*   **Licencia:** GPL v2
*   **Uso:** Motor de monitoreo con plugins para chequear estado de hosts y servicios vía SNMP, ICMP, etc.
*   **Ideal para:** Ambientes donde se requiere máxima personalización de checks y alertas.  


### **Netdata**

*   **Licencia:** GPL v3
*   **Uso:** Monitoreo en tiempo real con actualización por segundo, métricas detalladas e IA para detección.
*   **Ideal para:** Resolver problemas de rendimiento en tiempo real en servidores, contenedores y nube. 


### **ELK Stack (Elasticsearch, Logstash, Kibana)**

*   **Licencias:** Elasticsearch/Kibana bajo AGPL; Logstash y Beats open source
*   **Uso:** Ingesta, almacenamiento y visualización de logs y datos de eventos.
*   **Ideal para:** Log management, análisis en profundidad, monitoreo con búsquedas complejas.  
 
### **Icinga**

*   **Licencia:** GPL v2
*   **Uso:** Monitoreo de infraestructura, redes y aplicaciones, con alertas y paneles web.
*   **Ideal para:** Sustituto moderno de Nagios, entornos empresariales con alta personalización.

 
***

### **Gestión Empresarial (ERP y CRM)**

**Odoo**

**Licencia:** LGPL v3  
**Uso:** Suite empresarial modular que integra ERP, CRM, contabilidad, inventario, ventas, marketing y más en una sola plataforma.  
**Ideal para:** Automatización de procesos, gestión integral de negocios, e-commerce, fabricación, recursos humanos.

***

### **Gestión de Activos y Servicios de TI (ITAM / ITSM)**

### FusionInventory
FusionInventory es **open source** y se utiliza principalmente como complemento para GLPI. Su función principal es realizar el **descubrimiento automático y la gestión de inventario de hardware y software** en una red.

###  **¿Qué hace FusionInventory?**

*   **Inventario automático**: Detecta equipos, servidores, dispositivos de red, impresoras, software instalado, etc.
*   **Escaneo de red**: Descubre dispositivos conectados mediante SNMP, WMI, SSH, etc.
*   **Gestión de paquetes**: Permite desplegar software en equipos administrados.
*   **Integración con GLPI**: Envía la información recolectada directamente a GLPI para mantener el inventario actualizado.
*   **Agente multiplataforma**: Funciona en Windows, Linux, macOS.

###  **Licencia**

*   Es **gratuito y open source**, bajo licencia **GPL v2**.
*   No requiere pago por uso, aunque existen empresas que ofrecen soporte profesional y servicios adicionales.

 
### GLPI
GLPI (Gestionnaire Libre de Parc Informatique) es una herramienta **open source** diseñada para la **gestión de activos de TI y soporte técnico**  (ITAM) y  (ITSM). Se utiliza principalmente en entornos corporativos para administrar recursos tecnológicos y brindar atención a usuarios. Sus principales funciones son:

###  **¿Para qué sirve GLPI?**

1.  **Gestión de inventario de TI**
    *   Permite registrar y controlar equipos, servidores, dispositivos de red, software, licencias, contratos, etc.
    *   Ofrece integración con herramientas de descubrimiento automático (como FusionInventory).

2.  **Mesa de ayuda (Help Desk)**
    *   Gestión de tickets para soporte técnico.
    *   Seguimiento de incidencias, solicitudes y problemas.
    *   Asignación de tareas a técnicos y control de SLA (acuerdos de nivel de servicio).

3.  **Gestión de usuarios y perfiles**
    *   Control de accesos, roles y permisos.
    *   Integración con LDAP/Active Directory.

4.  **Gestión de proyectos y cambios**
    *   Planificación de proyectos relacionados con TI.
    *   Control de cambios y actualizaciones en infraestructura.

5.  **Reportes y estadísticas**
    *   Informes sobre tickets, inventario, costos, tiempos de resolución, etc.

6.  **Integración y extensibilidad**
    *   Compatible con plugins para ampliar funcionalidades (monitorización, automatización, etc.).
    *   API REST para integrarse con otras plataformas.
 

### OCS Inventory
OCS Inventory (Open Computer and Software Inventory) es una herramienta **open source** diseñada para la **gestión automática del inventario de hardware y software** en una red corporativa.

###  **¿Qué es OCS Inventory?**

*   Es un sistema que permite descubrir y registrar automáticamente todos los dispositivos conectados a la red (PC, servidores, impresoras, dispositivos móviles, etc.).
*   Funciona mediante **agentes instalados en los equipos** que envían información al servidor OCS.
*   Compatible con Windows, Linux, macOS y otros sistemas.

### **¿Para qué sirve?**

1.  **Inventario de hardware y software**
    *   Detecta CPU, RAM, discos, tarjetas de red, sistema operativo, aplicaciones instaladas.
2.  **Escaneo de red**
    *   Descubre dispositivos mediante protocolos como SNMP.
3.  **Gestión de paquetes**
    *   Permite desplegar software o actualizaciones en equipos administrados.
4.  **Integración con GLPI**
    *   OCS puede enviar datos a GLPI para mantener el inventario actualizado.
5.  **Control de licencias**
    *   Ayuda a identificar software no autorizado o sin licencia.

###  **Licencia**

*   Es **gratuito y open source**, bajo licencia **GPL**.
*   No requiere pago, aunque existen empresas que ofrecen soporte profesional.


 ---

  
###  **¿Qué es Zentyal?**
**Zentyal** es una solución **open source** que convierte un servidor Linux (generalmente Ubuntu) en un **servidor de red completo para pequeñas y medianas empresas**. Está diseñado para ser una **alternativa a Windows Server** y ofrece una interfaz web amigable para administrar servicios.


*   Es una distribución basada en Ubuntu orientada a la gestión de redes y servidores.
*   Permite administrar servicios de infraestructura desde una interfaz gráfica sin necesidad de usar comandos complejos.


###  **¿Para qué sirve Zentyal?**

1.  **Controlador de dominio y Active Directory**
    *   Implementa autenticación centralizada de usuarios y equipos.
    *   Compatible con **Samba 4**, lo que permite integrarse con entornos Windows.

2.  **Servidor de archivos e impresoras**
    *   Compartición de recursos en red con permisos y cuotas.

3.  **Servidor de correo**
    *   Incluye servicios como SMTP, IMAP, POP3, antivirus y antispam.

4.  **Servidor DHCP y DNS**
    *   Asigna direcciones IP y resuelve nombres en la red local.

5.  **Firewall y Gateway**
    *   Control de tráfico, NAT, VPN (OpenVPN e IPsec).

6.  **Gestión centralizada**
    *   Todo se administra desde una interfaz web intuitiva.




### **1. Bacula**

*   **¿Qué es?**  
    Bacula es una solución **open source** para **copias de seguridad (backup) y restauración** en entornos empresariales.
*   **¿Para qué sirve?**
    *   Realiza **backups automáticos** de servidores, bases de datos y estaciones de trabajo.
    *   Permite **restaurar datos** en caso de pérdida o desastre.
    *   Soporta múltiples sistemas operativos y almacenamiento en disco, cinta o nube.
*   **Caso típico:**  
    Una empresa con varios servidores Linux y Windows usa Bacula para programar copias de seguridad diarias y restaurar datos ante fallos.


### **3. TrueNAS**

*   **¿Qué es?**  
    TrueNAS es un sistema operativo **open source** basado en FreeBSD para crear **almacenamiento en red (NAS)**.
*   **¿Para qué sirve?**
    *   Permite montar un **servidor de almacenamiento centralizado** para archivos, backups y máquinas virtuales.
    *   Soporta protocolos como SMB, NFS, iSCSI.
    *   Ofrece **ZFS** para alta integridad y snapshots.
*   **Caso típico:**  
    Una empresa implementa TrueNAS para tener un repositorio seguro donde guardar backups y compartir archivos entre departamentos.


 

###  **¿Qué es MeshCentral?**

*   Es un servidor que permite **administración remota** de computadoras, tanto dentro como fuera de la red corporativa.
*   Funciona mediante **agentes instalados en los dispositivos** que se conectan al servidor MeshCentral.
*   Compatible con Windows, Linux y macOS.
 

###  **¿Para qué sirve?**

1.  **Acceso remoto seguro**
    *   Control total del escritorio (similar a TeamViewer o AnyDesk).
    *   Acceso a la línea de comandos (SSH, PowerShell).

2.  **Gestión centralizada**
    *   Inventario básico de dispositivos.
    *   Organización por grupos y usuarios.

3.  **Transferencia de archivos**
    *   Subir y descargar archivos entre el administrador y el equipo remoto.

4.  **Multiusuario y roles**
    *   Permite que varios técnicos trabajen en diferentes dispositivos con permisos definidos.

5.  **Open Source y autoalojado**
    *   No depende de servicios externos, ideal para empresas que buscan privacidad.
 
