================================================================================
🎯                     LES POINTURES DES FLÉCHETTES                            🎯
================================================================================
              L U C K O ' S   D A R T S   T E A M   S C O R E R                 
================================================================================

    "L'application web ultime qui transforme vos soirées fléchettes ordinaires
              en championnats du monde survoltés et ultra-immersifs !"

================================================================================

[SOMMAIRE]

  1. PRÉSENTATION GÉNÉRALE & CONCEPT
  2. LES POINTS FORTS DE L'APPLICATION
  3. GUIDE COMPLET DES 11 MODES DE JEU ET VARIANTES
  4. L'INTERFACE UTILISATEUR COMPACTE & ULTRA-TACTILE
  5. LE SYSTÈME DE SYNTHÈSE VOCALE ET EFFETS AUDIO AVANCÉS
  6. ARCHITECTURE TECHNIQUE & PERFORMANCE DU CODE
  7. L'ALGORITHME DE "CHECKOUT" INTELLIGENT
  8. SUPPORT MULTILINGUE INTÉGRÉ
  9. GUIDE D'INSTALLATION ET DISPOSITIF PWA
 10. FEUILLE DE ROUTE & ÉVOLUTIONS FUTURES
 11. CRÉDITS & REMERCIEMENTS


================================================================================
1. PRÉSENTATION GÉNÉRALE & CONCEPT
================================================================================

Bienvenue dans l'univers de "Les Pointures des fléchettes", le compteur de score
le plus complet, ergonomique et électrisant du web ! Développé pour et par la 
"Lucko's Darts Team", cette application a été conçue pour éliminer la friction 
des calculs mentaux fastidieux et maximiser le plaisir de jeu autour de la cible.

Que vous soyez un joueur du dimanche cherchant une ambiance de pub conviviale, 
un groupe d'amis prêt à en découdre dans un mode "Killer" sans pitié, ou un 
compétiteur acharné analysant ses combinaisons de "Checkout" sur un 501, cette 
application s'adapte à tous les profils et à toutes les configurations de cibles.

Propulsée par une interface moderne aux accents "Cyber-Neon" (combinant des 
teintes de bleu profond, violet électrique, jaune or et rouge écarlate), elle 
intègre des technologies audio natives pour une immersion totale : bruitages 
dynamiques synthétisés par code, alertes vocales personnalisées en fonction des 
actions, et animations visuelles explosives à chaque grand coup d'éclat.


================================================================================
2. LES POINTS FORTS DE L'APPLICATION
================================================================================

🚀 ZÉRO INSTALLATION, ZÉRO CONFIGURATION
   Ouvrez le fichier HTML dans n'importe quel navigateur moderne (Mobile, 
   Tablette, PC, Smart TV) et commencez à jouer immédiatement. L'application 
   fonctionne à 100% côté client (Offline First).

🧠 LE CERVEAU DU REPARTITEUR DE DOUBLE ET TRIPLE
   Un pavé numérique adaptatif révolutionnaire qui change de couleur en 
   fonction du multiplicateur sélectionné (Simple, Double ou Triple). Finies 
   les erreurs de saisie ! Le pavé s'illumine en vert fluo pour les Doubles et 
   en rouge électrique pour les Triples.

🎙️ UN ARBITRE INTERNATIONAL À LA MAISON
   Grâce à l'API SpeechSynthesis intégrée, l'application annonce le nom des 
   joueurs, commente les manches gagnées, crie "BUST !" lors des scores brisés 
   et réagit même aux lancers mythiques avec des touches d'humour locales.

📊 PERSISTANCE DES DONNÉES (LOCALSTORAGE)
   Une coupure de batterie ? Un appel inattendu ? Aucun problème ! Vos joueurs, 
   vos scores en cours, l'historique complet de la partie et vos configurations 
   de langue sont sauvegardés instantanément dans la mémoire locale de votre 
   appareil. Vous pouvez reprendre la partie exactement là où vous l'avez laissée.

