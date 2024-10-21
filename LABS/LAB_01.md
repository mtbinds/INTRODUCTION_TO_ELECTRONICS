# TP 01 : Les Composants de Base en Électronique

## Objectifs du TP :

- Comprendre le fonctionnement et les caractéristiques des composants électroniques de base.
- Réaliser des simulations pour observer les comportements de ces composants dans différents circuits.
- Mesurer et analyser les paramètres électriques associés à chaque type de composant.

## Logiciel requis :

- **Tinkercad Circuits**, **Proteus**, ou **Multisim** pour la simulation des circuits.
- Un ordinateur avec accès au logiciel de simulation.

---

## 1. Résistances

### 1.1 Définition

Les **résistances** limitent le courant dans un circuit et dissipent l'énergie électrique sous forme de chaleur.

### 1.2 Fonctionnement

- La loi d'Ohm, `V = I × R`, relie la tension ***(V)***, le courant ***(I)*** et la résistance ***(R)***.
  
### 1.3 Types de Résistances

1. **Résistances fixes** : Valeur constante.
2. **Résistances variables (potentiomètres)** : Valeur ajustable.
3. **Résistances de puissance** : Conçues pour dissiper des quantités élevées d'énergie.

### 1.4 Application Pratique

#### Partie 00 : Mesure de la Résistance

**Objectif** : Mesurer la résistance d'un circuit simple.

**Procédure** :

1. Ouvrez le logiciel de simulation.
2. Créez un circuit avec une résistance de **100Ω** connectée à une source de **9V**.
3. Utilisez un **multimètre** virtuel pour mesurer la tension aux bornes de la résistance et le courant à travers celle-ci.
4. Calculez la résistance à partir de ***la loi d'Ohm***.

### 1.5 Observations

- Notez les valeurs mesurées et vérifiez si elles correspondent à la valeur de la résistance utilisée.

---

## 2. Condensateurs

### 2.1 Définition

Les **condensateurs** stockent de l'énergie électrique sous forme de champ électrique.

### 2.2 Fonctionnement

- La capacité ***(C)*** d'un condensateur est donnée par la formule : `C = Q / V`.

### 2.3 Types de Condensateurs

1. **Condensateurs électrolytiques** : Haute capacité, polaires.
2. **Condensateurs céramiques** : Non polaires, adaptées à des applications haute fréquence.
3. **Condensateurs à film** : Haute stabilité.

### 2.4 Application Pratique

#### Partie 01 : Stockage et Décharge d'un Condensateur

**Objectif** : Observer le chargement et le déchargement d'un condensateur.

**Procédure** :

1. Ouvrez votre simulateur et créez un circuit avec un condensateur de **100µF**, une résistance de **1kΩ** et une source de **9V**.
2. Observez le temps de chargement du condensateur à travers un **oscilloscope virtuel**.
3. Déconnectez la source d'alimentation et observez la décharge du condensateur à travers la résistance.

### 2.5 Observations

- Notez la forme de l'onde de tension pendant le chargement et le déchargement du condensateur.

---

## 3. Inductances

### 3.1 Définition

Les **inductances** stockent de l'énergie sous forme de champ magnétique.

### 3.2 Fonctionnement

- La tension (V) aux bornes d'une inductance est donnée par : `V = L × (dI/dt)`.

### 3.3 Types d'Inductances

1. **Inductances à air** : Utilisées pour des fréquences élevées.
2. **Inductances noyées** : Contiennent un noyau magnétique.
3. **Transformateurs** : Transfèrent de l'énergie entre circuits.

### 3.4 Application Pratique

#### TP 3 : Mesurer l'Inductance

**Objectif** : Observer le comportement d'une inductance dans un circuit.

**Procédure** :

1. Créez un circuit avec une inductance de **10mH** en série avec une source de **9V** et une résistance de **100Ω**.
2. Mesurez la tension et le courant à l'aide de multimètres virtuels.
3. Calculez l'énergie stockée dans l'inductance.

### 3.5 Observations

- Notez comment la tension varie lorsque le courant change.

---

## 4. Diodes

### 4.1 Définition

Les **diodes** permettent au courant de circuler dans une seule direction, essentielles pour le redressement du courant.

### 4.2 Fonctionnement

- En polarisation directe, elles laissent passer le courant. En polarisation inverse, elles bloquent le courant.

### 4.3 Types de Diodes

1. **Diodes standard** : Utilisées pour le redressement.
2. **Diodes Zener** : Régulent la tension.
3. **Diodes Schottky** : Commutation rapide et faible tension de seuil.

### 4.4 Application Pratique

#### TP 4 : Redressement avec une Diode

**Objectif** : Observer le fonctionnement d'une diode en tant que redresseur.

**Procédure** :

1. Créez un circuit avec une source CA (5Vpp), une diode et une résistance de **1kΩ**.
2. Mesurez la tension en sortie de la diode avec un oscilloscope virtuel.
3. Comparez les formes d'onde en entrée et en sortie.

### 4.5 Observations

- Notez les différences entre les signaux d'entrée et de sortie.

---

## 5. Transistors

### 5.1 Définition

Les **transistors** amplifient ou commutent des signaux électroniques.

### 5.2 Fonctionnement

- Dans un BJT, le courant de base contrôle le courant collecteur-émetteur.

### 5.3 Types de Transistors

1. **Transistors bipolaires (BJT)** : Amplification des signaux.
2. **Transistors à effet de champ (FET)** : Haute impédance.
3. **Transistors MOSFET** : Commutation rapide.

### 5.4 Application Pratique

#### TP 5 : Amplification avec un Transistor

**Objectif** : Utiliser un transistor pour amplifier un signal.

**Procédure** :

1. Créez un circuit avec un transistor ***BJT***, une source de signal d'entrée (par exemple, un générateur de fonctions) et une résistance de charge.
2. Mesurez le signal d'entrée et le signal de sortie avec un oscilloscope virtuel.
3. Calculez le gain du transistor.

### 5.5 Observations

- Notez la relation entre le signal d'entrée et le signal de sortie.

---

## Conclusion

Ce TP vous a permis d'explorer les composants de base de l'électronique à travers des simulations pratiques. En observant les comportements des résistances, condensateurs, inductances, diodes et transistors, vous avez acquis une compréhension essentielle de leur fonctionnement et de leurs applications dans les circuits électroniques.

---

