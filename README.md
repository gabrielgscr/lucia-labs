# lucia-labs

Repository of labs and examples for the **Lucia** programming language.

Language: [English](#what-is-lucia) | [Espanol](#espanol)

## What is Lucia?

Lucia is an experimental programming language with an education-first focus, designed to help people learn with strong foundations and evolve toward professional-level development. This repository contains practical examples to explore Lucia syntax and capabilities.

## Examples

In [compiler-examples/](compiler-examples/), you will find the basic language examples.

## Running Examples

You need Lucia installed. Then you can run any example with:

```bash
lucia run compiler-examples/HelloWorld.lucia
```

## Lucia CLI Basics

Main commands:

```bash
lucia run compiler-examples/HelloWorld.lucia
lucia compile compiler-examples/00_features.lucia
```

Save generated output:

```bash
lucia compile compiler-examples/00_features.lucia --save
```

Choose output target (for example, JavaScript):

```bash
lucia run compiler-examples/HelloWorld.lucia --target js
```

Useful CLI options:

- `--save`: saves generated output files.
- `--out <path>`: sets a custom output path (requires `--save`).
- `--target <python|javascript|js>`: selects the target language.
- `--show-python`: prints generated code to the console.
- `--debug`: prints full traceback details on errors.

## Resources

- Official downloads (Lucia and Lucia Editor): [www.lucia-lang.com/download](https://www.lucia-lang.com/download)
- Direct Windows download (Lucia + Editor suite): [www.lucia-lang.com/download/file?file=windows-main](https://www.lucia-lang.com/download/file?file=windows-main)
- Direct macOS download (PKG installer): [www.lucia-lang.com/download/file?file=mac-suite-pkg](https://www.lucia-lang.com/download/file?file=mac-suite-pkg)
- Direct macOS download (Lucia Editor): [www.lucia-lang.com/download/file?file=mac-editor-app](https://www.lucia-lang.com/download/file?file=mac-editor-app)
- Direct Linux download (Lucia Community): [www.lucia-lang.com/download/file?file=linux-main](https://www.lucia-lang.com/download/file?file=linux-main)
- Official documentation: [www.lucia-lang.com/docs](https://www.lucia-lang.com/docs)
- Official roadmap: [www.lucia-lang.com/roadmap](https://www.lucia-lang.com/roadmap)
- Community forum: [www.lucia-lang.com/forum](https://www.lucia-lang.com/forum)

## Espanol

### Que es Lucia?

Lucia es un lenguaje de programacion experimental con enfoque educativo, disenado para ayudar a aprender con bases solidas y evolucionar hacia un nivel profesional. Este repositorio contiene ejemplos practicos para explorar la sintaxis y capacidades de Lucia.

### Ejemplos

En [compiler-examples/](compiler-examples/) encontraras los ejemplos basicos del lenguaje.

### Ejecutar ejemplos

Necesitas tener Lucia instalado. Luego puedes ejecutar cualquier ejemplo con:

```bash
lucia run compiler-examples/HelloWorld.lucia
```

### CLI de Lucia: uso basico

Comandos principales:

```bash
lucia run compiler-examples/HelloWorld.lucia
lucia compile compiler-examples/00_features.lucia
```

Guardar salida generada:

```bash
lucia compile compiler-examples/00_features.lucia --save
```

Elegir target de salida (por ejemplo, JavaScript):

```bash
lucia run compiler-examples/HelloWorld.lucia --target js
```

Opciones utiles del CLI:

- `--save`: guarda los archivos de salida generados.
- `--out <ruta>`: define una ruta de salida personalizada (requiere `--save`).
- `--target <python|javascript|js>`: selecciona el lenguaje objetivo.
- `--show-python`: imprime el codigo generado en consola.
- `--debug`: muestra detalles completos del traceback cuando hay errores.

### Recursos

- Descargas oficiales (Lucia y Lucia Editor): [www.lucia-lang.com/download](https://www.lucia-lang.com/download)
- Descarga directa para Windows (suite Lucia + Editor): [www.lucia-lang.com/download/file?file=windows-main](https://www.lucia-lang.com/download/file?file=windows-main)
- Descarga directa para macOS (instalador PKG): [www.lucia-lang.com/download/file?file=mac-suite-pkg](https://www.lucia-lang.com/download/file?file=mac-suite-pkg)
- Descarga directa para macOS (Lucia Editor): [www.lucia-lang.com/download/file?file=mac-editor-app](https://www.lucia-lang.com/download/file?file=mac-editor-app)
- Descarga directa para Linux (Lucia Community): [www.lucia-lang.com/download/file?file=linux-main](https://www.lucia-lang.com/download/file?file=linux-main)
- Documentacion oficial: [www.lucia-lang.com/docs](https://www.lucia-lang.com/docs)
- Roadmap oficial: [www.lucia-lang.com/roadmap](https://www.lucia-lang.com/roadmap)
- Foro de comunidad: [www.lucia-lang.com/forum](https://www.lucia-lang.com/forum)
