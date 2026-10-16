# FF OC — Laboratorio STRIDE + DevSecOps (local, gratuito)

Laboratorio local reproducible de Threat Modeling y DevSecOps para demostrar
competencias de seguridad aplicada: modelado de amenazas, análisis estático,
dependencias, imágenes e IaC, pruebas dinámicas, gestión de vulnerabilidades,
remediación y verificación.

Estado actual: bootstrap inicial. El desarrollo se realizará en la rama
`feat/stride-devsecops-lab`.

## Principios

- Sin servicios de pago, tarjeta ni recursos cloud facturables.
- Sin CI/CD automático por defecto.
- Sin alteración de otros proyectos ni servicios compartidos.
- Toda la documentación técnica de usuario está en español.

## Requisitos

- Docker y Docker Compose
- Git y GitHub CLI
- Java 21, Maven (vía imagen Docker) cuando se incorpore la aplicación

## Estructura prevista

```
app/ tests/ scripts/ evidence/ compose.yaml Dockerfile docs/ ...
```

## Licencia

Uso educativo y de portafolio.
