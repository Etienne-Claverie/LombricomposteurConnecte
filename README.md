
Param�tres :
Avec capteurs :
	- Temp�rature -> entre 15 et 25 celsius
	- Humidit� -> entre 75 et 85%
	- gaz -> 30:1 carbon/nitrogen + 10% oxyg�ne
	- pH percolat (et g�n�ral) -> entre 6.5 et 8. (besoin de traitement ult�rieur, percolat doit faire del'engrais acide)

Sans capteurs :
	- Lumi�re -> endroit sombre
	- Bruit -> endroit calme
	- A�ration -> endroit bien a�r� (processus a�robie)


CONTRAINTES : 
	Le compost doit �tre retourn� r�guli�rement + cuve ferm�e (pour la lumi�re).
	prix ?
	dur�e de vie des �quipements

CAPTEURS :
	Voir capteurs

PLACEMENT DES CAPTEURS : /!\ contraintes
    
    Temperature/humidit� :		
	Dans un premier temps : deux sondes "� main", fils suffisament long. Arduino -> boitier (dedans, dehors ?)

    Capteurs gaz : plac�s au dessus (haut de la cuve)

    Sonde pH : dans le seau qui r�colte le percolat (immersion constante != tests r�guliers) -> reli�s � la m�me arduino (probl�mes de fils)


TRAVAIL SUR LE CODE :

	d�tecter les trop grandes variations : moyenne des valeurs sur une heure ? une journ�e ? stocker donn�es pour v�rifier � la main
	Si variation : pr�venir si on approche d'un seuil. Rappeler les causes possibles et les solutions envisageables.
	Mettre en place la communication arduino/machines (avec Lora)


TRAITEMENT DES DONNEES





INTERFACE UTILISATEUR
