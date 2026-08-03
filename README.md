# iCentral App Forwarder


Página que redirecciona automáticamente a los usuarios a la tienda de aplicaciones correspondiente según su dispositivo:

- **iOS**: https://apps.apple.com/us/app/icentral-app/id6792386283
- **Android**: https://play.google.com/store/apps/details?id=mx.com.icentral.clientes

Si no se puede detectar el dispositivo, se muestran botones para ambas plataformas.

## Despliegue en Vercel

1. Sube este proyecto a un repositorio de GitHub, por ejemplo `icentral-dev/icentral-app-forwarder`.
2. En Vercel, importa el repositorio.
3. Configura el dominio personalizado `app.icentral.com.mx` en el panel de Vercel.
4. Despliega.

## Desarrollo local

```bash
npm install
npm start
```
