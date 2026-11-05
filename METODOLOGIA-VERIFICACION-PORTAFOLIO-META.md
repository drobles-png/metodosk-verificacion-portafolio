# Metodología de Verificación de Portafolios Comerciales de Meta

Proceso estándar de Bakano para verificar el estado "Negocio verificado" de un
Portfolio Comercial (Meta Business Manager) de un cliente. Aplica a cualquier
portafolio nuevo o que aparezca como "Sin verificar" en
**Configuración > Información del negocio > Estado de la verificación del negocio**.

## 1. Qué es y por qué importa

La verificación de negocio es el proceso con el que Meta confirma que un
Portfolio Comercial pertenece a una empresa legítima y real. Sin ella, el
cliente pierde acceso a límites más altos de cuentas publicitarias, a la API
de WhatsApp Business a escala, a ciertos permisos avanzados y a productos que
Meta restringe a negocios verificados.

## 2. Prerrequisitos antes de iniciar el trámite en Meta

Reunir esto ANTES de tocar el Business Manager evita el error más caro: un
rechazo por datos que no coinciden.

- [ ] **Razón social exacta** tal como aparece en el documento legal de
      constitución (RUC, escritura, nombramiento), incluyendo sufijos
      ("S.A.", "Cía. Ltda.", puntos, comas).
- [ ] **Dirección fiscal exacta**, con el mismo formato/abreviaturas del
      documento oficial (ej. "Km 2.5 vía a Samborondón" vs "Kilómetro 2.5...").
- [ ] **Número de teléfono del negocio** que el cliente pueda contestar o que
      tenga buzón/verificación por SMS o llamada.
- [ ] **Sitio web activo y en línea**, con el **nombre legal del negocio**
      visible en el pie de página (footer), idealmente igual al de los
      documentos.
- [ ] **Correo corporativo** con el mismo dominio del sitio web (no Gmail,
      Hotmail, etc.) para poder confirmar propiedad del dominio.
- [ ] **Acceso al DNS o al hosting del dominio** (para poder subir un archivo
      HTML, agregar una meta etiqueta o crear un registro TXT).
- [ ] **2-3 documentos oficiales** que muestren nombre + dirección, o nombre +
      teléfono, con fecha de emisión de los últimos 3-6 meses. Ejemplos
      válidos: RUC, nombramiento del representante legal, certificado de
      constitución, planilla de servicio básico a nombre de la empresa,
      registro tributario.
- [ ] Documentos escaneados en **buena resolución, sin recortes**, en PDF o
      imagen nítida (no fotos torcidas ni capturas de pantalla borrosas).
- [ ] Si el documento no está en inglés y Meta lo solicita en ese idioma:
      traducción certificada adjunta junto con el documento original.

## 3. Checklist de ejecución paso a paso

1. **Entrar al portafolio correcto**
   - [ ] Confirmar que se está dentro del Business Manager del cliente (no de
         Bakano) antes de editar nada.
2. **Completar/corregir Información del negocio**
   - [ ] `Configuración > Información del negocio > Editar`: cargar razón
         social, dirección y teléfono exactamente como en los documentos.
3. **Iniciar verificación**
   - [ ] Ir a **Seguridad del negocio** (Security Center) o al botón
         **"Ver detalles" / "Iniciar verificación"** en el estado de
         verificación.
   - [ ] Seleccionar el país de registro del negocio (define qué documentos
         acepta Meta).
   - [ ] Subir los 2-3 documentos preparados en el paso 2.
4. **Verificar el dominio del sitio web**
   - [ ] Ir a `Seguridad de marca > Dominios` (Brand Safety and Suitability).
   - [ ] Agregar el dominio (ej. `metodosk.ec`).
   - [ ] Elegir un método de verificación:
     - Registro **TXT en el DNS** (recomendado si se tiene acceso al
       proveedor de dominio), o
     - **Archivo HTML** subido a la raíz del sitio, o
     - **Meta tag** en el `<head>` del sitio.
   - [ ] Confirmar "Verificar dominio" y esperar la validación.
