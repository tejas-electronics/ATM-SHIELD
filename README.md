# ATM SHIELD
### Predicting High-Risk ATM Withdrawal Areas

**SIH 2026 Problem Statement:** SIH26184  
**Ministry / Department:** Ministry of Home Affairs – Indian Cyber Crime Coordination Centre (I4C)  
**Theme:** Cybersecurity  
**Project type:** Software prototype

## 1. Project overview

ATM SHIELD is a proposed area-level risk-awareness system. It aims to analyse patterns in cybercrime-related complaints by area and time, estimate which areas may need closer attention, and present the results through a map-based dashboard for authorised teams.

The system focuses on **locations and patterns**, not identifying or accusing individuals. A predicted risk level is a signal for further human review; it is not proof that a crime has occurred.

## 2. Problem being addressed

ATM-related cybercrime complaints can be difficult to examine across different locations and time periods. A structured way to view complaint patterns may help authorised teams notice possible hotspots and prioritise verification.

## 3. Proposed workflow

1. Collect an approved dataset or use clearly labelled sample data for development.
2. Clean and prepare the records.
3. Analyse location- and time-based patterns.
4. Estimate an area-level risk score.
5. Display low, medium, and high risk categories on a map/dashboard.
6. Present trends and alerts to authorised users.
7. Require human verification before any operational response.

## 4. Proposed technology stack

- **Language:** Python
- **Data processing:** Pandas, NumPy
- **Machine learning:** Scikit-learn
- **Map visualisation:** Folium
- **Dashboard:** Streamlit
- **Prototype storage:** SQLite

These are proposed technologies for the planned system. The supplied HTML demo is a front-end simulation and does not, by itself, implement this full backend stack.

## 5. What is included in this repository?

| Path | Contents |
|---|---|
| `index.html` | GitHub Pages landing page |
| `demo/` | Interactive judges' demo (fictional sample data) |
| `learning-app/` | Project learning and presentation guide |
| `docs/` | Project explanation and technical documentation |
| `presentation/` | SIH 2026 short presentation |

## 6. Run the prototype

You can open `index.html` in a browser, or enable GitHub Pages to publish the landing page. The interactive demo and learning app are static HTML files and do not require a server.

## 7. Current prototype status and limitations

- The supplied demo uses synthetic/fictional sample areas, scores, and complaint counts.
- The demo's alert-generation interaction is illustrative; it does not send real alerts.
- There is no live crime-data feed, bank integration, police-system integration, or deployed prediction service in this HTML prototype.
- Model accuracy has not been established using verified operational data.
- Real deployment would require official data access and approval, privacy and security controls, testing, and human oversight.

## 8. Responsible-use principles

- Use only lawfully obtained, authorised, and appropriately protected data.
- Avoid personal identification or profiling.
- Treat scores as indicators for review, not as evidence or accusations.
- Evaluate false positives, false negatives, data quality, and geographic bias.
- Restrict access to authorised personnel and maintain appropriate audit controls.

## 9. References

- SIH 2026 problem statement: https://sih2026.vuce.in/ps/SIH26184
- Smart India Hackathon: https://sih.gov.in/
- Scikit-learn documentation: https://scikit-learn.org/stable/
- Streamlit documentation: https://docs.streamlit.io/
- Folium documentation: https://python-visualization.github.io/folium/

## 10. Team

Team size: 4 members. Add the confirmed team name and member details here before public submission.

---

**Note:** This repository documents a student concept and demonstration prototype. It should not be represented as a validated crime-prediction or law-enforcement system.
