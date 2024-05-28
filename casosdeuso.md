- **Actores**: Usuario, Administrador.

- **Precondiciones**: El usuario debe estar registrado en el sistema.

- **Flujo principal**:
    1. El usuario inicia sesión en el sistema.
    2. El sistema muestra el dashboard con los datos de monitorización.
    3. El usuario visualiza los datos y realiza acciones.
    4. El usuario cierra sesión.

- **Postcondiciones**: El sistema guarda las acciones del usuario.

# Escenario principal - ingreso al sistema

1. El usuario inicia sesión en el sistema.
2. El sistema muestra el dashboard con los datos de monitorización.
3. El usuario visualiza los datos y realiza acciones.
4. El usuario cierra sesión.
5. El sistema guarda las acciones del usuario.

# Escenario alternativo - error en el ingreso al sistema

1. El usuario inicia sesión en el sistema.
2. El sistema muestra un mensaje de error.
3. El usuario cierra sesión.
4. El sistema guarda las acciones del usuario.
5. El sistema guarda el error.
6. El sistema envía un correo al administrador.

pienso
¿que voy a poder hacer en el sistema de monitorización?

- ver los logs de los servicios que vincule
- ver las metricas (de rendimiento, uso de recursos y de actividad/personalizadas) de los servicios que vincule
- ver los errores de los servicios que vincule
- ver el tiempo de vida de los servicios vinculados

¿que va a poder hacer el administrador?

- lo mismo que el usuario normal
- crear, modificar y eliminar usuarios (tambien congelar/ desanilitar usuarios)
- monitorizar los logs del sistema de monitorización
