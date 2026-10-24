# coipo_chatcoip — guía para agentes

## Resumen
Repositorio vacío de código (VERIFICADO con `git ls-files`: solo workflow de README, `.gitattributes`, `.gitignore`, README e
`insumos/`). No inventes qué hace ni qué stack usa: el nombre no es evidencia. Propósito, usuarios y stack: pendiente de
confirmar por el equipo.

## Estructura
`.github/workflows/readme.yml` (generador externo `Sud-Austral/coipo_aireadme@v1`), `insumos/` (problema, solución, manifiesto), `README.md`.

## Comandos de build/test/lint
No existen. No ejecutes instalaciones ni despliegues pensando que hay algo que construir.

## Convenciones
- Documentación en español; marcar lo no comprobado como INFERIDO o «no lo comprobé».
- Las marcas `[PENDIENTE]` de `insumos/` las cierra el equipo, no un asistente.

## Qué no tocar
- `.github/workflows/readme.yml`: referencia fijada a `v1` (el `uses:` y `engine_ref` deben coincidir).
- Si se agrega código, actualizar README, CLAUDE.md e `insumos/` en el mismo cambio.
