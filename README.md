# DNI Protegido

**https://miguelmato.github.io/dni-protegido/**

Herramienta web gratuita para proteger las copias de tu DNI antes de enviarlas:

- Recortar y enderezar las fotos del anverso y el reverso.
- Tapar, pixelar o difuminar datos sensibles (número de soporte, CAN, firma…).
- Pasar a blanco y negro y ajustar contraste y brillo.
- Marca de agua en mosaico con destinatario, finalidad y fecha, líneas de seguridad onduladas y ruido anti-borrado.
- Exportar a PDF o JPG.

## Privacidad

Todo se procesa en el navegador. La página no tiene dependencias externas y su
`Content-Security-Policy` bloquea cualquier conexión de red, así que las fotos
nunca salen de tu dispositivo. También puedes descargar `index.html` y abrirlo
sin conexión.

## Por qué la protección no se puede quitar

Cada página del PDF es una única imagen JPEG con la marca de agua, las zonas
tapadas y el ruido fundidos en los píxeles. No hay capas, anotaciones ni texto
que eliminar.

## Licencia

MIT
