# Watt's Up? Synthetic Data for Buildings

This repository contains the challenge data and links to the participating 
teams' repositories for the **Watt's Up? Hack for Energy Efficiency – 
Synthetic Data for Buildings** hackathon, held at TU Wien on 22–23 February 2025.

🔗 [Hackathon event page](https://events.asc.ac.at/event/173/)

This hackathon was funded by the EU project 
[MODERATE](https://moderate-project.eu/) (grant No 101069834) and EuroCC 2.

---

## 📊 Challenge Data

Participants worked with a time series dataset of building energy consumption.
The goal was to generate realistic, GDPR-compliant synthetic data that 
preserves the statistical properties of the original.

| File | Description |
|---|---|
| `Consumption_data_hourly.csv` | Hourly energy consumption time series for 1,300 buildings covering the full year 2022 (8,760 rows). Semicolon-delimited. The `time` column contains timestamps in `DD.MM.YYYY HH:MM` format; each subsequent column (1–1300) is a building ID with numeric kWh values. |
| `Labels_consumption_data.csv` | Metadata for the 1,300 buildings. Semicolon-delimited. Columns: `ID` (building identifier), `Heatpump` (0/1), `Electric_Vehicle` (0/1), `PV_Installation` (0/1), and `Category` (derived label combining installed technologies, e.g. `NONE`, `Only_PV`, `EV_NoPV`, `EV+PV`, `PV+HP`). |

---

## 🏆 Team Repositories

| Team | Repository |
| --- | --- |
| Team 1 – Ländle meets Budapest | [github.com/am11001/watt_s_up](https://github.com/am11001/watt_s_up) |
| Team 2 – UBITransform | [github.com/birrwahn/hackathon-watts-up](https://github.com/birrwahn/hackathon-watts-up) |
| Team 3 – Energy encryptors | [github.com/jenicek/energy_encryptors](https://github.com/jenicek/energy_encryptors) |
| Team 4 – Ekin KAAN | [github.com/ekingit/hackathon](https://github.com/ekingit/hackathon) |
| Team 5 – Internationals | [github.com/HanRewan/Internationals2](https://github.com/HanRewan/Internationals2) |
| Team 6 – Son of a GAN | |
| Team 7 – Synthetic Haribros | |
| Team 8 – TU4code | [github.com/inquisitour/energy-efficiency](https://github.com/inquisitour/energy-efficiency) |

---

## 📄 Acknowledgements

This hackathon was jointly organized by VSC Research Center (TU Wien), 
dataLAB (TU Wien), EuroCC Austria, the Vienna Data Science Group, 
the EU project MODERATE, TU Wien, and e-think energy research.

The MODERATE project has received funding from the European Union's 
Horizon Europe research and innovation programme under grant agreement 
No 101069834.