# Carol & Camila cumplen 10

Invitación web para el cumpleaños número 10 de Carol y Camila — sábado 26 de septiembre de 2026, fiesta tropical.

## Qué es

Una sola página HTML autocontenida (`index.html`): sin build, sin dependencias, sin backend.
Solo carga tipografías desde Google Fonts; todo lo demás (estilos, animaciones, mapa
ilustrado, marco botánico, confeti, música generada) va embebido.

## Ver en local

Abre `index.html` en el navegador, o levanta un servidor estático:

```bash
python3 -m http.server 8000
# luego abre http://localhost:8000
```

## Publicar con GitHub Pages

1. Sube este repo a GitHub.
2. Settings → Pages → Source: `Deploy from a branch` → rama `main`, carpeta `/ (root)`.
3. La página queda en `https://<usuario>.github.io/<repo>/`.

## Contenido

- Portada con nombres, globos de número "10" y atardecer tropical animado
- Cuenta regresiva en vivo
- Accesos rápidos: ubicación · confirmar · calendario · regalos
- Fotos de las cumpleañeras (con visor ampliado)
- Detalles del evento y "agregar al calendario"
- Cómo llegar (mapa ilustrado + Google Maps / Waze)
- Mesa de regalos
- Código de vestimenta interactivo ("gama de colores")
- Confirmación de asistencia que arma el mensaje y lo envía por WhatsApp
- Botón de música (melodía tropical suave generada en el navegador)

## Pendientes

- Fotos reales de Carol y Camila
- Hora exacta de la fiesta (ahora hay un valor de referencia: 3:00 pm)
- Nombre del lugar (si aplica)

---

Proyecto personal. No reutilizar sin permiso.
