# Atelier KiCad — Conception de schéma et de PCB

## Objectif de l’atelier

Cet atelier a pour but d’introduire les participants à **KiCad**, un logiciel libre de conception de circuits imprimés (PCB).  
Il est divisé en **deux sections complémentaires** :

1. **Conception du schéma électronique**
2. **Conception du PCB**

Lorsqu’il est offert en personne, ces deux parties sont présentées séparément afin de permettre aux participants de se familiariser graduellement avec l’interface et le flux de travail de conception.

---

## Partie 1 – Schéma électronique

- Correspond à la **section 3 du guide**.  
- Le fichier `C3I_A25_schema_reference` contient le **schéma de référence** (PDF seulement) que les participants peuvent suivre pour se repérer.
- Les participants doivent **designer eux-mêmes** le composant **SN74LS47N** afin d’apprendre à utiliser l’éditeur de symboles de KiCad.

### Assignation des empreintes (footprints)

Avant de passer à la conception du PCB (section 4 du guide), **chaque composant du schéma doit avoir une empreinte assignée**.  
Trois options s’offrent à vous :

1. **Trouver les composants vous-même** sur [DigiKey](https://www.digikey.ca) et assigner les empreintes correspondantes.  
2. **Suivre les listes de composants DigiKey** disponibles dans l’**Annexe A du guide**, au format **SMD** ou **THT**, selon votre préférence.  
3. **Utiliser les liens des BOMs** (listes de matériel) des **kits de composantes C3I**, obtenus via [LCSC](https://www.lcsc.com).

---

## Partie 2 – Conception du PCB

Avant de commencer cette section :

- Vous devez disposer d’un **schéma complet avec toutes les empreintes assignées** :
  - Si vous partez de votre propre conception, **validez votre schéma une dernière fois** avant l’importation.
  - Si vous utilisez le **projet KiCad fourni**, ajoutez la **footprint manquante de l'interrupteur SPDT**.  
  Trois options sont possibles :
  1. Trouver la composante correspondante sur **DigiKey** et assigner l’empreinte manuellement.  
  2. Suivre la **liste DigiKey** (SMD ou THT) disponible en **Annexe A du guide**.  
  3. Utiliser les **liens du BOM LCSC** correspondant au **kit de composantes C3I**.

### Importation et validation

- Lors de l’importation des composantes sur le PCB, **assurez-vous qu’aucune erreur ne soit détectée** (et idéalement aucun Warning).  
- Avant de procéder au routage, il est fortement recommandé d’avoir assisté ou lu le ppt du **séminaire sur les normes de conception PCB**, qui aborde les bonnes pratiques de disposition et de fabrication.

---

## Listes de composantes (BOM)

Quatre combinaisons sont possibles selon vos besoins :

| Type de BOM | Plateforme | Format disponible | Usage recommandé |
|--------------|-------------|-------------------|------------------|
| DigiKey BOM – THT | DigiKey / Annexe du guide | `lien de liste Digikey` | Pour commander vos propres composantes traversantes |
| DigiKey BOM – SMD | DigiKey / Annexe du guide | `lien de liste Digikey` | Pour commander vos propres composantes montées en surface |
| LCSC BOM – THT | LCSC / dossier `BOM_kits` | `.pdf` | Pour obtenir le **kit C3I THT** lors des ateliers de soudure |
| LCSC BOM – SMD | LCSC / dossier `BOM_kits` | `.pdf` | Pour obtenir le **kit C3I SMD** lors des ateliers de soudure |

> Les BOMs du dossier `BOM_kits` sont celles utilisées pour préparer les kits de composantes C3I (payants) distribués durant les ateliers de soudure.

---

## Notes finales

- Les participants peuvent choisir de suivre une seule des deux parties ou de réaliser le projet complet.  
- L’objectif est d’acquérir une **compréhension pratique de la conception électronique**, de la création du schéma jusqu’à la mise en page du PCB.
- En cas de problème ou pour valider vos choix de composants, n’hésitez pas à contacter l’équipe C3I.



