
## ✅ Procesamiento y Análisis de Datos

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

## ✅ Bases de Datos

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

## ✅ Orquestación y Workflow

10. **Apache Airflow**  
    - **Licencia:** Apache License 2.0  
    - **Uso:** Orquestación de pipelines de datos.  
    - **Ideal para:** ETL, Data Engineering.  

11. **Luigi**  
    - **Licencia:** Apache License 2.0  
    - **Uso:** Creación de workflows complejos.  
    - **Ideal para:** Procesos batch.  

---

## ✅ Machine Learning y Ciencia de Datos

12. **TensorFlow**  
    - **Licencia:** Apache License 2.0  
    - **Uso:** Framework para Deep Learning.  
    - **Ideal para:** IA, modelos predictivos.  

13. **Scikit-learn**  
    - **Licencia:** BSD  
    - **Uso:** Algoritmos clásicos de Machine Learning.  
    - **Ideal para:** Clasificación, regresión, clustering.  

---

## ✅ Visualización

14. **Apache Superset**  
    - **Licencia:** Apache License 2.0  
    - **Uso:** BI y dashboards interactivos.  
    - **Ideal para:** Visualización empresarial.  

15. **Matplotlib / Seaborn**  
    - **Licencia:** BSD  
    - **Uso:** Gráficos estadísticos en Python.  
    - **Ideal para:** Análisis exploratorio.  

---

## ✅ PBX

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

## ✅ Contenedores

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

 
