# Redacted BannerLab v1.1.2 Patch

Cette version apporte plusieurs nouveautés importantes à RBL, ainsi
qu'un ensemble de corrections sur les overlays, la création de fresques
et les outils du Lab.

## Nouveautés

### OSCAR · Mission Overlay

-   Ajout et amélioration du suivi flottant pendant les missions.
-   Suivi de progression directement au-dessus d'Ingress.
-   Corrections du lancement et de la reprise de l'overlay.

### LEON · Kikimeter / Kinetic Tracker

-   Nouveau suivi automatique de distance pour les capsules Kinetic.
-   Plusieurs suivis peuvent fonctionner simultanément.
-   Chaque Kikimeter possède son **nom**, sa **couleur** et sa
    **distance cible**.
-   Affichage sous forme d'overlays flottants indépendants.
-   Suivi automatique basé sur l'activité du téléphone.
-   Correction permettant de réafficher un Kikimeter après avoir fermé
    son overlay.

### Overlays LEON

-   **Appui + déplacement** pour déplacer un overlay.
-   **Appui long fixe** pour ouvrir directement le grand overlay / Lab.
-   Le **triple tap** reste disponible.
-   Gestion commune pour Drone, Timers et Kikimeter.

### Recherche de fresques

-   La dernière recherche est désormais conservée.
-   Les résultats restent affichés après consultation d'une fresque.
-   Restauration de la **position dans la liste** au retour.
-   Plus besoin de ressaisir la ville ou de relancer systématiquement la
    recherche.

### Inventaire & clés

-   Amélioration de la gestion des clés de portails manuelles.
-   Recherche et synchronisation déclenchables sans lancer une requête à
    chaque saisie.
-   Tri des clés par **nom** ou par **quantité**.
-   Amélioration de l'affichage de l'inventaire et utilisation des
    assets du jeu.

## Corrections

-   Correction d'un problème pouvant faire **réapparaître OSCAR à
    l'ouverture d'Ingress** alors qu'aucune mission ne devait être
    reprise.
-   Correction du comportement des overlays Kinetic après fermeture.
-   Correction de plusieurs problèmes de navigation dans les interfaces
    comportant beaucoup de lignes.
-   Ajustements de la barre de navigation verticale des fresques.
-   Correction de la gestion de certains champs texte Android pouvant
    être **vidés lors de leur validation**, notamment :
    -   texte ajouté comme calque sur une image ;
    -   titre de mission.
-   Amélioration de la gestion des claviers Android et des événements de
    composition de texte.
-   Divers correctifs de navigation entre les étages et les outils du
    Lab.

## IGOR / MILO / Bannergress

Les outils et plugins Bannergress existants sont **conservés** dans
cette version. Les derniers correctifs ont volontairement évité de
modifier cette partie afin de ne pas introduire de nouvelle régression.

------------------------------------------------------------------------

**Redacted BannerLab 1.1.2 Patch**

`// Explore. Create. Hack.`
