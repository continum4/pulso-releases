# Pulso

Un diario de padecimientos para Android. Anota cada día qué te pasó y con qué
intensidad, y míralo todo junto en el calendario del mes.

Lo que escribes se queda en tu teléfono. No hay cuentas, ni servidores, ni
sincronización: la aplicación **no declara el permiso de internet**, así que no
tienes que fiarte de nuestra palabra — puedes comprobarlo en la lista de
permisos que te enseña el propio Android.

**[Descargar la última versión](https://github.com/continum4/pulso-releases/releases/latest)**
· [Qué es Pulso](https://pulso.continum4.com)
· [Política de privacidad](https://pulso.continum4.com/privacidad.html)

## Qué hay aquí

Solo el APK firmado de cada versión, en la sección *Releases*. El código fuente
no es público.

## Instalar

1. Descarga `pulso.apk` desde la [última versión](https://github.com/continum4/pulso-releases/releases/latest).
2. Ábrelo desde el teléfono. Android te pedirá permiso para instalar
   aplicaciones de origen desconocido: es lo normal en cualquier aplicación que
   no venga de una tienda, y el permiso se concede solo para esta.
3. Puede que veas un aviso de Play Protect diciendo que no reconoce la
   aplicación. Es por lo mismo, no porque haya encontrado nada.

Necesitas **Android 8.0 o superior**.

Si ya tienes Pulso instalado, la versión nueva se instala encima y **conserva tu
historial**. No desinstales para actualizar: eso sí borra tus datos.

## Versiones nuevas

Pulso no se actualiza sola: no se conecta a nada, así que no puede avisarte
desde dentro. Cuando salga una versión, la encontrarás aquí y en
[pulso.continum4.com](https://pulso.continum4.com).

Para actualizar, descarga el APK nuevo e instálalo encima del que tienes. Tu
historial se conserva.

## Comprobar lo que descargas

Cada versión publica la huella SHA-256 de su archivo junto al enlace. Para
verificar que lo que bajaste es exactamente eso:

```
sha256sum pulso.apk
```

Todas las versiones están firmadas con la misma clave, `CN=Pulso, O=continum4,
C=ES`, cuyo certificado tiene esta huella:

```
bafd2fbcb2b250d2d40b2c88119e2c800253651058fded49bea63b09cf65f5ae
```

Que la firma sea siempre la misma es lo que permite que una versión se instale
encima de la anterior sin perder nada. Un APK de Pulso firmado con otra clave no
lo hemos publicado nosotros.

## Un fallo, una idea

Desde la aplicación: **Ajustes → Enviar comentarios**. Se abre tu correo con el
mensaje preparado, así que ves lo que mandas antes de mandarlo.
