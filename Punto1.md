## Definición de CI (Integración Continua)
La Integración Continua (CI) es una práctica de desarrollo de software en la que los cambios en el código se integran con frecuencia en un repositorio compartido y se prueban automáticamente. Su objetivo principal es detectar errores tempranos, mejorar la calidad del software y reducir el tiempo de entrega.

Ejemplo: Imagina un equipo de desarrollo trabajando en una aplicación. Cada vez que un desarrollador realiza cambios en el código y los envía al repositorio central (push), un sistema de CI ejecuta automáticamente pruebas unitarias para verificar que los nuevos cambios no hayan roto funcionalidades existentes.

## Definición de CD (Entrega/Despliegue Continuo)
El término CD puede referirse a Entrega Continua (Continuous Delivery) o Despliegue Continuo (Continuous Deployment).

Entrega Continua: Automatiza la preparación del código para su lanzamiento, asegurando que siempre esté en un estado listo para producción.

Despliegue Continuo: Va un paso más allá y despliega automáticamente cada cambio aprobado a producción sin intervención manual.

Ejemplo: Una empresa de comercio electrónico utiliza CD para su plataforma. Cada nueva función desarrollada pasa por pruebas automáticas y, una vez validada, se despliega directamente en producción sin intervención manual. Así, los usuarios siempre tienen acceso a la versión más actualizada del software.

## Herramientas de CI/CD
Ahora se describe tres herramientas populares utilizadas en CI/CD:

1. GitHub Actions
GitHub Actions es una plataforma de automatización integrada en GitHub que permite configurar flujos de trabajo de CI/CD mediante archivos YAML.

Ventajas: ✅ Integración nativa con GitHub. ✅ Gran cantidad de acciones predefinidas. ✅ Fácil configuración mediante YAML.

Desventajas: ❌ Puede ser costoso para proyectos grandes. ❌ Dependencia de GitHub. ❌ Tiempo de ejecución limitado en planes gratuitos.

2. GitLab CI/CD
GitLab CI/CD es una solución de CI/CD integrada en GitLab que permite definir pipelines en archivos .gitlab-ci.yml.

Ventajas: ✅ Integración completa con GitLab. ✅ Compatibilidad con múltiples entornos. ✅ Potente gestión de permisos y seguridad.

Desventajas: ❌ Configuración inicial compleja. ❌ Puede consumir muchos recursos en servidores propios. ❌ Algunas funciones avanzadas requieren versiones pagas.

3. Jenkins
Jenkins es una herramienta de automatización de código abierto que permite construir, probar y desplegar software de manera continua.

Ventajas: ✅ Extremadamente flexible con plugins. ✅ Código abierto y gratuito. ✅ Compatible con diversos lenguajes y entornos.

Desventajas: ❌ Configuración inicial más difícil que otras herramientas. ❌ Requiere mantenimiento frecuente. ❌ Interfaz de usuario menos intuitiva.