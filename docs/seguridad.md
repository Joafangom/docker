# Seguridad del gestor

| Comprobación | Antes | Después |
|---|---|---|
| Cabecera Server | nginx/1.30.5 | nginx |
| /xmlrpc.php | 405 Method Not Allowed | 403 Forbidden |
| /wp-config.php | 200 OK | 403 Forbidden |
| PHP en uploads | Ejecuta (Devuelve 2) | 403 Forbidden |
| Edición de ficheros desde el panel | Accesible | Desactivado |
| Límite de intentos de login | Sin límite | Bloqueo activo |

## Medidas aplicadas y por qué
(Redacta aquí tus conclusiones sobre por qué se ha aplicado cada regla en nginx y WordPress)
