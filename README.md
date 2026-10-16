# PAD San Cristóbal–Mahr Túnel — Control de subsanación

Aplicación web independiente en HTML/CSS/JavaScript, lista para publicar como sitio estático en Vercel.

## Funciones incluidas
- Dashboard con KPIs, distribución por autoridad, estados y prioridades.
- Matriz de observaciones con búsqueda y filtros.
- Edición de estado, prioridad, responsable, fecha, avance, entregables y notas.
- Alta de observaciones nuevas.
- Importación de matriz en JSON/CSV y exportación a CSV.
- Persistencia local mediante `localStorage` para modo demostración.

## Importante antes del uso real
Los cambios se guardan únicamente en el navegador actual. Esta versión NO tiene autenticación ni base de datos compartida. Para trabajo multiusuario, integrar Supabase (Auth, tablas y políticas RLS) y migrar el almacenamiento local a la base de datos.

Los registros iniciales proceden de `Matriz_Maestra_PAD_San_Cristobal_Mahr_Tunel.xlsx`. Las filas ANA marcadas como pendientes de extracción son marcadores de trabajo, no textos oficiales; validar contra el documento fuente y reemplazarlas antes de usar el sistema como matriz oficial.

## Publicación en Vercel
1. Subir el contenido de esta carpeta a un repositorio GitHub NUEVO.
2. En Vercel, elegir Add New → Project e importar ese repositorio.
3. No requiere variables de entorno en esta versión estática.
4. Desplegar. El nombre de dominio estará sujeto a disponibilidad.
