# BUG-002 — Usuario PRT accede a URL FSM

**Severidad:** High  
**Ambiente:** QA  
**Rol:** PRT  

## Resumen
Usuario sin grupo FSM no debe ver Service Reports.

## Pasos
1. Login PRT
2. Abrir `/my/fsm/service_reports`

## Actual
(Documentar status real: 403 / redirect / contenido)

## Esperado
403 o página de acceso denegado; sin datos del listado.

## Evidencia
Status HTTP + captura.
