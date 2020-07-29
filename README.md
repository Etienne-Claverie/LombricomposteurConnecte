Quelques informations sur le compost :

Param�tres optimaux du compost:

	Avec capteurs :
		- Temp�rature -> entre 15 et 25 celsius
		- Humidit� -> entre 75 et 85%
		- gaz -> 30:1 carbon/azote + 10% oxyg�ne
		- pH percolat (et g�n�ral) -> entre 6.5 et 8. (besoin de traitement ult�rieur, percolat doit faire del'engrais acide)

	Sans capteurs :
		- Lumi�re -> endroit sombre
		- Bruit -> endroit calme
		- A�ration -> endroit bien a�r�

A PROPOS DU PROJET :

	CONTRAINTES : 
		Le compost doit �tre retourn� r�guli�rement + cuve ferm�e (pour la lumi�re).
		dur�e de vie des �quipements
		prix des �quipements

	CAPTEURS RETENUS:
		Voir Hardware.txt ( https://github.com/GuitouBDA/ArduinoCompost/blob/guillaume/Hardware.txt )

	PLACEMENT DES CAPTEURS : /!\ contraintes
    
		Temperature/humidit� : deux sondes filaires plong�es dans le compost

		Sonde pH : pour une mesure, � placer dans le seau qui r�colte le percolat.Les relev�s sont ponctuels, la sonde ne doit pas rest�e immerg�e.

	UTILISATION : Voir Notice.txt ( https://github.com/GuitouBDA/ArduinoCompost/blob/guillaume/Notice.txt ) 

	AMELIORATIONS POSSIBLE : 
		Notification quand un param�tre sort des normes ou connait une �volution anormale.
		Mesurer la masse du compost pour determiner la masse de terreau/de vers.

	INTERFACE UTILISATEUR
		Donn�es pouss�es dans Stellio (voir wiki).
		Dashboard � impl�menter.
