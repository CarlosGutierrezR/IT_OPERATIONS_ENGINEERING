<div align="center">

# IT Operations Engineering

### Laboratorios reproducibles · Diagnóstico técnico · Documentación operativa

[![Estado](https://img.shields.io/badge/Estado-En%20construcción-F59E0B?style=for-the-badge)](#estado-actual)
[![Linux](https://img.shields.io/badge/Linux-Ubuntu%2024.04-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)](#entorno-de-trabajo)
[![Git](https://img.shields.io/badge/Git-Control%20de%20versiones-F05032?style=for-the-badge&logo=git&logoColor=white)](#método-de-resolución)
[![WSL2](https://img.shields.io/badge/WSL2-Laboratorio-0078D4?style=for-the-badge&logo=windows&logoColor=white)](#entorno-de-trabajo)

Portafolio técnico de resolución de incidencias de **Git, Linux y redes**, construido mediante laboratorios reproducibles y documentación operativa.

[Objetivo](#objetivo) · [Áreas técnicas](#áreas-técnicas-del-proyecto) · [Soluciones](#soluciones-verificadas) · [Método](#método-de-resolución) · [Estructura](#estructura-del-repositorio)

</div>

---

## Objetivo

Demostrar un proceso profesional de troubleshooting: reproducir el problema, recopilar evidencia, aislar la causa raíz, aplicar el cambio mínimo, verificar el resultado y documentar la recuperación.

Todos los casos proceden de escenarios ficticios de laboratorio. No representan incidencias ni datos de organizaciones reales.

## Áreas técnicas del proyecto

- Administración y diagnóstico de Linux mediante WSL2 y Bash.
- Control de versiones, recuperación y trazabilidad con Git.
- Diagnóstico de conectividad y configuración de red.
- Automatización segura con Bash y PowerShell.
- Diseño de pruebas reproducibles y criterios de aceptación.
- Elaboración de runbooks, evidencias y procedimientos de reversión.

## Entorno de trabajo

| Componente | Uso |
|---|---|
| Windows + PowerShell | Administración del entorno anfitrión |
| WSL2 + Ubuntu 24.04 LTS | Laboratorios Linux desechables |
| Git + GitHub | Historial, revisión y publicación de soluciones |
| Bash + `iproute2` | Diagnóstico y automatización en Linux |

## Soluciones verificadas

| ID | Incidencia | Área | Estado | Evidencias |
|---|---|---|---|---|
| OPS-001 | Recuperación segura de una configuración | Git / Linux | En preparación | Pendiente de validación |

Una solución solo cambia a **verificada** cuando sus pruebas se han ejecutado y sus resultados están documentados en el repositorio.

## Método de resolución

```text
Síntoma -> Reproducción -> Evidencia -> Hipótesis -> Cambio mínimo -> Pruebas -> Runbook
```

Cada entrega debe incluir:

1. descripción y alcance del incidente;
2. pasos de reproducción;
3. diagnóstico sustentado en evidencias;
4. causa raíz;
5. solución implementada;
6. pruebas y criterios de aceptación;
7. reversión o recuperación, cuando corresponda;
8. limitaciones conocidas.

## Estructura del repositorio

```text
.
├── incidents/   # Informes de incidencias resueltas
├── configs/     # Configuraciones de ejemplo saneadas
├── scripts/     # Automatizaciones operativas
├── tests/       # Pruebas reproducibles
├── runbooks/    # Procedimientos de operación y recuperación
└── docs/        # Arquitectura y documentación complementaria
```

## Controles de publicación

Antes de incorporar una solución se comprueba que:

- el problema puede reproducirse en un laboratorio aislado;
- la causa está respaldada por evidencia técnica;
- el cambio es mínimo, revisable y reversible;
- las pruebas indicadas fueron ejecutadas realmente;
- no existen secretos, credenciales ni datos personales;
- la documentación permite repetir la verificación.

## Estado actual

La estructura inicial está preparada y el primer caso, **OPS-001**, se encuentra en fase de laboratorio. El repositorio crecerá únicamente con soluciones que hayan superado sus criterios de aceptación.

---

<div align="center">

**Evidencia antes que afirmaciones. Cambios mínimos, pruebas reproducibles y documentación clara.**

</div>
