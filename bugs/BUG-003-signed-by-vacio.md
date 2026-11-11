# BUG-003 — Signed By vacío muestra valor inconsistente

**Severidad:** Medium  
**Ambiente:** QA  
**Rol:** DSP  

## Resumen
Registro con PDF/firma pero `signed_by` vacío debe renderizar celda vacía de forma consistente.

## Pasos
1. Abrir listado
2. Ubicar appointment con Signed By vacío
3. Abrir PDF

## Actual
(Describir: blank / undefined / otro texto)

## Esperado
Celda vacía o guion; PDF sigue abriendo.

## Evidencia
Captura de fila + PDF.
