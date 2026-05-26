# Monitor TES · República de Colombia

Dashboard interactivo de análisis de renta fija colombiana.

## Funcionalidades
- Curva de rendimientos TES actual vs 3, 6 y 12 meses
- Calculadora precio / YTM / duración / convexidad / DV01
- Simulador de shocks de tasa (+50, +100, +200 bps)
- VaR de portafolio TES (delta-normal, 95%/99%)
- Comparador CDT vs TES (neto de retención en fuente)
- Panel DeFi vs TES (Aave v3 vs deuda soberana COP)
- Datos en tiempo real: IBR, TRM, IPC, Tasa Banrep (API SDMX Banrep)

## Despliegue
Sitio estático. Solo subir `index.html` a Netlify.

## Fuentes de datos
- TES: Precia PRO (referencial)
- IBR / TRM / IPC / Tasa Banrep: API SDMX Banco de la República
- DeFi: Aave v3 (referencial)

## Contexto regulatorio
Herramienta educativa. No constituye asesoría de inversión.
La actividad de análisis y visualización no requiere licencia AMV.
