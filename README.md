# F1 Classic Era Data Analysis (1950–2012)
 
Data visualization project analyzing Formula 1 data from the classic era (1950–2012), before the introduction of KERS and DRS. Built with Python using multiple libraries and data sources.
 
---
 
## Questions & Visualizations
 
| Question | Chart Type | Library |
| --- | --- | --- |
| Q1: Which teams dominated F1 between 1950 and 2012? | Bar chart | Seaborn |
| Q2: How did Schumacher, Senna, and Alonso's performance evolve? | Line chart | Plotly |
| Q3: Does starting position affect the final race result? | Scatter + regression | Seaborn |
| Q4: Which circuits have the fastest pit stops? | Box plot | Plotly |
| Q5: Which nationalities produced the most World Champions? | Bar chart | Matplotlib |
 
---
 
## Data Sources
 
- **CSV files** — results, races, drivers, constructors, pit stops, qualifying (hosted on GitHub)
- **Jolpica API** — historical F1 World Champions per year (HTTP requests, successor to Ergast API)
---
 
## Key Findings
 
- **Ferrari** leads with 200+ victories, followed by McLaren and Williams
- **Schumacher** dominated 2000–2004, **Senna** was the most consistent, **Alonso** ended the era strong
- Strong correlation between qualifying position and race result — starting further up the grid significantly improves chances of winning
- **Spanish and German GPs** have the most consistent pit stops; **Singapore** records the slowest due to its street circuit layout
- **Great Britain** leads with 14 World Championship titles, followed by Germany (10) and Brazil (8)
---
 
## Requirements
 
```bash
pip install pandas matplotlib seaborn plotly requests
```
 
---
 
## How to Run
 
1. Open `Proyect_Data_Visualization.ipynb` in Jupyter Notebook or Google Colab
2. Run all cells in order
3. CSV files are loaded from GitHub, API calls are made to Jolpica
---
 
## Tech Stack
 
- Python 3
- Pandas, Matplotlib, Seaborn, Plotly
- Jolpica API (REST)
- Jupyter Notebook
