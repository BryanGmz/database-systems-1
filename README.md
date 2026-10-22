# Sistemas de Bases de Datos 1 · Herramientas de práctica

Material interactivo del curso **2817 – Sistemas de Bases de Datos 1** (CUNOC – USAC).

Sitio publicado: https://bryangmz.github.io/database-systems-1/

## Herramientas

| Herramienta                     | Tema                          | Carpeta          | Enlace                                                     |
| ------------------------------- | ----------------------------- | ---------------- | ---------------------------------------------------------- |
| Álgebra relacional, paso a paso | Unidad 8                      | `algebra/`       | https://bryangmz.github.io/bases-de-datos-1/algebra/       |
| Normalización, paso a paso      | Unidad 9                      | `normalization/` | https://bryangmz.github.io/bases-de-datos-1/normalization/ |
| Inyección SQL, paso a paso      | Material de apoyo · security | `security/`     | https://bryangmz.github.io/bases-de-datos-1/security/     |

Cada herramienta tiene pestañas con su propio enlace, por ejemplo `algebra/#division`, `normalization/#pedido` o `security/#simulador`.

## Estructura

```
index.html                 portada con las tarjetas de cada herramienta
assets/css/curso.css       estilos compartidos (colores, tipografía, tablas)
algebra/index.html         Álgebra relacional paso a paso
normalization/index.html   Normalización paso a paso
security/
  index.html               Inyección SQL paso a paso
  sqli_data.js             contenido del recorrido y el glosario
.nojekyll                  indica a GitHub Pages que publique los archivos tal cual
```

## Cómo agregar una herramienta nueva

1. Crea una carpeta nueva, por ejemplo `sql/`, con su propio `index.html`.
2. En ese `index.html`, enlaza los estilos compartidos con `<link rel="stylesheet" href="../assets/css/curso.css">`.
3. En `index.html` de la raíz, copia un bloque `<a class="tool">` y cambia la carpeta y el texto.
4. Sube los cambios. GitHub Pages los publica en unos minutos.

## Nota sobre la herramienta de security

La página de inyección SQL es material educativo: todos los ejemplos corren sobre una base de datos simulada dentro del navegador. No se conecta a ninguna base real.
