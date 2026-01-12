# 🚀 Projet Ascension - Phase 1 : Atelier Mini-Fusée

**Club IMSAT - IMT Atlantique (Campus de Brest)**

Ce dépôt contient les ressources et la documentation technique du **Projet Ascension**. Cet atelier vise la conception et la fabrication de **mini-fusées à eau avancées** par les étudiants de première année.

Contrairement aux fusées à eau classiques constituées uniquement d'une bouteille, ce projet introduit une architecture modulaire complexe avec un fuselage externe et une structure interne imprimée en 3D, rapprochant la démarche des contraintes réelles de l'ingénierie spatiale.

---

## 🎯 Objectifs

L'atelier a été conçu pour répondre à quatre critères principaux:

* **Pédagogie :** Découverte des outils de l'ingénieur (CAO, simulation, machines-outils) et du Fablab.
* **Performance :** Assurer un vol stable (sans vrille ni retournement) et une hauteur minimale.
* **Faisabilité :** Fabrication entièrement réalisable au sein du Fablab de l'école.
* **Sécurité :** Matériaux légers, absence de pointes et périmètre de sécurité avec lancement à distance.

---

## 🛠️ Architecture Technique

La fusée se divise en plusieurs sous-systèmes modulaires :

| Composant | Description & Fabrication |
| :--- | :--- |
| **Fuselage** | Tube en carton (type stockage de posters) offrant une longueur aérodynamique supérieure à l'impression 3D standard. |
| **Bloc Moteur** | Pièce maîtresse conçue sous Fusion 360 et imprimée en 3D (PLA). Elle accueille la bouteille et fait la jonction avec le fuselage via des vis et inserts filetés. |
| **Propulsion** | Bouteille d'eau gazeuse (plastique plus épais résistant à la pression) servant de réservoir. |
| **Ailerons** | Réalisés en bois (contreplaqué). Structure en "T" permettant de les glisser dans le fuselage sans fixation supplémentaire pour un remplacement facile. |
| **Ogive** | Polystyrène taillé (au cutter) pour absorber les chocs et garantir la sécurité. |

---

## 💻 Stack Technique & Outils

Les étudiants ont utilisé les logiciels et matériels suivants pour mener à bien le projet :

* **Simulation & Dimensionnement :**
    * [OpenRocket](https://github.com/openrocket/openrocket) et *Stab Traj* pour valider l'aérodynamisme.
    * Calcul du Centre de Gravité (CG) et du Centre de Poussée (CP).
* **Conception (CAO/DAO) :**
    * **Fusion 360** pour la modélisation 3D du bloc moteur et de la base.
    * **Inkscape** pour le dessin vectoriel des ailerons (courbes de Bézier).
* **Fabrication (Fablab) :**
    * Imprimantes 3D (PLA).
    * Découpeuse Laser (Ailerons).
    * Perceuse à colonne et scie à chantourner.

---

## 👥 Équipe de Coordination

**Coordinateurs de l'atelier :**
* Bruyère Thomas 
* Aulaire Mathis 
