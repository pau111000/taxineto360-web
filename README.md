# TaxiNeto360 · Documentación legal y descripción de la app

**TaxiNeto360** es una aplicación para conductores y empresas de taxi que facilita el registro de jornadas y la liquidación real de cada turno. Permite llevar un control claro de entradas y salidas, horas y minutos trabajados, kilómetros recorridos, número de servicios, licencias asignadas, empresa, fotos de soporte y exportación de datos a CSV.

---

## Enlaces oficiales

- **Política de Privacidad:** https://pau111000.github.io/taxineto360-web/politica-privacidad-taxineto360.html  
- **Términos y Condiciones:** https://pau111000.github.io/taxineto360-web/terminos.html

> Estos documentos están disponibles públicamente en GitHub Pages. La URL de la política es la que se usa también en Google Play.

---

## Qué hace la app

- **Inicio de sesión y registro** con correo y contraseña (Firebase Authentication).
- **Sesión persistente**: el usuario permanece conectado hasta cerrar sesión manualmente.
- **Registro de jornada**: inicio/fin de turno, horas y minutos trabajados, kilómetros, número de servicios, empresa, licencia y conductor.
- **Cálculo de liquidaciones**: totales por jornada, saldo neto del conductor y del jefe/empresa.
- **Historial completo** de jornadas para consulta y auditoría interna.
- **Adjuntos**: posibilidad de subir fotos como evidencia o constancia para el jefe.
- **Exportación**: descarga de reportes en formato **CSV**.

---

## Permisos y datos

**Permisos solicitados:**
- **Cámara** y **galería** para adjuntar fotos.
- **Almacenamiento/descargas** para exportar y guardar archivos CSV.

**Datos que se gestionan:**
- **Cuenta**: correo electrónico y contraseña (gestionado por Firebase Auth).
- **Operativa**: horarios de entrada y salida, horas/minutos trabajados, kilómetros, número de servicios.
- **Identificación laboral**: empresa, conductor, licencia asignada.
- **Económicos**: importes de jornada, totales de liquidación, saldos.
- **Archivos**: fotografías adjuntas y CSV generados.

> El acceso a los datos se restringe por usuario. Cada cuenta solo ve y gestiona su propia información.

---

## Tecnología

- **Firebase Authentication** (cuentas de usuario con email/contraseña).
- **Firebase Firestore** (base de datos de jornadas e historial).
- **Firebase Storage** (almacenamiento de fotos y CSV).
- **Android (Jetpack Compose)** para la interfaz y experiencia móvil.

---

## Soporte

- **Contacto:** taxi360barcelona@gmail.com

---

## Actualizaciones de estos documentos

Para mantener la documentación legal al día, se editan los archivos HTML en este repositorio y se publican automáticamente mediante GitHub Pages. Las URLs anteriores permanecen estables.

---

## Copyright

© TaxiNeto360. Todos los derechos reservados.
