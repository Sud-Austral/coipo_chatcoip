# coipo_chatcoip

Repositorio **sin código de aplicación** a la fecha (2026-10-24). VERIFICADO con `git ls-files` sobre `origin/main`: solo contiene
`.gitattributes`, `.gitignore`, `.github/workflows/readme.yml`, este README y la carpeta `insumos/`. No hay manifiestos de
dependencias, entrypoints, pruebas, Docker ni variables de entorno.

El nombre sugiere un chat para COIPO, pero eso no está respaldado por ningún archivo: qué es, para quién y con qué
stack se construirá queda **pendiente de confirmar por el equipo**.

## Qué hay

| Ruta | Contenido |
|---|---|
| `.github/workflows/readme.yml` | Llama al generador de README/insumos `Sud-Austral/coipo_aireadme` (versión `v1`) en cada push a `main` y a demanda |
| `insumos/` | `00-PROBLEMA.md`, `01-SOLUCION.md` y `MANIFIESTO.yaml`: casi todo marcado `[PENDIENTE]` por falta de evidencia |
| `CLAUDE.md` | Guía para agentes |

## Cómo ejecutarlo, configuración, pruebas y despliegue

No aplica: no hay nada que ejecutar. Cuando se agregue código, actualizar este README con comandos, variables (solo
nombres) y despliegue reales.

## Documentos

[`CLAUDE.md`](CLAUDE.md) · [`insumos/00-PROBLEMA.md`](insumos/00-PROBLEMA.md) · [`insumos/01-SOLUCION.md`](insumos/01-SOLUCION.md)
