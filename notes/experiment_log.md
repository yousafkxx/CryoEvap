# Experiment log - vertical tank (LH2_mid)

Notebook: LH2_midExperiment1L.ipynb (copy of LH2_mid.ipynb)
Tank: d_i = 8 m, V = 2033 m3, eta_w = 0.8, T_air = 293.15 K
BOG = plateau value at end of run, in kg/h (printed as data['BOG'][-1] * 3600)

| Run | LF | P (Pa) | Q_b (W) | Plateau BOG (kg/h) | Notes |
|---|---|---|---|---|---|
| baseline | 0.50 | 101325 | 100 | 8.43 | hand estimate ~8.7 kg/h, so consistent |
| LF up | 0.90 | 101325 | 100 | 9.16 | absolute BOG ~9% higher; loss per day lower (~0.17% vs ~0.28%) |
| P up | 0.50 | 300000 | 100 | TBC | |
| Qb zero | 0.50 | 101325 | 0 | TBC | prediction: ~7.6 kg/h |

## Observations
- Higher fill gives a higher absolute BOG but a lower relative loss per day.
- To confirm with supervisor: should the optimisation minimise absolute BOG (kg/h) or % of stored mass lost per day?

## To do
- Run P up and Qb zero experiments, replace TBC with results
- Check the BOG curve has levelled off in each run
