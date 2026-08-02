# PÉRIMÈTRE — HLP/habitation-la-pinede

## Mission (1 phrase)
Foyer du **site public de l'Habitation La Pinède** (décision Benjamin 2026-08-02) et des artefacts de marque exigés par les plateformes tierces (icônes/favicons App Store, TikTok dev portal).

## Je possède (source de vérité — fait foi en cas de doublon)
- Le site public de la maison : à construire ici (cadrage `/cadrage-projet` requis avant tout code)
- Icônes/favicons de marque : `apple-touch-icon.png`, `favicon.ico`, `icon-16.png`, `icon-32.png`, `icon-192.png`, `icon-512.png`
- **Politique de confidentialité — FAIT FOI** : `privacy-policy.html` (version maintenue, enrichie favicon + logo le 2026-07-07 pour la review TikTok ; la copie de `HLP/hlp-media` est un doublon périmé du 2026-05-22)

## Je fais / je ne fais PAS
- ✅ Site public de la maison (pages, contenu de séjour, réservation) + dépôt des assets exigés par les stores/plateformes
- ⛔ Je ne produis pas de contenu social ni de calendrier éditorial → `HLP/hlp-social`
- ⛔ Je ne stocke pas les médias lourds publiés → `HLP/hlp-media`
- ⛔ Rien ne se construit ici sans cadrage (`/cadrage-projet`) — le foyer est tranché, le site reste à cadrer

## Interfaces
- **J'entre** : rien de systématique (repo dormant, pas de pull actif)
- **Je sors** : `icon-512.png` et favicons — consommés manuellement par Benjamin (upload TikTok dev portal) ; référencés depuis `HLP/hlp-social/ROADMAP.md`
- **Miroirs** : `privacy-policy.html` existe aussi dans `HLP/hlp-media/` — **arbitré le 2026-08-02 : cette version fait foi.** Le texte juridique des deux fichiers est **strictement identique** (vérifié au diff) ; l'écart est cosmétique (favicon + logo ajoutés ici le 07/07 pour la review TikTok) et la copie `hlp-media` est antérieure (22/05) **et cassée si servie** (les 5 icônes qu'elle référence n'existent pas dans ce repo). Doublon à supprimer — voir QUESTION.

## M'adresser un travail
Chip `spawn_task` cwd=`/Users/benjamindupouy/Developer/Claude-Projet/HLP/habitation-la-pinede` ·
brief à froid : lire `ETAT.md` d'abord (statut dormant, question ouverte) · ne rien construire sans cadrage explicite.

## QUESTION
1. ✅ **TRANCHÉ (Benjamin, 2026-08-02)** : le site public de l'Habitation La Pinède vit **ici**, dans le groupe `HLP`. Reste à cadrer (`/cadrage-projet`) avant toute ligne de code.
2. ⏳ **Autorité tranchée** (cette version fait foi) ; **suppression du doublon `hlp-media/privacy-policy.html` en attente d'une vérification Benjamin** : si une URL raw `hlp-media/privacy-policy.html` est enregistrée dans un portail développeur (Pinterest, TikTok, Meta), la supprimer casserait la déclaration — vérifier les portails d'abord, puis supprimer.
