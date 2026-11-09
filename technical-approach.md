# Technical Approach

## Proposed stack

| Component | Proposed tool | Role |
|---|---|---|
| Programming | Python | Core processing |
| Data preparation | Pandas, NumPy | Cleaning and analysis |
| Machine learning | Scikit-learn | Pattern analysis and risk estimation |
| Map | Folium | Geographic visualisation |
| Dashboard | Streamlit | Interactive dashboard |
| Prototype database | SQLite | Local development storage |

## Planned pipeline

Approved/sample data → preprocessing → feature/pattern analysis → area-level risk estimate → map/dashboard → authorised human review.

## Important implementation distinction

The repository currently includes static HTML demonstration pages. The stack above is the proposed implementation direction; it should not be mistaken for an already connected or trained machine-learning backend. A real model, validated dataset, evaluation results, and secure data pipeline must be implemented and tested separately.
