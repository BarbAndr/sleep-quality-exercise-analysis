# sleep-quality-exercise-analysis_něco jiného
Comparing sleep quality on training vs. non-training days  - visualization in Google Colab.

# Analýza vlivu silového tréninku na kvalitu spánku

Projekt analyzuje můj osobní spánek a silové tréninky za rok 2024-2025 pomocí dat z Garmin hodinеk.

## Cíl projektu
Zjistit, jak silový trénink ovlivňuje:
- Délku spánku
- Kvalitu spánku (Overall Score, Quality Score)
- Zda existuje zpožděný efekt (den po tréninku)
- Zda intenzita tréninku hraje roli

## Data
- **Spánek:** 358 dní (prosinec 2024 - prosinec 2025)
- **Tréninky:** 93 silových tréninků
- **Zdroj:** Garmin Connect export

## Hlavní zjištění

### 1. Trénink zlepšuje kvalitu spánku
- **S tréninkem:** Overall Score 81.2 (+2.4)
- **Bez tréninku:** Overall Score 78.9
- **Efekt je nejsilnější hned tu noc po tréninku**

### 2. Kratší, ale kvalitnější
- S tréninkem: 7.1 hodin (o 20 min méně)
- Ale Quality Score o 4 body vyšší!

### 3. Intenzita není všechno
- **Lehké tréninky** (<1026 kcal): Nejlepší spánek (83.2 score)
- **Těžké tréninky** (>1597 kcal): Horší spánek (79.4 score)
- **Závěr:** Přetrénování škodí!

## Technologie
- Python 3
- Pandas (čištění dat)
- Matplotlib, Seaborn (vizualizace)
- Google Colab

## Autor
Barb - Student datové analýzy