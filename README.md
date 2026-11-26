# aplicaciones
para iesp

## Simulador de Evaluación – Análisis Delictual

Archivo: [`index.html`](index.html)

Simulador de examen multiple choice para la Licenciatura en Seguridad Pública (UNT). Cada examen sortea **21 preguntas al azar** del banco del módulo elegido y tiene **25 minutos** de tiempo:

- **Unidad 1** – Fundamentos y Política Criminal (banco de 30 preguntas)
- **Unidad 2** – Metodología y Objeto Criminológico (banco de 30 preguntas)
- **Unidad 3** – Estadística Moral y Positivismo (banco de 30 preguntas)
- **Simulacro General** – Examen integrador que sortea de las 90 preguntas

Características:

- Pantalla previa con las reglas y botón «Comenzar examen»; el reloj de 25:00 arranca recién al presionarlo.
- Si se agota el tiempo, el examen se cierra solo y las preguntas sin contestar cuentan como incorrectas.
- Navegación estrictamente unidireccional: cada respuesta queda bloqueada y no se puede volver atrás (también se bloquea el botón «Atrás» del navegador).
- Opciones mezcladas al azar en cada intento.
- Resultado final con criterio de aprobación ≥ 60 % (13 de 21), tiempo utilizado, detalle de respuestas y descarga del acta en `.txt`.

Para usarlo, abrí `index.html` en el navegador o publicalo con GitHub Pages (Settings → Pages → rama `main`, carpeta raíz).
