DETECTIVES DEL DINERO — versión con inicio de sesión Google

1. Publica este index.html en GitHub Pages (o en otro servidor HTTPS).
2. En Firebase Console > Authentication > Settings > Authorized domains,
   agrega el dominio de tu página publicada, por ejemplo:
   TUUSUARIO.github.io
3. Abre la página publicada y pulsa "Entrar con Google".
4. La versión actual identifica al participante y protege el inicio de la misión.
5. El siguiente paso será conectar Cloud Firestore para guardar puntuaciones,
   respuestas, reflexiones y equipos.

IMPORTANTE:
- No compartas contraseñas, claves privadas ni archivos de cuenta de servicio.
- La configuración web de Firebase incluida en este archivo es la configuración
  de la aplicación cliente. La protección de los datos se hará mediante las
  reglas de seguridad de Firebase cuando conectemos Firestore.
