# lucia-labs

Repositorio de laboratorios y ejemplos del lenguaje de programación **Lucia**.

## ¿Qué es Lucia?

Lucia es un lenguaje experimental con enfoque educativo, pensado para aprender con bases sólidas y evolucionar hacia un nivel profesional. Este repositorio reúne ejemplos prácticos para explorar su sintaxis y capacidades.

## Ejemplos

En la carpeta [`compiler-examples/`](compiler-examples/) encontrarás los ejemplos básicos del lenguaje, organizados por tema y nivel de complejidad.

## Cómo ejecutar los ejemplos

Necesitas tener instalado el compilador de Lucia. Luego puedes ejecutar cualquier ejemplo con:

```bash
lucia run compiler-examples/HelloWorld.lucia
```

## Uso básico del CLI de Lucia

Comandos principales:

```bash
lucia run compiler-examples/HelloWorld.lucia
lucia compile compiler-examples/00_features.lucia
```

Guardar el archivo generado:

```bash
lucia compile compiler-examples/00_features.lucia --save
```

Elegir el target de salida (por ejemplo, JavaScript):

```bash
lucia run compiler-examples/HelloWorld.lucia --target js
```

Opciones útiles del CLI:

- `--save`: guarda el archivo generado.
- `--out <ruta>`: define una ruta de salida personalizada (requiere `--save`).
- `--target <python|javascript|js>`: selecciona el lenguaje objetivo.
- `--show-python`: muestra el código generado en consola.
- `--debug`: muestra más detalle de errores (traceback completo).

## Recursos

- Descargas oficiales (Lucia y Lucia Editor): [www.lucia-lang.com/download](https://www.lucia-lang.com/download)
- Descarga directa en Windows (suite Lucia + Editor): [www.lucia-lang.com/download/file?file=windows-main](https://www.lucia-lang.com/download/file?file=windows-main)
- Descarga directa en macOS (instalador PKG): [www.lucia-lang.com/download/file?file=mac-suite-pkg](https://www.lucia-lang.com/download/file?file=mac-suite-pkg)
- Descarga directa en macOS (Lucia Editor): [www.lucia-lang.com/download/file?file=mac-editor-app](https://www.lucia-lang.com/download/file?file=mac-editor-app)
- Descarga directa en Linux (Lucia Community): [www.lucia-lang.com/download/file?file=linux-main](https://www.lucia-lang.com/download/file?file=linux-main)
- Documentación oficial: [www.lucia-lang.com/docs](https://www.lucia-lang.com/docs)
- Roadmap oficial: [www.lucia-lang.com/roadmap](https://www.lucia-lang.com/roadmap)
- Comunidad (foro): [www.lucia-lang.com/forum](https://www.lucia-lang.com/forum)
