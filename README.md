# Utiliser une MagicGeek TV et Home Assistant pour afficher les prochains trains
# au départ d'une gare sncf vers une autre (ici d'Enghien les Bains vers Paris Nord)

<img src="data/MagicTV.png" width="150" height="150"> <img src="data/trains.png" width="150" height="150">

Le projet:
- Afficher le nombre de minutes restantes avant les 3 prochains trains au départ de la Gare d'Enghien les Bains, vers Paris Gare du Nord
- utiliser un code couleur sur le premier train à venir:
  Vert si on a le temps ( >5 mn)
  Orange si il est temps de partir (<5 mn et >3minutes)
  Rouge si il faut se dépecher (<3mn)
- afficher que les prochains trains (l'API à tendence à conserver un temps négatif lorsque le train vien de partir...)


Le materiel requis:
- Un écran GeekMagic – Station de prévision météo WiFi 
  https://fr.aliexpress.com/item/1005006159850972.html
- Home Assistant, avec une Clé API SNCF
  https://ressources.data.sncf.com/pages/accueil/
- installer Train Traveler dans Home Assitant ou l API REST
  (Les deux methodes sont décrites)
