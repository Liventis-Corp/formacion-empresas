# LIVENTIS LAB — Formación Empresarial

Proyecto estático para GitHub y Vercel. Nombre recomendado del repositorio: `liventis-formacion-empresas`.

## Contenido
- `index.html`: landing corporativa, registro HubSpot y formulario de necesidades formativas.
- `logo-liventis.jpg`: logotipo original facilitado por la empresa.
- `vercel.json`: configuración básica para Vercel.

## Publicación
1. Crear un repositorio privado en GitHub.
2. Subir los tres archivos directamente a la raíz del repositorio (no la carpeta ni el ZIP).
3. Importar el repositorio en Vercel, con Framework Preset `Other` y Root Directory `./`.
4. Verificar el despliegue y realizar una prueba real de registro en HubSpot.
5. URL prevista para integrar en WordPress: https://liventiscorp.com/formacion-empresas/

## Integraciones
- Formulario HubSpot: región EU1; portal 149636353; form b316210e-b4a0-4010-8b43-85a51797460b.
- Calendly: https://calendly.com/aranzazurodriguez

## Advertencias importantes
- El evento `hs-form-event:on-submission:success` desbloquea visualmente el segundo formulario tras el envío correcto de HubSpot. No es una autenticación ni un sistema seguro de control de acceso.
- Deben verificarse los valores de las propiedades ocultas (landing de origen = Formación empresarial; servicio = Formación corporativa). El formulario compartido por todas las páginas no asegura por sí mismo el envío de esos valores.
- El formulario detallado de necesidades se procesa exclusivamente en el navegador. **No se envía a HubSpot ni a Liventis**. El usuario puede copiar su resumen y compartirlo durante una reunión. Para un envío automático real se requiere integrar esas respuestas con HubSpot mediante nuevas propiedades y un mecanismo de envío apropiado.
- Verificar textos legales y consentimiento de privacidad del formulario antes de publicar.
- Si se usa Vercel para captación comercial, revisar un plan que permita usos comerciales.
