# Órbita · Spelling Adventure

Juego de práctica oral de Spelling Bee con temática espacial.

- 97 palabras distintas y las 100 entradas de la lista de segundo grado.
- Audio integrado: letras en inglés y luego la palabra completa.
- Modo de escucha, misiones y simulacro acompañado.
- Avance guardado en el navegador de cada dispositivo.
- Deletreo por micrófono en las misiones de práctica, con validación de letras.
- Sin cuentas del niño ni grabaciones guardadas por la app. El navegador puede usar un servicio externo para reconocer la voz.

## Abrir en una tablet

Abrir el enlace de GitHub Pages en Safari o Chrome. Tocar «Escuchar deletreo» para empezar.
El audio se activa al tocar un botón.

## Publicación

En Settings → Pages, elegir Deploy from a branch, rama main y carpeta / (root).
El archivo index.html contiene todo lo necesario para jugar.

## Micrófono

Las letras se fijan solo al confirmarse y se añaden al siguiente espacio. Los resultados provisionales no cambian las casillas. La app reutiliza el reconocedor y recuerda la preferencia de activación, pero el permiso lo controla el navegador: elegir Permitir para este sitio si vuelve a preguntar.

El archivo audio-library.txt conserva la biblioteca de audio de la versión anterior. boot.js lee solo su JSON de audio sin ejecutar el HTML archivado.
