# TP 00 : Notions de Base en Électricité (Simulation)

## Objectifs du TP :

- Comprendre les concepts de tension, courant, et résistance via une simulation.
- Vérifier la loi d'Ohm à l'aide d'un simulateur.
- Mesurer et calculer la puissance consommée dans un circuit simple en utilisant des outils virtuels.

## Logiciel requis :

- **Tinkercad Circuits**, **Proteus**, ou **Multisim** pour la simulation des circuits.
- Un ordinateur avec accès au logiciel de simulation.

---

## 1. Mesure de la Tension (V)

### Objectif :

- Simuler et mesurer la **tension** entre deux points dans un circuit.

### Procédure :

1. **Ouvrir le logiciel de simulation** :

   - Démarrez votre simulateur (par exemple, ***Tinkercad Circuits***).
   
2. **Configurer le circuit** :

   - Placez une **source d'alimentation DC** (par exemple, une pile de ***9V***) sur la zone de simulation.
   - Ajoutez un **voltmètre virtuel** dans le circuit.
   
3. **Effectuer les connexions** :

   - Connectez le voltmètre entre les deux bornes de la source d'alimentation pour mesurer la tension.

4. **Ajouter une résistance** :

   - Ajoutez une résistance de **100Ω** en série avec la source d'alimentation.

5. **Mesurer la tension** :

   - Mesurez la tension aux bornes de la résistance à l'aide du voltmètre virtuel.

### Observations :

- Notez la valeur de la tension mesurée dans chaque étape.
- Observez comment la tension est répartie dans le circuit.

---

## 2. Mesure du Courant (I)

### Objectif :

- Mesurer le **courant** dans un circuit avec une résistance.

### Procédure :

1. **Configurer le circuit** :

   - Dans votre simulateur, créez un circuit avec une source d'alimentation de **9V** et une résistance de **220Ω**.

2. **Ajouter un ampèremètre** :

   - Insérez un **ampèremètre virtuel** en série avec la résistance pour mesurer le courant.

3. **Exécuter la simulation** :

   - Lancez la simulation et notez la valeur du courant affichée par l'ampèremètre.

### Calcul théorique :

- Utilisez la loi d'Ohm pour prédire le courant dans le circuit :

   `I = V / R`
   
   Où :
   - `V` est la tension ***(9V)***,
   - `R` est la résistance ***(220Ω)***.

### Observations :

- Comparez la valeur mesurée du courant avec celle calculée théoriquement.

---

## 3. Vérification de la Loi d'Ohm

### Objectif :

- Vérifier la relation entre tension, courant et résistance dans un circuit simulé.

### Procédure :

1. **Configurer le circuit** :

   - Montez un circuit dans le simulateur avec une résistance de **330Ω** et une source d'alimentation de **9V**.

2. **Mesurer les grandeurs** :

   - Mesurez la **tension** aux bornes de la résistance avec un voltmètre et le **courant** traversant la résistance avec un ampèremètre.

3. **Calculer la résistance** :

   - Calculez la résistance à partir de la loi d'Ohm :

   `R = V / I`

### Observations :

- Comparez la résistance calculée avec la valeur nominale de la résistance.
- Vérifiez la cohérence avec la loi d'Ohm.

---

## 4. Calcul de la Puissance (P)

### Objectif :

- Mesurer et calculer la **puissance** consommée dans un circuit simulé.

### Procédure :

1. **Configurer le circuit** :

   - Utilisez une résistance de **1kΩ** et connectez-la à la source d'alimentation de **9V** dans le simulateur.

2. **Mesurer les grandeurs** :

   - Mesurez la tension aux bornes de la résistance avec un voltmètre et le courant traversant la résistance avec un ampèremètre.

3. **Calculer la puissance** :

   - Calculez la puissance consommée en utilisant la formule :

   `P = V × I`

4. **Utiliser une formule alternative** :
   
   - Utilisez la formule alternative pour calculer la puissance :

   `P = I² × R`

### Observations :

- Comparez les puissances calculées avec les deux formules.
- Notez comment la puissance varie en fonction de la résistance et du courant.

---

## 5. Comparaison des résultats

### Table des mesures (dans le simulateur) :

| Résistance (Ω) | Tension (V) | Courant (A) | Résistance calculée (Ω) | Puissance (W) |
|----------------|-------------|-------------|--------------------------|---------------|
| 100            | ...         | ...         | ...                      | ...           |
| 220            | ...         | ...         | ...                      | ...           |
| 330            | ...         | ...         | ...                      | ...           |
| 1000           | ...         | ...         | ...                      | ...           |

### Analyse :

- Analysez la relation entre les différentes grandeurs en fonction de la loi d'Ohm.
- Comparez les puissances calculées dans les différentes configurations.

---

## Conclusion

Ce TP de simulation vous a permis de :

- Mesurer virtuellement la tension, le courant, et la résistance.
- Vérifier la loi d'Ohm à l'aide d'un simulateur.
- Calculer la puissance consommée dans un circuit à partir des données simulées.

Grâce à la simulation, vous pouvez explorer ces notions sans utiliser d’équipement réel, tout en visualisant le comportement des circuits électriques en temps réel. Cela constitue une première étape avant de manipuler des circuits physiques.

---

