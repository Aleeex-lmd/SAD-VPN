# Configuración de openVPN de acceso remoto con clave estática compartida

Realiza este ejercicio con un compañero, de manera que en un equipo instaláis el servidor openVPN y en otro el cliente. El montaje debe tener las siguientes características:

- La autenticación entre cliente y servidor se realiza mediante el método básico de clave estática compartida
- El cliente debe tener acceso a la red virtual del servidor
- Realiza el montaje tanto en modo router (dispositivo tun) como en modo bridge (dispositivo tap)
- Comenta en clase los parámetros que pueden mejorar la conexión (compresión, recuperación de la conexión, ...)
- Para el servicio openVPN en el equipo cliente, instala el complemento para openVPN de Network-Manager y repite la configuración del cliente con Network-Manager.
- Repite la configuración con el cliente Windows de openVPN

**Nota:** Ten en cuenta que KVM pone reglas de iptables bastante restrictivas hacia la red local, por lo que inicialmente no es posible conectase desde fuera.