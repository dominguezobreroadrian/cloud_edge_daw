# Tarea (a+b) · Cloud: niveles y funciones (DAW 1º)

## 🅰️ Tarea A — Niveles de cloud (IaaS/PaaS/SaaS)
Crea una tabla con 10 servicios reales. Incluye enlace oficial y justifica responsabilidades.

| Servicio | Proveedor | Nivel (IaaS/PaaS/SaaS) | Enlace oficial | ¿Qué gestiona el proveedor? | ¿Qué gestiona el equipo/usuario? |
|---------|----------|-------------------------|----------------|-----------------------------|----------------------------------|
| Amazon EC2 | AWS | IaaS | https://aws.amazon.com/ec2/ | Hardware, red, virtualización y centros de datos | Sistema operativo, software, aplicaciones y datos |
| Google Compute Engine | Google Cloud | IaaS | https://cloud.google.com/compute | Infraestructura física y virtual | Configuración del SO y aplicaciones |
| Azure Virtual Machines | Microsoft Azure | IaaS | https://azure.microsoft.com/services/virtual-machines/ | Servidores, red y almacenamiento | Instalación y mantenimiento del sistema y apps |
| OpenStack | OpenStack Foundation | IaaS | https://www.openstack.org/ | Plataforma de infraestructura cloud | Gestión de máquinas virtuales |
| AWS Elastic Beanstalk | AWS | PaaS | https://aws.amazon.com/elasticbeanstalk/ | Runtime, escalado y balanceo de carga | Código de la aplicación |
| Google App Engine | Google Cloud | PaaS | https://cloud.google.com/appengine | Infraestructura, runtime y escalado automático | Desarrollo y despliegue del código |
| Heroku | Salesforce | PaaS | https://www.heroku.com/ | Plataforma y despliegue automático | Código y datos de la app |
| Gmail | Google | SaaS | https://workspace.google.com/gmail/ | Aplicación completa y mantenimiento | Uso del correo y gestión de mensajes |
| Salesforce CRM | Salesforce | SaaS | https://www.salesforce.com/ | Software, plataforma e infraestructura | Configuración y uso del CRM |
| Dropbox | Dropbox Inc. | SaaS | https://www.dropbox.com/ | Almacenamiento y aplicación | Subir y organizar archivos |

## 🅱️ Tarea B — Funciones principales de cloud (arquitectura)
Incluye un diagrama (ASCII/Mermaid/imagen) y una explicación breve.

### Diagrama
```text
[ Usuario / Navegador ]
          |
          v
        [ CDN ]
          |
          v
 [ Frontend (Hosting Cloud) ]
          |
          v
   [ API Backend ]
      |        |
      v        v
 [ Base de   [ Storage
   Datos ]     de Archivos ]

