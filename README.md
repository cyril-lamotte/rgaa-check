# RGAA Check

Projet d'application web pour remplacer le fichiers excel des audits d'accessibilité.

## Pourquoi créer cette application ?

Le but est d'oublier les tableaux excel gargantuesques ou les rapports PDF de 100 pages.
Ce produit serait une interface web, claire, et fonctionnelle.

## Objectifs personnels

Apprendre une technologie front (vue / angular / react...)


## Comment ça marcherait en théorie ?

1. Configuration d'un projet
  - Un utilisateur créé un projet (nom du projet / url / URL et noms des pages testées)

2. Consultation
  - La liste des critère RGAA est visible, chaque critère est par défault "non-testé" c'est une synthèse de toute les pages.
  - Sur chaque critère, on peut voir la liste des pages en echec.
  - Chaque page est cliquable et affiche la liste des critères (filtrable par état)
  - L'état des critères permet de calculer le taux de confirmité global et le taux moyen.

3. Phase de récolte d'anomalie

  - L'utilisateur changer l'état d'un critère d'un page/composant en Non applicable / Validé / Corrigé / Autres...
  - L'utilisateur peut créer une non conformité associée à un critère et à la page courante.
  
