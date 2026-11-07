# Polyimide Mechanics

## Files

| File | Purpose |
| --- | --- |
| `monomers_smiles.csv` | SMILES of 180 dianhydrides in the first column and 226 diamines in the second. The columns are independent lists. |
| `External_validation.csv` | MD reference values and model predictions for 48 external-test structures: 240 records at 100–500 K and 48 at 1000 K. Physical-model predictions are included only at 1000 K. |
| `Distribution of mechanical properties of polyimide.html` | Interactive property distribution for 40,680 polyimides. Open in a browser and click a point to view its properties and molecular structure. |
| `PI_Mechanics_Predictor.exe` | Windows program for predicting fracture stress, modulus, toughness and fracture-stress decay rate (FSDR). |

## How to use the program

1. On 64-bit Windows, double-click `PI_Mechanics_Predictor.exe`. No Python installation is required.
2. **Single molecule:** enter a repeat-unit SMILES, retaining the `*` connection markers, set the temperature in K, and click **Predict properties**.
3. **Batch prediction:** click **Open CSV**, select the SMILES column and a temperature column or fixed temperature, then click **Run batch prediction**.
4. Click **Export CSV** to save predictions. For a single molecule, select an atom-contribution view and click **Save PNG** to save its image.
