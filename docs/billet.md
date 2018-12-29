# Titre

## Cartouche d'identification

- Manifestation : Codeurs En Seine 2018
- Lieu : Kindarena - Rouen
- Conférence : Des microservices aux migroservices
- Horaire de la conférence : 10h
- Durée de la conférence : 1h
- Conférencier(s) :
  - Francois Teychene ([Twitter](https://twitter.com/fteychene), [GitHub](https://github.com/fteychene))
- Audience : 100 spectateurs
- Auteur du billet : Thomas Boucher
- Mots-clés: Microservice, migroservice, monolith, distributed services, automatisation, container

## Support
- Lien vers le support (diapos) présenté en conférence : [Slides conférence](https://docs.google.com/presentation/d/1Z3hkFPBPBTX7sRxmwzBnPfS_AaI6zLz18BrMeSpmXw8/present?slide=id.g480600b79f_0_1973)
- Nombre de diapos du support : 87
- Plan du support : pas de plan annoncé.

## Résumé
L'articheture microservices tient son origine dnas le fait qu'une application monolotique devient très difficillement maintenable dans le temps, ainsi que peu scalable. L'architecture microservice est à la mode en ce moment, et cette mode est accentuée par l'arrivée des conteneurs comme Docker. Beaucoup de solutions techniques sont disponibles pour mettre en place, mais la plupart d'entre elles sont lourdes et très couteuses à mettre en place. L'architecture microservices apporte donc sont lot de difficultés. Il devinet difficile de traiter les erreurs (si un service est HS par exemple, ou si la réponse attendue n'est pas la bonne) ou de proposer un service de logging global. On peut avoir un effet "boule de neige" si ces réglages ne sont pas bien fait. Tout doit être pensé et mis en place dès le premier jour, de même que l'automatisation pour déployer ces services correctement. C'est à ce moment là que les "migroservices" interviennent. A mi chemin entre le microservices et l'architecture monolitique, les migroservices" permettent aux développeurs de ne pas repenser entièrement leur façon de faire, en ayant un type d'architecture moins précis. F.Teychene précise que cette solution hybride serait donc moins couteurse et reviendrait à faire du monolithe modulaire. 


## Architecture et facteur qualité
Pour l'architecture microservices:
- Tolérance aux pannes: La tolérance aux pannes est améliorée du fait d'avoir plus de services indépendants, mais les erreurs sont plus diffiles à gérer.
- Facilité de modification: Plus le nombre de ligne d'un projet est petit, plus le projet est maintenable. 
- Interopérabilité: Ces microservices peuvent être exécutés dans n'importe quel environemment, sur différentes machines.
