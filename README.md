# Parkinson Demographie-Analyse

Dieses Projekt untersucht einen demographischen Datensatz zur Parkinson-Erkrankung. Die Analyse kombiniert programmatische Datenzeilen in Python mit einer interaktiven visuellen Aufbereitung in Power BI.

## 📁 Projektstruktur

Das Repository ist wie folgt aufgebaut:

* **`projekt_parkinson.ipynb`** – Das Jupyter Notebook mit der vollständigen Python-Analyse.
* **`Dashboard_Parkinson_Projekt.pbix`** – Ein Power BI Dashboards zur visuellen Exploration.
* **`demographics.xls`** – Der zugrundeliegende demographische Datensatz.
* **`Fragestellung_Projekt_Parkinson.pdf`** – Die zugrundeliegenden Leitfragen und Ziele dieser Analyse.

## 🚀 Analyse-Schwerpunkte

* **Fragestellung** – Systematische Beantwortung der vorgegebenen Kernfragen aus dem PDF-Dokument.
* **Explorative Datenanalyse (EDA)** – Statistische Auswertung von demographischen Faktoren und Testergebnissen in Python.
* **Interaktives Dashboard** – Visueller Einblick in den Datensatz nach Bereinigung in Power BI für schnelle Erkenntnisse.

## 🛠️ Technologien & Tools

* **Python 3.x** & **Jupyter Notebook** (Pandas, NumPy, Matplotlib, Seaborn, scipy.stats)
* **Microsoft Power BI** (Datenvisualisierung & Dashboard-Design)
* **Microsoft Excel** (Datenbasis im `.xls`-Format)

📊 Wichtigste Erkenntnisse (Insights)

* **Demographische Trends & Krankheitsbild:** Ein deutlicher Männeranteil unter den Parkinson-Patienten (63,6 %) im Vergleich zur Kontrollgruppe (54,8 %), wobei primär leicht betroffene, selbstständige Patienten im Datensatz vertreten waren.
* **Alter & Mobilitätsfaktoren:** Mit steigendem Alter zeigen vor allem männliche Patienten einen höheren Schweregrad der Erkrankung sowie eine moderate Korrelation zwischen Alter und dem TUAG-Testergebnis (Timed Up and Go).
* **Methodische Limitationen:** Datenqualitätsprobleme durch uneinheitliche Maßeinheiten aus drei verschiedenen Studienquellen und eine relativ kleine Kohorte (161 Probanden), die zukünftige Längsschnittstudien erfordert.

<img width="2505" height="1440" alt="dashboard_parkinson_projekt" src="https://github.com/user-attachments/assets/fe022f65-2a28-425f-92f3-bf5164fb7aeb" />

## 👤 Autor

* **FFingerhutAnalytics** – [GitHub-Profil](https://github.com/FFingerhutAnalytics)

## 💽 Datenquelle

* **[PhysioNet](https://physionet.org/) :** Goldberger, A., Amaral, L., Glass, L., Hausdorff, J., Ivanov, P. C., Mark, R., ... & Stanley, H. E. (2000). PhysioBank, PhysioToolkit, and PhysioNet: Components of a new research resource for complex physiologic signals. Circulation [Online]. 101 (23), pp. e215–e220. RRID:SCR_007345. [(Link)](https://physionet.org/content/gaitpdb/1.0.0/)
