# Api - Hotel

## Destacados

1. *Conectividad a la Base de Datos:*
   - Conexión mediante Entity Framework.

2. *Refactorización del Código:*
   - Introducción una capa de abstracción para evitar el acceso directo al contexto de la base de datos desde el controlador.
   - Utilización Objetos de Transferencia de Datos (DTOs) para manejar la sobrepublicación de datos y mejorar la seguridad.
   - Refactorización del controlador para reducir la complejidad y lógica innecesaria.

3. *Seguridad de la API:*
   - Implementación de JSON Web Tokens (JWT) como estándar de la industria para la seguridad de nuestra API.

4. *Registro y Manejo de Errores:*
   - Introduccion del registro de eventos utilizando la biblioteca de log Serial Log.
   - Configuramos la biblioteca para registrar información, advertencias y errores.
   - Implementamos registros informativos y de advertencia en diversas partes de la aplicación.
