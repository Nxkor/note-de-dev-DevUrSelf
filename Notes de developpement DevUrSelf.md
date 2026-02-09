# Nom de l’App : **DevUrSelf**

---

## Design & style / genre

**Couleurs principales :**

* Noir (dark theme)
* Blanc cassé (light theme)

**Couleurs secondaires :**
Personnalisables par l’utilisateur, par défaut : doré avec nuances légères.

Style minimaliste mais premium
Animations fluides
Sons minimalistes et propres

---

## Optimisation & sécurité

* Application fortement optimisée pour les téléphones à faibles performances, avec une fluidité constante des animations et des sons.
* Sécurité renforcée contre les hacks basiques afin d’éviter la perte de comptes et les failles courantes, et possiblement le vol ou l'abus d'API.

---

## Organisation visuelle de l’accueil

Barre de navigation en bas de l’écran, divisée en **5 icônes** :

### 1re catégorie (menu principal/accueil)
* Accueil affichant le niveau du joueur au centre d’une carte.
* Les professions liées aux prochaines quêtes sont affichées sur le côté droit, avec le titre de la catégorie correspondant à la profession et au prochain niveau.
* Icône en haut à droite de cette catégorie affichant : quêtes restantes, demandes d’amis, messages de l’application.

### 2e catégorie
* Quêtes journalières et hebdomadaires, affichage de la streak.

### 3e catégorie
* Social : amis à ajouter, gestion des demandes d'amis, affichage des utilisateurs en ligne ou de leur dernière connexion par recherche, niveau du joueur visible lors de la consultation d’un profil. (voir la section **Profil** pour afficher tous les paramêtres modifiables)

### 4e catégorie
* Boutique de l’application (entièrement gratuite, sauf achat valide du **Booster Pass**, permettant de passer un jour sans pénalité. Sans cela, une perte d’XP est appliquée si les quêtes ne sont pas validées).

### 5e catégorie
* Profil (avec affichage paramêtrable) :
- Nombre de quêtes validées
- Niveau du joueur, xp nécessaire avant le prochain niveau
- Description du profil (2 lignes d'une trentaine de caractères chacune)
- Localisation (ville /+ pays)

---

## Quêtes

### Journalières
**Physiques :**
* Effectuer un certain nombre de répétitions d’un exercice aléatoirement donné (pompes, squats, tractions, abdos, fentes, curls avec poids).
* Passer un certain temps à courir ou à faire la planche.
* Avoir manger sainement, divers et varié (fruits, légumes, viandes) et boire au minimum 1,5 L d’eau.

**Sociales :**
* Passer un certain temps avec sa famille.
* Passer un certain temps avec ses amis.

**Spirituelles / Mentales :**
* Méditer pendant un certain nombre de minutes.
* Prier pendant un certain temps (si religieux).

Ces quêtes sont des exemples et peuvent être complétées par d’autres.
Il y aurait x3 quêtes physiques, x1 sociale & x1 spirituelle.

### Hebdomadaires
* Aller à la piscine pendant un certain temps (sauf si pas de piscine dans la ville, paramêtrable).
* Sortir se balader dans un parc ou un espace dédié pendant un certain temps.
* Aller courir un certain nombre de kilomètres.
* Si dans une grande ville, aller visiter un lieu précis.
* Calculs de réussite pour certaines quêtes (Certaines quêtes journalières peuvent être communes avec des quêtes hebdomadaires.)

**Mise en situation :**
Une quête hebdomadaire demande d’effectuer 50 pompes, et une quête journalière en demande 10.
Si l’utilisateur valide les 10 pompes, la progression de la quête hebdomadaire est automatiquement mise à jour.
Chaque validation journalière contribue donc à la complétion de la quête hebdomadaire.

---

## Social

### Profil

* Personnalisation de la photo de profil et description (limitée : 2 lignes de 30 caractères chacune.).
* Profil public ou privé.
* Public : tout le monde peut voir le profil.
* Demandes d’amis activables ou désactivables.
* Affichage du statut en ligne/hors ligne, du rang, du pseudo, de la taille, du streak de connexion et de complétion des quêtes, de l’XP et du niveau du joueur.

### Signalement (avec personnalisation)

* Photo de profil à signaler.
* Description du profil à signaler.
* Compte à signaler.

Si le signalement s’avère valide, l’élément concerné (photo, description ou compte) est supprimé du profil signalé.

---

## Daily Rewards

Chaque jour de connexion (ou chaque **streak**), l’utilisateur reçoit un lot de récompenses instantanées mais suffisement minimales pour lancer le joueur à faire des quêtes journalières.
De potentielles idées de dailyrewards : obtention d'un peu d’XP ainsi que de l’or de jeu à dépenser dans la boutique du jeu.

---

## Récompenses

Dans le cas où l’utilisateur complète ses quêtes dans les délais :

Exemple :
Le lundi, une quête demande de faire 50 pompes. Si l’utilisateur les effectue toutes, le jeu augmente la difficulté de la quête de **1 point**.
Si l’utilisateur valide à nouveau 50 pompes le lendemain (mardi), la difficulté passe de 1 à 2.
Plus le nombre de quêtes validées est élevé, plus les récompenses le sont aussi.

Chaque semaine, de nouvelles quêtes hebdomadaires apparaissent, offrant des récompenses liées à des événements, à d’autres quêtes, à l’amélioration du profil et à la progression du niveau.

Lors de l’achèvement d’une quête, l’utilisateur déverrouille automatiquement une quantité de **Crédits**, proportionnelle à la difficulté de la quête.
Ces crédits sont utilisables dans la boutique pour divers objets (ex. objets RP de l’app), pour offrir de l’XP à un ami ou compléter des collections de trophées.
Les crédits agissent comme une monnaie échangeable entre joueurs.

## Pénalités

Dans le cas où l’utilisateur ne complète pas ses quêtes dans les délais :
* Si une quête demande 50 pompes et que seulement 25 sont réalisées, le jeu enregistre le nombre de pompes non faite et les rajoute sur la prochaine quête du même type.
* Lors de la prochaine apparition du même type de quête (ici sont les pompes), et que l'utilisateur ne complète toujours pas sa quête à 100%, le % restant de pompes non faites sera ajouté à la prochaine apparition de cette quest-type,
cette mécanique de pénalité est empilable 7 fois. Au bout de la 7° fois, une perte d'expérience progressive relative à la quête est observée. x2 XP de soustraite relativement au gain de la quête en question si elle n'est toujours pas complétée dans les délais.
Cette seconde mécanique de pénalité est empilable 7 fois aussi. Chaque jour de plus sans compléter la quête dans les délais rajoutera 1 cumul d'xp en moins (jour 1 = x-2XP, jour 2 = x-3XP, jour 3 = x-4XP etc jusqu'au Jour 7)

