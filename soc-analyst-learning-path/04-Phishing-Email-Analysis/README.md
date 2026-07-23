# 04 - Phishing Email Analysis

**Statut :** 🟧 en cours (7 leçons, 11 questions, 4 alertes SOC, 1 challenge, 1 quiz — ~1h, niveau Beginner)

## Résumé

Section pratique sur l'analyse d'emails de phishing (vecteur d'attaque le plus courant en cybersécurité) : headers d'email, analyse statique/dynamique, techniques complémentaires, puis mise en pratique sur 4 alertes SOC réelles.

## Leçons

- ✅ [Introduction to Phishing](./01-Introduction-to-Phishing.md)
- ✅ [Information Gathering](./02-Information-Gathering.md)
- ✅ [What is an Email Header and How to Read Them?](./03-What-is-an-Email-Header.md)
- ✅ [Email Header Analysis](./04-Email-Header-Analysis.md)
- ⬜ Static Analysis
- ⬜ *(leçons suivantes à venir)*
- ⬜ Quiz de validation

## Points clés à retenir

- Le phishing correspond à la phase **Delivery** du Cyber Kill Chain : exploiter le facteur humain plutôt que la technique.
- Sans SPF/DKIM/DMARC configurés, un domaine est vulnérable au spoofing — à vérifier via MXToolbox.
- Le champ **Received** (lu de bas en haut) révèle le vrai chemin technique d'un email, indépendamment du `From` affiché.
- Deux réflexes rapides face à un email suspect : (1) le serveur SMTP correspond-il au domaine prétendu ? (2) `From` et `Reply-To` sont-ils identiques ?
- Une incohérence From/Reply-To ne suffit pas seule à prouver le phishing — il faut recouper avec le contenu, les pièces jointes et les URLs.
