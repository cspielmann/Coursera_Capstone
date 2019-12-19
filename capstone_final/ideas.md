this is an examge file
    A description of the problem and a discussion of the background. (15 marks)
    A description of the data and how it will be used to solve the problem. (15 marks)
    
  
  Restaurant "La ö" wants to go big !
  Could "La ö" restaurant be turned as a franchise business into other montpellier ? 
  
  Introduction
  
  Two very friends of mine, Laura and Denis, are hosting a very good and high-end "fast" food restaurant in Montpellier,France. You can get more detail on the venue and the delicisous meals they propose daily (all homemade!) on their facebook account (https://www.facebook.com/restaurant.la.o/). The restaurant is located in the ArtFx special effects school premises (https://artfx.school/) and propose lunch and snacks to students and white-collar people of the sourroundings. 
  If you go to this city, feel free to drop yourself there and tell to Laura that you got this address from Christophe of Zoufftgen. (ask for the Poutine meal...)
  In order to pursue their adventure, Laura and Denis would be interesting to see if restaurant "La ö" could be turned out as a franchise restaurant business. Hence several question may help them to see if it worth the pain:
  - Where do we find neighborhoods in Montpellier (and other cities in the future) that are similar to the  one where the restaurant is currently located "La ö"? (in terms of inhabitants, working customer, business offices and venues) 
  - What are the competitor that they may face in those similar neighbourhood?
  - What are the ratings of those competitors compared to the ones of "La ö"?
  - What is the trend of each neighborhood in the next 10 years? 
 
 Data requirement
 
 - Geographic and demographic data of montpellier neighboorhood.
 - List of venues in montpellier including ratings.
 - Criminal rate if possible
 - city traffic
 
 Analytic approach
 We will use unsupervised Machine Learning (ML) clustering to find Montpellier neighborhood that are similar to the one of la ö. We will display that on a map for a preliminary overview. 
 Then we will focus on the competitors that are into the same cluster and compare their rating with the ones of La ö. We will display that with regular graph.
 Other ML algo ?
 
 Data source
 - facebook graph API
 - FourSquare API
 - OpenData Monpellier (https://data.montpellier3m.fr/) : demographic data, geographic data, socioeconomic data of each neighborhood
 Unfortunately FourSquare data source does not include restaurant La ö neither a lot of other venues in Montpellier.
 
 References
 - Géolocalisation details (https://perso.esiee.fr/~courivad/Python1/15-geo.html)
 - https://data.montpellier3m.fr/
 - https://www.insee.fr
 - https://www.insee.fr/fr/statistiques/1405599?geo=EPCI-243400017
 - https://inhesj.fr/ondrp
 - https://www.data.gouv.fr
 - https://france-decouverte.geoclip.fr
 
 
 wikipedia
 
 Neighbourhoods of Montpellier
Since 2001, Montpellier has been divided into seven official neighbourhoods, themselves divided into sub-neighbourhoods. They are Montpellier-centre : historical centre (Écusson), Comédie, Gares, Faubourg Boutonnet, Saint-Charles, Faubourg Saint-Jaume, Peyrou, Les Arceaux, Figuerolles, Faubourg du Courreau, Gambetta, Clémenceau, Méditerranée, boulevard de Strasbourg, Le Triangle, Polygone, Antigone, Nouveau-Monde, Parc à Ballons, Les Aubes, Les Beaux-Arts, Saint-Lazare.
    Croix-d'Argent : avenue de Toulouse, Croix d'Argent, Mas Drevon, Tastavin, Lemasson, Garosud, Mas de Bagnères, Mas Nouguier, les Sabines, Lepic, Pas du Loup, Estanove, les Bouisses, Val-de-Crozes, Bagatelle.
    Les Cévennes : Les Cévennes, Alco, Le Petit Bard, Pergola, Saint-Clément, Clémentville, Las Rebès, La Chamberte, La Martelle, Montpellier-Village, Les Grisettes, Les Grèzes.
    Mosson : La Mosson, Celleneuve, La Paillade, les Hauts-de-Massane, Le Grand-Mail, Les Tritons.
    Hôpitaux-Facultés : Malbosc, Saint-Priest, Euromédecine, Zolad, Plan des 4 Seigneurs, Hôpitaux, IUT, Père Soulas, Universités, Vert-Bois, Hauts de Boutonnet, Aiguelongue, Justice, Parc zoologique de Lunaret, Agropolis.
    Port-Marianne : La Pompignane, Richter, Millénaire, Jacques Cœur, Consuls de Mer, Grammont, Odysseum, Montaubérou, La Méjanelle, Cambacérès.
    Prés d'Arènes : Les Prés d'Arènes, Avenue de Palavas, La Rauze, Tournezy, Saint-Martin, Les Aiguerelles, Pont-Trinquat, Cité Mion.
 
