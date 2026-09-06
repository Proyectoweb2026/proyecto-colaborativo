# Registro y Gestión de Aplicaciones

## Descripción
Módulo de AppConnect para registrar, editar y administrar aplicaciones asociadas a la plataforma de forma rápida y segura.

## Campos Registrados y Editables
* **Nombre de la aplicación** (Único y obligatorio)
* **Categoría / Tipo** (Obligatorio)
* **Descripción breve**
* **Versión** (Ej. v1.0.0 - Obligatorio)
* **Fecha de integración / Edición**
* **Estado** (Activo / Inactivo)

## Validaciones para Asegurar Validez
* **Campos requeridos:** Ningún campo obligatorio puede quedar vacío.
* **Unicidad:** No se permiten nombres de aplicaciones duplicados.
* **Formato de versión:** Debe seguir la nomenclatura `X.Y.Z`.
* **Verificación de cambios:** Toda modificación actualiza automáticamente la fecha de última edición y valida la consistencia de los datos.

## Funcionamiento y Objetivo
Permite crear nuevos registros y modificar los existentes garantizando que la información del catálogo de AppConnect sea válida, precisa y esté siempre actualizada.
