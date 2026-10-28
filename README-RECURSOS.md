# Kits de edicion y produccion cinematografica

Recursos adicionales a la biblioteca de efectos sonoros de este repositorio.

## 1. Cinema Director Edition

- Archivo: [skills/video-saas-premium-cinema.zip](skills/video-saas-premium-cinema.zip)
- Contiene la skill `video-saas-premium`, sus scripts, recursos de referencia, ejemplos y el respaldo del paquete original.
- Incluye el instalador `video-saas-premium/scripts/install_official_hyperframes.py`: las skills oficiales de HyperFrames se obtienen de su repositorio original durante la instalacion y no estan integradas en este ZIP.

## 2. Kit Editor del Club

- Archivo: [kits/kit-editor-club-no-fonts.zip](kits/kit-editor-club-no-fonts.zip)
- Incluye los scripts de montaje, motion graphics, tipografia, audio y masterizacion, ademas de ejemplos, documentacion y referencias visuales.
- Se omitieron unicamente los cuatro archivos binarios de tipografias `.ttf`. Los avisos de licencia y las indicaciones de instalacion permanecen en el kit. Para usar las tipografias originales, instalarlas por separado desde sus proveedores oficiales.

## Uso

1. Descargar los ZIP desde este repositorio y extraerlos.
2. Colocar `video-saas-premium` como skill en el entorno del agente compatible (Claude Code o Codex).
3. Seguir `video-saas-premium/README.md` y `video-saas-premium/README-CINEMA.md`.
4. Instalar las skills oficiales de HyperFrames siguiendo las instrucciones de la skill.
5. Tener disponibles las dependencias necesarias de Python, Node, FFmpeg, Blender, etc., segun las escenas y herramientas utilizadas.
6. Utilizar el Kit Editor como biblioteca complementaria. No sustituye las instrucciones cinematograficas de la skill principal.

La carpeta existente `new sfx/` permanece intacta.
