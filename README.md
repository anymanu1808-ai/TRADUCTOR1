# Traductor

Traductor web de una sola página. Sin dependencias ni instalación: solo HTML, CSS y JavaScript.

## Características

- Detección automática del idioma de origen
- 13 idiomas, intercambio rápido de origen y destino
- Copiar y escuchar la traducción
- Tema claro y oscuro según el sistema
- Atajo: Ctrl + Enter para traducir

## Uso local

Abre `index.html` en tu navegador.

## Publicar en GitHub Pages

1. Crea un repositorio y sube estos archivos (`index.html` y `README.md`).
2. Ve a **Settings → Pages**.
3. En **Branch**, elige `main` y la carpeta `/ (root)`, y pulsa **Save**.
4. Tu traductor estará en `https://TU-USUARIO.github.io/NOMBRE-DEL-REPO/`.

## Notas

Usa la API pública de [MyMemory](https://mymemory.translated.net/doc/spec.php), que no requiere clave pero limita cada petición a 500 caracteres y el uso diario por IP.

## Licencia

MIT
