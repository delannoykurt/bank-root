## Client
|Nom	|Désignation|	Type	|Taille|	Remarque|	Null ?|	Valeur par défaut|
| --- | --- | --- | --- | --- | --- | --- |
|ID_Client|	ID du client|	INT	11	|Clé primaire	|Non	|
|Nom|	Nom du client|	VARCHAR	50|		Non|	
|Prénom|	Prénom du client|	VARCHAR	50|		Non|	
|Adresse|	Adresse du client|	VARCHAR	255|		Oui|	
|Téléphone|	Numéro de téléphone du client|	VARCHAR	20|		Oui|	
|Email|	Adresse e-mail du client|	VARCHAR	50|		Oui|


## Compte
| Nom | Désignation | Type | Taille | Remarque | Null ? | Valeur par défaut |
| --- | --- | --- | --- | --- | --- | --- |
| ID_Compte | ID du compte | INT | 11 | Clé primaire | Non |  |
| ID_Client | ID du client propriétaire | INT | 11 | Clé étrangère | Non |  |
| Numéro_Compte | Numéro de compte | VARCHAR | 20 |  | Non |  |
| Solde | Solde actuel | DECIMAL | 10,2 |  | Non | 0 |
| Date_Ouverture | Date d'ouverture du compte | DATE |  |  | Non |  |

## Admin
| Nom | Désignation | Type | Taille | Remarque | Null ? | Valeur par défaut |
| --- | --- | --- | --- | --- | --- | --- |
| ID_Admin | ID de l'admin | INT | 11 | Clé primaire | Non |  |
| Nom_Utilisateur | Nom d'utilisateur | VARCHAR | 50 |  | Non |  |
| Mot_de_passe | Mot de passe | VARCHAR | 255 |  | Non |  |
| Nom | Nom de l'admin | VARCHAR | 50 |  | Non |  |
| Prénom | Prénom de l'admin | VARCHAR | 50 |  | Non |  |
| Email | Adresse e-mail de l'admin | VARCHAR | 50 |  | Oui |  |