5. **Confirmar coincidencia de correo**
   - [ ] Verificar que el correo de contacto del negocio use el mismo dominio
         ya verificado.
6. **Enviar y monitorear**
   - [ ] Enviar la solicitud y anotar la fecha de envío en la plantilla de
         seguimiento (sección 6).
   - [ ] Revisar el estado cada 2-3 días desde el Security Center (tiempo
         típico de respuesta: 3-15 días hábiles).

## 4. Errores que causan rechazo (y cómo evitarlos)

| Causa | % aprox. de rechazos | Cómo evitarlo |
|---|---|---|
| Nombre legal no coincide exactamente | Mayoría de los casos | Copiar el nombre tal cual el documento, sin abreviar ni completar por cuenta propia |
| Dirección con formato distinto | Frecuente | Igualar abreviaturas, pisos, referencias, exactamente como el documento |
| Teléfono no verificable | Frecuente | Usar un número que el cliente conteste o con buzón activo |
| Documento de mala calidad (foto torcida, recorte, sin membrete oficial) | Frecuente | Escanear en PDF, 300 DPI, documento completo visible |
| Usar factura o extracto bancario sin membrete oficial como único soporte | Frecuente | Priorizar RUC, constitución, nombramiento o planilla de servicios |
| Sitio web sin el nombre legal en el footer, o sitio caído | Frecuente | Confirmar que el sitio esté activo y el footer tenga la razón social |
| Reenviar la solicitud el mismo día tras un rechazo | Común, agrava el problema | Corregir el dato exacto que Meta señaló, esperar 24 h y recién reenviar |

## 5. Documentos aceptados por país (referencia rápida)

- **Ecuador**: RUC, nombramiento del representante legal, escritura de
  constitución, planilla de servicio básico a nombre de la empresa.
- **Genérico / otros países**: licencia comercial, certificado de registro
  tributario, artículos de incorporación, documento oficial de la cámara de
  comercio local.
- Meta mantiene una lista específica por país dentro del propio flujo de
  verificación (aparece al elegir el país) — siempre confirmar ahí antes de
  preparar documentos, porque puede variar.

## 6. Plantilla de seguimiento (duplicar una fila por cliente/portafolio)

| Cliente | ID de portafolio | Fecha envío | Documentos usados | Dominio verificado (Sí/No) | Estado Meta | Motivo de rechazo (si aplica) | Fecha reenvío | Responsable |
|---|---|---|---|---|---|---|---|---|
| Ej: Karen López Armijos | 1840184922706204 | | | | Sin verificar | | | |

## 7. Estados posibles y siguiente acción

- **Sin verificar** → Ejecutar checklist de la sección 3.
- **En revisión** → Solo monitorear, no reenviar ni editar datos mientras esté en este estado.
- **Verificado** → Cerrar el caso en la plantilla de seguimiento.
- **Rechazado** → Ir a la tabla de la sección 4, identificar el campo señalado
  por Meta, corregirlo puntualmente, esperar 24 h y reenviar.

---

Fuentes consultadas para esta metodología:
- [Meta Verification Documents: What Gets Accepted (2026)](https://singhamandeep.com/meta-business-verification-documents-required/)
- [How to Verify Your Business Manager (2026)](https://www.gabrielegalluzzo.com/posts/How-to-Verify-Your-Meta-Business-Manager)
- [Facebook Business Manager Verification Guide (2026)](https://affinect.com/facebook-business-manager-verification)
- [Meta Domain Verification Step by Step](https://qtonix.com/blog/how-to-verify-your-domain-in-meta-business-manager-step-by-step-guide/)
- [Meta Business Verification Rejected? 20 Reasons & Fixes](https://chakrahq.com/article/meta-business-verification-rejected-reasons/)
- [Meta Business Verification Rejected? 7 Fixes That Work in 2026](https://anylinga.com/blog/en/meta-business-verification-rejected-7-fixes.html)
