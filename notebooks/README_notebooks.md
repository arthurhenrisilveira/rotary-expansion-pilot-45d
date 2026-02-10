# Data Pipeline (Colab)

This notebook builds the municipal-level dataset used in the Power BI dashboard.

## How to run
1. Open the notebook in Google Colab
2. Mount Google Drive (`drive.mount(...)`)
3. Update the paths in the CONFIG section:
   - `MUNICIPIOS_XLSX`
   - `ROTARY_CLUBS_CSV`
   - output paths (`OUT_...`)
4. Run all cells

## Outputs
- `rotary_clubs_with_municipio_pop_v*.xlsx` (joined dataset)
- `join_exceptions_missing_population_v*.xlsx` (join exceptions)
- `Relatorio_Mensal_Rotary_Municipios_*.xlsx` (director-ready report)
