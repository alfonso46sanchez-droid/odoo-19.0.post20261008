# Proyecto de prácticas de Odoo 19

Este proyecto reúne mis módulos de prácticas.

## Requisitos

| Elemento | Versión utilizada o procedencia |
| --- | --- |
| Odoo | 19.0, paquete 19.0.post20261008 |
| Python | 3.14.4 |
| PostgreSQL | 18.6 |
| Sistema | Ubuntu 26.04.1 LTS en WSL |

### Entorno de Python

Se usa Python 3.14.4 dentro del entorno virtual `.venv/`.

## Estructura

La carpeta **custom_addons** contiene nuestros módulos.

Este paso es *opcional* si ya existe el entorno.

Abre `GUIA_PROYECTO.md` y ejecuta `git status`.

## Material del proyecto

- Módulos propios en `custom_addons/`.
- Guía del entorno en `GUIA_PROYECTO.md`.
  - Versión de Odoo.
  - Comando de arranque.

## Comprobación de una mejora

1. Guarda los archivos.
2. Revisa las diferencias.
3. Prueba el comportamiento.
4. Prepara y confirma los cambios.

## Verificaciones

- [x] Comprobar la rama activa.
- [ ] Revisar el contenido preparado.
- [ ] Crear el commit de documentación.

> Nota: la base de datos se respalda por separado.

Texto del apartado anterior.

---

Texto de un bloque distinto.

```bash
git status
git diff --staged
```

```python
nombre_modulo = "mi_modulo"
print(nombre_modulo)
```

| Archivo | Función | Se versiona |
| --- | --- | :---: |
| `GUIA_PROYECTO.md` | Instrucciones propias | Sí |
| `.venv/` | Entorno local | No |
| `*.local.conf` | Configuración privada | No |


Escribe \*texto\* para mostrar los asteriscos.

| Expresión | Significado |
| --- | --- |
| `a \| b` | Una barra vertical dentro de la celda |

```text
On branch main
nothing to commit, working tree clean
```