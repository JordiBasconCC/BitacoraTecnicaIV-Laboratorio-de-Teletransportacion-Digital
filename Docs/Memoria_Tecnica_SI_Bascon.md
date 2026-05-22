# **UD07. Elaboración de documentación técnica y uso de aplicaciones de propósito general**

**Alumno:** Jordi Bascón  
**Ciclo:** 1ºDAW  
**Fecha:** 15/05/26

## Índice

[**1.- Análisis de Necesidades	3**](#1.--análisis-de-necesidades)

[**2.- Estimación de Costes de Infraestructura	3**](#2.--estimación-de-costes-de-infraestructura)

[**3.- Estrategia de Despliegue y Comunicación	3**](#3.--estrategia-de-despliegue-y-comunicación)

[**4.- Justificación Científica	4**](#4.--justificación-científica)

[**\*.- Citas	4**](#*.--citas)

# 1.- Análisis de Necesidades 

Con Guacamole y Docker se resolverán problemas dentro de la empresa como pueden llegar a ser la centralización de todos los procesos, obtener una mayor seguridad a la hora de acceder y solucionar alguna incompatibilidad que pueda llegar a tener el sistema, además se obtiene un gran ahorro de recursos al utilizar estas dos herramientas.

Se elige esta opción ya que conectando directamente por RDP se puede llegar a exponer el puerto y que exista probabilidad de un ataque de fuerza bruta al servidor.

# 2.- Estimación de Costes de Infraestructura 

<img width="1195" height="294" alt="image" src="https://github.com/user-attachments/assets/abe610a7-1b32-4a61-843b-d0fba56ea324" />


# 3.- Estrategia de Despliegue y Comunicación {#3.--estrategia-de-despliegue-y-comunicación}

Para el despliegue y la transferencia de los archivos de la aplicación al entorno de producción, utilizaremos SFTP. No se usará el  FTP tradicional, ya que este transmite tanto las credenciales como los datos en texto plano, exponiendo el sistema a ataques de interceptación.

La elección de SFTP es debida a su robustez en seguridad, al operar sobre el protocolo SSH (situado en el puerto 22), con esto se garantiza que todo el canal de comunicación esté completamente cifrado de extremo a extremo, protegiendo el código fuente y las configuraciones sensibles durante el tránsito.

Para la gestión de incidentes y el monitoreo en tiempo real, se integrará Slack con nuestro sistema de alertas automáticas y le configuraremos un canal dedicado llamado alertas de producción, al cual el servidor enviará una notificación inmediata en caso de que ocurra una caída del sistema o un pico crítico en el uso de CPU. Al centralizar estas alertas en Slack, el equipo técnico recibirá notificaciones instantáneas en sus dispositivos móviles y de escritorio, permitiendo una coordinación inmediata, la asignación de un responsable y la resolución del problema en minutos, minimizando así el impacto en los usuarios. 

# 4.- Justificación Científica 

La implementación de un sistema de Planificación de Recursos Empresariales (ERP) es una estrategia para mejorar la eficiencia en la industria textil. Este estudio investiga la instalación de un sistema ERP basado en Odoo para optimizar los procesos de producción. Se utilizó un enfoque cualitativo descriptivo mediante observaciones, entrevistas y análisis de documentos. La evaluación del sistema se hizo mediante modelado de procesos utilizando BPMN y DFD. La implementación del ERP Odoo incluyó módulos de Ventas, Inventario, Fabricación, Compras, Contabilidad, Nómina, CRM, Empleados y Datos de Medición. Los resultados mostraron que Odoo integró los procesos de negocio, disminuyó el registro manual, aceleró el flujo de trabajo y mejoró la precisión de los datos. De este modo, se comprobó que Odoo ERP incrementa la eficiencia en la producción en la industria textil. 

# \*.- Citas 

U. Universidad Esa Unggul, "MPLEMENTASI ERP ODOO UNTUK MENINGKATKAN EFISIENSI PROSES PRODUKSI: STUDI KASUS PADA PT IDOLA KARYA SEMPURNA", Universidad Esa Unggul, . \[Online\]. Available: https://jurnal.goretanpena.com/index.php/JSSR/article/view/5700. \[Accessed: 05-22-2026\].
