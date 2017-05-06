Pr�requis:

   --> Modules:
       >> mysql.
       >> validator.
       >> socket.io.
   --> Base de donn�es:
       >> nom: pictionary-db
       >> connexion: root/root
       >> tables:
          * users:
              id: number / auto-increment + primary key
              username: varchar 255
              password: varchar 255
              language: varchar 255
          * rooms:
              id: number / auto-increment + primary key
              nameRoom: varchar 255
              languageRoom: varchar 255

Informations:
   
   --> Accessible � "localhost:1337"
   --> Login fonctionnel
   --> Register fonctionnel
   --> Rooms:
       >> Possibilit� de cr�er une room
       >> Possibilit� de choisir une room
       >> Pas de limite de joueur et pas de lancement de partie en fonction des rooms
       >> Bouton "Jouer!" pour rejoindre le pictionary (sans notion de room)
   --> Aire de jeu fonctionnelle
       >> Le token de jeu est distribu� � un joueur (indiqu� dans le chat) qui doit ensuite cliquer sur "D�part"
   --> Profil: ossature seulement
   --> Pas de ladder

