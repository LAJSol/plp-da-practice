# County Rainfall and Planting Advisory

**Author:** Leah Atieno J. · **Cohort:** 1MillionDevs Cohort

---

## Project Summary

A farmer-support NGO (non-governmental organisation) sends SMS (Short Message Service) planting advice to farmers in five Kenyan counties: Nairobi, Nakuru, Kisumu, Mombasa and Machakos.

The project analysed monthly rainfall readings in millimetres; the hand-entered Machakos data had invalid April and September values, which were replaced with the rounded average of valid readings (68 mm), and the results—including annual totals, wettest and dry months, and two-month planting windows—were saved in `rainfall_summary.csv`.

## How to Run

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](<your Open in Colab link>)

1. Open `rainfall_analysis.ipynb` in Colab and choose **Runtime → Run all**.
2. Running the notebook creates `rainfall_summary.csv`.
3. Offline: run `pip install -r requirements.txt`, then open the notebook
   in Jupyter or VS Code.

## Planting advisory

- Farmers in Nairobi, Nakuru, Kisumu and Mombasa should plant in April to May, the wettest two months, and have seed and land ready by the end of March.
- Machakos farmers should plant in November to December and use drought-tolerant crops, mulching or water storage, because Machakos is the driest county (811 mm a year, 6 dry months).
- Data-quality warning: two Machakos readings (April and September) were missing and estimated at 68 mm, so Machakos advice is less certain until the real readings are recovered.

## Files

- `README.md`: this page
- `rainfall_analysis.ipynb`: the cleaning and analysis
- `rainfall_summary.csv`: one row per county
- `requirements.txt`: the libraries used
