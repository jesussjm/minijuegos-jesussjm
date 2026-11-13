# Mapa de navegación

```
index.html (bienvenida)
   └─ "Entrar con Google" → apodo.html
          └─ "Continuar" → lobby.html

Desde lobby, tienda, personaje y configuración se puede ir
a cualquiera de las otras tres con el menú.

configuracion.html
   ├─ "Cerrar sesión" → index.html
   └─ "Borrar cuenta" → index.html
```

¿Qué ha sido más rápido?
Maquetar con Tailwind CSS ha sido más rápido porque no requiere crear clases personalizadas ni cambiar constantemente entre el archivo HTML y la hoja de estilos externa para aplicar márgenes, colores o distribuciones básicas.

¿Qué HTML se lee mejor?
El HTML con clases propias (BEM) se lee mucho más limpio y estructurado. En Tailwind, las etiquetas acumulan cadenas muy largas de clases de utilidad (bg-slate-800 text-yellow-500 p-4 ...), lo que dificulta distinguir el propósito semántico del código a simple vista.

¿Qué haríais si hubiera que cambiar el color principal en todas las pantallas?
Con CSS tradicional o Sass bastaría con modificar una sola variable en :root (por ejemplo, --color-principal). En Tailwind, al estar hardcodeado mediante clases de utilidad en cada elemento de los archivos HTML, habría que buscar y reemplazar manualmente la clase de color en todas las vistas o configurar un archivo de tema personalizado.