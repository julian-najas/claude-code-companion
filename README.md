# Claude Code · índice por síntoma

**Este repositorio es una salida generada. No lo edites a mano.**

155 páginas, una por síntoma real de Claude Code, con su causa y el módulo
que lo explica. Se generan desde los 21 módulos canónicos de la guía
[Claude Code en producción](https://github.com/julian-najas/manual-claude-code).

**Sitio:** https://julian-najas.github.io/claude-code-companion/

## Cómo se genera

```bash
# en el repositorio de la fábrica, no en este
python3 fabrica/generar-companion.py
./fabrica/publicar-companion.sh
```

Si encuentras un error en una página, **el arreglo va en el módulo de origen**,
no aquí: cualquier cambio hecho en este repositorio se pierde en la siguiente
publicación.

## Qué lo hace distinto

Las afirmaciones de la guía de la que sale este índice **se ejecutan cada
madrugada contra el binario de Claude Code instalado**, y el resultado se publica
se vea bien o se vea mal:
[estado de verificación](https://github.com/julian-najas/manual-claude-code/blob/main/D2-verificador/ESTADO.md).

- **Edición redactada contra:** Claude Code 2.1.228
- **Compatibilidad comprobada contra:** 2.1.232 (Claude Code)
- **Generado desde el commit:** [`11d4ab2`](https://github.com/julian-najas/manual-claude-code/commit/11d4ab227b27f4235ca66648e0bbd6ee4bc06906)
- **Generado el:** 2026-08-14T08:15:14Z

La procedencia completa, legible por máquina, está en
[`procedencia.json`](/claude-code-companion/procedencia.json): con ella cualquiera puede clonar la
fábrica en ese commit exacto y **regenerar byte a byte** lo que está leyendo.

## Licencia

El **generador y la fábrica** que producen este sitio son MIT: están en el
[repositorio de origen](https://github.com/julian-najas/manual-claude-code/blob/main/LICENSE).

El **texto de estas páginas** es © 2026 Cosas Agénticas, todos los derechos
reservados. Puedes leerlo, usarlo en tu trabajo y citarlo con enlace. No puedes
republicarlo ni traducirlo.

## Aviso

Sin afiliación, patrocinio ni respaldo de Anthropic. Claude y Claude Code son
marcas de Anthropic PBC.
