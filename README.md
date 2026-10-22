# Anniversaires – Caisse Populaire SUCCÈS

Application web pour **gérer les anniversaires du personnel** et **créer en quelques secondes les cartes « Joyeux anniversaire »** aux couleurs de la Caisse, prêtes à publier.

Elle fonctionne dans le navigateur, s'installe comme une application sur téléphone ou ordinateur, et marche **hors ligne**.

---

## 1. Ce que vous pouvez faire

- Tenir la **liste du personnel** avec photo, poste, service, téléphone et date d'anniversaire
- Voir qui fête son anniversaire **aujourd'hui, demain ou cette semaine** (cloche de notifications)
- **Générer la carte** d'une personne, la télécharger en image (PNG), la partager (WhatsApp, etc.) ou l'imprimer
- Consulter un **calendrier mensuel** et des **statistiques**
- **Importer** une liste depuis Excel ou CSV, **exporter** en CSV, Excel ou PDF
- **Sauvegarder et restaurer** toutes les données

---

## 2. Démarrer

### Ouvrir l'application
Ouvrez l'adresse fournie par votre administrateur (par exemple `https://nom.github.io/anniversaires/`).

### Se connecter
Saisissez l'utilisateur et le mot de passe fournis.
*(Par défaut : `admin` / `succes2026` — à faire changer par l'administrateur, voir section 9.)*

### Installer l'application (recommandé)
- **Android (Chrome)** : appuyez sur le bouton **Installer** en haut de l'écran, ou sur le menu ⋮ puis « Installer l'application ».
- **iPhone (Safari)** : bouton **Partager** puis **« Sur l'écran d'accueil »**.
- **Ordinateur (Chrome ou Edge)** : cliquez sur l'icône d'installation à droite de la barre d'adresse.

Une fois installée, l'application s'ouvre en plein écran et fonctionne même sans connexion.

---

## 3. Gérer la liste

### Ajouter une personne
1. Appuyez sur **+ Ajouter** (en bas à droite).
2. Choisissez une **photo** (champ « Photo »).
3. Remplissez **prénom, nom, poste**, puis service et téléphone si vous voulez.
4. Choisissez **Née / Né**, le **jour** et le **mois** de naissance.
5. Choisissez le **modèle de carte** (vert, bleu, violet ou rose).
6. Appuyez sur **Enregistrer**.

### Ajuster la photo directement sur la carte
Le formulaire affiche la carte telle qu'elle sera publiée. Le texte se met à jour pendant que vous tapez.
- **Déplacer** : glissez la photo avec le doigt ou la souris.
- **Agrandir / réduire** : pincez avec deux doigts, utilisez la molette de la souris ou le curseur.
- **Pivoter** : boutons ⟲ et ⟳ (utile si la photo est couchée).
- **Recentrer** : remet le cadrage de départ.

Ce que vous voyez dans le cadre est exactement ce qui sera enregistré.

### Modifier ou supprimer
Sur la ligne de la personne : **Modifier** ou **Supprimer** (une confirmation est demandée).

### Rechercher et filtrer
- Le champ de **recherche** cherche dans le nom, le prénom, le poste et le service (les accents sont ignorés).
- Les filtres **mois** et **poste** réduisent la liste.
- La pastille **« Dans les 30 jours »** n'affiche que les anniversaires proches.

La liste est triée par **anniversaire le plus proche**.

---

## 4. Créer et utiliser une carte

Appuyez sur **Voir** pour ouvrir la carte, puis :

| Bouton | Action |
|---|---|
| **Télécharger en PNG** | Enregistre la carte en image haute qualité |
| **Partager** | Envoie l'image par WhatsApp, Messenger, e-mail… (selon votre téléphone) |
| **WhatsApp** | Ouvre la conversation avec la personne (si un téléphone est renseigné) avec un message prêt ; joignez ensuite l'image |
| **Imprimer** | Imprime la carte seule |

---

## 5. Notifications et rappels

- La **cloche 🔔** indique le nombre d'anniversaires à venir. Appuyez dessus pour voir la liste (« Aujourd'hui », « Demain », « Dans N jours ») et ouvrir directement la carte.
- Un **bandeau jaune** apparaît en haut de la liste le jour même.
- Dans la cloche, vous pouvez **activer les notifications du navigateur** : une alerte est envoyée à l'ouverture de l'application pour les anniversaires d'aujourd'hui et de demain (une fois par jour).
- Le délai d'alerte (1, 3, 7 ou 14 jours) se règle dans **⚙️ Données & réglages → Rappels**.

> Les notifications ne s'envoient que **lorsque l'application est ouverte**. Elles ne se déclenchent pas toutes seules en arrière-plan.

---

## 6. Calendrier et statistiques

- **Calendrier** : naviguez de mois en mois avec ‹ ›. Les jours avec anniversaire sont colorés avec un compteur. Touchez un jour pour voir les personnes concernées.
- **Statistiques** : nombre de personnes, anniversaires dans les 30 jours, répartition **par mois** et **par service**.

---

## 7. Importer, exporter, sauvegarder (⚙️)

