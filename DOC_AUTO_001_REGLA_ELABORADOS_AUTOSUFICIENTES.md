# DOC-AUTO-001 · Norma de elaboración documental autosuficiente
**FinitySAP · 10-11-2026 · propuesta pendiente de aprobación por Paola**

## Aplicación obligatoria
Todo elaborado o artefacto (Word, PDF, MD, informe, acta, procedimiento, cartilla, plan, presentación, o libro Excel documental) debe **entenderse y utilizarse por sí mismo** sin reconstruir una conversación de chat ni inferir información faltante. Este requisito es transversal a Assessment, diseño, construcción SAP, pruebas ERP/UAT, despliegue, AMS y gobierno.

## Revisión mediante Editor Documental
El agente especialista prepara el contenido y **convoca a `editor-documental` antes de publicar o entregar**. Si el entorno no admite invocar subagentes, aplica la misma lista de verificación y deja constancia; no afirmar que ejecutó algo que no hizo. La revisión no sustituye controles técnicos, propietarios ni autorizaciones.

## Comprobaciones
1. Explicar objetivo, destinatario, alcance/exclusiones, contexto, metodología y definiciones/acrónimos.
2. Explicar los datos con su universo, fuente, fecha/corte, significado, responsables, resultados y decisiones.
3. Incorporar anexos pertinentes con referencia cruzada, nombre, versión, estado y fuentes. El texto principal explica lo esencial sin remitir ciegamente a anexos.
4. Distinguir **Hecho / Interpretación / Por confirmar**. Documentar discordancias y pendientes; nunca inventar datos, vínculos ni validaciones.
5. Usar estilos profesionales en Word/PDF, tablas legibles, índice/secciones, enlaces verificados, títulos y numeración. Comprobar contenido final, no sólo borrador.
6. No llamar «adjunto», «publicado», «enviado», «agendado» ni «aprobado» a nada que no tenga evidencia.
7. Resultado editorial: **Conforme / Conforme con pendientes / No conforme**, con brechas y acciones pendientes.
8. Respetar reglas de datos, PR y aprobación humana. No exponer secretos ni información personal innecesaria.

## Caso de aplicación ERP/UAT
El documento Plan UAT debe integrar Markdown de cada cartilla como anexo legible, con procesos, posiciones, ejecutores, escenarios, datos, resultados esperados y evidencias. Cuando las versiones finales estén publicadas en SharePoint, incluir su **URL verificada** y el enlace verificado del Excel de coordinación de Roberto; hasta entonces marcar «pendiente». No sustituir los anexos autosuficientes por enlaces sin contexto.

## Referencia de implementación
La especificación del agente se encuentra en el proyecto Aguas Andinas, `.claude/agents/editor-documental.md` de PR #207. Si se requiere uso autónomo en este repo, se debe instalar y probar su propia definición de agente, sin asumir conexión automática de otros repositorios.
