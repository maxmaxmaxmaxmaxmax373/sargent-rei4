# Data

The underlying data for the tables in Chapters 3 and 4, one CSV per table.

- **`csv_tables/`** — raw extraction, one file per table (`Table3.1.csv` … `Table3.27.csv`,
  `Table4.1.csv` … `Table4.12.csv`). Values as they appear in the printed tables.
- **`cleaned_csv/`** — the same tables with tidy column headers and numeric types
  (`Table3.1_cleaned.csv`, …), convenient for loading with pandas.

Example:

```python
import pandas as pd
df = pd.read_csv("data/cleaned_csv/Table3.1_cleaned.csv", index_col=0)
```

The table numbers here match the `Table 3.N` / `Table 4.N` numbers used in the
chapters. (The source spreadsheets are `chapter_3.xlsx` and `chapter_4.xlsx` in the
project's working folder; they can be added here too if wanted.)
