# Sistemas de Bases de Datos 1 · Herramientas de práctica

Material interactivo del curso **2817 – Sistemas de Bases de Datos 1** (CUNOC – USAC).

Sitio publicado: https://bryangmz.github.io/database-systems-1/

## Herramientas

| Herramienta                     | Unidad | Carpeta          | Enlace                                                     |
| ------------------------------- | ------ | ---------------- | ---------------------------------------------------------- |
| Álgebra relacional, paso a paso | 8      | `algebra/`       | https://bryangmz.github.io/database-systems-1/algebra/       |
| Normalización, paso a paso      | 9      | `normalizacion/` | https://bryangmz.github.io/database-systems-1/normalizacion/ |

Cada herramienta tiene pestañas con su propio enlace, por ejemplo `algebra/#division` o `normalizacion/#pedido`.

## Estructura

```
index.html              portada con las tarjetas de cada herramienta
assets/css/curso.css    estilos compartidos (colores, tipografía, tablas)
algebra/index.html      Álgebra relacional paso a paso
normalization/index.html Normalización paso a paso
.nojekyll               indica a GitHub Pages que publique los archivos tal cual
```

## Cómo agregar una herramienta nueva

1. Crea una carpeta nueva, por ejemplo `sql/`, con su propio `index.html`.
2. En ese `index.html`, enlaza los estilos compartidos con `<link rel="stylesheet" href="../assets/css/curso.css">`.
3. En `index.html` de la raíz, copia un bloque `<a class="tool">` y cambia la carpeta y el texto.
4. Sube los cambios. GitHub Pages los publica en unos minutos.
