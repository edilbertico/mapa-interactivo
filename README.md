# Mapa Interactivo — Regiones de Salud · Cundinamarca

Mapa interactivo de 116 municipios en 14 regiones de salud con red de hospitales y portafolio de servicios por tipología (Circular 041 / REPS).

## Archivo principal
- `index.html` — Mapa interactivo (archivo único, sin build). Abrir directo en navegador o vía GitHub Pages.
- `MAPA_INTERACTIVO_V3_PORTAFOLIO.html` — copia con nombre versionado

## Datos
- `7092026_Portafolio.csv` — Fuente: Distribución Prestación portafolios servicios por Tipologías para cada región Salud a nivel municipal (253 registros)

## Funcionalidades
- 8 desplegables: Región Salud PTRRMR, Municipio, Prestador — ESE REPS, Sede — REPS, Sede — PTRRMR, Tipología, Zona, Carácter + buscador
- Tabla portafolio (9 columnas) filtrada en tiempo real, vinculada al mapa
- Exportar CSV (`;`) y Descargar PDF (jsPDF + autoTable) sobre datos filtrados
- Cartografía oficial IGAC 2022 (IDEC) + referencia salud mental

## Uso local
Doble clic en `index.html` — no requiere servidor.

## GitHub Pages
Activar en Settings → Pages → Source: Deploy from a branch → Branch: main / root
