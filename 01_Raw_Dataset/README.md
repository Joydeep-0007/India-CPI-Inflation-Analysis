# 01 · Raw Dataset

The original files. **Do not edit them**; save every change into `02_Cleaned_Dataset/`.

| File | Rows | Coverage | Columns |
|---|---|---|---|
| `cpi-national.csv` | 164 | Jan 2013 – Aug 2026 | `year, month, combined_index, rural_index, urban_index, combined_inflation, rural_inflation, urban_inflation` |
| `cpi-categories.csv` | 720 | Jan 2025 – Aug 2026 | `category` (12 divisions), `year, month, sector` (Combined/Rural/Urban), `index_value, inflation_rate` |
| `cpi-states.csv` | 2,140 | Jan 2025 – Aug 2026 | `state` (36), `year, month, sector, index_value, inflation_rate` |
| `cpi-items.csv` | 7,160 | Jan 2025 – Aug 2026 | `category › sub_group › class › sub_class › item` (358 items), `code, year, month, index_value, inflation_rate` |

**Note:** the first line of every file is a `# source…` comment. Remove it before using the first row as headers.

**Inflation (YoY %)** = (Index this month ÷ Index same month last year − 1) × 100.
