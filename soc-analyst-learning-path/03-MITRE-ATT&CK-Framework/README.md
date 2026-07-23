# 03 - MITRE ATT&CK Framework

**Statut :** ✅ terminé (8 leçons, 19 questions, 1 quiz — ~1h, niveau Easy)

## Résumé

Cours théorique sur le framework MITRE ATT&CK : base de connaissance des tactiques et techniques (TTPs) réellement utilisées par les attaquants. Approfondit un concept déjà croisé en section 1 (SOAR/playbooks) et section 2 (Cyber Kill Chain).

## Prérequis annoncés

- Compréhension de base des concepts de cybersécurité
- Familiarité avec les réseaux et systèmes d'exploitation
- Connaissance des vecteurs d'attaque et acteurs de la menace courants

## Leçons

- ✅ [Introduction](./01-Introduction.md)
- ✅ [Introduction to MITRE](./02-Introduction-to-MITRE.md)
- ✅ [Matrix](./03-Matrix.md)
- ✅ [Tactics](./04-Tactics.md)
- ✅ [Techniques and Sub-Techniques](./05-Techniques-and-Sub-Techniques.md)
- ✅ [Mitigations](./06-Mitigations.md)
- ✅ [Groups](./07-Groups.md)
- ✅ [Software](./08-Software.md)
- ✅ [Quiz de validation](./09-Quiz-MITRE-ATT-CK.md) (14 points)

## Points clés à retenir

- Hiérarchie complète du framework : **Tactic → Technique → Sub-Technique → Procedure**, puis **Mitigation** (défense), **Group** (qui) et **Software** (avec quel outil).
- 3 matrices selon la plateforme ciblée : **Enterprise** (la plus riche), **Mobile**, **ICS** (industriel).
- Chaque élément (tactique, technique, mitigation, groupe, logiciel) a un ID unique et une fiche documentée sur [attack.mitre.org](https://attack.mitre.org).
- Le framework sert autant à la détection réactive (comprendre une attaque en cours) qu'à l'anticipation proactive (threat hunting, Threat Intelligence).
