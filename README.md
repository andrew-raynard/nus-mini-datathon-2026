# NUS SDS × DSESC Mini Datathon 2026

**Project:** Evaluating Singapore's Certificate of Entitlement (COE) Category A/B system through data analysis, forecasting, and policy simulation.

## Research question
Does the existing Category A/B split still distinguish mass-market cars from higher-value cars? Should LTA retain, merge, or redesign the categories?

## Planned analysis
- Analyse Category A/B premium trends, gaps, and bidding pressure.
- Forecast premiums using time-aware validation and simple baselines.
- Explore registrations by car make and fuel type, including EV trends.
- Evaluate hypothetical merged-category premiums under explicit assumptions.
- Present a policy recommendation, trade-offs, and limitations.

## Repository structure
```
main.ipynb              # Analysis notebook (provided starter template)
data/
  coe_bidding.csv        # COE bidding results
  car_registrations.csv  # New registrations by make
docs/
  briefing.pdf           # Competition briefing
requirements.txt         # Python dependencies
```

## Getting started
```bash
python -m pip install -r requirements.txt
jupyter notebook main.ipynb
```
The notebook's relative dataset paths are already matched to the files under `data/`.

## Competition deliverables
Submission requires `main.ipynb`, `main.html`, `requirements.txt`, `deck.pdf` (maximum 12 slides), and `data/`, packaged as `[TeamName].zip` (maximum 200 MB). Deadline: **30 October 2026, 2:00 PM SGT**. The GitHub repository is for collaboration; the required ZIP must still be submitted separately.

## Status
Work in progress. Findings and recommendations have not yet been established.

## Data and attribution
Datasets: Singapore Land Transport Authority, as supplied in the competition materials. See `docs/briefing.pdf` for context and source notes.
