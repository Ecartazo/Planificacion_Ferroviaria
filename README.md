# Planificacion_Ferroviaria
# Proyecto Google Sheets + Scripts

Este repositorio contiene scripts de Google Apps Script para automatizar tareas en un Google Sheet.

---

## Scripts

### 1️⃣ ponerFechaHora
Actualiza la celda `L1` de la hoja `PLAYA` con la fecha y hora actuales.

**Uso:**
1. Abrir el Google Sheet.
2. Ir a **Extensiones → Apps Script**.
3. Pegar el contenido de `poner_fecha_hora.gs`.
4. Ejecutar `ponerFechaHora`.

---

### 2️⃣ climaSemanalIconos
Obtiene el pronóstico semanal del clima para Rosario desde la API de Open-Meteo y coloca los íconos en la hoja activa:

- Columnas G y H: íconos + día de la semana.
- Tooltip: descripción del clima al pasar el mouse.

**Uso:**
1. Abrir el Google Sheet.
2. Ir a **Extensiones → Apps Script**.
3. Pegar el contenido de `clima_semanal_iconos.gs`.
4. Ejecutar `climaSemanalIconos`.

> ⚠️ Permite acceso a Internet la primera vez.

---

### 3️⃣ pintarPorHora
Cambia el color de fondo y del texto de los rangos `O1:P4` según la hora del día:

- 0–5 h → O1:P1 (madrugada)  
- 6–11 h → O2:P2 (mañana)  
- 12–17 h → O3:P3 (tarde)  
- 18–23 h → O4:P4 (noche)

**Uso:**
1. Abrir el Google Sheet.
2. Ir a **Extensiones → Apps Script**.
3. Pegar el contenido de `pintar_por_hora.gs`.
4. Ejecutar `pintarPorHora`.

---

## Carpeta `data`
Contiene `sheet_limpio.csv`, una versión exportada del Google Sheet (sin datos sensibles), para usar con los scripts.
