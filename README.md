# Asignación de tareas — Salón del Reino (GitHub Pages)

Webapp **totalmente estática**, sin servidor, sin base de datos y sin dependencias. Todo está en **index.html**.

## Cómo publicarla en GitHub Pages

1. En GitHub crea un repositorio nuevo, por ejemplo `limpieza-salon-reino` (público si quieres usar la ruta gratuita habitual).
2. Sube el archivo **index.html** a la raíz del repositorio (Add file > Upload files > Commit changes).
3. Abre **Settings > Pages**.
4. En **Build and deployment**, selecciona **Deploy from a branch** y después **main / (root)**. Pulsa **Save**.
5. En Pages aparecerá la dirección pública, del tipo `https://TU_USUARIO.github.io/limpieza-salon-reino/`.

## Cómo funciona

- Pulsa el botón grande «¡Descubre tu tarea!»; no hace falta escribir ningún nombre.
- Aparece una ilustración estilizada del trabajo, con la descripción en español.
- Pulsa «Siguiente persona» para pasar el teléfono a la siguiente persona.
- Cuando las 8 tareas estén asignadas, el botón queda desactivado.
- «Gestión» permite ver las asignaciones, modificar las tareas y pulsar «Reset».
- No se registran nombres: cada persona debe pulsar el botón una sola vez y pasar el teléfono al siguiente participante.

## Las 8 tareas iniciales

1. Aspirar el podio
2. Escoba atrapapolvo · 1
3. Escoba atrapapolvo · 2
4. Baño de hombres
5. Baño de mujeres
6. Cubo de agua y fregona para la sala (solo manchas)
7. Cubo y fregona para los baños
8. Cambio de bolsas de basura

## Importante sobre el almacenamiento

**Los datos se guardan en localStorage del navegador, no en GitHub.** La asignación se conserva cuando se cierra y se vuelve a abrir la página en el mismo navegador, siempre que no se borren los datos del sitio. No uses navegación privada.

**No hay sincronización entre teléfonos** ni entre navegadores: utiliza siempre el mismo teléfono y el mismo navegador para todas las asignaciones de la ronda. Si abres el sitio en otro móvil, comenzará con los ocho trabajos disponibles en ese móvil.

**No hay contraseña para «Gestión»**. Todos los usuarios que tengan acceso al teléfono podrán pulsar «Reset». Si necesitas protección real o sincronización entre teléfonos, haría falta otra arquitectura.

## Uso sin nombres

La aplicación ya no pide nombres. Cada pulsación asigna una tarea distinta y la guarda en el navegador. Después pulsa «Siguiente persona». La lista visible en «Gestión» solo indica el número de extracción y su tarea.
