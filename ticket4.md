# Ticket 4 : Design -> Refactorisation de M2L avec le framework WebArt

| Élément existant | Responsabilité | Destination WebArt |
| ---------------- | -------------- | ------------------ |
|data/data.sql|Accès aux données|data/|
|data/schema.sql|Accès aux données|data/|
|public/index.html|Routage|www/|
|public/enregister-reservation.php|Affichage|page/|
|public/nouvelle-reservation.php|Affichage|page/|
|public/recherche.php|Affichage|page/|
|public/salles.php|Affichage|page/|
|public/supprimes-reservation.php|Affichage|page/|
|y'en a pas|Code HTML commun|page/template/|
|src/Model/Ligue.php|Traitement|controle/|
|src/Model/Reservation.php|Traitement|controle/|
|src/Model/Salle.php|Traitement|controle/|
|src/Repository/Database.php|Traitement|controle/|
|src/Repository/LigueRepository.php|Traitement|controle/|
|src/Repository/ReservationRepository.php|Traitement|controle/|
|src/Repository/SalleRepository.php|Traitement|controle/|
|/config/database.php|Configuration|config/|