---

## Système de niveaux & rangs

**Rangs & XP (XP = 100 %) :**
* Rang 1 - E - (niveaux 0 à 10) : +0 à 10 % d’XP par niveau.
* Rang 2 - D - (niveaux 10 à 25) : +10 jusqu'à 15 % d’XP par niveau.
* Rang 3 - C - (niveaux 25 à 40) : +15 jusqu'à 25 % d’XP par niveau.
* Rang 4 - B - (niveaux 40 à 55) : +25 jusqu'à 40 % d’XP par niveau.
* Rang 5 - A - (niveaux 55 à 75) : +40 jusqu'à 50 % d’XP par niveau.
* Rang 6 - S - (niveaux 75 à 100) : +50 jusqu'à 70 % d’XP par niveau.
* Rang 7 - Nation - (niveaux 100 à 105) : +70 jusqu'à 100 % d’XP par niveau.

Les rangs changent automatiquement selon le niveau.
Les professions de quêtes progressent moins rapidement que les rangs principaux.

Au-dessus du niveau 30, il n'est plus nécessaire de devoir compléter toutes les quêtes quotidiennement, mais au minimum x3 par semaine, sous peine de pénalité.
Au-dessus du niveau 70, il n’est plus obligatoire de compléter les quêtes quotidiennement, sans aucune pénalité.
À afficher dans l'écran des notifications dans l'accueil une fois le niveau requis obtenu.

---

### Calcul des rangs/niveaux à la première connexion
* Quantité de sport effectuée (hors école + école).
* Temps de révision hebdomadaire / par jour en semaine.
* Temps passé à méditer par semaine / jour.
* Temps passé avec des amis ou la famille par semaine (en physique)
* Poids / taille / âge / sexe (homme/femme).

---

## Nouveaux objectifs

### Objectifs sociaux (minimum 10 requis)
* Ajouter un utilisateur en ami.
* Compléter une quête avec un utilisateur ami.
* Offrir un minimum d'expérience à un ami (partage d’expérience).
* Une fois les quêtes hebdomadaires terminées, les utilisateurs débloquent une **Multiplayer Quest**.
  L’XP gagnée est significativement plus élevée que pour les quêtes solo.
* Un certains nombre de quête / niveaux passé.e.s, les utilisateurs débloquent la "Quête Communautaire" qui est une quête avec une limite de complétion journalière 10x plus grande qu'une quête du même type

**Mise en situation pour : objectifs communautaires (niveau ~20 requis).**
  - Une quête cummunautaire intitulée "Faire 200k pompes" où tout les utilisateurs possédant les prérequis peuvent faire avancer cette quête. Chaque jour, on à la possibilité d'ajouter jusqu'à 500 pompes (si notre même type de quête -ici les pompes- est d'un max de 50 pompes par jour.
  - Soit un maximum de complétion journalière s'élevant à x10 par rapport à une quête journalière.
  - Cette quête n'a aucun délais, elle peut être finie en 2 jours comme en 2 mois. Elle requiert surtout un certain nombre d'utilisateurs.
  - La progression est mise à jour en temps réel.
  - Elle donne de l'xp relativement aux efforts donnés : si donné qu'une quête journalière "Faire 50 pompes" donne 100 XP, et qu'on en fait 500 et que l'objectif est complété, on serait récompensé de 1k XP (dans cet exemple : une pompe = 2XP).

Les objectifs sociaux (ou "Quêtes communautaires") ne serait limités qu'à 3 silmutanément : x1 Physique, x1 Sociale, x1 Mentale.
Si possédant déjà l'accès aux objectifs sociaux, la quête journalière/hebdomadaire ferait avancer en temps réel l'objectif social.



