# 🤓 Explicación JS

Ahora la inicialización (init) carga los shows de TVMaze, elige aleatoriamente uno para el hero y renderiza una fila de tendencias; además se conecta el formulario de búsqueda (wireSearch) para limpiar el contenedor de filas y mostrar resultados dinámicos. Se añadieron comprobaciones y valores por defecto para imágenes (placehold.co) y texto, y se usan funciones utilitarias como fetchJSON para manejo consistente de errores, escapeHTML para evitar inyecciones y stripHTML para limpiar resúmenes, lo que mejora la seguridad y la presentación del contenido.

En la capa de UI, renderHero aplica correctamente la imagen de fondo del hero (hero.style.backgroundImage) y ajusta el color del texto, mientras que renderRow y posterCard construyen las tarjetas con scroll horizontal y placeholders cuando falta imagen. Al hacer clic en una tarjeta se abre el modal con openDetail que obtiene la info completa del show y la monta en HTML (géneros como badges, resumen, rating, enlace al sitio), resultando en una interfaz completa y coherente: hero visible, filas con pósters desplazables, búsqueda funcional y modal de detalle operativo.

---

## Navegación
- [Home](README.md)
- [Index](index.html)
- [ExplicacionIndex](exindex.md)
- [CSS](./css/app.css)
- [ExplicacionCSS](excss.md)
- [JS](./js/app.js)
