# EasyRules
Moteur de jeu de rôle papier virtuel

But :
Fournir une solution client-serveur permettant à un mj et à une compagnie d'aventuriers de faire une partie d'un jeu de rôle quelconque.

Fonctionnalités :
Serveur :
  - Editeur de scenario (
                        map [
                            nature ( sol, arbre, roche, trou),
                            construction (murs, portes, maison, tours)
                            ],
                        Personnages [
                            visuel,
                            équipement,
                            caractéristiques,
                            monture,
                            compagnon
                            ],
                        Effets [
                            feu,
                            eau,
                            lumière,
                            sorts,
                            coups,
                            brouillard de guerre
                            etc..
                            ]
                        Events [
                            délimiteur de zone (invisible pour joueur mais visible pour mj avec activation manuelle),
                            effets de l'events (actions préprogrammées et script),
                            durée (0 - infini, le reste en secondes)
                            ]
                        );

  - Interface de jeu  (
                      choix,
                      events,
                      contrôle des joueurs,
                      chat,
                      jet de dés,
                      etc..
                      )
Client :
  - Interface de connection
  - Interface de jeu  (
                      affichage map,
                      chat,
                      jet de dés,
                      etc..
                      )

Technologies employées :
  - Graphisme et Sons : SFML
  - Réseau : Lib SFML Network ou TCP/IP à la mano
  - UI : QT (ou SFML si integration impossible)
  - Données : Base de données (sqlite ? SPARQL ?)

État d'avancement :
 - Début de la conception
