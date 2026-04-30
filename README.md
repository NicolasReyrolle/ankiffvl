# AnkiFFVL - Révisions QCM FFVL

<p align="center">
   <a href="https://reynadan.github.io/ankiffvl/">Pour s'entrainer c'est par là » ANKIFFVL</a>
</p>
  
Application de révision des questions du QCM de la Fédération Française de Vol Libre (FFVL) utilisant la méthode de répétition espacée (style Anki).

## Fonctionnalités

- **777 questions** issues du QCM officiel FFVL (parapente uniquement)
- **Thèmes colorés** par niveau de brevet (vert, bleu, marron, gris, violet)
- **Score journalier** : pourcentage de réussite basé sur les points FFVL réels (ex : 270/360 pts)
- **Objectif 75%** : seuil de réussite visualisé sur le graphique (15/20)
- **Répétition espacée** : les questions sont reproposées selon votre niveau de maîtrise
- **Notation manuelle** : boutons "Difficile" et "Apprise" pour contrôler votre progression
- **Filtre par thème** : réviser un thème ciblé (Météo, Mécavol, Réglementation…)
- **Filtre Difficiles** : liste des questions ratées plusieurs fois ou marquées difficiles
- **Diagrammes explicatifs** : schémas pour illustrer les concepts clés
- **Profil et statistiques** : graphique d'évolution, historique en points FFVL, meilleure série
- **PWA** : installable sur mobile comme une application native
- **Multi-utilisateurs** : chaque utilisateur a sa propre progression
- **Hors-ligne** : fonctionne sans connexion internet

## Niveaux de brevet

| Niveau | Couleur | Questions | Seuil examen |
|--------|---------|-----------|--------------|
| Brevet Initial | Vert (V) | 162 | 135/180 pts (75%) |
| Brevet de Pilote | Bleu (B) | 325 | 270/360 pts (75%) |
| Brevet Confirmé | Marron (M) | 214 | 135/180 pts (75%) |
| Qualification Treuil | Gris (T) | 76 | - |
| **Total** | | **777** | |

> Les questions spécifiques au delta (préfixes H, R, X) ont été retirées.

## Système de score

Le score correspond au **pourcentage de points FFVL obtenus dans la journée** :

- Chaque réponse correcte rapporte ses points (ex : +6 pour une bonne réponse)
- Réponse partielle sur une question multi-choix : les points partiels comptent (ex : 3/6)
- **Objectif** : atteindre 75% (équivalent 15/20 à l'examen)

## Système de répétition espacée

| Niveau | Intervalle | Indicateur |
|--------|------------|------------|
| 0 | - | ○○○○○○○○ (nouvelle) |
| 1–7 | 1 min → 14 jours | progression |
| 8 | 30 jours | ●●●●●●●● (maîtrisée) |

- **Bouton "Apprise"** : force le niveau 8 directement
- **Bouton "Difficile"** : force le niveau 1 et marque la question

## Filtres

| Filtre | Contenu |
|--------|---------|
| À réviser | Questions dues + nouvelles |
| Nouvelles | Questions jamais vues |
| ⚠ Difficiles | Marquées "Difficile" ou ratées 2+ fois |
| Toutes | Toutes les questions du niveau |

Combinables avec le **filtre par thème**.

## Thèmes des questions

| Préfixe | Thème | Nb |
|---------|-------|----|
| A | Météo / Aérologie | 111 |
| E | Mécavol / Aérodynamique | 89 |
| F | Facteurs humains | 39 |
| G | Aérodynamique avancée | 35 |
| L | Matériel / Équipement | 32 |
| N | Structure de l'aile | 66 |
| P | Sites & Nature | 30 |
| S | Réglementation FFVL | 187 |
| U | Situations pratiques | 93 |
| W | Pratique / Progression | 95 |

## Utilisation

1. Ouvrir `index.html` dans un navigateur (ou installer en PWA)
2. Entrer votre nom ou pseudo
3. Sélectionner votre niveau de brevet
4. Sélectionner un thème et/ou un filtre (optionnel)
5. Cliquer sur "Commencer la session"
6. Cocher les bonnes réponses et valider
7. Après validation : noter "Difficile" ou "Apprise" selon votre ressenti

## Source des questions

Questions issues du dépôt [qcmffvl](https://github.com/jruffet/qcmffvl) de @jruffet.

## Licence

avec <3 par [Daniel Reynaud](https://github.com/reynadan) — [Licence CC 3.0](https://creativecommons.org/licenses/by/3.0/)