### Importer une liste Excel ou CSV
1. Ouvrez **⚙️ Données & réglages → Importer**.
2. Choisissez votre fichier `.xlsx` ou `.csv`.

Colonnes reconnues (l'ordre n'a pas d'importance, les accents et majuscules sont ignorés) :

| Colonne | Exemple |
|---|---|
| Prénom | Marie |
| Nom | Dupont |
| Poste | Caissière |
| Service | Agence centrale |
| Genre | Née / Né (ou F / M) |
| Jour + Mois | 21 + Octobre (ou 10) |
| ou **Date** | 21/10/1990 (l'année est ignorée) |
| Téléphone | +50937000000 |

Prénom, Nom et la date sont obligatoires. Les **doublons** (même prénom + nom) sont ignorés, et un résumé indique combien de lignes ont été ajoutées ou refusées. Un **modèle CSV** est téléchargeable dans la même fenêtre. Les photos ne s'importent pas : ajoutez-les ensuite une par une.

### Exporter
CSV, Excel, PDF ou impression : l'export suit la **liste affichée**, donc les filtres et la recherche sont pris en compte. Le bouton **ZIP** génère toutes les cartes affichées en images PNG.

### Sauvegarder et restaurer
- **Sauvegarder (JSON)** : télécharge un fichier avec toute la liste, le logo et le message de la carte. Conservez-le sur Drive, par e-mail ou sur un ordinateur.
- **Restaurer** : recharge ce fichier (remplace la liste actuelle, après confirmation).
- Un rappel s'affiche si aucune sauvegarde n'a été faite depuis **14 jours**.

---

## 8. Personnaliser

- **Logo** : appuyez sur le logo en haut à gauche, puis choisissez une image (PNG conseillé, la transparence est conservée). « Rétablir » remet le logo d'origine. Le logo apparaît aussi sur les cartes.
- **Message de la carte** : ⚙️ → *Message de la carte*. Le changement est immédiat pour toutes les cartes.
- **Thème sombre** : ⚙️ → *Apparence*.
- **Modèle de couleur** : choisi pour chaque personne dans le formulaire.

---

## 9. Informations pour l'administrateur

### Changer le mot de passe
Dans le fichier `index.html`, repérez la ligne :
```js
const USER = 'admin', PASS = 'succes2026';
```
et remplacez les valeurs. Attention : c'est une barrière simple, le mot de passe reste lisible dans le code. Évitez de publier des données sensibles sur un dépôt public.

### Mettre en ligne sur GitHub Pages
1. Créez un dépôt GitHub et déposez tous les fichiers à la racine (*Add file → Upload files*).
2. *Settings → Pages → Deploy from a branch → main / (root)*.
3. Après une minute, l'application est disponible sur `https://votre-nom.github.io/nom-du-depot/`.

### Mettre à jour
Remplacez les fichiers modifiés sur GitHub, puis changez le numéro de version dans `sw.js` (`const V = 'succes-v5'` → `'succes-v6'`). Les appareils récupèrent la nouvelle version à leur deuxième ouverture.

### Fichiers du projet
`index.html` (application) · `sw.js` (mode hors ligne) · `manifest.webmanifest` et `icon-*.png` (installation) · `.nojekyll`.

---

## 10. À savoir (limites)

- **Les données sont stockées dans l'appareil et le navigateur utilisés.** Elles ne sont pas partagées entre téléphones ou collègues. Faites des **sauvegardes régulières**, et ne videz pas les données du navigateur sans sauvegarde.
- Chaque appareil a sa propre liste : pour la retrouver ailleurs, **restaurez** un fichier de sauvegarde ou **importez** un fichier Excel/CSV.
- Les outils Excel, PDF et ZIP se téléchargent à la **première utilisation** : une connexion internet est nécessaire une fois, puis ils restent disponibles hors ligne.
- La photo d'origine n'est pas conservée : seule la partie cadrée est enregistrée. Pour dézoomer sur une photo déjà recadrée, rechargez-la.

---

## 11. Problèmes fréquents

| Problème | Solution |
|---|---|
| Je ne vois pas le bouton « Installer » | Utilisez Chrome (Android) ou Safari → Partager → « Sur l'écran d'accueil » (iPhone). |
| Les notifications n'arrivent pas | Autorisez-les dans la cloche 🔔, vérifiez les réglages du navigateur, et ouvrez l'application : elle ne les envoie qu'à l'ouverture. |
| La photo est couchée | Utilisez les boutons de rotation ⟲ ⟳ dans le formulaire. |
| L'import ne reconnaît pas mes colonnes | Vérifiez les titres (Prénom, Nom, Jour, Mois ou Date) ou partez du **modèle CSV**. |
| Excel / PDF / ZIP ne se télécharge pas | Connectez-vous à internet une première fois pour charger l'outil. |
| J'ai changé de téléphone, ma liste a disparu | Restaurez votre **sauvegarde JSON** (⚙️ → Restaurer). |
| L'ancienne version s'affiche encore | Fermez et rouvrez l'application deux fois pour recevoir la mise à jour. |

---

*Caisse Populaire SUCCÈS — www.succes.coop*
