# Atención al cliente con IA · Proyecto Final IA Automation

Flujo que recibe las consultas de clientes desde un formulario, las guarda en
Airtable, las clasifica y redacta una respuesta con IA, y espera mi aprobación
por mail antes de contestarle al cliente.

**Stack:** n8n Cloud · Airtable · OpenAI GPT-4o-mini · Gmail

## Entregables
- 📄 Documentación (diagrama, cumplimiento de la consigna, costos y pruebas): `docs/Proyecto_Final_IA_Automation.pdf`
- 🗺️ Diagrama de arquitectura: `docs/arquitectura.png`
- ⚙️ Flujo principal: `workflow/flujo.json`
- ⚙️ Workflow de errores: `workflow/errores.json`
- 📝 Formulario de contacto: https://alan233.app.n8n.cloud/form/a05536bf-4409-4d33-a645-d17d702fb330
- 🗄️ Base de datos (Airtable): https://airtable.com/invite/l?inviteId=invHJs8zilKwP1Ifj&inviteToken=037ab2e0aabe1dfec47d7000208175a4d257c33030c4a31f5dc896306ff6b252
- 🖼️ Capturas de las pruebas: carpeta `screenshots/`

## Importar el flujo
Importar los dos JSON en n8n, reasignar las credenciales (Airtable, OpenAI y
Gmail) y, en el flujo principal, seleccionar el workflow de errores en
*Settings → Error workflow*.
