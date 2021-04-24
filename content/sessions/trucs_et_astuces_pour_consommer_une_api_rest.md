---
key: trucs_et_astuces_pour_consommer_une_api_rest
title: Trucs et astuces pour consommer une API REST
language: French
level: beginner
speakers:
  - youri_bonnaffe
format: conference
draft: false
tags:
  - _method___tools
---
Consommer une API REST fait désormais partie de notre quotidien de développeur. Que ce soit pour appeler un composant de notre belle architecture micro-services, un service externe hébergé par un tiers, réaliser un appel HTTP est plus que courant dans nos applications. **Nous avons à disposition pléthore de ressources pour bien concevoir son API REST mais comment faisons-nous pour en consommer une de manière efficace ?**

- Cela commence souvent par la découverte d'une nouvelle API. Ai-je la chance de disposer d'une documentation complète ? Ou bien va-t-il falloir découvrir l'API ? Quels sont les outils qui peuvent m'aider pour démarrer ?

- Une fois les premiers services découverts, comment les intégrer dans mon application ? Avec un client HTTP basique comme le nouveau client du JDK11 ou bien un client REST complet comme Feign ?

- Dites donc, nous venons d'ajouter du code à notre application, quid des tests ? Faut-il appeler l'API directement dans ses tests ou bien rejouer les réponses ?

- Appeler une API c'est facile mais comment s'assurer de ses performances en production ? Comment tracer et débugger les appels ?

Je vous propose de faire le tour des outils et pratiques utiles pour la consommation des APIs REST en Java, en évoquant notamment : 
  - outils HTTP : OpenAPI, Postman, cURL
  - clients HTTP & REST : JDK11, Apache, Feign, Retrofit
  - techniques de test avec Wiremock
  - pratiques pour la production : performances, traçabilité, logs

---

*La présentation se veut plutôt comme un back to basics autour d'HTTP et REST centrée autour d'outils et pratiques éprouvés. Point de frameworks flambants neufs mais des techniques apprises au quotidien. L'objectif est de faire un tour d'horizon orienté vers la pratique avec démos et du code pour permettre à chacun d'améliorer sa manière d'utiliser une API REST.*

