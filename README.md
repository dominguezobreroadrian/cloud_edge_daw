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
```

### Explicación (8–12 líneas) (Describe el flujo front → API → BBDD/storage y dónde entra la cloud) 

El usuario accede a la aplicación web desde su navegador utilizando Internet.  
El frontend de la aplicación está alojado en un servicio cloud y se entrega al usuario a través de un CDN, lo que mejora la velocidad de carga.  
Cuando el usuario interactúa con la interfaz, el frontend envía peticiones HTTP a la API backend.  
La API backend se ejecuta en la cloud y es la encargada de procesar la lógica de negocio.  
Para guardar información estructurada, la API se conecta a una base de datos cloud.  
Los archivos como imágenes, vídeos o documentos se almacenan en un servicio de almacenamiento cloud.  
La cloud permite que la aplicación escale automáticamente según la demanda.  
Además, ofrece alta disponibilidad y acceso seguro a todos los componentes.

### Mapeo de funciones cloud a componentes (mínimo 3) 

- Procesamiento → API backend en la cloud  
- Ejecución → Hosting cloud del frontend y del backend  
- Almacenamiento → Base de datos cloud y almacenamiento de archivos  
- Intercambio → API REST y CDN para comunicación de datos

## 📚 Fuentes (enlaces oficiales) (Enlaces oficiales usados en la tabla A y en la B))

- https://aws.amazon.com/ec2/
- https://cloud.google.com/compute
- https://azure.microsoft.com/services/virtual-machines/
- https://www.openstack.org/
- https://aws.amazon.com/elasticbeanstalk/
- https://cloud.google.com/appengine
- https://www.heroku.com/
- https://workspace.google.com/gmail/
- https://www.salesforce.com/
- https://www.dropbox.com/