⚖️ GESTION DU MATCH ET SÉCURITÉ ANTI-ERREUR
   L'application gère nativement le système de manches (Legs), réorganise l'ordre 
   des joueurs par un simple glisser/bouton, et dispose d'une fonction "UNDO" 
   (Annuler) universelle et illimitée pour corriger la moindre erreur de saisie 
   sans jamais bloquer la partie.


================================================================================
3. GUIDE COMPLET DES 11 MODES DE JEU ET VARIANTES
================================================================================

L'application intègre une variété impressionnante de modes de jeu, reproduisant 
fidèlement les règles internationales et introduisant des modes exclusifs :

--------------------------------------------------------------------------------
A. LE TRADITIONNEL "X01" (Variantes : 201, 301, 501)
--------------------------------------------------------------------------------
   - CONCEPT : Le mode de compétition reine. Chaque joueur démarre avec un 
     capital de points (201, 301 ou 501) et doit le réduire à exactement zéro.
   - MÉCANIQUE DOUBLE-OUT : Pour gagner la manche, le joueur doit impérativement 
     terminer sur un secteur DOUBLE ou sur le centre parfait (Bull's Eye).
   - GESTION DU BUST : Si un joueur dépasse le score (descend en dessous de 0) ou 
     se retrouve avec un reliquat de 1 point (rendant un Double Out impossible), 
     un écran géant "BUST !" apparaît, le tour est annulé, et la parole passe au 
     joueur suivant.

--------------------------------------------------------------------------------
B. LE CRICKET TACTIQUE (Variantes : Standard, Cut-Throat)
--------------------------------------------------------------------------------
   - CONCEPT : Les joueurs doivent "fermer" les secteurs clés de la cible : le 
     15, 16, 17, 18, 19, 20 et le BULL.
   - FONCTIONNEMENT : Toucher un secteur 3 fois (les doubles comptent pour 2, les 
     triples pour 3) permet de le fermer. Si vous touchez à nouveau un secteur 
     que vous avez fermé alors qu'un adversaire ne l'a pas fait, vous accumulez 
     des points supplémentaires.
   - INTERFACE DÉDIÉE : Une grille dynamique affiche instantanément l'état de 
     fermeture de chaque joueur avec des symboles visuels progressifs (/, X, Ⓧ).

--------------------------------------------------------------------------------
C. LE CRUENTÉ "KILLER" (Variantes : 3 Vies, 5 Vies)
--------------------------------------------------------------------------------
   - CONCEPT : Un mode multijoueur d'élimination directe extrêmement intense.
   - PHASE 1 (L'INITIATION) : Au début, chaque joueur sélectionne ou se voit 
     attribuer un numéro cible unique. Il doit d'abord toucher son propre numéro 
     pour accumuler des vies. Dès qu'il atteint le maximum (3 ou 5), il devient 
     officiellement un "KILLER" (Tueur).
   - PHASE 2 (LA CHASSE) : Une fois devenu Killer, le joueur doit viser les 
     numéros de ses adversaires pour détruire leurs vies. Un double enlève 2 vies, 
     un triple en enlève 3. Le dernier survivant gagne le match !
   - SÉCURITÉ : Si un Killer touche par mégarde son propre numéro, il s'inflige 
     des dégâts et perd une vie !

--------------------------------------------------------------------------------
D. LE STRATÉGIQUE "CAPITAL" (Variantes : Départ 0, Départ 40)
--------------------------------------------------------------------------------
   - CONCEPT : Un jeu de survie basé sur l'adresse et la régularité.
   - LE PARCOURS : Tous les joueurs doivent viser une séquence obligatoire de 
     cibles, tour après tour : [15] -> [16] -> [DOUBLE] -> [17] -> [18] -> 
     [TRIPLE] -> [19] -> [20] -> [BULL].
   - LA SANCTION DU DIVISEUR : À chaque tour, les points marqués sur la cible du 
     moment s'ajoutent au capital du joueur. MAIS attention : si le joueur manque 
     complètement sa cible lors de ses 3 fléchettes, son capital est IMMÉDIATEMENT 
     DIVISÉ PAR DEUX ! La tension est maximale sur les tours Double et Bull.

--------------------------------------------------------------------------------
E. LE CRUEL "CHÂTEAU" (Variantes : 5, 10, 15 ou 20 Tours)
--------------------------------------------------------------------------------
   - CONCEPT : Une guerre de forteresses virtuelles représentées à l'écran par 
     un superbe mur de briques en pyramide inversée.
   - DÉROULEMENT : Chaque joueur choisit un numéro secret ou public. Toucher son 
     propre numéro construit son château (Simple = 1 brique, Double = 2, Triple = 3).
   - SABOTAGE : Toucher le numéro d'un rival détruit les briques de son château.
   - VICTOIRE : Le premier joueur à ériger un château de 15 briques l'emporte 
     instantanément, sinon le décompte final après épuisement des tours désigne 
     le grand vainqueur.

--------------------------------------------------------------------------------
F. LE COMPACT "SHANGHAI" (Variantes : 7 Tours)
--------------------------------------------------------------------------------
   - CONCEPT : Un sprint de précision pure à travers la cible. Les joueurs 
     enchaînent les secteurs du 1 au 7 (ou plus selon variante).
   - MARQUAGE : Seuls les lancers dans le numéro du tour rapportent des points.
   - LE COUP DE MAÎTRE "SHANGHAI" : Si au cours d'un même tour (3 fléchettes), 
     un joueur réussit l'exploit de toucher le Simple, le Double ET le Triple du 
     numéro en cours, il réalise un "SHANGHAI" et REMPORTE IMMÉDIATEMENT la partie, 
     quel que soit son score ou celui de ses opposants !

--------------------------------------------------------------------------------
G. LE TERRIBLE "BÂTARD" (Variantes : 10 Tours)
--------------------------------------------------------------------------------
   - Un mode hybride sans pitié reprenant le principe du Capital, où les cibles 
     changent de manière dynamique et où les lancers manqués détruisent votre 
     propre tableau de marque. Réservé aux joueurs au mental d'acier.

--------------------------------------------------------------------------------
H. L'INNOVANT "FOLLOW ME" (Variantes : Standard)
--------------------------------------------------------------------------------
   - CONCEPT : Un jeu d'adresse tactique en 10 tours où les joueurs se dictent 
     les cibles à atteindre.
   - PASSAGE DE RELAIS : Au début, 3 numéros aléatoires sont générés. Le joueur 1 
     lance ses fléchettes. Les numéros qu'il réussit à toucher deviennent les 
     cibles OBLIGATOIRES pour le joueur suivant. S'il en touche moins de 3, le 
     système complète de façon aléatoire.
   - STRATÉGIE : Allez-vous viser un secteur facile pour assurer vos points, ou 
     chercher un triple excentré très difficile pour piéger et couler le joueur 
     qui passe juste après vous ?


================================================================================
4. L'INTERFACE UTILISATEUR COMPACTE & ULTRA-TACTILE
================================================================================

L'un des défis majeurs d'un bon compteur de fléchettes est de permettre une 
saisie rapide sans forcer les joueurs à s'approcher d'un petit écran les mains 
pleines de fléchettes. Notre interface résout ce problème avec brio :

   [ Zone Info Manche : Rappel du Mode, de la Variante et du Tour en cours ]
   ──────────────────────────────────────────────────────────────────────────
   [ Carte du Joueur Actif : Énorme pavé lumineux pulsant à la couleur du    ]
   [ joueur, affichant son score en taille XXL et l'état de ses 3 flèches.    ]
   ──────────────────────────────────────────────────────────────────────────
   [ Multiplicateurs de Tir : 3 Boutons Géants Tactiles                      ]
   [  [ SIMPLE (Défaut)]   -   [ DOUBLE (Jaune/Vert)]   -   [ TRIPLE (Rouge)]]
   ──────────────────────────────────────────────────────────────────────────
   [ Pavé Numérique Dynamique (Grille 5x4 optimisée pour les pouces)          ]
   [  [ 20 ]  [ 19 ]  [ 18 ]  [ 17 ]  [ 16 ]                                 ]
   [  [ 15 ]  [ 14 ]  [ 13 ]  [ 12 ]  [ 11 ]                                 ]
   [  [ 10 ]  [ 09 ]  [ 08 ]  [ 07 ]  [ 06 ]                                 ]
   [  [ 05 ]  [ 04 ]  [ 03 ]  [ 02 ]  [ 01 ]                                 ]
   ──────────────────────────────────────────────────────────────────────────
   [ Boutons de Raccourcis Spéciaux et Utilitaires                            ]
   [  [ BULL (25)]   -   [ ZÉRO / MISS (0) ]   -   [ ↩ ANNULER (UNDO) ]      ]

Chaque pression de bouton déclenche instantanément une action, met à jour le 
moteur de rendu virtuel et enchaîne de manière fluide sans aucun rechargement.


================================================================================
5. LE SYSTÈME DE SYNTHÈSE VOCALE ET EFFETS AUDIO AVANCÉS
================================================================================

L'immersion ne serait pas complète sans un environnement audio ultra-réactif. 
L'application utilise exclusivement l'API Web Audio native du navigateur pour 
générer ses sons mathématiquement à la volée. Aucun fichier audio lourd (.mp3 
ou .wav) n'est téléchargé, garantissant une légèreté absolue du code !

- LE BRUIT DE L'IMPACT (Dart Sound) :
  Une combinaison d'une onde en triangle à 320Hz glissant rapidement vers 180Hz 
  couplée à un bruit blanc de très courte durée simule parfaitement la fléchette 
  qui se fiche dans le liège de la cible.
  
- LES ANNONCES DE TRADITION :
  L'arbitre virtuel est doté d'une personnalité bien trempée. En plus d'annoncer 
  le score ou le joueur, le script surveille des lancers spécifiques :
    * Si vous touchez un 18 dans des conditions mémorables, le système s'exclame 
      avec ferveur : "Jean-Pierre !"
    * Si vous validez un secteur 13 de façon magistrale, l'application vous 
      gratifie d'un vibrant : "Thérèse !"

- LES FANFARES DE VICTOIRE :
  Lorsqu'une manche ou le match est remporté, un algorithme joue une suite 
  d'accords harmoniques parfaits en onde sinusoïdale (Do-Mi-Sol-Do) accompagnée 
  d'un grand rideau de confettis virtuels tombant du haut de l'écran.


================================================================================
6. ARCHITECTURE TECHNIQUE & PERFORMANCE DU CODE
================================================================================

Le projet tient entièrement dans une structure épurée et moderne, optimisée pour 
les performances mobiles et le respect des standards du web :

- SINGLE FILE APPLICATION (SFA) :
  Le fichier `index.html` regroupe l'ensemble du balisage HTML5, les feuilles de 
  style CSS3 avancées et la logique algorithmique JavaScript ES6+. C'est le Graal 
  de la portabilité.

- GESTION D'ÉTAT CENTRALISÉE (State Management) :
  Toute la partie est pilotée par un objet global unique nommé `S` qui maintient 
  l'état en temps réel :
  ```javascript
  let S = {
      screen: 'home',      // Écran actif ('home', 'game')
      game: 'x01',         // Mode sélectionné
      variant: '501',      // Variante active
      players: [],         // Liste des joueurs intégrés au match
      scores: {},          // Tableau de score vivant de chaque joueur
      wins: {},            // Compteur de manches gagnées pour le format de match
      cp: 0,               // Index du joueur courant (Current Player)
      throws: [],          // Tableau des fléchettes lancées dans le tour en cours
      multiplier: 1,       // Multiplicateur sélectionné (1, 2, 3)
      round: 1             // Numéro du tour global
  };