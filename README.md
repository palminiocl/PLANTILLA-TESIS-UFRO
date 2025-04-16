# Plantilla de Tesis UFRO

Este repositorio contiene una plantilla en LaTeX adaptada para la elaboración de tesis de pregrado o postgrado en la **Universidad de La Frontera (UFRO)**. Se estructura de acuerdo con los lineamientos generales de formato institucional y está pensada para facilitar la escritura modular, clara y reproducible de un documento académico.

## ☁️ Ideal para usar en Overleaf

Esta plantilla está diseñada para ser fácilmente compatible con [Overleaf](https://www.overleaf.com), una plataforma online para escribir documentos en LaTeX sin necesidad de instalar software adicional. Solo debes subir todos los archivos contenidos en este repositorio a un nuevo proyecto en Overleaf, y compilar con **PDFLaTeX** o **XeLaTeX**.

## 📁 Estructura del proyecto

```
PLANTILLA_TESIS_UFRO/
│
├── Plantilla_Tesis_Ufro.tex         # Archivo principal del documento
├── UFRO_Tesis.sty                   # Paquete de estilo específico para la UFRO
├── UFRO_Style.sty                   # Estilo general del documento
├── bibliografia/                    # Archivos .bib para referencias
├── capitulo_0/                      # Resumen, agradecimientos, abreviaciones, etc.
├── capitulo_1/... capitulo_6/      # Capítulos individuales del cuerpo del documento
├── anexo/                           # Anexos adicionales
├── img/                             # Imágenes institucionales o decorativas
└── Plantilla_Tesis_Ufro.pdf        # Ejemplo compilado (puede omitirse en público)
```

## ⚙️ Requisitos

- [LaTeX](https://www.latex-project.org/get/) local (TeX Live o MiKTeX) o **Overleaf**
- Editor local sugerido: [TeXstudio](https://www.texstudio.org/) o [VSCode + LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop)

## 🚀 Compilación

1. Abre el archivo `Plantilla_Tesis_Ufro.tex` con tu editor LaTeX preferido o súbelo a Overleaf.
2. Compila con **PDFLaTeX** o **XeLaTeX**.
3. Compila varias veces si usas bibliografía o referencias cruzadas.

### Bibliografía

- Edita el archivo `bibliografia/Bibliografia.bib`.
- Usa `\cite{clave}` para citar dentro del texto.
- Compila con `bibtex` o con la herramienta de bibliografía de Overleaf.

## 🛠️ Personalización

- Cambia el contenido de `\author{}`, `\title{}` y `\profguia{}` en el archivo principal.
- Agrega capítulos con `\include{capitulo_X/archivo}`.
- Anexos van en `anexo/`.

## 🔒 Consideraciones de privacidad

Antes de compartir tu tesis en línea:
- Revisa que no hayas dejado información personal como RUT, dirección, correos o nombres completos.
- Anonimiza campos como `\author{}`, `\email{}`, `\profguia{}`, etc.
- Puedes usar scripts para detectar datos sensibles automáticamente.

## 👤 Autor original

Esta plantilla fue desarrollada por **Ramiro Saavedra G.** como base para tesis de la UFRO. Todos los derechos de autor pertenecen a él. Este repositorio la adapta y reorganiza con fines académicos de uso libre.

## 📄 Licencia

Este proyecto está disponible bajo la licencia [MIT](https://opensource.org/licenses/MIT). Puedes usarlo libremente con fines académicos o personales.
