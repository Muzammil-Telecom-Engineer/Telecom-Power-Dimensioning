# Telecom Power Dimensioning Model

Excel-based model to size the power system of a telecom site (-48V DC):
battery bank, rectifier modules (N+1), AC breaker, DG set and DC cable.

## What it does
Enter the site load, backup time and battery type. The model calculates:
- Battery capacity (Ah) with DoD, ageing and temperature factors
- Rectifier modules with N+1 redundancy
- AC input current and breaker size
- DG set size (kVA) with growth margin
- DC cable size from voltage drop

## Sheets
| Sheet | Purpose |
|---|---|
| Site Power Dimensioning | Main calculator (inputs and results) |
| Scenario 2 Lithium | Second example with lithium battery |
| Charts | Bar, line and pie charts of results |
| Notes | Formulas and assumptions |

## Example Result (60 A load, 6 h backup, VRLA)
| Item | Result |
|---|---|
| Battery | 600 Ah |
| Rectifier | 4 x 50 A (N+1) |
| AC breaker | 40 A |
| DG set | 15 kVA |
| DC cable | 50 mm2 |

## Charts
![Charts overview](images)

## How to use
1. Download `Site_Power_Dimensioning.xlsx`
2. Change only the yellow input cells
3. Read the results in the green cells

## Note
Input values are typical and for learning purposes. Real projects follow
customer specifications and vendor datasheets.

## Author
Muzammil | Telecommunication Engineer
LinkedIn: www.linkedin.com/in/muzammil0904
