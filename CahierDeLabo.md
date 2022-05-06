# Cahier de laboratoire TSM_AppElm

## Informations importantes

### Paramètres d'une antenne

- Paramètres physique
  - Taille
  - Matériaux $\epsilon_r$ 
  - Permittivité $\sigma$ 
- Paramètres circuit
  - S11 vs f
  - s11 @ f_r
  - Bande passante -> -10[dB] ou -6[dB]
- Paramètres de rayonnement (transmission)
  - Gain
  - Efficacité
  - Directivité
  - Diagramme de rayonnement 3D/2D/1Dpolaire

### Evolution des paramètres sur la physique

Tableau de variation des paramètre physique sur les paramètres du circuit

$\Delta f$ = variation de la fréquence de résonance

$\Delta S_{11}$ = variation de la profondeur du pic du $S_{11}$ 

## Tableau de modification de l'antenne dipôle FR4

| $\Delta = 10\%$            | $ref$ [mm] | $\Delta f$ [MHz] | $\Delta S_{11}$ [dB] |
| -------------------------- | ---------- | ---------------- | -------------------- |
| i (largeur piste)          | 0.8        | $\uparrow$ 4     | $\downarrow$ 0.216   |
| ws (Largeur PCB)           | 30         | 0                | $\uparrow$ 0.059     |
| ls (Longueur PCB)          | 120        | 0                | $\uparrow$ 0.010     |
| l1 (longueur brin antenne) | 4          | $\downarrow$ 24  | $\uparrow$ 0.927     |
| l2 (largeur brin antenne)  | 19.5       | $\downarrow$ 188 | $\downarrow$ 1.030   |
## Tableau de modification de l'antenne dipôle Céramique

| $\Delta = 10\%$            | $ref$ [mm] | $\Delta f$ [MHz] | $\Delta S_{11}$ [dB] |
| -------------------------- | ---------- | ---------------- | -------------------- |
| i (largeur piste)          | 0.8        |                  |                      |
| ws (Largeur PCB)           | 20         |                  |                      |
| ls (Longueur PCB)          | 100        |                  |                      |
| l1 (longueur brin antenne) | 2          |                  |                      |
| l2 (largeur brin antenne)  | 16         |                  |                      |