# TaxiNeto360 · Documentos legales y descripción de la app

**TaxiNeto360** es una app para conductores y empresas de taxi que facilita el registro de jornadas y la liquidación real de cada turno: entradas/salidas, horas y minutos trabajados, kilómetros recorridos, número de servicios, licencias, empresa, adjuntos (fotos) y exportación a CSV.

---

## 🔗 Enlaces oficiales (GitHub Pages)

- **Sitio (portada):** https://pau111000.github.io/taxineto360-web/
- **Política de Privacidad:** https://pau111000.github.io/taxineto360-web/politica-privacidad-taxineto360.html
- **Términos y Condiciones:** https://pau111000.github.io/taxineto360-web/terminos.html
- **Eliminar cuenta y datos (web):** https://pau111000.github.io/taxineto360-web/eliminar-cuenta.html

> La **URL de Política** se usa en Google Play (App content → Privacy policy).  
> La **URL de Eliminación** se usa en Google Play (Data safety → Data deletion → *Delete account URL*).

---

## Qué hace la app

- **Inicio de sesión y registro** con correo y contraseña (Firebase Authentication).
- **Sesión persistente** hasta cerrar sesión manualmente.
- **Registro de jornada:** inicio/fin de turno, horas/minutos, km, servicios, empresa, licencia, conductor.
- **Cálculo de liquidaciones:** totales por jornada, saldo neto del conductor y del jefe/empresa.
- **Historial completo** de jornadas.
- **Adjuntos:** subir fotos como evidencia/constancia.
- **Exportación:** reportes en **CSV**.

---

## Permisos y datos

**Permisos solicitados:**
- **Cámara/Galería** para adjuntar fotos.
- **Almacenamiento/Descargas** para exportar/guardar CSV.

**Datos gestionados:**
- **Cuenta:** correo + contraseña (Firebase Auth).
- **Operativa:** horarios de entrada/salida, horas/minutos, km, servicios.
- **Identificación laboral:** empresa, conductor, licencia.
- **Económicos:** importes de jornada, liquidaciones y saldos.
- **Archivos:** fotos y CSV generados.

> El acceso a los datos está restringido por usuario (reglas de Firestore/Storage).

---

## Tecnología

- **Firebase Authentication** (cuentas).
- **Firebase Firestore** (jornadas e historial).
- **Firebase Storage** (fotos y CSV).
- **Android · Jetpack Compose** (UI).

---

## 📄 Archivos de este repositorio

- `index.html` — Portada con enlaces a todos los documentos.
- `politica-privacidad-taxineto360.html` — Política de Privacidad pública.
- `terminos.html` — Términos y Condiciones.
- `eliminar-cuenta.html` — Página web para iniciar eliminación de cuenta y datos.
- (Opcional) `README.md` — Este documento.


## Recordatorio para Google Play

- **Privacy policy URL:** `https://pau111000.github.io/taxineto360-web/politica-privacidad-taxineto360.html`  
- **Delete account URL:** `https://pau111000.github.io/taxineto360-web/eliminar-cuenta.html`

Dentro de la app, incluye un botón visible **“Eliminar cuenta y datos”** (Ajustes → Privacidad) que borre cuenta y datos automáticamente.

---

##  Soporte

- Email: **taxi360barcelona@gmail.com**

---

## © Copyright

© TaxiNeto360. Todos los derechos reservados.

