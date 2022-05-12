# Cahier de laboratoire TSM_AppElm

## Informations importantes

### Paramètres d'une antenne

- Paramètres physique
  - Taille
  - Matériaux $\epsilon_r$ 
  - Permittivité $\sigma$ 
- Paramètres circuit
  - $S_{11}$ vs $f$
  - $S_{11}$ @ $f_r$
  - Bande passante -> -10[dB] ou -6[dB]
- Paramètres de rayonnement (transmission)
  - Gain
  - Efficacité
  - Directivité
  - Diagramme de rayonnement 3D/2D/1Dpolaire

### Antenne planaire dipôle

![](C:\MASTER\Soft\Labo_SIM\Github\TSMAppElm_Labo02\Figures\dimensions.png)

$e$ : épaisseur cuivre ($35$ $\mu m$)

$h$ : épaisseur substrat ($1.6$ $mm$)

$\epsilon_r$ : permittivité du substrat 

### Evolution des paramètres sur la physique

Tableau de variation des paramètre physique sur les paramètres du circuit

$\Delta f$ = variation de la fréquence de résonance

$\Delta S_{11}$ = variation de la profondeur du pic du $S_{11}$ 

### Tableau de modification de l'antenne dipôle FR4

| $\Delta = 10\%$            | $ref$ [mm] | $\Delta f$ [MHz] | $\Delta S_{11}$ [dB] |
| -------------------------- | ---------- | ---------------- | -------------------- |
| i (largeur piste)          | 0.8        | $\uparrow$ 4     | $\downarrow$ 0.216   |
| ws (Largeur PCB)           | 30         | 0                | $\uparrow$ 0.059     |
| ls (Longueur PCB)          | 120        | 0                | $\uparrow$ 0.010     |
| l1 (longueur brin antenne) | 4          | $\downarrow$ 24  | $\uparrow$ 0.927     |
| l2 (largeur brin antenne)  | 19.5       | $\downarrow$ 188 | $\downarrow$ 1.030   |
### Tableau de modification de l'antenne dipôle Céramique (alumina 99% lossfree)

| $\Delta = 10\%$            | $ref$ [mm] | $\Delta f$ [MHz] | $\Delta S_{11}$ [dB] |
| -------------------------- | ---------- | ---------------- | -------------------- |
| i (largeur piste)          | 0.8        | $\uparrow$ 8     | $\downarrow$ 0.1933  |
| ws (Largeur PCB)           | 20         | $\downarrow$ 4   | $\uparrow$ 0.05154   |
| ls (Longueur PCB)          | 100        | 0                | $\downarrow$ 0.07415 |
| l1 (longueur brin antenne) | 2          | $\downarrow$ 16  | $\uparrow$ 0.4974    |
| l2 (largeur brin antenne)  | 16         | $\downarrow$ 184 | $\downarrow$ 0.42109 |