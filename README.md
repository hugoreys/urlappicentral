# iCentral App Forwarder

Página de descarga de **iCentral App** con redirección automática a la tienda correspondiente:

- **iOS**: https://apps.apple.com/us/app/icentral-app/id6792386283
- **Android**: https://play.google.com/store/apps/details?id=mx.com.icentral.clientes

Si no se puede detectar el dispositivo, se muestran botones para ambas plataformas.

## Vista previa al compartir (WhatsApp / redes)

La página incluye meta tags Open Graph y Twitter Card, más `og-image.jpg` (1200×630), para que al compartir el enlace aparezcan el logo y la descripción.

URL de producción actual: https://urlappicentral.vercel.app/

> Tip: WhatsApp cachea las previews. Si no se actualiza de inmediato, prueba el enlace con un query param (`?v=2`) o usa [Facebook Sharing Debugger](https://developers.facebook.com/tools/debug/).

## Despliegue en Vercel

1. Conecta este repositorio en Vercel.
2. (Opcional) Configura el dominio personalizado, por ejemplo `app.icentral.com.mx`.
3. Si cambias el dominio canónico, actualiza las URLs absolutas de `og:*` y `canonical` en `index.html`.

## Desarrollo local

```bash
npm start
```
