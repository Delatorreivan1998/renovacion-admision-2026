# renovacion-admision-2026
Automatización de renovaciones y admisiones 2026 - Google Apps Script
# 🔄 Sistema de Renovación y Admisión 2026
**Assistire - Centro de Rehabilitación Integral**

Automatización completa del proceso de renovación de prestaciones 2026, desarrollada en Google Apps Script sobre Google Sheets. El sistema procesa miles de filas evaluando condiciones de cobertura y aplica resultados automáticamente, respetando los límites de ejecución de Google.

---

## ⚙️ Archivos del proyecto

| Archivo | Función |
|---|---|
| `importante.gs` | Lógica principal de validación y procesamiento |
| `duplicado.gs` | Procesamiento de formularios y respuestas |
| `emails_renovacion.gs` | Envío automático de emails a pacientes |

---

## 🚀 Funcionalidades

- Procesamiento en bloques de 120 filas con trigger cada 1 minuto
- Corte automático por tiempo (55s) con guardado de progreso en `PropertiesService`
- Lock de concurrencia (`LockService`) para evitar ejecuciones paralelas
- Lógica condicional por tipo de prestación: Integración Escolar, Terapias, Módulos
- Envío de emails automáticos con estado de renovación
- Funciones utilitarias: iniciar, pausar y resetear el proceso

---

## 🛠️ Stack

`Google Apps Script` · `Google Sheets` · `GmailApp` · `PropertiesService` · `LockService` · `ScriptApp Triggers`

---

## 👤 Autor
Iván De la torre — [GitHub](https://github.com/Delatorreivan1998)
