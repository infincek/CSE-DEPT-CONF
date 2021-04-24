---
key: implementer_un_webhook__pas_si_simple
title: Implémenter un Webhook, pas si simple !
language: French
level: beginner
speakers:
  - guillaume_laforge
format: conference
draft: false
tags:
  - _cloud___infra
---
Les Webhooks, vous connaissez ? Vous en avez sans doute déjà utilisé, par exemple pour être notifié d’un commit sur Github, pour réagir à l’arrivée d’un SMS avec Twilio, ou pour que votre chatbot Dialogflow réponde à ses interlocuteurs.

Côté consommateur de Webhook, cela semble plutôt facile à développer… Côté serveur, c’est “juste” une API à implémenter, non ? Hmm… En fait, nous allons voir que ce n’est peut-être pas si simple que cela !

Après une introduction au concept de Webhook, nous créerons notre callback pour être notifié d’un événement. Puis nous passerons de l’autre côté du miroir, en créant notre propre Webhook. Nous étudierons comment gérer la queue des abonnements des clients, traiter les erreurs, debugger son Webhook, faire des retry sans submerger le client s’il échoue, et sécuriser le Webhook.
