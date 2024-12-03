# Proyecto ERP Websy

Este repositorio contiene la implementación de un sistema ERP basado en [Odoo](https://www.odoo.com/) para la empresa Websy. El proyecto incluye configuraciones de Docker y scripts para garantizar la seguridad y funcionalidad del sistema.

## Descripción del Proyecto

Websy es una startup tecnológica especializada en consultoría, desarrollo de software a medida y ciberseguridad. Este proyecto busca centralizar y optimizar las operaciones de Websy mediante un ERP, mejorando la eficiencia en áreas clave como:
- Gestión de proyectos
- CRM
- Finanzas
- Recursos humanos
- Automatización de marketing

## Tecnologías Utilizadas

- **ERP**: Odoo
- **Control de versiones**: Git
- **Contenedores**: Docker
- **Lenguajes de programación**: Python, YAML (para configuraciones)

## Estructura del Proyecto

- `docker-compose.yml`: Configuración de Docker para despliegue del ERP.
- `.gitignore`: Exclusión de archivos sensibles y temporales del control de versiones.
- `src/`: Código fuente personalizado del proyecto.
- `config/`: Archivos de configuración, incluyendo seguridad.

## Requisitos Previos

1. **Docker y Docker Compose** instalados.
2. Acceso a las claves de configuración (almacenadas en un archivo `.env` no incluido en este repositorio por seguridad).

## Instalación

1. Clonar este repositorio:
   ```bash
   git clone https://github.com/usuario/repositorio.git
