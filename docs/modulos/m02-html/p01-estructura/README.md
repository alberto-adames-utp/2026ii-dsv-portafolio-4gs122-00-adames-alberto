# Práctica 1 — Estructura básica

**Sitio de la Clínica Veterinaria ConSentidos**
Desarrollo de Software V · Módulo II: Páginas web y HTML
Prof. José Peralta B. · Universidad Tecnológica de Panamá, Centro Regional de Veraguas

---

## Qué contiene este paquete

| Archivo | Qué es |
| --- | --- |
| `assets/css/consentidos.css` | Hoja de estilos del sitio. **No la modifiques:** se estudia y se cambia en el Módulo III. |
| `assets/img/logo-consentidos.svg` | Logotipo de la clínica, en formato vectorial. |
| `assets/img/luna.svg` | Ilustración de Luna; la usarás en la Práctica 2. |

## Dónde va

Dentro de tu repositorio de portafolio, en la carpeta de esta práctica:

```
docs/modulos/m02-html/p01-estructura/
```

Cuando termines, la carpeta debe verse así:

```
p01-estructura/
├── README.md              ← este archivo
├── index.html             ← lo escribes tú, siguiendo la guía
└── assets/
    ├── css/
    │   └── consentidos.css
    └── img/
        ├── logo-consentidos.svg
        └── luna.svg
```

> Cada práctica lleva su propia copia de `assets/`. Así cada carpeta se abre y se
> publica por separado, y si rompes algo en una, las demás siguen funcionando.

## Cómo abrir la página

Con la extensión **Live Server** de Visual Studio Code: botón **Go Live** en la
barra inferior. La dirección empezará por `http://127.0.0.1:5500`.

No la abras con doble clic. Eso la carga con el protocolo `file://` y más
adelante te bloqueará recursos como los subtítulos de video.

## Antes de entregar

1. Valida el documento en <https://validator.w3.org>, pestaña **Validate by
   Direct Input**, y corrige todos los errores.
2. Comprueba la lista de verificación de la guía.
3. Confirma y sube los cambios:

   ```bash
   git add docs/modulos/m02-html/p01-estructura
   git commit -m "Práctica 1: estructura básica de index.html"
   git push
   ```

4. Abre la URL de GitHub Pages y comprueba que la página se ve con estilos.

## Recuerda

- Nombres de archivos y carpetas en **minúsculas**, sin espacios, sin tildes ni
  eñes, separando palabras con guiones.
- Tu identificación va **en la cabecera** de la página: nombre completo y código
  de grupo con tu número de lista, por ejemplo `4GS122-07`. Nunca la cédula: el
  repositorio es público.
