# BUG-001 — Paginación no aparece con pocos registros (esperado) vs umbral mal documentado

**Severidad:** Low  
**Ambiente:** QA  
**Rol:** DSP  

## Resumen
Con ≤25 reportes el pager no se muestra. El CA pedía validar página 2 sin indicar el page size.

## Pasos
1. Entrar a Service Reports con 12 registros
2. Buscar controles de paginación

## Actual
No hay página 2.

## Esperado
Documentar page sizes (25/50/100/200) y seed de datos >25 para la prueba.

## Evidencia
Contador = 12; limit = 25.
